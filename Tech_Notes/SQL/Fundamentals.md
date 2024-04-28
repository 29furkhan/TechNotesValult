### Self join: ^37a06b

Description
> `1. Data when joined with itself is a self join.`
> `2. Useful when you want to compare rows of same dataset or find relation between columns of same dataset.`
> `3. Give different alias at the time of join to same dataframe.`
> `4. Self join can be inner, left, right, outer.`

Example
>![[self-join.png]]

Data
> ```python
> santa_cols = ["sender_color", "Name", "receiver_color"]
santa_data = [("red", "Furkhan", "blue"), ("blue", "Akshay", "yellow"), ("yellow", "Rita", "red")]
df = spark.createDataFrame(santa_data, schema=santa_cols)

>```
+------------+-------+--------------+
|sender_color|   Name|receiver_color|
+------------+-------+--------------+
|         red|Furkhan|          blue|
|        blue| Akshay|        yellow|
|      yellow|   Rita|           red|
+------------+-------+--------------+
>```

Code
> ```python
> # Unprocessed code. (columns from both)
> df.alias("a").join(df.alias("b"),
col("a.sender_color") == col("b.receiver_color"),
"inner").show()
>
#Processed code
df.alias("a").join(df.alias("b"),
col("a.sender_color") == col("b.receiver_color"),
"inner") \
.select(
"b.Name", #Observe b.Name
col("a.Name").alias("Santa") #Observe a.Name
).show()
> ```

Result
>```
#Unprocessed
>+------------+-------+--------------+------------+-------+--------------+
|sender_color|   Name|receiver_color|sender_color|   Name|receiver_color|
+------------+-------+--------------+------------+-------+--------------+
|        blue| Akshay|        yellow|         red|Furkhan|          blue|
|         red|Furkhan|          blue|      yellow|   Rita|           red|
|      yellow|   Rita|           red|        blue| Akshay|        yellow|
+------------+-------+--------------+------------+-------+--------------+
>
#processed
+-------+-------+
|   Name|  Santa|
+-------+-------+
|Furkhan| Akshay|
|   Rita|Furkhan|
| Akshay|   Rita|
+-------+-------+
>```
****
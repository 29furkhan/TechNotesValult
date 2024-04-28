****
##### Window Functions ^c18388

> `1. Window functions are used to calculate results, such as rank, row_number, over a range of input values.`
> `2. Window functions operates on group of rows (partition) and returns a single value for each input row.`
> `3. Kinds of window functions.`
> >`1. Ranking functions` 
> >`2. Analytical functions`
> >`3. aggregate functions`
> 
> `1. Ranking functions: row_number(), rank(), and dense_number() are ranking functions. These assigns the sequential numbers to DFs based on criteria specified in partition. `
>*  [[Functions#^04cbdc|row_number()]]
>* [[Functions#^23ec05|rank()]]
>* [[Functions#^78d32c|dense_rank()]]
>
> `Both rank and dense_rank assigns the same rank if duplicates are found even in criteria. However, row_number randomly assigns unique value to each input.`
> 
> More on window functions can be read [Here](https://sparkbyexamples.com/pyspark/pyspark-window-functions/#ranking-functions)


##### Schema  Comparison ^496137

> `1. It helps us unify the schema in case we deal with multiple dataframes.`
>> `1. Find missing columns`
>> `2. Collect all the columns`
>> `3. Compare schema`
>
>```python
># Compare schema of 2 DFs.
>if df1.schema == df2.schema:
>	print("Schema is same")
>else:
>	print("Schema is not same")
>```
>```python
># Find missing columns
>set(df1.schema) - set(df2.schema)
># or
>set(df1.columns) - set(df2.columns)
>```
>```python
># Collect all columns
>all_cols = set(df1.columns + df2.columns)
>```
>```python
># Add the missing columns with None value
>for i in all_cols:
>	df2 = df2.withColumn(i, lit(None))
>```
****
##### StructType and StructField ^8a58d8

> Description
> >`1. Classes used to programmatically specify the schema of the DF. We can use it to create complex structures like struct, array, and map columns.,`
> `2. StructType: Class to create structure of DF.`
> >`3. StructField: Specify column name, data type, flag for null, nested arrays, etc.`
>
>Imports
>>```python
>>from pyspark.sql.types import StructType, StructField, StringType, IntegerType, FloatType, ArrayType
>>```
>
>Data
>```python
># Schema preparation
>schema = StructType([
StructField("Name", StringType(), True),
StructField("Age", IntegerType()),
StructField("Commission", FloatType()),
StructField("Address", StructType([
>	StructField("City", StringType()),
>	StructField("State", StringType()),
>	StructField("Pincode", IntegerType()),
>	])),
StructField("Technologies", ArrayType(StringType()))
])
># Prepare data as per schema
data = [("Furkhan", 29, 6500.234,("Pune", "Maharashtra", 412308), ["Python", "SQL", "PySpark"])]
df = spark.createDataFrame(data=data, schema=schema)
>```
>Resultant Schema
>```
>|-- Name: string (nullable = true)
 |-- Age: integer (nullable = true)
 |-- Commission: float (nullable = true)
 |-- Address: struct (nullable = true)
 |    |-- City: string (nullable = true)
 |    |-- State: string (nullable = true)
 |    |-- Pincode: integer (nullable = true)
 |-- Technologies: array (nullable = true)
 |    |-- element: string (containsNull = true)
>```
##### MapType and ArrayType ^08821d

**MapType**
>Description
>>`* Represents python dictionary that stores key-value pair.`
>>`* MapType object consists of key type, value type, Nullable.`
>
>Imports
>```python
>from pyspark.sql.types import MapType
>```
>Data
>```python
># Schema for a map type
>schema = StructType([
>	StructField("Name", StringType(), False),
>	StructField("Properties", MapType(StringType(), StringType(), False))
])
>```
>Schema
>```python
>root
 |-- Name: string (nullable = false)
 |-- Properties: map (nullable = true)
 |    |-- key: string
 |    |-- value: string (valueContainsNull = false)
>```
>Queries
>```python
>data = [("Furkhan", {
"Age": "24",
"Gender": "Male",
"Salary": "100$"
})]
df = spark.createDataFrame(data=data, schema=schema)
>```
>Result
>```
>+-------+-------------------------------------------+
|Name   |Properties                                 |
+-------+-------------------------------------------+
|Furkhan|{Salary -> 100$, Gender -> Male, Age -> 24}|
+-------+-------------------------------------------+
>```

**ArrayType**
>Description
>
>> `* Array of multiple elements of same type. `
> >` * ArrayType(<DataType> of elements)`
> 
> Imports
>```python
>from pyspark.sql.types import ArrayType
>```
> Data and Schema
>```python
># Schema for a map type
schema = StructType([
>	StructField("Company", StringType(), False),
>	StructField("Locations", ArrayType(StringType(), True))
])
> # Data as per the schema, some NULLs and ""
>data = [("TCS", ("Pune", None, "Chennai")), ("Infosys", ("Mumbai", "", "Raichur"))]
df = spark.createDataFrame(data=data, schema=schema)
>```
> Result
>```
>+-------+---------------------+--------+
|Company|Locations            |Location|
+-------+---------------------+--------+
|TCS    |[Pune, NULL, Chennai]|Pune    |
|TCS    |[Pune, NULL, Chennai]|Chennai |
|Infosys|[Mumbai, , Raichur]  |Mumbai  |
|Infosys|[Mumbai, , Raichur]  |Raichur |
+-------+---------------------+--------+
>```
##### Apache Spark Architecture
Task
##### Apache Spark Submit
##### Multiple ways to create an Empty dataframe/ RDD.




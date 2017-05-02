# 23.2

Primary datatypes
The primitive data types include Integers, Boolean, Floating point numbers and strings.
TINYINT	Y	10Y


Complex datatypes
The complex data types include Arrays, Maps and Structs. These data types are built on using the primitive data types.

Arrays: Contain a list of elements of the same data type. These elements are accessed by using an index. For example an array, “fruits”, containing a list of elements [‘apple’, ’mango’, ‘orange’], the element “apple” in the array can be accessed by specifying fruits[1].
Syntax: ARRAY<data_type>

Maps: Contains key, value pairs. The elements are accessed by using the keys. For example a map, “pass_list” containing the “user name” as key and “password” as value, the password of the user can be accessed by specifying pass_list[‘username’]
Syntax: MAP<primitive_type, data_type>

Structs: Contains elements of different data types. The elements can be accessed by using the dot notation. For example in a struct, ”car”, the color of the car can be retrieved as specifying car.color
Syntax: STRUCT<col_name : data_type [COMMENT col_comment], ...>

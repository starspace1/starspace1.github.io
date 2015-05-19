Numeric
-----------
* Holds floats or integers
* Create a new one like this: x = 4 or x = 4.0, for integer or float, respectively
* Mathematical operators such as +, -, /, and * (add, subtract, divide, and multiply) can be used like on a regular calculator (for example, x + 6 or x / 2.0 or 4 + 1).
* Note that if you combine types (float with integer) when using a mathematical operator, the result will be a float.
* You can compare floats and integers using < , > , <=, >= and ==. For example, testing 4 == 3.5 would return false, but 5 == 5 would return true.

String
-----------

* Holds text
* Create a new one like this: str = "hello" or str = 'hello'
* The + operator can be used to concatenate strings, for example if str1 = "hello" and str2 = " there", str1 + str2 would give you "hello there", another string.
* The * operator can be used to make copies of a string. For example, "Str" * 5 returns another string, "StrStrStrStrStr" which is the original string, five times.
* The <, >, <=, and >= operators can be used to compare lengths of strings. For example "StringThing" > "String" returns true because "StringThing" has more characters.
* The == operator can be used to compare strings, and returns a boolean. For example, "str" == "str" returns true, but "st" == "str" returns false.

Array
-----------

* Group of numeric or string objects accessible by index
* Create a new one like this: my_arr = [] (this is empty), integer_array = [1, 3, 6], other_array = [1, 3.0, "stuff"] (you can mix types)
* You can use the + operator to concatenate arrays. For example, [1, "a"] + ["b", 5, 2] returns the array [1, "a", "b", 5, 2]

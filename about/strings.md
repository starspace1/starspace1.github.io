#String
A string holds text

##Creation
Create a new one like this, with double quotes: 
```
str = "hello"
```
or like this, with single quotes:
```
str = 'hello'
```
##Operators
The + operator can be used to concatenate strings. 

For example if str1 = "hello" and str2 = " there", str1 + str2 would give you "hello there", another string.

The * operator can be used to make copies of a string. For example:
```
"Str" * 5 #=> "StrStrStrStrStr"
```
Basically, it repeats the original string, five times.

The <, >, <=, and >= operators can be used to compare lengths of strings. For example 
```
"StringThing" > "String" #=> true
```
because "StringThing" has more characters.

The == operator can be used to compare strings, and returns a boolean. For example, 
```
"str" == "str" #=> true
"str" == "st" #=> false
```
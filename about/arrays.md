# Arrays

An array is a group of numeric or string objects accessible by index. It is ordered.

##Creation
Create a new, empty array like this: 
```
my_arr = []
```
Create an array of integers like this:
```
integer_array = [1, 3, 6]
```
Create an array of mixed types (integers, floats, strings) like this:
```
other_array = [1, 3.0, "stuff"]
```
##Operations
You can use the + operator to concatenate arrays:
```
[1, "a"] + ["b", 5, 2] #=> [1, "a", "b", 5, 2]
```
You can use the * operator to duplicate arrays:
```
 [2, 4, 4]*4 => [2, 4, 4, 2, 4, 4, 2, 4, 4, 2, 4, 4]
```
##Access
You access elements in an array by using brackets. Arrays are zero-indexed. So to get the third element in integer_array above, use:
```
other_array[2] #=> "stuff"
```
##Iterating
You can iterate through an array like this:
```
a = [1, 3, 5]
a.each do |i|
  puts i
end
```
And you will see this:
```
1
3
5
```
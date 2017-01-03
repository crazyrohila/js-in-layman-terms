# Concat:

Merge two arrays; returns new array and keep the original as it is.

```
var arr1 = ['Hey', 'Hi'];
var arr2 = [1, 2, 'hola'];
var arr3 = arr1.concat(arr2);
```

# Push:

Add new item to end of array; takes multiple arguments.

```
var arr1 = ["hey", "hi"];
arr1.push("hola", "hello");
console.log(arr1); // ["hey", "hi", "hola", "hello"]
```

# Unshift:

Add new item at start of array; takes multiple arguments.

```
var arr1 = ["hey", "hi"];
arr1.unshift("hola", "hello");
console.log(arr1); // ["hola", "hello", "hey", "hi"]
```

# Pop:

Remove item from end of array.

```
var arr1 = ["hey", "hi"];
arr1.pop();
console.log(arr1); // ["hey"]
```

# Shift:

Remove item from start of array.

```
var arr1 = ["hey", "hi"];
arr1.shift();
console.log(arr1); // ["hi"]
```

# Splice:

Remove multiple items starting from given index. Returns the array of removed items.

```
var arr1 = ["hey", "hi", "hello", "hola", 1, 3];
var rarr = arr1.splice(3, 2); // It says: remove 2 items starting from index 3.
console.log(rarr); // ["hola", 1]
console.log(arr1); // ["hey", "hi", "hello", 3]
```

# Slice:

Copy items of array in new array without modifying original array.

```
var arr1 = ["hey", "hi", "hello", "hola", 1, 3];
var sarr = arr1.slice(3, 4);
console.log(sarr); // ["hola"]
console.log(arr1); // ["hey", "hi", "hello", "hola", 1, 3]
```

# ToString:

Returns the string of array data without modifying original array. We can't format the output string with any seperator. @see #Join

```
var arr1 = ["hey", "sanjay", "!"];
var s = arr1.toString();
console.log(s); // "hey,sanjay,!"
```

# Join:

Returns string of array data with desired seperator.

```
var arr1 = ["hey", "sanjay", "!"];
var s1 = arr1.join(' ');
var s2 = arr1.join();
console.log(s1); // "hey sanjay !"
console.log(2); // "hey,sanjay,!" <- Join is same as toString(), if no seperator is provided
```

# Reverse:

Does what it says, reverse the order of array items.

```
var arr1 = [1,4,9,3,5,2];
arr1.reverse();
console.log(arr1); // [2, 5, 3, 9, 4, 1]
```

# @todo more...

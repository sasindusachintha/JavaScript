# JavaScript Array Master Notes

This guide covers JavaScript array methods with examples and outputs.
Useful for beginners and interview preparation.
---

## Add/ Remove

### ➕ push()   :- Adds one or more elements to the end of an array.
![push](ss/push.jpg)

### ➖ pop()   :- Removes the last element from an array.
![pop](ss/pop.jpg)

### ⬅️ unshift() :- Adds elements to the beginning of an array.
![unshift](ss/unshift.jpg)

### ➡️ shift() :- Removes the first element of an array.
![shift](ss/shift.jpg)

### ✂️ splice() – Remove at Index
![splice-remove](ss/splice1.jpg)

### ✨ splice() – Insert at Index
![splice-insert](ss/splice2.jpg)

---

## Iteration/ Transform

### 🔄 map() :- Creates a new array by transforming each element using a function.
✅ Used when you want to modify every value.
![map](ss/map.jpg)

### 🔁 forEach()  :- Executes a function for each element.
⚠️ Does NOT return a new array.
![forEach](ss/forEach.jpg)

### 🔁 flatMap() :- Runs map() then flattens result one level.
![flatMap](ss/flatMap.jpg)

---

## Search/ Find

### 🎯 find() :- Returns the first element that satisfies a condition.
![find](ss/find.jpg)

### 📍 findIndex() :- Returns index of first matching element.
![findindex](ss/findIndex.jpg)

### 🔚 findLast() :-  Returns the last element matching a condition.
![findLast](ss/findLast.jpg)

### 🔚 findLastIndex() :- Returns the index of the last element in an array that satisfies a given condition.
![findLAstIndex](ss/findLAstIndex.jpg)

### ✅ includes() :- Checks if an array contains a value.
![includes](ss/includes.jpg)

### 📌 indexOf() :- Returns index of a value (or -1 if not found).
![indexOf](ss/indexOf.jpg)

### 📌 lastIndexOf()  :- Returns the last index where a value appears (or -1 if not found).
![lastIndexOf](ss/lastIndexOf.jpg)

---

## Filter/ Reduce

### 🔍 filter() :- Returns the last index where a value appears. Returns -1 if not found.
![filter](ss/filter.jpg)

### ✅ reduce() :- Reduces an array into one single value (sum, total, object, etc.).
![reduce](ss/reduce.jpg)

### ✅ reduceRight() :- Same as reduce() but processes elements from right to left.
![reduceRight](ss/reduceRight.jpg)

---

### Boolean Checks

### 🔘 some() :- Checks if at least one element matches a condition.
![some](ss/some.jpg)

### ✅ every() :- Checks if all elements satisfy a condition.
![every](ss/every.jpg)

---

## Order/ Sort

### 🔃 sort() :- Sorts elements (modifies original array).
![sort](ss/sort.jpg)

### 🔄 reverse() :- Reverses array in place.
![reverse](ss/reverse.jpg)

### 🆕 toSorted() :- Returns a sorted copy without changing original array.
![tosorted](ss/toSorted.jpg)

### 🆕 toReversed() :- Returns reversed copy without modifying original.
![toreversed](ss/toReversed.jpg)

---

## Slice/ Copy/ Replace

### ✂️ slice() :- Returns a portion of an array without changing the original.
![slice](ss/slice.jpg)

### ✨ with() :- Returns a new array with one element replaced at a specific index.
Original array is unchanged.
![with](ss/with.jpg)

### 🆕 toSplice() :- Non-mutating version of splice().
Creates a modified copy instead of changing the original.
![toSpliced](ss/toSpliced.jpg)

### 🆕 toSpliced() :- Adds/removes elements by without modifying the original array.
![toSplicedR2](ss/toSplicedR.jpg)

---

## Combine/ Convert

### ➕ concat() :- Combines arrays into a new array.
![concat](ss/concat.jpg)

### 🔗 join() :- Converts array into a string.
![join](ss/join.jpg)

### 🔤 toString() :- Converts array into a comma-separated string.
![toString](ss/toString.jpg)

---

## Structure Helpers

### 📏 flat() :- Flattens nested arrays.
![flat](ss/flat.jpg)

### ❓ Array.isArray() :- Checks whether a value is an array.
![isArray](ss/isArray.jpg)

### 🖌 fill() :- Fills array elements with a static value.
![fill](ss/fill.jpg)

### 📋 copyWithin() :- Copies part of an array to another position inside the same array.
Modifies original array.
![copyWithin](ss/copyWithin.jpg)

---

## Info

### 📐 length :- Property that returns or sets number of elements.
![length](ss/length.jpg)

### 📑 entries() :- Returns an iterator containing index + value pairs.
![entries](ss/entries.jpg)

### 🔑 keys() :- Returns iterator containing array indexes.
![keys](ss/keys.jpg)
 
### 💎 values() :- Returns iterator containing array values.
![values](ss/values.jpg)

---

## Creation

### 📥 Array.from() :- Creates an array from iterable or array-like objects.
![from](ss/from.jpg)

### 📤 Array.of() :- Creates an array from given arguments.
![of](ss/of.jpg)

---
## Spread

### 🔀 Combined [...arr1, ...arr2]   :- Combines arrays into a new array.
![combined](ss/combined.jpg)

---
✅ Done
---














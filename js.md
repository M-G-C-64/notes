

- JS is a client side language
- PHP is a server side language
- JS code should be embedded in head tag, so it loads first
- External JS code loads faster using caching technique

| Sl.no | Item name | Item-value | Item-description |
|:--:|:--:|:--:|:--|
| 1 | `document.write` | anything | prints value in the document |
| 2 | `.getElementById("Id_name")` | | gets the element with that id name |
| 3 | `.innerHTML = 5+6`| any html we want | adds the given html inside the selected element |
| 4 | `//` | | comment single line |
| 5 | `/* code_here */`|| multi-line comments |
| 6 | `var a = `| value | holds a new variable |
| 7 | `var object = {"field_1":"value1", "field_2":"value2"};`| | holds field, value pairs |
| 8 | `.length`| | outputs length of variable |
| 9 | `Math.random()`| | generate random number between 0, 1|
|10 | `Math.min(num1, num2)`|| outputs minimum value|
|11 | `Math.max(num1, num2)`|| outputs maxx value|
|12 | `Math.round(number)`|| rounds number|
|13 | `Math.floor(number)`|| rounds down|
|13 | `Math.ceil(number)`|| rounds up|
|14 | `list[index]`|| return index value of the list |
|15 | `list.toString()`|| returns all items in the list as a String seperated by ","|
|16 | `list.join('character')`|| returns items of the list seperated by provided character |
|17 | `list.pop()`|| removes the last item in an list|
|18 | `list.shift()`|| removes teh first item|
|19 |`list.push("name")`|| adds element to end of list|
|19 |`list.unshift("name")`|| adds element to begginnign of list|
|20 | `delete list[index]`|| deletes the item|
|21 | `list.splice(start_index_value, number_of_items_to_be_removed, new_item1, new_item2...)`|| adds new items to the list at the given position|
|22 | `list.sort()`| | sorts the elements |
|23 | `list.reverse()`|| sorts in reverse|
|24 | `list1.concat(list2)`|| concats 2nd list at end of 1st|
|25 | `if (condition) {commands}`|| executes if condition is true|
|26 | `if else() {}`|||
|27 | `else {}`|||
|28 | `==`|| equal to |
|29 | `===`|| equal to value and equal to type|
|30 | `!=`, `!==`|| negation of original |
|31 | `Boolean(condition)`|| returns weather statement is true or false|
|32 | `for(count=0; count<=10; count++) {}`|| for loop runs until condition is false|
|33 | `for (item in object)`|| iterates over items inside the object|
|34 | while(condition) {} || runs while the condition is true|
|35 | `do{statements} while(condition)`|| runs do, stops if condition false|
|36 | `function func_name(parameters) {statements}`|||
|37 | `break`|| breaks the loop|
|38 | `continue`|| skips the current loop|
|39 | `return value`||returns the value from a function|
|40 | `<button onclick="getElementById("id").innerHTML=Date()">text</button>`|| displays output when onclick|
|41 | `<button onmouseover="getElementById("id").innerHTML=Date()">text</button>`|| displays output when on mouse hover|
|42 | `<button onmouseout="getElementById("id").innerHTML=Date()">text</button>`|| displays output when on mouse hover out|
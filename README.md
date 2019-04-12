# A Cheatsheet of Common JavaScript (ES6) VS. Python 3 Syntax

|                                                                                      |                                                                                  |                                                                                                                         | 
|--------------------------------------------------------------------------------------|----------------------------------------------------------------------------------|-------------------------------------------------------------------------------------------------------------------------| 
| JavaScript (ES6)                                                                     | Python 3                                                                         | Notes                                                                                                                   | 
| String methods / properties                                                          |                                                                                  |                                                                                                                         | 
| str.length                                                                           | len(string)                                                                      |                                                                                                                         | 
| ,reversed(string),".reverse() is an array method in JavaScript, NOT a string method" |                                                                                  |                                                                                                                         | 
|                                                                                      | str.count(searchvalue)                                                           | Returns the number of occurrences of a substring in a string.                                                           | 
| str.charAt(index)                                                                    | str[index]                                                                       |                                                                                                                         | 
| str.concat()                                                                         | str1 + str2                                                                      |                                                                                                                         | 
| str.endsWith(suffix)                                                                 | str.endswith(suffix)                                                             | "Python's string.endswith() also take options ""start"" and ""end"" parameters"                                         | 
| str.includes(searchvalue)                                                            | searchvalue in str                                                               |                                                                                                                         | 
| str.indexOf(searchvalue)                                                             | str.index(searchvalue)                                                           |                                                                                                                         | 
| str.lastIndexOf(searchvalue)                                                         | str.rfind(searchvalue)                                                           | Both return -1 if the substring is not found                                                                            | 
| str.math(/regex/g)                                                                   | re.findall(regex)                                                                | "Python requires ""import re"""                                                                                         | 
|                                                                                      | str.format(keywords)                                                             | Powerful function with many use cases. Similar in some ways to JavaScript's more limited template literals              | 
| "str.padStart(targetLength                                                           |  padString)                                                                      |                                                                                                                         | 
| str.padEnd(targetLength, padString)"                                                 | "str.zfill(width)                                                                |                                                                                                                         | 
| str.ljust(width                                                                      |  fillstring)                                                                     |                                                                                                                         | 
| str.rjust(width, fillstring)"                                                        | str.zfill() pads the left side of the string with zeros.                         |                                                                                                                         | 
| str.repeat(num)                                                                      | str * num                                                                        |                                                                                                                         | 
| "str.replace(/searchvalue/g, newvalue)"                                              | "str.replace(searchvalue, newvalue)"                                             | "Both are nonmutating. ""g"" modifier reqired in Javascript to replace all."                                            | 
| str.search(searchvalue)                                                              | str.find(searchvalue)                                                            |                                                                                                                         | 
| "str.slice(start, end)"                                                              | str[start:end]                                                                   | Both are nonmutating.                                                                                                   | 
| "str.split("""")"                                                                    | "str.split("""")"                                                                | JavaScript method with no properties splits on every charecter. Python method with no properties splits on every space. | 
| str.startsWith(searchvalue)                                                          | str.startswith(searchvalue)                                                      |                                                                                                                         | 
| "str.substr(start, length)"                                                          | str[start:end]                                                                   | JavaScript .slice() and .substring methods are similar with some differences.                                           | 
|                                                                                      | str.swapcase()                                                                   |                                                                                                                         | 
| str.toLowerCase()                                                                    | str.lower()                                                                      |                                                                                                                         | 
| str.toUpperCase()                                                                    | str.upper                                                                        |                                                                                                                         | 
| str.trim()                                                                           | str.strip()                                                                      |                                                                                                                         | 
|                                                                                      |                                                                                  |                                                                                                                         | 
| JavaScript array vs Python list                                                      |                                                                                  |                                                                                                                         | 
| array.length                                                                         | len(list)                                                                        |                                                                                                                         | 
| "array.toString()                                                                    |                                                                                  |                                                                                                                         | 
| array.join("""")",""""".join(list)"                                                  | "JavaScript .toString() leaves the commas in, equivalent to Python "","".join()" |                                                                                                                         | 
| array.pop()                                                                          | list.pop(-1)                                                                     | Both remove the last element of the array/list and return that value.                                                   | 
| array.push(elmnt)                                                                    | list.append(elmnt)                                                               | JavaScript .push() returns the new array length. Python .append doesn't return any value.                               | 
| array.shift()                                                                        | list.pop(0)                                                                      |                                                                                                                         | 
| array.unshift(elmnt)                                                                 | "list.insert(0, elmnt)"                                                          | JavaScript .unshift() returns the new array length. Python insert doesn't return any value.                             | 

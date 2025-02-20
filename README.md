# JavaScript Loose Equality (==) with Null and Undefined

This example demonstrates a common pitfall in JavaScript: the unexpected behavior of the loose equality operator (==) when comparing null and undefined.  While seemingly intuitive, loose equality can lead to subtle bugs if not carefully considered. The issue is highlighted in the `bug.js` file.

The solution, shown in `bugSolution.js`, addresses this by using strict equality (===) which avoids type coercion and leads to more predictable behavior. Using strict equality consistently can help avoid these types of issues.
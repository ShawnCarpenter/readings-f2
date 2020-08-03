# Template strings and forEach

## Yay! for template strings

Template strings are easier to read and easier to get right. When would you not want to use template strings?

 Really, there must be some situation where they aren't the best option but I'm not sure what that situation is. Other than supporting really old browsers. Like reeally old browsers.

## forEach()

foreach() runs a callback function for each element in an array. It returns undefined.

Oh, hey I found this out the hard way.
>There is no way to stop or break a forEach() loop other than by throwing an exception. If you need such behavior, the forEach() method is the wrong tool.

I went with a for loop instead. I probably should have just used find() instead.


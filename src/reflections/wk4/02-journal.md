## Promises

# What are the three states of a Promise?
The three states of a Promise is Pending, Resolved, and Rejected. The pending state is the initial state before the Promise is resolved or rejected. The resolved is a completed promise, and rejected is a failed promise.

# How do promises seek to resolve the issues of "callback hell"?
If we attach promises to callbacks instead of passing them through, it will look much cleaner because you can chain callbacks together. This is how to avoid 'callback hell'.

# What is the difference between .then() and .catch()?
The .then() method is used after a promise is resolved, and a .catch() method is used in case the promise is rejected. You can use the .catch() method after the .then() method as well, that way if the promise is rejected it jumps right over to the .catch().

afternoon challenge: https://github.com/hannahmilam/fall21-gregslist
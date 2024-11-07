## Await - promise.all()

Another way to take advantage of concurrency when we have multiple promises which can be executed simultaneously is to await a Promise.all().
We can pass an array of promises as the argument to Promise.all(), and it will return a single promise. Promise is an object that can be used to get the outcome of an asynchronous operation when that result is not instantly available.

This promise will resolve when all of the promises in the argument array have resolved. This promise’s resolve value will be an array containing the resolved values of each promise from the argument array.

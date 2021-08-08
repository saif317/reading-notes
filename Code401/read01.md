# **Node Ecosystem, TDD, CI/CD**

<img src="https://upload.wikimedia.org/wikipedia/commons/thumb/9/99/Unofficial_JavaScript_logo_2.svg/1024px-Unofficial_JavaScript_logo_2.svg.png" width="200">

## Describe (in plain English) what Array.map() does:

* [The map() method creates a new array populated with the results of calling a provided function on every element in the calling array.](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/map)

## Describe (in plain English) what Array.reduce() does:
    
* [The reduce() method executes a reducer function (that you provide) on each element of the array, resulting in a single output value.](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/Reduce)

## Provide code snippets showing how to use superagent() to fetch data from a URL and log the result
* With normal Promise .then() syntax : `superagent.post('/api/pet').then(console.log).catch(console.error);`

* Again with async / await syntax : 
```
(async () => {
  try {
    const res = await superagent.post('/api/pet');
    console.log(res);
  } catch (err) {
    console.error(err);
  }
})();
```

## Explain promises as though you were mentoring a Code 301 level student

* [A promise is a special JavaScript object that links the “producing code” and the “consuming code” together. In terms of our analogy: this is the “subscription list”. The “producing code” takes whatever time it needs to produce the promised result, and the “promise” makes that result available to all of the subscribed code when it’s ready.](https://javascript.info/promise-basics)

## Are all callback functions considered to be Asynchronous? Why or Why Not?

* No, the developer can use promises to make the callback Synchronous with the original function
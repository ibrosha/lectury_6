# lectury_6

# What is Synchronous in JavaScript?

- Что такое синхронность в JavaScript? Поскольку его базовый язык JavaScript является синхронным. Синхронный означает, что код выполняется в определенной последовательности инструкций, заданных в программе. Каждая инструкция ожидает завершения выполнения предыдущей инструкции.

![](https://www.scaler.com/topics/images/synchronous-vs-asynchronous-javascript-thumbnail.webp)

# ASYNCHRONOUS

- Различия между асинхронным и синхронным режимами включают в себя: Асинхронный режим является многопоточным, что означает, что операции или программы могут выполняться параллельно. Синхронизация является однопоточной, поэтому одновременно будет выполняться только одна операция или программа. Async не является блокирующим, что означает, что он отправляет несколько запросов на сервер.


## ASYNCHRONOUS

- Asynchronous code in JavaScript can be written using
- callbacks, 
- promises, 
- async/await syntax

- Обратные вызовы — это функции, которые передаются в качестве аргументов другим функциям и выполняются при вызове.
функция выполняет свою задачу. Обратные вызовы можно использовать для обработки асинхронных операций путем передачи обратного вызова.
функцию в асинхронный метод, который затем вызывает функцию обратного вызова после завершения операции.

![](/Screenshot_1.png)

# What is a Promise in JavaScript?

- What is a Promise in JavaScript? A Promise is a special JavaScript object. It produces a value after an asynchronous (aka, async) operation completes successfully, or an error if it does not complete successfully due to time out, network error, and so on.

- In JavaScript, a promise is a good way to handle asynchronous operations. It is used to 
find out if the asynchronous operation is successfully completed or not.

# A promise may have one of three states
- Pending

- Fulfilled

- Rejected


### To create a promise object, we use the Promise() constructor. let promise = new Promise(function(resolve, reject){ //do something }); The Promise() constructor takes a function as an argument. The function also accepts two functions resolve() and reject() .

![](/Без%20названия.png)

# Promise

- To create a promise object, we use the Promise() constructor.

![](/Screenshot_2.png)

- The Promise() constructor takes a function as an argument. The function also 
accepts two functions resolve() and reject().

- If the promise returns successfully, the resolve() function is called. 
And, if an error occurs, the reject() function is called.

# Async function

In JavaScript, async is a keyword placed before a function to allow the function to return a promise. Since JavaScript is a synchronous language, Async functions let us write promise-based code as if it were synchronous, but without blocking the execution thread that allows the code to run asynchronously.

![](https://blog.risingstack.com/wp-content/uploads/2021/06/async-await-nodejs-1024x486.png)

- We use the async keyword with a function to represent that the function is an 
asynchronous function. The async function returns a promise.

# Async await

- There is a special syntax for dealing with promises called "async/await". It is surprisingly easy to
understand and use.
The await keyword will cause the JavaScript interpreter to wait until the promise to the right of await
is fulfilled. After that, it will return its result, and code execution will continue.


![](/Screenshot_3.png)

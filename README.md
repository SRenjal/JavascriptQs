# JavascriptQs


###### What is `async` and `await`

<details><summary><b>Answer</b></summary>

`async` and `await` are features in JavaScript that allow for easier handling of asynchronous operations, such as fetching data from a server, reading a file, or waiting for a timer to finish. They were introduced in ECMAScript 2017 (ES8) and have since become a standard part of modern JavaScript.

Here's a brief explanation of each:

1. **`async`**: This keyword is used to declare that a function will handle asynchronous operations. Functions declared with `async` always return a promise, even if you don't explicitly return a promise inside the function. This makes it possible to use `await` within the function.

2. **`await`**: This keyword is used to pause the execution of an `async` function until a promise is resolved. It can only be used within an `async` function. When `await` is used, the function is paused until the promise is settled (fulfilled or rejected). If the promise is fulfilled, `await` returns the fulfilled value; if the promise is rejected, it throws an error, which can be caught using `try...catch`.

Here's a simple example:

```javascript
async function fetchData() {
  try {
    const response = await fetch('https://api.example.com/data');
    const data = await response.json();
    return data;
  } catch (error) {
    console.error('Error fetching data:', error);
    throw error;
  }
}

// Using the fetchData function
fetchData()
  .then(data => {
    console.log('Fetched data:', data);
  })
  .catch(error => {
    console.error('Error in fetchData:', error);
  });
```

In this example:

- `fetchData()` is declared as an `async` function, so it can use `await` to pause execution until the `fetch` operation is complete.
- Inside `fetchData()`, `await fetch('https://api.example.com/data')` pauses execution until the HTTP request is complete and the response is available.
- `await response.json()` pauses execution until the response body is read and parsed as JSON.
- If any errors occur during the asynchronous operations, they are caught by the `try...catch` block and logged.
- The `fetchData()` function returns a promise, so it can be used with `.then()` and `.catch()` to handle success and error cases respectively.

</details>

######

<details><summary><b>Answer</b></summary>

</details>
######

<details><summary><b>Answer</b></summary>

</details>
######

<details><summary><b>Answer</b></summary>

</details>
######

<details><summary><b>Answer</b></summary>

</details>
######

<details><summary><b>Answer</b></summary>

</details>
######

<details><summary><b>Answer</b></summary>

</details>
######

<details><summary><b>Answer</b></summary>

</details>
######

<details><summary><b>Answer</b></summary>

</details>
######

<details><summary><b>Answer</b></summary>

</details>
######

<details><summary><b>Answer</b></summary>

</details>
######

<details><summary><b>Answer</b></summary>

</details>
######

<details><summary><b>Answer</b></summary>

</details>
######

<details><summary><b>Answer</b></summary>

</details>
######

<details><summary><b>Answer</b></summary>

</details>
######

<details><summary><b>Answer</b></summary>

</details>
######

<details><summary><b>Answer</b></summary>

</details>
######

<details><summary><b>Answer</b></summary>

</details>
######

<details><summary><b>Answer</b></summary>

</details>
######

<details><summary><b>Answer</b></summary>

</details>

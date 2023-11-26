This is a quiz to check comprehension for reading through the documentation at https://developer.mozilla.org/en-US/docs/Web/API/Location.
You don’t have to memorize the page and can treat this as an open book quiz. The answers to some of the questions here won’t be on just the
page above, you’ll need to follow links to find the information on a related page.

Even if you already know the answer from experience, try to find the information in the documentation anyway.

---

### Part 1
**Answer the following questions using `https://rosiecheeks.tattoo/art#featured` as the url for the page.**
**For example, the value of `location.href` would be `https://rosiecheeks.tattoo/art#featured`.**

1. What is the value of `location.origin` for the url?

2. What is the value of `location.hash` for the url?

3. What is the value of `location.port` for the url?

### Part 2
Answer the following questions using `http://localhost:8080/blog/posts?tag=travel` as the url for the page.
For example, the value of `location.href` would be `http://localhost:8080/blog/posts?tag=travel`.

4. What is the value of `location.host` for the url?

5. What is the value of `location.pathname` for the url?

6. Some code you are working on is running into a problem with the `location.previous` field, which has
the value `undefined` for the url above. Why is this value `undefined`?

8. Given the url used in these examples above, what would the following code do?
```
console.log(location.href);
location.href = ‘https://www.google.com’;
```

### Part 3
The location object has fields that can be referenced, such as `location.port`, but it also has functions that can be called on it.
Answer the following questions about the functions available on the `location` object.

8. How many functions are mentioned in the documentation as being available on the `location` object and what are they?

9. A script you are working with uses the `location.assign()` method, but the code raises an exception with the error code `SYNTAX_ERROR`. What does this error mean?

10. How long has the `location.replace()` method been supported for the Microsoft Edge web browser?

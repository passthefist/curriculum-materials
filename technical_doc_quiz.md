This is a quiz to check comprehension for reading through the documentation at https://developer.mozilla.org/en-US/docs/Web/API/Location.
You don’t have to memorize the page and can treat this as an open book quiz. The answers to some of the questions here won’t be on just the
page above, you’ll need to follow links to find the information on a related page.

Even if you already know the answer from experience, try to find the information in the documentation anyway.

---

### Part 1
**Answer the following questions using `https://rosiecheeks.tattoo/art#featured` as the url for the page.**
**For example, the value of `location.href` would be `https://rosiecheeks.tattoo/art#featured`.**

1. What is the value of location.origin for the url?
https://rosiecheeks.tattoo

2. What is the value of location.hash for the url?
The value is `#featured`. The hash symbol is included in the value.

3. What is the value of location.port for the url?
The value is an empty string or ‘’. This information can be found by following the `location.port` link to a page with more details about the field: https://developer.mozilla.org/en-US/docs/Web/API/Location/port

### Part 2
Answer the following questions using `http://localhost:8080/blog/posts?tag=travel` as the url for the page.
For example, the value of `location.href` would be `http://localhost:8080/blog/posts?tag=travel`.

4. What is the value of `location.host` for the url?
localhost:8080

5. What is the value of `location.pathname` for the url?
/blog/posts

6. What is the value of `location.previous` for the url?
This value is undefined, since the `location` object has no `previous` field.

7. Given the url used in these examples above, what would the following code do?
```
console.log(location.href);
location.href = ‘https://www.google.com’;
```

This will redirect the current page to `https://www.google.com`. Documentation for this behavior can be found at https://developer.mozilla.org/en-US/docs/Web/API/Location/href.

### Part 3
The location object has fields that can be referenced, such as `location.port`, but it also has functions that can be called on it.
Answer the following questions about the functions available on the `location` object.

8. How many functions are mentioned in the documentation as being available on the `location` object and what are they?

The documentation mentions 4 functions, under the “methods” section, since methods are another name for functions.
These functions are `assign()`, `replace()`, `reload()`, and `toString()`.

9. A script you are working with uses the `location.assign()` method, but the code raises an exception with the error code `SYNTAX_ERROR`. What does this error mean?

It means that the url given to the `location.assign()` method is invalid.
This information can be found at the page https://developer.mozilla.org/en-US/docs/Web/API/Location/assign.

10. How long has the `location.replace()` method been supported for the Microsoft Edge web browser?
Since Version 12, which was released 2015-07-28. This information can be found at https://developer.mozilla.org/en-US/docs/Web/API/Location/replace#browser_compatibility,
and then clicking on the cell. <img width="290" alt="edge_docs" src="https://github.com/passthefist/curriculum-materials/assets/279303/354573ee-7d7f-4b83-9ea8-956d7902a135">


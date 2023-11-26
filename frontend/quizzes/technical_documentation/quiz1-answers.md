This is the answer key for quiz1.md

---

### Part 1

1. The value of `location.origin` for the url is `https://rosiecheeks.tattoo`.
This information can be found in the [Location Anotomy](https://developer.mozilla.org/en-US/docs/Web/API/Location#location_anatomy) part of the documentation.

2. The value of `location.hash` for the url is `#featured`. The hash symbol is included in the value.
This information can be found in the same Location Anatomy part of the documentation and also by clicking the
[location.hash](https://developer.mozilla.org/en-US/docs/Web/API/Location/hash) field to go to a page with more
details about it.

4. The value of location.port for the url is is an empty string or ‘’. This information can be found by following the
[location.port](https://developer.mozilla.org/en-US/docs/Web/API/Location/hash link to a page with more details about the field.

### Part 2

4. The value of `location.host` for the url is `localhost:8080`. This is found at the same place as questions 1 and 2.

5. The value of `location.pathname` for the url is `/blog/posts`. This is found at the same place as questions 1, 2, and 4.

6. The value of `location.previous` for the url is undefined since the `location` object has no `previous` field. This is
sort of a trick question, and the answer cannot be found directly in the documentation. However, it can be inferred since
the documentation does not include any references to a `previous` field. Sometimes, code might not be following correct
usage according to documentation.

8. The code in this question will first print the url for the current page, which is `http://localhost:8080/blog/posts?tag=travel`.
Next, it will redirect the page to ‘https://www.google.com’. Documentation for this behavior can be found at
https://developer.mozilla.org/en-US/docs/Web/API/Location/href.

### Part 3
The location object has fields that can be referenced, such as `location.port`, but it also has functions that can be called on it.
Answer the following questions about the functions available on the `location` object.

8. The documentation mentions 4 functions, under the [Instance Methods](https://developer.mozilla.org/en-US/docs/Web/API/Location#instance_methods)
section, since methods are another name for functions. These functions are `assign()`, `replace()`, `reload()`, and `toString()`.

10. This error means that the url given to the `location.assign()` method is invalid. This information can be found at the page
for https://developer.mozilla.org/en-US/docs/Web/API/Location/assign.

10. The `location.replace()` method been supported by the Microsoft Edge web browser since Version 12, which was released 2015-07-28.
This information can be found at https://developer.mozilla.org/en-US/docs/Web/API/Location/replace#browser_compatibility,
and then clicking on the cell. <img width="290" alt="edge_docs" src="https://github.com/passthefist/curriculum-materials/assets/279303/354573ee-7d7f-4b83-9ea8-956d7902a135">

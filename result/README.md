#  Form Submission Result Page

This displays the user's submitted form data using **HTML**, **CSS**, and **JavaScript**.  
It works with a validated form (`form.html`) and shows the input values using **URL parameters**.

---

##  What This Page Does

- It reads the submitted form data from the **URL**.
- Extracts parameters like `fullname`, `email`, `age`, and `gender`.
- Displays the data in a well-styled result box.
- Has a **"Go Back"** button to return to the form.

---
### 1. Submission:
When the user submits the form from `form.html`, JavaScript redirects them to:

### 2. Extraction:
In `result.html`, this line extracts all the parameters from the URL:

```js
const params = new URLSearchParams(window.location.search);
const fullname = params.get('fullname') || "Not provided";
outputDiv.innerHTML = `
  <p><strong>Full Name:</strong> ${fullname}</p>
  ...
`;


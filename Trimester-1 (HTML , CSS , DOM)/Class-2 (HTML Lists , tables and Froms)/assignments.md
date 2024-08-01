### Problem 1: Grocery List

**Statement:**  
Create an HTML document that displays a grocery list using both ordered and unordered lists. The ordered list should represent categories, and each category should contain an unordered list of items.

**Description:**  
Your task is to create a grocery list that categorizes items into different sections such as "Fruits," "Vegetables," and "Dairy." Each category should be represented using an ordered list, and the items under each category should be represented using unordered lists.

**Hints:**  
- Use `<ol>` for ordered lists and `<ul>` for unordered lists.
- Each category should be an item in the ordered list, and the items within each category should be listed as unordered lists.

**Solution Approach:**  
1. Create an ordered list to represent the categories.
2. For each category, create an unordered list to represent the items within that category.
3. Nest the unordered list inside the ordered list.

**Code Stub:**
```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Grocery List</title>
</head>
<body>
    <!-- Add your ordered and unordered lists here -->

</body>
</html>
```

**Complete Solution:**
```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Grocery List</title>
</head>
<body>
    <h1>Grocery List</h1>
    <ol>
        <li>Fruits
            <ul>
                <li>Apples</li>
                <li>Bananas</li>
                <li>Oranges</li>
            </ul>
        </li>
        <li>Vegetables
            <ul>
                <li>Carrots</li>
                <li>Broccoli</li>
                <li>Spinach</li>
            </ul>
        </li>
        <li>Dairy
            <ul>
                <li>Milk</li>
                <li>Cheese</li>
                <li>Yogurt</li>
            </ul>
        </li>
    </ol>
</body>
</html>
```

**Test Cases:**
1. Verify that the categories "Fruits," "Vegetables," and "Dairy" are displayed in order.
2. Verify that each category contains the correct unordered list of items.
3. Check the document structure to ensure the ordered list contains unordered lists.

---

### Problem 2: Contact Form

**Statement:**  
Create an HTML form that allows users to enter their contact information, including name, email, and message.

**Description:**  
Design a simple contact form using HTML form elements. The form should have fields for the user's name, email address, and a message. Include appropriate labels for each field and a submit button.

**Hints:**  
- Use `<form>` to create the form.
- Use `<label>` and `<input>` for name and email fields.
- Use `<textarea>` for the message field.
- Include a `<button>` or `<input type="submit">` to submit the form.

**Solution Approach:**  
1. Create a form element to contain the form fields.
2. Use input elements for the name and email, and a textarea for the message.
3. Use label elements to provide labels for each form field.
4. Add a submit button to submit the form.

**Code Stub:**
```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Contact Form</title>
</head>
<body>
    <!-- Add your form elements here -->

</body>
</html>
```

**Complete Solution:**
```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Contact Form</title>
</head>
<body>
    <h1>Contact Us</h1>
    <form action="#" method="post">
        <label for="name">Name:</label>
        <input type="text" id="name" name="name" required>
        <br>
        <label for="email">Email:</label>
        <input type="email" id="email" name="email" required>
        <br>
        <label for="message">Message:</label>
        <br>
        <textarea id="message" name="message" rows="4" cols="50" required></textarea>
        <br>
        <input type="submit" value="Submit">
    </form>
</body>
</html>
```

**Test Cases:**
1. Verify that all form fields are present: name, email, and message.
2. Check that labels are correctly associated with their respective inputs using the `for` attribute.
3. Ensure that submitting the form without filling all fields shows a required field message (this may vary based on browser validation settings).

---

### Problem 3: Student Grade Table

**Statement:**  
Create an HTML table to display a list of students and their grades in different subjects. Include a header row with column titles.

**Description:**  
Design a table to show student names along with their grades in three subjects: Math, Science, and English. The table should have a header row with column titles, and at least three rows of data.

**Hints:**  
- Use `<table>` to create the table.
- Use `<tr>` for table rows, `<th>` for header cells, and `<td>` for data cells.
- Ensure that the first row of the table uses header cells for column titles.

**Solution Approach:**  
1. Create a table element.
2. Add a header row using `<th>` to define the column titles.
3. Add rows of student data using `<td>` for each cell.

**Code Stub:**
```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Student Grades</title>
</head>
<body>
    <!-- Add your table here -->

</body>
</html>
```

**Complete Solution:**
```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Student Grades</title>
</head>
<body>
    <h1>Student Grades</h1>
    <table border="1">
        <thead>
            <tr>
                <th>Name</th>
                <th>Math</th>
                <th>Science</th>
                <th>English</th>
            </tr>
        </thead>
        <tbody>
            <tr>
                <td>John Doe</td>
                <td>90</td>
                <td>85</td>
                <td>88</td>
            </tr>
            <tr>
                <td>Jane Smith</td>
                <td>92</td>
                <td>89</td>
                <td>91</td>
            </tr>
            <tr>
                <td>Emily Johnson</td>
                <td>85</td>
                <td>87</td>
                <td>90</td>
            </tr>
        </tbody>
    </table>
</body>
</html>
```

**Test Cases:**
1. Verify that the table has four columns: Name, Math, Science, and English.
2. Check that the table has at least three rows of student data.
3. Ensure that the header row uses `<th>` elements and the data rows use `<td>` elements.


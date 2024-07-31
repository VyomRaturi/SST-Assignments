### Problem 1: Creating a Simple Webpage with Headings

#### Problem Name: Basic Headings Webpage

#### Problem Statement
Create a simple webpage that includes various heading tags to structure the content.

#### Description
You are required to create a basic HTML page that contains headings to organize content. Use heading tags from `<h1>` to `<h6>` to display a title, a subtitle, and several section headers.

#### Hints
- Use `<h1>` for the main title.
- Use `<h2>` for subtitles.
- Use `<h3>` to `<h6>` for section headings.

#### Solution Approach
1. Create an HTML document with a `<head>` and `<body>`.
2. Use the `<h1>` tag for the main title.
3. Use the `<h2>` tag for the subtitle.
4. Use the `<h3>` to `<h6>` tags for different sections.

#### Code Stub
```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Webpage</title>
</head>
<body>
    <!-- Write your code here -->
</body>
</html>
```

#### Complete Solution
```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Webpage</title>
</head>
<body>
    <h1>Main Title</h1>
    <h2>Subtitle</h2>
    <h3>Section 1</h3>
    <h4>Section 1.1</h4>
    <h5>Section 1.1.1</h5>
    <h6>Section 1.1.1.1</h6>
</body>
</html>
```

#### Test Cases
1. The page should have an `<h1>`
2. The page should have an `<h2>` 
3. The page should have an `<h3>` 
4. The page should have an `<h4>` 
5. The page should have an `<h5>`  
6. The page should have an `<h6>`

---

### Problem 2: Adding an Image to Your Webpage

#### Problem Name: Image Display

#### Problem Statement
Create an HTML page that displays an image using the `<img>` tag.

#### Description
You need to create an HTML document that includes an image. Use the `<img>` tag to embed an image from a given URL.

#### Hints
- Use the `src` attribute to specify the image URL.
- Use the `alt` attribute to provide alternative text for the image.

#### Solution Approach
1. Create an HTML document with a `<head>` and `<body>`.
2. Use the `<img>` tag to add an image to the page.
3. Set the `src` attribute to the image URL.
4. Set the `alt` attribute to a description of the image.

#### Code Stub
```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Webpage</title>
</head>
<body>
    <!-- Write your code here -->
</body>
</html>
```

#### Complete Solution
```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Webpage</title>
</head>
<body>
    <img src="https://via.placeholder.com/150" alt="Placeholder Image">
</body>
</html>
```

#### Test Cases
1. The page should include an `<img>` tag.
2. The `src` attribute of the `<img>` tag should be set to "https://via.placeholder.com/150".
3. The `alt` attribute of the `<img>` tag should be set to "Placeholder Image".

---

### Problem 3: Creating Links with Anchor Tags

#### Problem Name: Anchor Tag Links

#### Problem Statement
Create an HTML page that includes anchor tags to link to other webpages.

#### Description
You need to create an HTML document that contains links to other webpages using anchor tags. Use the `<a>` tag to create links with descriptive text.

#### Hints
- Use the `href` attribute to specify the URL.
- The text between the `<a>` tags will be the clickable link text.

#### Solution Approach
1. Create an HTML document with a `<head>` and `<body>`.
2. Use the `<a>` tag to create links.
3. Set the `href` attribute to the URL you want to link to.
4. Provide descriptive link text between the opening and closing `<a>` tags.

#### Code Stub
```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Webpage</title>
</head>
<body>
    <!-- Write your code here -->
</body>
</html>
```

#### Complete Solution
```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Webpage</title>
</head>
<body>
    <a href="https://www.example.com">Visit Example.com</a>
    <a href="https://www.google.com">Visit Google</a>
</body>
</html>
```

#### Test Cases
1. The page should include an `<a>` tag with `href="https://www.example.com"` and link text "Visit Example.com".
2. The page should include an `<a>` tag with `href="https://www.google.com"` and link text "Visit Google".
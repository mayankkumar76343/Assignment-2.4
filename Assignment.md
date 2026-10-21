Assignment 2.4 — HTML Validation & Debugging1. Before: Buggy HTML Code
The following HTML contains several intentional errors.

<!DOCTYPE html>
<html>
<head>
    <title>HTML Debugging Assignment</title>
<body>
    <h1>Welcome to My Website
    <p>This is a sample paragraph.
    <img src="image.jpg">
    <ul>
        <li>HTML
        <li>CSS</ul>
    <a href="https://example.com">Visit Example
</body>
</html>
2. Errors Identified
Missing closing </head> tag.
Missing closing </h1> tag.
Missing closing </p> tag.
The image is missing an alt attribute.
Missing closing </li> tags.
Incorrect nesting of the </ul> tag.
Missing closing </a> tag.
Improper indentation and formatting.
3. Debugging Process
Step 1: Inspect with Browser DevTools
Open the HTML file in a web browser.
Right-click the webpage and select Inspect.
Open the Elements panel.
Inspect the HTML structure and identify incorrectly nested or automatically corrected elements.
Step 2: Validate the HTML
Open the W3C Markup Validation Service: https://validator.w3.org/
Upload the HTML file or paste the source code.
Review the reported errors and warnings.
Correct the markup and validate it again.
Step 3: Fix the Errors
Add missing closing tags.
Correct the nesting of list elements.
Add the required alt attribute to the image.
Properly indent the HTML code.
4. After: Corrected HTML Code
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>HTML Debugging Assignment</title>
</head>
<body>
    <h1>Welcome to My Website</h1>

    <p>This is a sample paragraph.</p>

    <img src="image.jpg" alt="A sample image">

    <ul>
        <li>HTML</li>
        <li>CSS</li>
    </ul>

    <a href="https://example.com">Visit Example</a>
</body>
</html>
5. Expected Webpage Output
The corrected webpage displays:

A heading: Welcome to My Website
A paragraph: This is a sample paragraph.
An image, if image.jpg exists in the correct location.
A bulleted list containing HTML and CSS.
A clickable link labeled Visit Example.
6. Screenshot Requirements
Capture and attach the following screenshots to the assignment:

Before debugging: The original HTML code with errors.
DevTools inspection: The Elements panel showing the webpage's DOM structure.
After debugging: The corrected webpage displayed in the browser.
Validation result: The W3C validator showing the corrected document has no HTML errors.
Note: The corrected HTML is designed to pass validation. The final result should be verified using the W3C validator.

7. Result
The HTML errors were identified and corrected. Missing tags and attributes were added, incorrect nesting was fixed, and the code was properly indented. Browser Developer Tools and the W3C Markup Validation Service were used as debugging and verification methods.

Conclusion: HTML validation and debugging help create well-structured, accessible, and maintainable webpages.


---

### **Sample 20 Questions with Answers (5 Marks Each)**

---

### **Unit 1: Introduction to HTML**

1. **What does HTML stand for, and what is its purpose?**
   - HTML stands for Hyper Text Markup Language. It is the standard markup language used for creating web pages. HTML is used to define the structure of a webpage by marking up the content with tags, such as headings, paragraphs, lists, links, images, and tables. It also supports multimedia, form creation, and linking different web pages together.

---

2. **Who invented HTML and when?**
   - HTML was invented by Sir Timothy John Berners-Lee (Tim Berners-Lee) in 1991. He developed it as a system to allow researchers at CERN to share and access documents using hyperlinks, leading to the creation of the World Wide Web.

---

3. **What is the difference between the Internet and the World Wide Web?**
   - The **Internet** is a global network that connects millions of computers, allowing data to be shared across different systems. It includes services like email, file transfer, and web browsing.
   - The **World Wide Web** (WWW) is a subset of the Internet, consisting of interconnected web pages that are accessed via browsers using HTTP. It uses web technologies like HTML to display content.

---

4. **What is the role of the `<doctype>` declaration in HTML?**
   - The `<!DOCTYPE html>` declaration defines the document type and version of HTML being used. It helps web browsers render the page correctly according to HTML standards. In HTML5, `<!DOCTYPE>` is simplified and only tells the browser that the document is written in HTML5.

---

5. **Explain the process of loading a webpage using HTTP.**
   - When you type a URL into a browser, the browser sends a request to the web server using the HTTP protocol. The server responds by sending back the HTML page or resource requested. If the page exists, the server sends a 200 OK response with the page content. If the page doesn’t exist, it sends a 404 error response.

---

### **Unit 2: Basic HTML Document Structure**

6. **Write a basic HTML document structure.**
   ```html
   <!DOCTYPE html>
   <html>
   <head>
       <title>My First Webpage</title>
   </head>
   <body>
       <h1>Welcome to my Webpage</h1>
       <p>This is a simple HTML document.</p>
   </body>
   </html>
   ```
   - This structure includes the doctype declaration, the `<html>` tag which contains the document, the `<head>` section with the title, and the `<body>` section where content is displayed.

---

7. **Explain the difference between the `<head>` and `<body>` elements in HTML.**
   - The `<head>` element contains meta-information about the webpage, such as the title, links to stylesheets, scripts, and metadata. It is not directly displayed on the page. The `<body>` element contains the actual content that is displayed in the browser, such as text, images, and links.

---

8. **What are HTML tags and how do they function?**
   - HTML tags are keywords enclosed in angle brackets (e.g., `<p>`, `<h1>`, `<a>`). They define how content should be displayed in a web browser. Most tags come in pairs: an opening tag (e.g., `<p>`) and a closing tag (e.g., `</p>`), with the content between them being affected by the tag.

---

9. **What is the purpose of the `<title>` element in HTML?**
   - The `<title>` element, placed inside the `<head>` section, defines the title of the webpage, which appears in the browser's title bar or tab. It is also used by search engines to index the content of the page, making it important for SEO.

---

10. **Explain the difference between block-level and inline-level elements.**
    - **Block-level elements** (e.g., `<div>`, `<p>`, `<h1>`) take up the full width available and start on a new line. They are used for structuring the layout of a webpage.
    - **Inline-level elements** (e.g., `<span>`, `<a>`, `<strong>`) do not start on a new line and only take up as much width as necessary. They are used to format text within block elements.

---

### **Unit 3: Content and Character Formatting**

11. **What is the difference between `<br>` and `<hr>` tags in HTML?**
    - The `<br>` tag inserts a line break, moving the content to the next line. It is an empty tag with no closing tag.
    - The `<hr>` tag inserts a horizontal rule (a line) used to separate sections of content. It is also an empty tag.

---

12. **How do you create an unordered list in HTML? Provide an example.**
    ```html
    <ul>
        <li>Item 1</li>
        <li>Item 2</li>
        <li>Item 3</li>
    </ul>
    ```
    - This code creates a bulleted (unordered) list with three list items: Item 1, Item 2, and Item 3.

---

13. **Explain how to format text in bold and italics using HTML.**
    - To make text bold, use the `<strong>` or `<b>` tag:
      ```html
      <strong>This text is bold.</strong>
      ```
    - To make text italicized, use the `<em>` or `<i>` tag:
      ```html
      <em>This text is italic.</em>
      ```

---

14. **What are special characters in HTML, and why are they used? Provide examples.**
    - Special characters in HTML are reserved characters that cannot be used directly in the content. They must be written as character entities. For example:
      - `<` is written as `&lt;`
      - `>` is written as `&gt;`
      - `&` is written as `&amp;`
      These are used to avoid confusion between content and HTML tags.

---

15. **How do you create a nested list in HTML? Provide an example.**
    ```html
    <ul>
        <li>Item 1
            <ul>
                <li>Subitem 1</li>
                <li>Subitem 2</li>
            </ul>
        </li>
        <li>Item 2</li>
    </ul>
    ```
    - This code creates an unordered list with "Item 1" having two subitems in a nested list.

---

### **Unit 4: Adding Links, Images, and Tables**

16. **How do you create a hyperlink in HTML? Provide an example.**
    ```html
    <a href="https://www.example.com">Visit Example</a>
    ```
    - This code creates a hyperlink that, when clicked, takes the user to `https://www.example.com`.

---

17. **Write HTML code to create a table with 2 rows and 2 columns.**
    ```html
    <table border="1">
        <tr>
            <td>Row 1, Cell 1</td>
            <td>Row 1, Cell 2</td>
        </tr>
        <tr>
            <td>Row 2, Cell 1</td>
            <td>Row 2, Cell 2</td>
        </tr>
    </table>
    ```
    - This code creates a simple table with two rows and two columns, with borders around each cell.

---

18. **How do you add an image to an HTML document? Provide an example.**
    ```html
    <img src="image.jpg" alt="Description of Image">
    ```
    - The `<img>` tag is used to add an image to a webpage. The `src` attribute specifies the image file location, and the `alt` attribute provides alternative text if the image cannot be displayed.

---

19. **Explain how to create a link that opens in a new tab.**
    - Use the `target="_blank"` attribute in the `<a>` tag to open the link in a new tab:
      ```html
      <a href="https://www.example.com" target="_blank">Visit Example</a>
      ```

---

20. **How do you add a caption to a table in HTML?**
    ```html
    <table>
        <caption>My Table Caption</caption>
        <tr>
            <td>Data 1</td>
            <td>Data 2</td>
        </tr>
    </table>
    ```
    - The `<caption>` tag adds a caption to a table, usually displayed above the table.

---

### **Next Steps:**

---

### **Unit 5: Forms and Input Elements**

21. **What is the purpose of the `<form>` element in HTML?**
    - The `<form>` element is used to collect user input. It creates a form on the webpage where users can enter data, such as text, numbers, or selections, and submit it to a server for processing. The form contains input elements such as text fields, checkboxes, radio buttons, and submit buttons.

---

22. **How do you create a password field in an HTML form?**
    ```html
    <form>
        <label for="password">Password:</label>
        <input type="password" id="password" name="password">
    </form>
    ```
    - The `type="password"` attribute creates a password input field where the user can enter a password, and the characters will be hidden.

---

23. **Explain the difference between the `GET` and `POST` methods in HTML forms.**
    - **GET**: The `GET` method appends form data to the URL, making it visible in the browser’s address bar. It is suitable for non-sensitive data and for retrieving data from the server (like search queries).
    - **POST**: The `POST` method sends form data as part of the request body, which is not visible in the URL. It is more secure and suitable for submitting sensitive information such as passwords.

---

24. **How do you create radio buttons in an HTML form? Provide an example.**
    ```html
    <form>
        <label for="option1">Option 1</label>
        <input type="radio" id="option1" name="options" value="1">
        
        <label for="option2">Option 2</label>
        <input type="radio" id="option2" name="options" value="2">
    </form>
    ```
    - This code creates two radio buttons, allowing the user to select only one option from the given choices.

---

25. **Write HTML code to create a dropdown menu in a form.**
    ```html
    <form>
        <label for="cars">Choose a car:</label>
        <select id="cars" name="car">
            <option value="volvo">Volvo</option>
            <option value="bmw">BMW</option>
            <option value="mercedes">Mercedes</option>
        </select>
    </form>
    ```
    - This code creates a dropdown menu where the user can select one car from the given options.

---

26. **What is the `<textarea>` element used for in forms? Provide an example.**
    - The `<textarea>` element is used for multi-line text input, such as entering comments or feedback. Example:
      ```html
      <form>
          <label for="comments">Comments:</label>
          <textarea id="comments" name="comments" rows="4" cols="50"></textarea>
      </form>
      ```

---

27. **How do you create a form that submits data to a server using the `POST` method?**
    ```html
    <form action="/submit-form" method="POST">
        <label for="name">Name:</label>
        <input type="text" id="name" name="name">
        <input type="submit" value="Submit">
    </form>
    ```
    - This code creates a form that submits the entered data using the `POST` method to the specified server endpoint (`/submit-form`).

---

28. **Explain the purpose of the `<fieldset>` and `<legend>` elements in HTML forms.**
    - The `<fieldset>` element groups related elements in a form, and the `<legend>` element provides a caption for the fieldset. Example:
      ```html
      <fieldset>
          <legend>Personal Information</legend>
          <label for="name">Name:</label>
          <input type="text" id="name" name="name">
      </fieldset>
      ```

---

29. **How do you create a submit button in an HTML form?**
    ```html
    <form>
        <input type="submit" value="Submit">
    </form>
    ```
    - This code creates a submit button that sends the form data to the server when clicked.

---

30. **How can you create a reset button in an HTML form, and what is its purpose?**
    ```html
    <form>
        <input type="reset" value="Reset">
    </form>
    ```
    - The reset button clears all the form fields, resetting them to their default values.

---

### **Unit 6: CSS and Styling Basics**

31. **What is CSS and why is it used in web development?**
    - CSS (Cascading Style Sheets) is used to style and layout HTML documents. It controls the appearance of elements on a webpage, including colors, fonts, spacing, layout, and more. CSS allows developers to separate content (HTML) from design (CSS), making websites easier to maintain and update.

---

32. **What is the difference between inline, internal, and external CSS?**
    - **Inline CSS**: Styles are applied directly to HTML elements using the `style` attribute (e.g., `<p style="color: red;">`).
    - **Internal CSS**: Styles are defined within the `<style>` element inside the `<head>` of the HTML document.
    - **External CSS**: Styles are placed in an external file (e.g., `styles.css`) and linked to the HTML document using the `<link>` element.

---

33. **Write CSS code to change the background color of a webpage to light blue.**
    ```css
    body {
        background-color: lightblue;
    }
    ```

---

34. **How do you center a block element horizontally using CSS?**
    ```css
    div {
        width: 50%;
        margin: 0 auto;
    }
    ```
    - The `width` property defines the width of the element, and the `margin: 0 auto;` centers it horizontally.

---

35. **What is the CSS box model?**
    - The CSS box model is a concept that describes the layout of elements in a webpage. It consists of four components:
      - **Content**: The actual content of the element (text or images).
      - **Padding**: The space between the content and the border.
      - **Border**: The line surrounding the padding.
      - **Margin**: The space outside the border, separating the element from other elements.

---

36. **Explain the difference between `margin` and `padding` in CSS.**
    - **Padding**: The space between the content of an element and its border. It increases the element’s size but doesn’t affect its position.
    - **Margin**: The space outside the element's border. It affects the distance between elements and can be used to position them.

---

37. **How do you apply a CSS rule to multiple elements in HTML? Provide an example.**
    - You can apply the same CSS rule to multiple elements by separating their selectors with commas. Example:
      ```css
      h1, h2, p {
          color: blue;
      }
      ```
    - This CSS rule applies the color blue to all `<h1>`, `<h2>`, and `<p>` elements.

---

38. **What is the purpose of the `float` property in CSS?**
    - The `float` property is used to position an element to the left or right of its container, allowing text or other elements to wrap around it. It is commonly used for creating multi-column layouts or for positioning images.

---

39. **Write CSS code to create a horizontal navigation bar with links.**
    ```css
    nav {
        background-color: #333;
    }

    nav a {
        color: white;
        padding: 14px 20px;
        text-decoration: none;
        display: inline-block;
    }

    nav a:hover {
        background-color: #ddd;
        color: black;
    }
    ```
    - This CSS code creates a horizontal navigation bar with links that change color when hovered.

---

40. **How do you create rounded corners for an element using CSS?**
    ```css
    div {
        border-radius: 10px;
    }
    ```
    - The `border-radius` property creates rounded corners for an element. In this case, it sets the corner radius to 10 pixels.

---

### **Next Steps:**

---

### **Unit 5: Forms and Input Elements (Continued)**

41. **What are the attributes of the `<form>` element in HTML?**
   - The main attributes of the `<form>` element are:
     - `action`: Specifies where to send the form data when the form is submitted.
     - `method`: Specifies how to send form data. The common methods are `GET` (appends form data to the URL) and `POST` (sends data as a request body).
     - `enctype`: Specifies how form data should be encoded when submitting it to the server (usually `multipart/form-data` for file uploads).
     - `target`: Specifies where to display the response (e.g., `_blank` for a new tab).

---

42. **How do you create a checkbox in an HTML form? Provide an example.**
   ```html
   <form>
       <label for="subscribe">Subscribe to newsletter:</label>
       <input type="checkbox" id="subscribe" name="subscribe" value="yes">
   </form>
   ```
   - This code creates a checkbox with a label. Users can check the box to subscribe to a newsletter.

---

43. **Explain the difference between a text input field and a textarea in an HTML form.**
   - A **text input field** (`<input type="text">`) is a single-line field used for short input, like entering a name or email.
   - A **textarea** (`<textarea>`) is a multi-line input field, typically used for longer text like comments or messages.
     ```html
     <input type="text" name="name">
     <textarea name="message" rows="4" cols="50"></textarea>
     ```

---

44. **What is the `placeholder` attribute in an HTML form? Provide an example.**
   - The `placeholder` attribute specifies a short hint or example inside the input field, guiding users on what to enter. This text disappears when the user starts typing.
     ```html
     <input type="text" name="username" placeholder="Enter your username">
     ```

---

45. **How do you create a file upload field in an HTML form?**
   ```html
   <form action="/upload" method="post" enctype="multipart/form-data">
       <label for="file">Choose file:</label>
       <input type="file" id="file" name="file">
       <input type="submit" value="Upload">
   </form>
   ```
   - This code allows users to select a file to upload. The `enctype="multipart/form-data"` attribute is required for file uploads.

---

46. **How do you create a form that includes a reset button? What does the reset button do?**
   - A reset button clears all form fields and resets them to their default values.
     ```html
     <form>
         <input type="text" name="name">
         <input type="reset" value="Reset Form">
     </form>
     ```

---

47. **What is the purpose of the `name` attribute in form input elements?**
   - The `name` attribute assigns a name to the input element. It is important because it is used as a key when the form data is submitted to the server. Without a `name`, the input data will not be sent.

---

48. **How do you make a specific option in a dropdown menu pre-selected in HTML?**
   ```html
   <select name="cars">
       <option value="volvo" selected>Volvo</option>
       <option value="bmw">BMW</option>
   </select>
   ```
   - The `selected` attribute makes the "Volvo" option pre-selected in this dropdown menu.

---

49. **Explain how to create an email input field in an HTML form.**
   ```html
   <form>
       <label for="email">Email:</label>
       <input type="email" id="email" name="email" required>
   </form>
   ```
   - The `type="email"` ensures that the input must be in a valid email format (e.g., user@example.com). The `required` attribute ensures that this field cannot be left empty.

---

50. **How do you create a hidden input field in an HTML form? Provide an example.**
   ```html
   <input type="hidden" name="userid" value="12345">
   ```
   - The `type="hidden"` input field is not visible to the user but still sends its value to the server when the form is submitted.

---

### **Unit 7: HTML Multimedia Elements**

51. **How do you add an audio file to a webpage using HTML?**
   ```html
   <audio controls>
       <source src="audiofile.mp3" type="audio/mpeg">
       Your browser does not support the audio element.
   </audio>
   ```
   - The `<audio>` tag allows you to add sound content to the webpage. The `controls` attribute adds play, pause, and volume controls.

---

52. **How do you embed a video in an HTML webpage?**
   ```html
   <video width="320" height="240" controls>
       <source src="video.mp4" type="video/mp4">
       Your browser does not support the video tag.
   </video>
   ```
   - The `<video>` tag is used to embed videos in HTML. It allows you to define controls, width, and height.

---

53. **What is the `controls` attribute in the `<audio>` and `<video>` tags?**
   - The `controls` attribute is used to add controls like play, pause, volume, and progress bar to the audio or video player. Without it, users will not have any interaction options.

---

54. **How can you autoplay a video on a webpage using HTML?**
   ```html
   <video width="320" height="240" autoplay>
       <source src="video.mp4" type="video/mp4">
       Your browser does not support the video tag.
   </video>
   ```
   - The `autoplay` attribute automatically plays the video when the page loads.

---

55. **Explain the use of the `<track>` element in HTML multimedia.**
   - The `<track>` element is used to specify text tracks for `<video>` and `<audio>` elements. It provides subtitles, captions, or descriptions in different languages.
     ```html
     <track src="subtitles_en.vtt" kind="subtitles" srclang="en" label="English">
     ```

---

56. **What are the different file formats supported by the `<audio>` tag in HTML?**
   - The `<audio>` tag supports:
     - MP3 (`audio/mpeg`)
     - WAV (`audio/wav`)
     - Ogg (`audio/ogg`)

---

57. **What are the different file formats supported by the `<video>` tag in HTML?**
   - The `<video>` tag supports:
     - MP4 (`video/mp4`)
     - WebM (`video/webm`)
     - Ogg (`video/ogg`)

---

58. **How do you loop a video or audio file using HTML?**
   - The `loop` attribute allows a video or audio file to repeat indefinitely.
     ```html
     <audio src="audiofile.mp3" controls loop></audio>
     <video src="videofile.mp4" controls loop></video>
     ```

---

59. **How do you add subtitles to a video using HTML?**
   ```html
   <video controls>
       <source src="video.mp4" type="video/mp4">
       <track src="subtitles_en.vtt" kind="subtitles" srclang="en" label="English">
   </video>
   ```
   - The `<track>` element adds subtitles to the video. The `src` attribute points to the subtitle file, `kind` specifies the type (subtitles), `srclang` defines the language, and `label` names the track.

---

60. **Explain the difference between `<embed>` and `<object>` elements in HTML.**
   - The `<embed>` tag is used to embed external content, such as multimedia, into a webpage, but it lacks the flexibility of the `<object>` tag.
   - The `<object>` tag can embed various types of media, including plugins and interactive content, and provides more control over how the object is displayed and how fallback content is handled.
     ```html
     <embed src="mediafile.mp4">
     <object data="mediafile.mp4"></object>
     ```

---

### **Unit 8: HTML Frames and Iframes**

61. **What is the purpose of the `<iframe>` element in HTML?**
   - The `<iframe>` (inline frame) element is used to embed another webpage inside the current webpage. It can display external content, such as a map or another website.
     ```html
     <iframe src="https://www.example.com" width="600" height="400"></iframe>
     ```

---

62. **How do you target a link to open in an `<iframe>`?**
   ```html
   <iframe name="myiframe" src="about:blank" width="600" height="400"></iframe>
   <a href="page.html" target="myiframe">Open in Iframe</a>
   ```
   - The `name` attribute of the `<iframe>` is used as the `target` for the link. When the link is clicked, the content is displayed in the

 iframe.

---

63. **Explain the `sandbox` attribute in an `<iframe>` element.**
   - The `sandbox` attribute applies extra restrictions to the content loaded in an iframe. For example, it can prevent scripts from running or block pop-ups. It enhances security by limiting the behavior of the embedded content.
     ```html
     <iframe src="page.html" sandbox></iframe>
     ```

---

64. **How do you make an iframe responsive in HTML?**
   - To make an iframe responsive, you can set its width to 100% and height proportional to the width. Use a container element with a percentage-based padding to maintain aspect ratio.
     ```html
     <div style="position: relative; padding-bottom: 56.25%; height: 0;">
         <iframe src="https://www.example.com" style="position: absolute; width: 100%; height: 100%;"></iframe>
     </div>
     ```

---

65. **What is the purpose of the `srcdoc` attribute in an `<iframe>`?**
   - The `srcdoc` attribute is used to specify the HTML content to display directly inside an iframe, rather than loading it from an external URL.
     ```html
     <iframe srcdoc="<p>This is content from srcdoc.</p>"></iframe>
     ```

---

### **Next Steps:**


---

### **Unit 8: HTML Frames and Iframes (Continued)**

66. **What is the difference between the `<iframe>` and `<frame>` elements in HTML?**
   - The `<iframe>` element is used to embed another webpage inside the current document. It is inline and can be placed anywhere within the HTML body.
   - The `<frame>` element, on the other hand, was used in the `<frameset>` model to divide a browser window into multiple, independently scrollable sections, each displaying different HTML documents. However, frames are deprecated in HTML5, while iframes are still used.
     ```html
     <iframe src="example.html"></iframe>
     <!-- Frameset example is deprecated -->
     ```

---

67. **How do you disable interaction with an iframe using HTML?**
   - You can disable interaction with an iframe using the `pointer-events: none;` CSS property. This will prevent users from clicking or interacting with the iframe content.
     ```html
     <iframe src="example.html" style="pointer-events: none;"></iframe>
     ```

---

68. **Explain how the `src` attribute works in an `<iframe>` element.**
   - The `src` attribute in an `<iframe>` specifies the URL of the document to be displayed inside the iframe. This can be any valid URL, including an external webpage or another page from the same domain.
     ```html
     <iframe src="https://www.example.com"></iframe>
     ```

---

69. **How do you prevent an iframe from loading content from external sites using the `sandbox` attribute?**
   - The `sandbox` attribute provides restrictions on what an iframe can do. To prevent an iframe from loading content from external sites, you can use the `sandbox` attribute without the `allow-same-origin` keyword.
     ```html
     <iframe src="example.html" sandbox></iframe>
     ```

---

### **Unit 9: HTML Tables**

70. **What is the purpose of the `<table>` element in HTML?**
   - The `<table>` element is used to create a table that organizes data into rows and columns. It is composed of several sub-elements, such as `<tr>` for rows, `<td>` for data cells, and `<th>` for header cells.
     ```html
     <table>
         <tr>
             <th>Heading 1</th>
             <th>Heading 2</th>
         </tr>
         <tr>
             <td>Data 1</td>
             <td>Data 2</td>
         </tr>
     </table>
     ```

---

71. **How do you span a table cell across multiple columns in HTML?**
   - You can use the `colspan` attribute in the `<td>` or `<th>` element to make a cell span across multiple columns.
     ```html
     <table>
         <tr>
             <td colspan="2">Spanning Two Columns</td>
         </tr>
     </table>
     ```

---

72. **How do you span a table cell across multiple rows in HTML?**
   - You can use the `rowspan` attribute in the `<td>` or `<th>` element to make a cell span across multiple rows.
     ```html
     <table>
         <tr>
             <td rowspan="2">Spanning Two Rows</td>
             <td>Row 1, Cell 2</td>
         </tr>
         <tr>
             <td>Row 2, Cell 2</td>
         </tr>
     </table>
     ```

---

73. **How do you create a table with a caption in HTML?**
   - The `<caption>` element is used to add a caption to a table, typically displayed above the table.
     ```html
     <table>
         <caption>Sample Table</caption>
         <tr>
             <th>Heading 1</th>
             <th>Heading 2</th>
         </tr>
         <tr>
             <td>Data 1</td>
             <td>Data 2</td>
         </tr>
     </table>
     ```

---

74. **What is the purpose of the `<thead>`, `<tbody>`, and `<tfoot>` elements in an HTML table?**
   - These elements help structure a table into distinct sections:
     - **`<thead>`**: Defines the table's header section.
     - **`<tbody>`**: Contains the table's body, where the main data is placed.
     - **`<tfoot>`**: Contains the table's footer, often used for summarizing the content or showing totals.
     ```html
     <table>
         <thead>
             <tr>
                 <th>Heading 1</th>
                 <th>Heading 2</th>
             </tr>
         </thead>
         <tbody>
             <tr>
                 <td>Data 1</td>
                 <td>Data 2</td>
             </tr>
         </tbody>
         <tfoot>
             <tr>
                 <td>Footer 1</td>
                 <td>Footer 2</td>
             </tr>
         </tfoot>
     </table>
     ```

---

75. **How do you add borders to a table in HTML?**
   - You can add borders to a table using the `border` attribute in the `<table>` element.
     ```html
     <table border="1">
         <tr>
             <th>Header 1</th>
             <th>Header 2</th>
         </tr>
         <tr>
             <td>Data 1</td>
             <td>Data 2</td>
         </tr>
     </table>
     ```

---

76. **Explain the use of the `scope` attribute in HTML tables.**
   - The `scope` attribute specifies whether a `<th>` element is related to a row, column, or group of rows/columns. It helps improve accessibility by indicating which header a cell relates to.
     ```html
     <th scope="col">Column Header</th>
     <th scope="row">Row Header</th>
     ```

---

77. **How do you create a table without borders in HTML?**
   - To create a table without borders, simply omit the `border` attribute or set it to `0`.
     ```html
     <table>
         <tr>
             <th>Header 1</th>
             <th>Header 2</th>
         </tr>
         <tr>
             <td>Data 1</td>
             <td>Data 2</td>
         </tr>
     </table>
     ```

---

78. **How do you control the alignment of text within a table cell in HTML?**
   - You can control text alignment in a table cell using the `align` attribute or using the `text-align` CSS property.
     ```html
     <table>
         <tr>
             <td align="center">Centered Text</td>
             <td align="right">Right-Aligned Text</td>
         </tr>
     </table>
     ```

---

79. **How do you create a table with alternating row colors in HTML?**
   - You can use the `bgcolor` attribute in the `<tr>` element to set the background color for alternating rows, or you can use CSS for this purpose.
     ```html
     <table>
         <tr bgcolor="#f2f2f2">
             <td>Row 1</td>
             <td>Data</td>
         </tr>
         <tr bgcolor="#ffffff">
             <td>Row 2</td>
             <td>Data</td>
         </tr>
     </table>
     ```

---

80. **What is the difference between `<th>` and `<td>` in HTML tables?**
   - `<th>` stands for **table header** and is used for table headers. By default, the content in `<th>` is bold and centered.
   - `<td>` stands for **table data** and is used for regular data cells in a table. The content in `<td>` is left-aligned by default.

---

### **Unit 10: HTML Forms (More Examples)**

81. **How do you add a label to an HTML form element?**
   - The `<label>` element is used to associate text with a specific form element, making the form more accessible.
     ```html
     <form>
         <label for="name">Name:</label>
         <input type="text" id="name" name="name">
     </form>
     ```

---

82. **Explain the difference between the `id` and `name` attributes in form elements.**
   - **`id`**: A unique identifier for an element in the DOM. It is used to target elements in JavaScript or CSS and to associate `<label>` elements with form inputs.
   - **`name`**: Specifies the name of the input field and is used when sending form data to the server. The `name` attribute is critical in form submission.

---

83. **How do you set a form field as required in HTML?**
   - The `required` attribute ensures that a user must fill in the field before submitting the form.
     ```html
     <input type="text" name="username" required>
     ```

---

84. **What does the `maxlength` attribute do in an HTML form input?**
   - The `maxlength` attribute specifies the maximum number of characters a user can enter into a text input field.
     ```html


     <input type="text" name="username" maxlength="20">
     ```

---

85. **How do you create a form that allows users to select multiple options from a list?**
   ```html
   <select name="cars" multiple>
       <option value="volvo">Volvo</option>
       <option value="bmw">BMW</option>
       <option value="mercedes">Mercedes</option>
   </select>
   ```
   - The `multiple` attribute allows users to select more than one option from the list.

---

86. **How do you pre-fill a form field with default text in HTML?**
   - You can use the `value` attribute to pre-fill an input field with a default value.
     ```html
     <input type="text" name="username" value="Default Username">
     ```

---

87. **How do you disable a form field in HTML?**
   - The `disabled` attribute disables a form field, preventing users from interacting with it.
     ```html
     <input type="text" name="username" disabled>
     ```

---

88. **How do you create a form with a dropdown list and a submit button?**
   ```html
   <form action="/submit-form" method="post">
       <label for="cars">Choose a car:</label>
       <select id="cars" name="cars">
           <option value="volvo">Volvo</option>
           <option value="bmw">BMW</option>
       </select>
       <input type="submit" value="Submit">
   </form>
   ```

---

89. **What is the difference between a radio button and a checkbox in HTML forms?**
   - **Radio Button**: Allows the user to select **only one** option from a group of options. Example:
     ```html
     <input type="radio" name="gender" value="male"> Male
     <input type="radio" name="gender" value="female"> Female
     ```
   - **Checkbox**: Allows the user to select **multiple** options from a group. Example:
     ```html
     <input type="checkbox" name="vehicle" value="car"> Car
     <input type="checkbox" name="vehicle" value="bike"> Bike
     ```

---

90. **How do you validate an email input field in HTML5?**
   - Use `type="email"` to ensure the user enters a valid email address format.
     ```html
     <input type="email" name="useremail" required>
     ```

---

### **Next Steps:**


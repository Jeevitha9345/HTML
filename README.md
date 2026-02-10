HTML
•	Html is developed and maintained  by WHATWG -> Web Hypertext Application Technology Working Group
•	HTML-> HyperText Markup Language -> core of World Wide Web (WWW)
•	Tells the browser how to display the content
•	HTML elements label pieces of content such as "this is a heading", "this is a paragraph", "this is a link", etc.
•	Simple text documents, Multimedia pages, Interactive web applications, Complex web-based software
•	Not only for static websites, but also it is used for dynamic and interactive websites -> backbone of modern web development
•	HTML supports everything from: Static web pages, Interactive forms, Games, Web-based applications
•	HTML is designed for Run in browsers, Have low CPU usage, Can be accessed from different locations
•	History
Early Development (1990–1997)
•	HTML originated at CERN
•	Later managed by the IETF
•	HTML 3.0 failed
•	HTML 3.2 succeeded (1997)
•	HTML 4 followed shortly
Shift to XHTML (1998–2003)
•	W3C stopped evolving HTML
•	Focus shifted to XHTML, an XML-based version
•	XHTML 1.0 introduced no new features
•	XHTML Modularization followed
•	XHTML2 attempted but was incompatible with existing HTML
DOM Development
•	DOM Level 1 (1998)
•	DOM Level 2 (2000–2003)
•	DOM Level 3 incomplete
Revival of HTML
•	XForms sparked renewed interest
•	Browser vendors realized XML could not replace HTML
•	Opera created an early HTML forms extension
•	Proposal rejected by W3C in 2004
Birth of WHATWG
•	Apple, Mozilla, and Opera formed WHATWG
•	Focus on:
o	Backward compatibility
o	Real-world browser behavior
o	Detailed specifications
Collaboration and Living Standard
•	W3C rejoined in 2006
•	HTML5 development started jointly
•	Split in 2011:
o	W3C wanted a finished version
o	WHATWG wanted a living standard
•	In 2019, both agreed to maintain one unified HTML standard

BASIC HTML STRUCTURE
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>My First Page</title>
</head>
<body>
    Content goes here
</body>
</html>

1️⃣ <!DOCTYPE html>
What is it?
•	It is not a tag
•	It tells the browser:
👉 “This webpage is written in HTML5”
Why we use it?
•	Browser has two modes:
o	Old mode (quirks mode)
o	New mode (standards mode)
<!DOCTYPE html> forces new / modern mode
Simple meaning: Browser, please behave properly.
2️⃣ <html> TAG
<html lang="en">
What is it?
•	The main container of the webpage
•	Everything in HTML is inside this tag
lang="en" means:
•	Page language is English
Why language is important?
•	Screen readers read correctly
•	Google understands content language
•	Helps translation
Example:
<html lang="ta">  <!-- Tamil page -->
🧠 Tells browser what language humans will read.
3️⃣ <head> SECTION
<head>
</head>
What is inside <head>?
•	Information about the page
•	NOT shown on the screen
Used for:
•	Page title
•	Language encoding
•	SEO info
•	Browser settings
❌ Don’t put text or images here
✌️Head is for browser, not for user.
4️⃣ <meta charset="UTF-8">
<meta charset="UTF-8">

What does it do?
•	Tells browser how to read letters
Why UTF-8?
•	Supports:
o	English
o	Tamil
o	Hindi
o	Emoji 😄
If we don’t use it:
•	Letters may break
•	Symbols may show wrong
🧠 UTF-8 = all languages support
5️⃣ <title> TAG
<title>My First Page</title>
What does it do?
•	Shows name in browser tab
•	Google uses it in search results
Rules:
•	Only one title
•	Must be meaningful
Good example:
<title>HTML Learning</title>
🧠 Title = page name for browser & Google
6️⃣ <body> TAG
<body>
</body>
What is it?
•	Contains everything user can see
Inside body:
•	Text
•	Images
•	Links
•	Forms
•	Tables
✌️Body = visible part of website
🔁 EASY STRUCTURE TO REMEMBER
Think like human body
DOCTYPE → Rules
html    → Body wrapper
head    → Brain (thinking, info)
body    → Face & hands (visible)
📝 ONE-LINE SUMMARY (VERY IMPORTANT)
•	DOCTYPE → Browser rules
•	html → Main container
•	head → Hidden info
•	body → Visible content

1. DOCUMENT STRUCTURE
<!DOCTYPE html>
<html lang="en">
<head>
  <title>My Website</title>
</head>
<body>
  Welcome to my site
</body>
</html>
📌 This is the minimum working HTML page
🟢 2. METADATA TAGS
<meta charset="UTF-8">
<meta name="description" content="Student portfolio website">
<link rel="stylesheet" href="style.css">
📌 Used for SEO, language support, CSS linking



🟢 3. HEADINGS & PARAGRAPH
<h1>Welcome</h1>
<h2>About Me</h2>
<p>I am learning HTML.</p>
📌 Used to structure content properly
🟢 4. TEXT FORMATTING
<p><strong>Important:</strong> Submit before Friday</p>
<p><em>Italic text</em></p>
<p><mark>Highlighted text</mark></p>
<p>Price <del>₹500</del> ₹300</p>
📌 Used in blogs, notices, offers
🟢 5. DIV & SPAN
<div>
  <h2>Section</h2>
  <p>Grouped content</p>
</div>
<p>This is <span>important</span> text</p>
📌 div → block
📌 span → inline
🟢 6. LINKS
<a href="https://google.com">Go to Google</a>
<a href="#contact">Go to Contact</a>
<a href="mailto:test@gmail.com">Send Email</a>
📌 Used for navigation & communication
🟢 7. IMAGES
<img src="profile.jpg" alt="My profile photo">
📌 alt is mandatory for accessibility & SEO
🟢 8. FIGURE & CAPTION
<figure>
  <img src="car.jpg">
  <figcaption>Sports Car</figcaption>    </figure>
📌 Used for images with description
🟢 9. LISTS
<ul>
  <li>HTML</li>
  <li>CSS</li>
</ul>
<ol>
  <li>Login</li>
  <li>Dashboard</li>
</ol>
📌 Used in menus, steps, features
🟢 10. DESCRIPTION LIST
<dl>
  <dt>HTML</dt>
  <dd>Markup language</dd>
</dl>
📌 Used for definitions
🟢 11. TABLES
<table border="1">
  <tr>
    <th>Name</th>
    <th>Marks</th>
  </tr>
  <tr>
    <td>Jeevi</td>
    <td>95</td>
  </tr>
</table>
📌 Used for reports, dashboards
🟢 12. FORMS
<form>
  <label>Name:</label>
  <input type="text">
  <button>Submit</button>
</form>
📌 Used for login, signup, feedback
🟢 13. INPUT TYPES
<input type="email" placeholder="Email">
<input type="password" placeholder="Password">
<input type="radio"> Male
<input type="checkbox"> Agree
📌 Used to collect user data
🟢 14. SELECT & TEXTAREA
<select>
  <option>India</option>
  <option>USA</option>
</select>
<textarea>Message</textarea>
📌 Used in forms
🟢 15. SEMANTIC TAGS 
<header>Website Header</header>
<nav>Menu</nav>
<main>Main content</main>
<section>About section</section>
<footer>Copyright 2026</footer>
📌 Used in real professional websites
🟢 16. DETAILS & SUMMARY
<details>
  <summary>More Info</summary>
  Hidden content here
</details>
📌 Click to expand content
🟢 17. IFRAME
<iframe src="https://example.com"></iframe>
📌 Used to embed another webpage
🟢 18. CODE & PRE
<pre>
function hello() {
  return "Hi";
}
</pre>
<code>console.log("Hello")</code>
📌 Used in documentation & tutorials
🟢 19. MEDIA
<audio controls src="song.mp3"></audio>
<video controls src="video.mp4"></video>
📌 Used in media websites
🟢 20. VOID TAGS OR SELF CLOSING TAGS (NO CLOSING)
<br>
<hr>
<img>
<input>
<meta>
📌 No closing tag needed



1️⃣ <header>
Use: Top section of page/section
<header>My Website</header>
Output:
👉 Displays My Website at the top
2️⃣ <nav>
Use: Navigation menu
<nav>Home | About | Contact</nav>
Output:
👉 Shows navigation links text
3️⃣ <main>
Use: Main content of page (only one allowed)
<main>Main Content Here</main>
Output:
👉 Displays main content area
4️⃣ <section>
Use: Logical grouping of content
<section>About Section</section>
Output:
👉 Displays “About Section”
5️⃣ <article>
Use: Independent content (blog, post)
<article>Blog Post</article>
Output:
👉 Displays “Blog Post”
6️⃣ <aside>
Use: Side content / ads
<aside>Advertisement</aside>
Output:
👉 Displays “Advertisement” on side
7️⃣ <footer>
Use: Bottom section
<footer>© 2026</footer>
Output:
👉 Displays copyright text
8️⃣ <figure>
Use: Image with description
<figure>
  <img src="car.jpg">
</figure>
Output:
👉 Shows image
9️⃣ <figcaption>
Use: Caption for image
<figure>
<img src="car.jpg">
<figcaption>Sports Car</figcaption>
</figure>
Output:
👉 Image + text Sports Car
🔟 <audio>
Use: Play audio
<audio controls src="song.mp3"></audio>
Output:
👉 Audio player with controls
1️⃣1️⃣ <video>
Use: Play video
<video controls src="video.mp4"></video>
Output:
👉 Video player
1️⃣2️⃣ <source>
Use: Multiple media formats
<video controls>
  <source src="video.mp4">
</video>
Output:
👉 Video plays
1️⃣3️⃣ <track>
Use: Subtitles
<video controls>
  <track kind="subtitles">
</video>
Output:
👉 Subtitle option available
1️⃣4️⃣ <details>
Use: Expand / collapse content
<details>
  Hidden Info
</details>
Output:
👉 Clickable arrow → shows content
1️⃣5️⃣ <summary>
Use: Title for details
<details>
  <summary>More</summary>
  Info here
</details>
Output:
👉 Click More → shows “Info here”
1️⃣6️⃣ <dialog>
Use: Popup dialog box
<dialog open>Hello</dialog>
Output:
👉 Small popup showing Hello
1️⃣7️⃣ <datalist>
Use: Input suggestions
<input list="city">
<datalist id="city">
 <option value="Chennai">
</datalist>
Output:
👉 Dropdown suggestion while typing
1️⃣8️⃣ <output>
Use: Display calculated result
<output>Result</output>
Output:
👉 Displays Result
1️⃣9️⃣ <meter>
Use: Measurement (low–high)
<meter value="6" min="0" max="10"></meter>
Output:
👉 Meter bar partially filled
2️⃣0️⃣ <progress>
Use: Task progress
<progress value="40" max="100"></progress>
Output:
👉 Progress bar at 40%
2️⃣1️⃣ <time>
Use: Date/time info
<time>10:30 AM</time>
Output:
👉 Displays 10:30 AM
2️⃣2️⃣ <data>
Use: Machine-readable value
<data value="101">Product</data>
Output:
👉 Displays Product
2️⃣3️⃣ <canvas>
Use: Draw graphics (JS)
<canvas width="100" height="50"></canvas>
Output:
👉 Empty drawing area
2️⃣4️⃣ <svg>
Use: Vector graphics
Output:
👉 SVG graphic space
2️⃣5️⃣ <template>
Use: Hidden reusable HTML
<template>
<p>Hello</p>
</template>
Output:
👉 Nothing visible (used by JS)
2️⃣6️⃣ <slot>
Use: Web components
<slot></slot>
Output:
👉 Placeholder content
🧠 EXAM ONE-LINE SUMMARY
HTML5 introduced semantic tags, media tags, interactive elements, and modern form controls to build rich web applications without plugins.

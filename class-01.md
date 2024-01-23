# Class-01 reading #

## HTTPoem ##
In the realm of bits and code so bright,
HTTP dances in the digital light.
Requests sail, like whispers in the air,
Data flows, a seamless affair.

GET and POST, a rhythmic tune,
Status codes sing beneath the moon.
Headers tell a tale so fine,
In the web of ones and zeros, we intertwine.

### Describe how HTML, CSS, and JS files are “parsed” in the browser. ###
**According to MDN Web Docs:** As the browser parses the HTML, it sends requests back to the server for any CSS files it has found from <link> elements, and any JavaScript files it has found from <script> elements, and from those, then parses the CSS and JavaScript.

### How can you find images to add to a Website? ###
**As stated on w3schools.com;** HTML Images Syntax
The HTML <img> tag is used to embed an image in a web page.

Images are not technically inserted into a web page; images are linked to web pages. The <img> tag creates a holding space for the referenced image.

The <img> tag is empty, it contains attributes only, and does not have a closing tag.

The <img> tag has two required attributes:

src - Specifies the path to the image
alt - Specifies an alternate text for the image


### How do you create a String vs a Number in JavaScript? ###
**Creating a String:**
Enclose text in single (' ') or double (" ") quotes.
Example:
let myString = 'Hello, World!';

**Creating a Number:**
Simply assign a numeric value without quotes.
Example:
let myNumber = 42;

### What is a Variable and why are they important in JavaScript? ###
**As stated on edureka.co:** Just like in algebra, we use variables in programming languages to hold values. JavaScript includes variables that are used to hold the data value and it can also be changed anytime.

**What is an HTML attribute?**
According to MDN Web Docs, an HTML attribute is a characteristic or property name that can be added to an HTML element to provide additional information or modify its behavior. Attributes are always included in the opening tag of an HTML element and are written as name-value pairs.

**Describe the Anatomy of an HTML element.**
Opening Tag: The element starts with an opening tag, which is the name of the element surrounded by angle brackets (e.g., <p>).

Attributes: Attributes provide additional information about the element and are included within the opening tag. They are written as name-value pairs (e.g., class="example").

Content: Some elements have content between the opening and closing tags. For example, a paragraph element <p> may contain text.

Closing Tag: The element ends with a closing tag, which is similar to the opening tag but includes a forward slash before the element name (e.g., </p>).

**What is the Difference between <article> and <section> element tags?**
The <article> and <section> elements are both used to structure content in HTML, but they have distinct purposes and use cases:

<article> Element:
Represents a self-contained piece of content that can be distributed and reused independently.
Typically used for content such as news articles, blog posts, forum posts, or any content that stands alone and makes sense on its own.
Should have a heading (e.g., <h1> to <h6>) to provide a title for the article.

<section> Element:
Represents a generic section of content that groups together thematically-related content.
It doesn't necessarily imply that the content is standalone and can be distributed independently.
Often used to divide a page into different sections for better organization.

<article> is more suitable for standalone, independent content, while <section> is used to group related content together.

**What Elements does a “typical” website include?**
A "typical" website includes a variety of HTML elements to structure and present its content. Here are some common elements you might find in a typical website:

<!DOCTYPE html> Declaration: Specifies the HTML version being used.

<html> Element: The root element that wraps the entire HTML document.

<head> Element: Contains meta-information about the document, such as the title, character set, linked stylesheets, and more.

<title> Element: Specifies the title of the document, which appears in the browser tab.

<body> Element: Contains the content of the HTML document.

Headings (<h1> to <h6>): Define headings of different levels.

Paragraphs (<p>): Used to structure text into paragraphs.

Links (<a>): Create hyperlinks to navigate to other pages or external resources.

Lists (<ul>, <ol>, <li>): Used for ordered or unordered lists.

Images (<img>): Embed images into the webpage.

Forms (<form>, <input>, <button>): Allow user input and data submission.

Tables (<table>, <tr>, <td>): Organize data in tabular form.

Divisions (<div>): Generic container used for layout and structure.

Sections (<section>): Group related content together.

Articles (<article>): Represent standalone, independent content.

Headers (<header>), Footers (<footer>), and Navigation (<nav>): Semantic elements for page structure.

**How does metadata influence Search Engine Optimization?**
Metadata plays a crucial role in Search Engine Optimization (SEO) by providing information about a web page to search engines.

**How is the <meta> HTML tag used when specifying metadata?**
The <meta> HTML tag is used to specify metadata about a document, providing information that is not displayed on the web page but is important for browsers and search engines. 

**What is the first step to designing a Website?**
To design a wireframe based on the websites purpose, goals, and target audience.

**What is the most important question to answer when designing a Website?**
What is the website going to be used for and what is it's purpose?

**Why should you use an <h1> element over a <span> element to display a top level heading?**
Much more clean and simple in the code.

**What are the benefits of using semantic tags in our HTML?**
By incorporating semantic tags appropriately, developers can create more accessible, maintainable, and SEO-friendly web pages.

**Describe 2 things that require JavaScript in the Browser?**
Form Validation:
JavaScript is often used to perform client-side form validation. This involves checking user input in web forms before submitting the data to the server. With JavaScript, you can validate fields such as email addresses, passwords, and numerical inputs in real-time, providing immediate feedback to users.
Dynamic Content and Interactivity:
JavaScript allows developers to create dynamic and interactive web pages by manipulating the Document Object Model (DOM). This includes updating content on the page without a full page reload, responding to user interactions (such as clicks or key presses), and creating animations.

**How can you add JavaScript to an HTML document?**
You can add JavaScript to an HTML document in several ways. Three common ways are: Inline Script, External Script file and Event Listeners.

## Things I want to know more about ##
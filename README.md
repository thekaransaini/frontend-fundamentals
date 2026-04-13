# Frontend Fundamentals

This document demonstrates my understanding of core frontend concepts with practical explanations.

---

Before diving into frontend fundamentals, let’s understand the most important concept to avoid any confusion in the future.

---

## Important Concept

### 1. What is the difference between Web Applications and Websites?

We usually think they are the same terms, but they are not.

| Feature                          | Website                                                                                    | Web Application                                                                                                                                                                                                                           |
| -------------------------------- | ------------------------------------------------------------------------------------------ | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Purpose                          | The purpose of a website is to provide informational or static content.                    | The purpose of a web application is to allow user interaction and perform dynamic operations like submitting forms or processing user data.                                                                                               |
| Interaction                      | It contains minimal interaction like reading information or clicking links.                | It includes high involvement of users for tasks like logging in or data manipulation such as editing, deleting, or creating new data.                                                                                                     |
| Complexity                       | It is very simple, mainly focused on displaying content with little or no backend.         | It is more complex, including both client-side and server-side development for proper data handling.                                                                                                                                      |
| Authentication and Authorization | It doesn’t require login/signup or authorization because information is open to all users. | It requires login/signup with authorization to provide personalized content as per user needs.                                                                                                                                            |
| Data Nature                      | In this, data is static and doesn’t change dynamically.                                    | Real-time data is used, and it is constantly updated based on user actions.                                                                                                                                                               |
| Data Processing                  | Primarily displays content without significant data manipulation.                          | It involves data processing tasks like storing, cleaning, and retrieving information.                                                                                                                                                     |
| Tech Stack                       | Mainly HTML, CSS, and JavaScript are used.                                                 | It involves frontend, backend, and database. Frontend includes HTML, CSS, JavaScript with frameworks like React, Angular, Vue.js, etc. Backend includes Node.js, Python, Java, PHP, etc. Databases include MongoDB, SQL, PostgreSQL, etc. |
| Maintenance                      | Occasional updates are required to update content or improve design.                       | Frequent updates and maintenance are required for security, features, and performance as the database grows.                                                                                                                              |
| Examples                         | Blogs, portfolios, news sites                                                              | Gmail, Notion, e-commerce platforms (like Amazon)                                                                                                                                                                                         |

---

### 2. What is the process of building a Real World Web Application?

We usually think that just like we build projects as solo developers at home, we will build them in a company in the same way. But this is not true.

There is a full-fledged cycle or set of steps where an idea takes shape into a real product. So it’s important to understand the overall cycle of building a real-world product, which helps us understand the importance of frontend and the flow of building a product.

#### 1. Ideation and Research

- This is the foundation stage of building our digital product.

- In this stage, we define our goals like what is the purpose of our web application and what problem it will solve in the market.

- Market research is conducted to better understand users' needs, preferences, and problems.

- Competitors are also analyzed to identify gaps in their products, so we can differentiate our strategy and product before launching it in the market.

Example: If we build an e-commerce platform, then we have to analyze existing players like Amazon, Meesho, Myntra. We can add a clothes try-on feature where users can try clothes virtually, which decreases return rates and improves customer satisfaction. We can also specify our target audience like Gen Z or millennials. We may include a creator feature just like Myntra did for promotional purposes.

#### 2. Planning and Strategy

- In this stage, we gather resources and plan our budget efficiently.

- We specify our features, functionalities, technical specifications, and tech stack.

- We create a strategy like breaking the development process into milestones or setting deadlines so the product is ready on time.

Example: Choose a tech stack like MERN, MEAN, or Java Spring Boot. Create a proper document where features, requirements, budget, and deadlines are written clearly.

#### 3. UI/UX Design

Here designers come into play who have knowledge of user psychology. They create user interfaces by considering the experience of users while interacting with the web app.

- Create a blueprint of our web app to visualize the layout.

- Develop interactive prototypes to test the user experience.

- Focus on aesthetics, simplicity, and usability, ensuring a seamless experience on different screen sizes.

Example: Use tools like Figma to design product pages, navigation menus, etc.

#### 4. Development

This is the stage where we see our web app becoming reality. This involves:

- **Frontend Development:** Build user-facing elements based on the design created by UI/UX designers using HTML, CSS, and JavaScript frameworks.

- **Backend Development:** Create server-side logic and integrate APIs and databases with the frontend.

- **Quality Assurance:** Ensure that what we promised to deliver to users is delivered with high quality. This includes testing for bugs and performance.

Example: Use React for frontend and Node.js with Express for backend, along with databases like MongoDB or SQL.

#### 5. Testing

This is the phase where our product goes through extensive testing.

- Verify all features work as promised.

- Check speed and performance of the application under different conditions like slow networks.

- Identify vulnerabilities and potential loopholes to protect user data from hackers.

Example: Test a payment gateway to ensure transactions occur smoothly without errors.

#### 6. Deployment

This is the time to launch our product in the market. Before launching, it involves some steps:

- Choose a reliable hosting provider to store our application on the internet.

- Choose a domain name that reflects our brand and differentiates us from competitors.

- Deploy our app to the server and make it accessible to users.

Example: Deploy the app on cloud platforms like AWS or Google Cloud.

#### 7. Maintenance and Updates

This is the final and never-ending stage of our web app.

- Resolve issues encountered by users.

- Add new features based on user feedback.

- Constantly improve speed and reliability.

#### 8. SEO and Marketing

People usually forget this stage, but it is one of the most important.

- Plan strategies and optimize the app for search engines to reach potential users through organic and paid search.

- Marketing involves promoting the product to potential customers and retaining them to improve profit and build long-lasting relationships.

---

### 3. How Frontend has evolved over the years?

Understanding this helps us stay updated with modern frontend development and stay one step ahead.

#### 1. Static Websites (1990s)

- Built only using HTML.
- No styling, no interactivity.
- Web pages looked like a digital newspaper.

#### 2. Introduction of Styling (Late 1990s – Early 2000s)

- CSS (Cascading Style Sheets) came into the industry, which allowed developers to style web pages like adding different colors, fonts, and layouts.

- Web pages looked more appealing than before.

#### 3. Adding Interactivity with JavaScript (Early 2000s)

- JavaScript was used to make websites interactive, including form validation, popups, dropdowns, and basic animations.

- Compatibility issues existed across browsers where the same code behaved differently.

#### 4. AJAX Era (Mid 2000s)

- Allowed developers to update data without reloading the page, improving performance and user experience.

Example: Gmail updates emails without refreshing the page.

#### 5. jQuery and Libraries (Late 2000s)

- JavaScript libraries like jQuery were introduced to simplify DOM manipulation.

- It solved browser compatibility issues.

#### 6. Rise of Modern Frameworks (2010s)

- Modern frameworks like React, Angular, and Vue.js structured frontend development.

- Component-based architecture helped in building reusable UI.

- Enabled development of single-page applications.

- Helped manage state efficiently.

#### 7. Advanced Frameworks and Rendering (Late 2010s – Present)

New technologies like Next.js and Svelte were introduced:

- **Server-side rendering:** Generates full HTML on the server for each request.

- **Static Site Generation:** Builds pages at compile time for better performance.

#### 8. Current Trends (2023–2025)

- **Progressive Web Apps (PWA):** Provide app-like experience with offline support.

- **AI Integration:** Personalized experiences and smarter search suggestions.  
  Example: YouTube recommendations.

- **Natural Interaction:** Users can interact with apps using voice or more human-like inputs.

---

## HTML5 Semantics

### 1. What is Semantic HTML? Why do we need it?

**Semantic HTML:** Semantic HTML is the practice of using HTML tags (called semantic elements) that reflect their meaning and purpose to both the browser and the developer.

We need semantic HTML for the following reasons:

- It helps deliver web content to everyone, including people with visual, auditory, motor, or cognitive disabilities.

- It helps search engines better understand the content, which increases the ranking and visibility of a website in search results.

- It makes the code more readable and supports cleaner development, which helps future developers understand the code by just scanning the tags.

- It also makes development easier, especially when working in a team.

Example: Using `<nav>` helps screen readers understand navigation sections, while using `<div>` does not provide that meaning.

---

### 2. What is the difference between Semantic elements and Non-semantic elements?

| Feature       | Semantic Elements                                                            | Non-Semantic Elements                                        |
| ------------- | ---------------------------------------------------------------------------- | ------------------------------------------------------------ |
| Definition    | Elements that reflect their meaning and purpose.                             | Elements that don’t reflect any specific meaning or purpose. |
| Purpose       | They provide structure and meaning to the webpage.                           | They are mainly used for styling and layout purposes.        |
| Readability   | It is easier for developers to read and understand the code structure.       | It is harder to understand the code structure.               |
| SEO           | They help increase visibility and ranking in search results.                 | They don’t contribute much to visibility and ranking.        |
| Accessibility | Content becomes more accessible to users, including those with disabilities. | Content is less accessible for users.                        |
| Example       | `<header>`, `<footer>`, `<article>`, `<section>`, `<nav>`                    | `<div>`, `<span>`                                            |

---

### 3. What are the problems with using too many `<div>` elements, and why should we move to semantic HTML?

The practice of using too many `<div>` elements is called "div soup".

These are the following problems that come with "div soup":

- **Accessibility Barriers:** Screen readers like NVDA or JAWS face difficulty navigating a page without semantic tags. General tags like `<div>` do not provide any context, which forces screen readers to guess the structure of the page. This creates difficulty for visually impaired users to navigate to specific sections.

- **Maintenance Difficulty:** Excessive use of nested `<div>` elements makes the code hard to debug and maintain, especially when working in a team or on large projects.

- **Poor Searchability:** Search engines use HTML structure to understand content hierarchy. When everything is wrapped in non-semantic tags, search engines may struggle to properly rank the page.

We move to semantic HTML for the following reasons:

- **Improved SEO:** Tags like `<article>`, `<section>`, and `<header>` help search engines understand and prioritize content, which leads to better search rankings.

- **Better Accessibility:** It improves accessibility for all kinds of users. For example, a `<nav>` tag automatically signals a navigation area to screen readers, allowing users to skip directly to important links.

- **Self-Documenting Code:** Using meaningful tags like `<aside>` or `<footer>` makes the code more readable without the need for unnecessary comments.

### 4. Explain all semantic elements in HTML.

#### 1. `<header>`

- Header is used to describe the introductory part of a webpage or a section.
- It typically contains a logo, navigation links, and headings.
- We can use it multiple times inside a web page.

**Example:**

```html
<header>
  <h1>My Website</h1>
  <nav>
    <a href="#">Home</a>
    <a href="#">About</a>
  </nav>
</header>
```

---

#### 2. `<nav>`

- Nav is used to wrap the navigation links only.
- Navigation links are those links that help users navigate through different pages in a web app.

**Example:**

```html
<nav>
  <a href="#">Home</a>
  <a href="#">About</a>
  <a href="#">Contact</a>
</nav>
```

---

#### 3. `<main>`

- Main represents the most important and unique part of the web page.
- There should be only one `<main>` per web page.
- It does not include header, footer, and navigation.

**Example:**

```html
<main>
  <p>This is the main content of the page.</p>
</main>
```

---

#### 4. `<section>`

- It groups related content together, usually with a theme.
- We can use any type of heading from `<h1>` to `<h6>` for the theme.

**Example:**

```html
<section>
  <h2>About Us</h2>
  <p>We are a company that builds websites.</p>
</section>
```

---

#### 5. `<aside>`

- Aside is used to wrap content that is related but not the main content.
- It contains extra or supporting information like sidebar, advertisements, or related links.

**Example:**

```html
<aside>
  <h3>Related Articles</h3>
  <ul>
    <li><a href="#">HTML Basics</a></li>
    <li><a href="#">CSS Guide</a></li>
  </ul>
</aside>
```

---

#### 6. `<article>`

- Article is used to define independent content.
- This content can stand alone from the rest of the web page.

**Example:**

```html
<article>
  <h2>My First Blog Post</h2>
  <p>This is my article content.</p>
</article>
```

---

#### 7. `<footer>`

- Footer element is used to define the bottom section of a web page or a section.
- It contains information like copyright, contact details, links, and author info.
- It provides secondary or ending information for `<section>` or `<article>`.

**Example:**

```html
<footer>
  <p>&copy; 2026 My Website</p>
  <a href="#">Privacy Policy</a>
</footer>
```

---

#### 8. `<time>`

- The `<time>` element is used to represent dates and times.
- It defines a specific date or time in both human-readable and machine-readable formats.

**Example:**

```html
<p>Published on <time datetime="2026-04-12">April 12, 2026</time></p>
```

---

#### 9. `<mark>`

- It is used to highlight important or relevant text in a specific context.
- By default, it highlights text with a yellow color.

**Example:**

```html
<p>This is a <mark>very important</mark> point.</p>
```

---

#### 10. `<details>` and `<summary>`

- It is used to create a collapsible section.
- Instead of showing all content at once, we let the user decide if they want to see more.
- `<summary>` is the visible heading that works as a toggle button to show or hide content.

**Example:**

```html
<details>
  <summary>Click to see more</summary>
  <p>This is hidden content that can be expanded.</p>
</details>
```

---

#### 11. `<figure>` and `<figcaption>`

- The `<figure>` element is used to wrap media content like images, diagrams, charts, or code snippets.
- `<figcaption>` provides a caption or description for the media content.
- `<figcaption>` should be placed inside `<figure>` before or after the media.

**Example:**

```html
<figure>
  <img src="image.jpg" alt="A beautiful view" />
  <figcaption>This is a beautiful landscape.</figcaption>
</figure>
```

---

#### 12. `<progress>`

- It is used to represent how much of a task is completed out of the total amount.
- We define attributes like `value="60"` and `max="100"` to show progress.

**Example:**

```html
<progress value="60" max="100"></progress>
```

---

#### 13. `<meter>`

- It is used to show a value within a known range.
- We define attributes like `value="60"`, `min="0"` and `max="100"`.
- `<meter>` is used for measurement, whereas `<progress>` is used for task completion.

**Example:**

```html
<meter value="70" min="0" max="100"></meter>
```

---

#### 14. `<address>`

- The `<address>` element is used to define contact information for a person, author, or organization.
- It usually contains email address, phone number, physical address, and author details.

**Example:**

```html
<address>
  Written by John Doe<br />
  <a href="mailto:john@example.com">john@example.com</a><br />
  New Delhi, India
</address>
```

---

#### 15. `<strong>`

- The `<strong>` element is used to indicate importance.
- The text appears bold, but it is not for styling.

**Example:**

```html
<p>This is <strong>very important</strong></p>
```

---

#### 16. `<em>`

- The `<em>` element is used to emphasize text relative to surrounding content.
- The text appears italic, but it is not for styling.

**Example:**

```html
<p>I <em>really</em> like this</p>
```

---

#### 17. `<abbr>`

- The `<abbr>` element is used to represent the full form of an abbreviation on hover.

**Example:**

```html
<p><abbr title="World Health Organization">WHO</abbr></p>
```

---

#### 18. `<cite>`

- The `<cite>` element is used to represent the title of a work like books, movies, or articles.

**Example:**

```html
<p>I read <cite>Harry Potter</cite></p>
```

---

#### 19. `<code>`

- It is used to represent code snippets in monospace font.

**Example:**

```html
<p>Use <code>console.log()</code> in JavaScript</p>
```

---

#### 20. `<kbd>`

- It is used to represent keyboard input.
- It is usually used to display shortcut keys.

**Example:**

```html
<p>Press <kbd>Ctrl</kbd> + <kbd>C</kbd> to copy</p>
```

---

#### 21. `<small>`

- It is used to represent less important text.
- It is usually used for legal or secondary text.

**Example:**

```html
<p>This is normal text <small>and this is smaller text</small></p>
```

---

### 5. Explain all semantic attributes in HTML.

#### 1. Global Semantic Attributes

These attributes can be used on almost all HTML elements.

#### 1. id

- Id must be unique for every element.
- Used to connect input element with label, for styling using id selector, and for targeting elements in JavaScript.

```html
<p id="intro">Hello</p>
```

#### 2. class

- Groups elements together, which helps us give the same styling to every element by using class selector.

```html
<p class="text">Hello</p>
```

#### 3. title

- It shows extra information on hover.

```html
<p title="More info">Hover me</p>
```

#### 4. lang

- This defines the language for the whole HTML document or specific element content.

```html
<html lang="en"></html>
```

#### 5. dir

- It is used to define the text direction with values like ltr (left to right) or rtl (right to left).

```html
<p dir="rtl">Text</p>
```

#### 6. hidden

- It is used to hide the element from the web page but still present in the document object model.

```html
<p hidden>Hidden text</p>
```

#### 7. tabindex

- It is used to control how users move between elements using the Tab key on the keyboard.
- Useful for users who don't have a mouse.
- Commonly used values are 0 (follow general order of the page), -1 (element cannot be accessed using tab).
- We can also specify custom order by giving values like 1, 2, 3 etc., but it is generally not recommended in real-world projects.

```html
<button tabindex="1">Click</button>
```

---

#### 2. ARIA (Accessibility) Attributes

These attributes are specially used to improve accessibility.

#### 1. role

- It defines the purpose of the element, mainly when the element is not semantic by default.

```html
<div role="navigation"></div>
```

#### 2. aria-label

- It adds a label to the element which is not visible on the web page but useful for screen readers.
- aria-label helps to describe the individual element better (like what it does), whereas role defines the purpose of the element (like button or navigation).

```html
<button role="button" aria-label="Close">X</button>
```

#### 3. aria-labelledby

- It labels an element by "pointing" to another element that is already visible on the web page.
- Instead of typing new text every time, it uses an existing ID to borrow the text from an existing heading or paragraph to describe the current element.

```html
<h2 id="title">Menu</h2>
<div aria-labelledby="title"></div>
```

#### 4. aria-hidden

- It hides an element from the screen reader entirely, even if the element is still visible on the web page.
- It is used when the element is unnecessary for people using screen readers.

```html
<div aria-hidden="true"></div>
```

#### 5. aria-expanded

- This attribute helps screen readers describe whether the collapsible element is currently open or closed, and it is usually updated using JavaScript.

```html
<button aria-expanded="false">Menu</button>
```

#### 6. aria-describedby

- It is used to give extra details or hints to the element for better understanding by screen readers.

```html
<input aria-describedby="hint" />
<p id="hint">Enter your name</p>
```

---

#### 3. Form Semantic Attributes

#### 1. type

- It helps the browser show the right keyboard on mobile and check whether the input given by the user is valid or not.

```html
<input type="email" />
```

#### 2. name

- It is used to identify the form data by the server when the form is submitted.

#### 3. placeholder

- It is used to provide a hint to the user while filling the form.
- We provide a hint in the input box, and the hint will disappear as the user starts typing.

```html
<input placeholder="Enter name" />
```

#### 4. required

- It forces the user to fill out the input field before submitting the form.
- If the input field is empty, the browser will show a warning message and not submit the form.

```html
<input required />
```

#### 5. readonly

- It allows the user to see and click the value, but they cannot change or edit it.

#### 6. disabled

- By using this attribute in the input field, the user is not able to interact with the input field at all.
- Disabled data is usually ignored when the form is sent.

#### 7. value

- It helps to store the actual content inside the element.
- For example: The input element stores whatever the user has typed. We can also set a value by default.

#### 8. autocomplete

- It helps the browser suggest saved information (like your address or email) to fill the form faster.

```html
<input autocomplete="email" />
```

---

### 4. Media Attributes

#### 1. alt

- It provides a text description of an image if it fails to load due to a network error or for screen readers.

```html
<img src="cat.jpg" alt="A cute cat" />
```

#### 2. controls

- It adds play, pause, and volume buttons to a video or audio player.
- Without this, the user has no way to start or stop the media.

```html
<video controls></video>
```

#### 3. autoplay, loop, muted

- It helps to control the behavior of media.
- Autoplay starts the media immediately as the web page loads.
- Loop makes the media repeat forever.
- Muted ensures it starts without sound (which is often required for autoplay to work).

---

### 5. Link Attributes

#### 1. href

- It includes the actual web address where the user can open the link by clicking it.

#### 2. target

- It tells the browser where to open the link.
- For example, target="\_blank" forces the link to open in a brand-new tab.

```html
<a href="#" target="_blank">Link</a>
```

#### 3. rel

- rel is used to establish the relationship between your page and the linked page.
- `rel="noopener"` is a way to tell the browser that the new tab doesn't have any control over the original page.

```html
<a rel="noopener"></a>
```

---

### 6. Data & Metadata Attributes

#### 1. data-\* (Custom Data)

- It allows developers to store custom information inside the element that is accessible using JavaScript.

```html
<div data-user-id="123"></div>
```

#### 2. content (Meta Tag)

- It contains metadata like description or other information used by browsers and search engines.

```html
<meta name="description" content="My website" />
```
---

## CSS3 layouts and responsiveness

### 2. Explain different CSS layout techniques (Flexbox, Grid, Float)

- CSS provides several layout techniques that help developers arrange elements on a webpage in a structured and visually appealing way.

- Among these, **Float**, **Flexbox**, and **Grid** are the most commonly used. Each technique was introduced at a different time and serves different purposes.

---

### 1. Float (Traditional Layout Technique)

- The **float** property was originally introduced to wrap text around images. Developers used it to create layouts by pushing elements to the left or right.

- For example, when we apply `float: left;` to an element, it moves to the left side of its container, and other content flows around it.

- There are issues with float such as overlapping elements, and it requires additional fixes like using the `clear` property.

- Because of these limitations, float is not commonly used for modern layouts.

#### Example:

```css
img {
  float: left;
}
```

---

### 2. Flexbox

- **Flexbox** is used to make a one-dimensional layout, which means it is used to arrange elements in a single direction, either in a row or a column.

#### Example:

```css
.container {
  display: flex;
  justify-content: center;
  align-items: center;
}
```

---

### Properties of Flexbox

#### 1. Flex Container Properties

These properties are applied to the parent element (the container) to control how its children are structured.

---

##### display

The `display` property is used to enable flexbox on an element.

```css
.container {
  display: flex;
}
```

---

##### flex-direction

This property defines the direction in which the flex items are placed inside the container.

```css
flex-direction: row;
flex-direction: column;
flex-direction: row-reverse;
flex-direction: column-reverse;
```

---

##### justify-content

This property controls how flex items are aligned along the main axis (horizontal by default).

```css
justify-content: flex-start;
justify-content: center;
justify-content: space-between;
justify-content: space-around;
justify-content: space-evenly;
```

---

##### align-items

This property aligns flex items along the cross axis (vertical by default).

```css
align-items: stretch;
align-items: center;
align-items: flex-start;
align-items: flex-end;
```

---

##### flex-wrap

This property is used to decide whether flex items wrap onto the next line or stay in a single line.

```css
flex-wrap: nowrap;
flex-wrap: wrap;
flex-wrap: wrap-reverse;
```

---

##### align-content

This property is used to control the spacing between rows when items wrap onto multiple lines.

```css
align-content: center;
align-content: space-between;
align-content: space-around;
align-content: stretch;
```

---

##### gap

The `gap` property adds space between flex items.

```css
gap: 10px;
```

---

#### 2. Flex Item Properties

These properties are applied to individual child elements inside the flex container.

---

##### flex-grow

This property is used to define how much a flex item should grow relative to other items.

```css
flex-grow: 1;
```

---

##### flex-shrink

This property is used to define how much a flex item should shrink when space is limited.

```css
flex-shrink: 1;
```

---

##### flex-basis

This property is used to define the initial size of a flex item before the distribution of extra space.

```css
flex-basis: 200px;
```

---

##### flex

This is a shorthand property for `flex-grow`, `flex-shrink`, and `flex-basis`.

```css
flex: 1 1 200px;
```

---

##### align-self

This property helps to override the alignment of a specific item.

```css
align-self: center;
align-self: flex-start;
align-self: flex-end;
```

---

### 3. CSS Grid

- **CSS Grid** is used to make a two-dimensional layout which allows to work with both rows and columns at the same time. This makes it ideal for designing complex and structured layouts.

- With Grid, you can define the number of rows and columns, control spacing, and place elements exactly where we want them.

#### Example:

```css
.container {
  display: grid;
  grid-template-columns: repeat(3, 1fr);
  gap: 10px;
}
```

---

### Properties of CSS Grid

#### 1. Grid Container Properties

These properties are applied to the parent element (the grid container) to define the overall layout.

---

##### display

The `display` property is used to enable grid layout on an element.

```css
.container {
  display: grid;
}
```

---

##### grid-template-columns

This property is used to define the number and size of columns in the grid.

```css
grid-template-columns: 200px 200px 200px;
grid-template-columns: repeat(3, 1fr);
```

---

##### grid-template-rows

This property is used to define the number and size of rows in the grid.

```css
grid-template-rows: 100px 100px;
```

---

##### gap

The `gap` property is used to create space between rows and columns.

```css
gap: 10px;
```

---

##### justify-content

This property helps to align the entire grid horizontally inside the container.

```css
justify-content: center;
justify-content: space-between;
```

---

##### align-content

This property helps to align the entire grid vertically inside the container.

```css
align-content: center;
align-content: space-around;
```

---

##### place-content

This is a shorthand for `align-content` and `justify-content`.

```css
place-content: center;
```

---

##### justify-items

This property helps to align grid items horizontally inside their grid cells.

```css
justify-items: center;
justify-items: start;
```

---

##### align-items

This property helps to align grid items vertically inside their grid cells.

```css
align-items: center;
align-items: stretch;
```

---

##### place-items

This is a shorthand for `align-items` and `justify-items`.

```css
place-items: center;
```

---

### 🧩 2. Grid Item Properties

These properties are applied to individual items inside the grid.

---

##### grid-column

This property defines how many columns an item should cover.

```css
grid-column: 1 / 3;
```

---

##### grid-row

This property defines how many rows an item should cover.

```css
grid-row: 1 / 2;
```

---

##### grid-area

This property is used to place an item in a specific area.

```css
grid-area: 1 / 1 / 3 / 3;
```

---

##### justify-self

This property helps to align a single item horizontally inside its cell.

```css
justify-self: center;
```

---

##### align-self

This property helps to align a single item vertically inside its cell.

```css
align-self: end;
```

---

##### place-self

This is a shorthand for `align-self` and `justify-self`.

```css
place-self: center;
```

---

### 3. What is Responsive Design? Explain Various Techniques for Building a Responsive Design.

- **Responsive design** is an approach where a website automatically adjusts its layout, content, and elements to look good on all screen sizes and devices, such as mobiles, tablets, and desktops.

- Instead of creating separate websites for different devices, responsive design ensures that one website works smoothly everywhere by adapting to the user’s screen.

---

### Why Responsive Design is Important

- In today’s world, there are many different devices with a lot of different screen sizes.

- A responsive design improves user experience, increases accessibility, and ensures that your website looks professional on every device.

---

### Various Techniques for Building a Responsive Design

We use a combination of the following techniques to build a responsive design:

---

### 1. Mobile-First Approach

- In this approach, we first design the website for small screens (mobile devices) and then gradually enhance it for larger screens.

```css
/* Mobile styles (default) */
.container {
  padding: 10px;
}

/* Tablet and above */
@media (min-width: 768px) {
  .container {
    padding: 20px;
  }
}
```

---

### 2. Flexible Layouts (Fluid Layouts)

To make the layout flexible, we use relative units instead of fixed units like pixels, which allow elements to resize automatically based on screen size.

### Types of Relative Units

### 1. `em`

The `em` unit is relative to the **font size of the parent element**.

#### Example:

```css
.parent {
  font-size: 16px;
}

.child {
  font-size: 2em; /* 2 × 16px = 32px */
}

.container {
  width: 90%;
}
```

---

### 2. `rem`

The `rem` unit is always relative to the root element (`html`) font size.

#### Example:

```css
html {
  font-size: 16px;
}

h1 {
  font-size: 2rem; /* 32px */
}
```

---

### 3. `% (Percentage)`

The percentage unit is relative to the parent element’s size.

#### Example:

```css
.container {
  width: 200px;
}

.box {
  width: 50%; /* 100px */
}
```

---

### 4. `vw` (Viewport Width)

- `vw` is relative to the width of the browser window.
- 1vw = 1% of viewport width

#### Example:

```css
div {
  width: 50vw;
}
```

---

### 5. `vh` (Viewport Height)

- `vh` is relative to the height of the browser window.
- 1vh = 1% of viewport height

#### Example:

```css
div {
  height: 100vh;
}
```

---

### 6. `vmin`

- `vmin` is based on the smaller value between viewport width and height.
- It selects the smaller dimension.

#### Example:

```css
div {
  width: 50vmin;
}
```

---

### 7. `vmax`

- `vmax` is based on the larger value between viewport width and height.
- It selects the larger dimension.

#### Example:

```css
div {
  width: 50vmax;
}
```

---

### 8. `ch`

- `ch` is relative to the width of the character "0" (zero).
- It is useful for controlling text width.

#### Example:

```css
p {
  width: 30ch;
}
```

---

### 9. `ex`

- `ex` is relative to the height of the lowercase letter "x".
- It is rarely used because it depends on font style.

---

### 10. `lh`

- `lh` is relative to the line height of the element.

#### Example:

```css
p {
  line-height: 20px;
  margin-top: 2lh; /* 40px */
}
```

---

### 11. `rlh`

- `rlh` is relative to the root element’s line height.
- Similar to `rem`, but based on line height.

---

### 3. CSS Flexbox and Grid

In modern days, we use Flexbox and Grid, which help to create flexible and adaptive layouts.

- **Flexbox** is used for one-dimensional layouts.
- **Grid** is used for two-dimensional layouts.

These tools make alignment, spacing, and responsiveness much easier.

---

### 4. Responsive Images and Media

We ensure images scale properly to fit different screen sizes without breaking the layout.

```css
img {
  max-width: 100%;
  height: auto;
}
```

We can also use the `srcset` attribute in HTML to load different image sizes for different devices.

---

### 5. Media Queries

- Media queries allow us to apply different styles based on screen size, resolution, or device type.
- We don't memorize screen sizes. We choose breakpoints, which means selecting that width in media queries where our layout breaks.

```css
@media (max-width: 600px) {
  body {
    font-size: 14px;
  }
}
```

---

### 6. Responsive Typography

Using relative units like `rem` or `em` helps text scale properly, which makes it readable on all devices.

```css
h1 {
  font-size: 2rem;
}
```

---

## 🧩 7. Viewport Meta Tag

This tag ensures that our website scales correctly on mobile devices.

```html
<meta name="viewport" content="width=device-width, initial-scale=1.0" />
```

---

## JavaScript (ES6+) concepts

### 1. What is the difference between var, let, and const? Explain scope and hoisting.

`var`, `let`, and `const` are used to declare variables, but they behave differently in terms of **scope**, **hoisting**, and **reassignment**.

---

### Difference Between `var`, `let`, and `const`

### `var`

The `var` keyword is the older way of declaring variables.

- It has **function scope**, not block scope.
- It can be **redeclared and updated**.
- It is **hoisted**, but initialized with `undefined`.

```javascript
var x = 10;
var x = 20; // allowed
```

---

### `let`

The `let` keyword was introduced in ES6 and is more modern.

- It has **block scope** (works inside `{}`).
- It can be **updated but not redeclared** in the same scope.
- It is **hoisted**, but not initialized (temporal dead zone).

```javascript
let y = 10;
y = 20; // allowed
// let y = 30; ❌ not allowed in same scope
```

---

### `const`

The `const` keyword is also introduced in ES6 and is used for constants.

- It has **block scope**.
- It **cannot be updated or redeclared**.
- It must be **initialized at declaration**.
- For objects/arrays, values inside can still change.

```javascript
const z = 10;
// z = 20; ❌ not allowed
```

---

### Scope

**Scope** determines where a variable can be accessed in the code.

### Function Scope (`var`)

A variable declared with `var` is accessible throughout the function.

```javascript
function test() {
  var a = 10;
}
```

---

### Block Scope (`let`, `const`)

Variables declared with `let` and `const` are only accessible inside the block `{}` where they are defined.

```javascript
if (true) {
  let b = 20;
  const c = 30;
}
// b and c are not accessible here
```

---

### Hoisting

**Hoisting** means JavaScript moves variable declarations to the top of their scope before execution.

---

### `var` Hoisting

```javascript
console.log(a); // undefined
var a = 5;
```

- Declaration is hoisted but Value shows `undefined`

---

### `let` and `const` Hoisting (Temporal Dead Zone)

```javascript
console.log(b); // ❌ ReferenceError
let b = 5;
```

- They are hoisted but not initialized.
- Accessing before declaration causes an reference error that's why this phase is called the **Temporal Dead Zone (TDZ)**.

---

### 2. What are Arrow Functions? How are they Different from Normal Functions (especially in terms of `this`)?

- **Arrow functions** are a shorter and more modern way to write functions in JavaScript.
- An arrow function uses the `=>` syntax instead of the `function` keyword.

### Example:

```javascript
// Normal function
function add(a, b) {
  return a + b;
}

// Arrow function
const add = (a, b) => {
  return a + b;
};
```

If the function contain only one line, we can also write like this:

```javascript
const add = (a, b) => a + b;
```

---

### Difference Between Arrow Functions and Normal Functions

---

### 1. `this` Keyword Behavior

### Normal Function:

In this function, the value of `this` depends on how the function is called.

```javascript
const obj = {
  name: "Karan",
  greet: function () {
    console.log(this.name);
  },
};

obj.greet(); // Karan
```

Here, `this` refers to the object (`obj`).

---

### Arrow Function:

Arrow functions do not have their own `this`. Instead, they **inherit `this` from their surrounding (lexical) scope**.

```javascript
const obj = {
  name: "Karan",
  greet: () => {
    console.log(this.name);
  },
};

obj.greet(); // undefined (or window.name in browser)
```

Here, `this` does not refer to `obj`, but to the outer scope (usually global).

---

### 2. Syntax Difference

Arrow functions provide a shorter syntax, especially for small functions.

```javascript
const square = (n) => n * n;
```

---

### 3. No `arguments` Object

Arrow functions do not have their own `arguments` object.

```javascript
function normal() {
  console.log(arguments);
}

const arrow = () => {
  console.log(arguments); // ❌ Error
};
```

---

### 4. Cannot Be Used as Constructors

Arrow functions cannot be used with the `new` keyword.

```javascript
const Person = (name) => {
  this.name = name;
};

// new Person("Karan"); ❌ Error
```

---

### 5. No `this` Binding Methods

Methods like `call()`, `apply()`, and `bind()` do not change `this` in arrow functions.

---

### 3. What is Destructuring and the Spread/Rest Operator in JavaScript?

### 📦 1. Destructuring

**Destructuring** is a way to extract values from arrays or properties from objects and assign them to variables in a simple and concise way.

---

### Array Destructuring

Instead of accessing values using indexes, we can directly assign them:

```javascript
const numbers = [10, 20, 30];

const [a, b, c] = numbers;

console.log(a); // 10
console.log(b); // 20
```

---

### Object Destructuring

We can extract properties from an object using their names:

```javascript
const user = {
  name: "Karan",
  age: 22,
};

const { name, age } = user;

console.log(name); // Karan
```

We can also rename variables:

```javascript
const { name: userName } = user;
```

---

### 2. Spread Operator (`...`)

The **spread operator** is used to copy elements from arrays or objects.

---

### With Arrays

```javascript
const arr1 = [1, 2];
const arr2 = [...arr1, 3, 4];

console.log(arr2); // [1, 2, 3, 4]
```

---

### With Objects

```javascript
const user = { name: "Karan" };
const updatedUser = { ...user, age: 22 };

console.log(updatedUser); // { name: "Karan", age: 22 }
```

---

### 3. Rest Operator (`...`)

The **rest operator** is used to collect multiple elements into a single variable.

---

### In Arrays

```javascript
const [first, ...rest] = [1, 2, 3, 4];

console.log(first); // 1
console.log(rest); // [2, 3, 4]
```

---

### In Functions

```javascript
function sum(...numbers) {
  return numbers.reduce((total, n) => total + n, 0);
}
```

Here, `...numbers` collects all arguments into an array.

---

### 4. What is the Event Loop in JavaScript? Explain Synchronous vs Asynchronous Behavior.

JavaScript is a **single-threaded language**, which means it can execute one task at a time. However, it can still able to handle multiple operations efficiently using **event loop**.

---

### Event Loop

The **event loop** is a mechanism that manages how JavaScript executes code, handles asynchronous operations, and ensures that tasks are processed in the correct order without blocking the main thread.

It continuously checks:

1. If the **call stack** is empty
2. If there are pending tasks in the **callback queue**

If the call stack is empty, the event loop takes a task from the queue and pushes it into the stack for execution.

---

### Synchronous Behavior

**Synchronous code** runs line by line, one after another. Each task must finish before the next one starts.

### Example:

```javascript
console.log("Start");
console.log("Middle");
console.log("End");
```

### Output:

```
Start
Middle
End
```

In this case, everything runs in order without any delay.

---

### Asynchronous Behavior

**Asynchronous code** allows certain tasks (like API calls, timers, or file reading) to run in the background without blocking the main thread.

### Example:

```javascript
console.log("Start");

setTimeout(() => {
  console.log("Inside Timeout");
}, 0);

console.log("End");
```

### Output:

```
Start
End
Inside Timeout
```

Even though the timeout is `0ms`, it is executed later because it is handled by the event loop.

---

### How It Works Together

1. Synchronous code runs first and fills the call stack.
2. Asynchronous tasks (like `setTimeout`, promises, etc.) are handled by browser APIs or Node.js APIs.
3. Once completed, their callbacks are placed in the **callback queue**.
4. The event loop waits for the call stack to be empty.
5. Then it pushes queued tasks into the call stack for execution.

---

### What is Callback Hell? How do Promises and async/await solve it?

### What is Callback Hell?

- **Callback hell** is a situation where multiple asynchronous operations are nested inside each other using callbacks.

- This creates deeply nested code that is hard to read, understand, and maintain.

### Example:

```javascript
getUser(function (user) {
  getOrders(user, function (orders) {
    getOrderDetails(orders, function (details) {
      processDetails(details, function (result) {
        console.log(result);
      });
    });
  });
});
```

This kind of structure is difficult to debug and manage, especially as the application grows.

---

### How Promises Solve Callback Hell

**Promises** provide a cleaner way to handle asynchronous operations by chaining `.then()` methods instead of nesting callbacks. It also provide better error handling using `.catch()`

### Example:

```javascript
getUser()
  .then((user) => getOrders(user))
  .then((orders) => getOrderDetails(orders))
  .then((details) => processDetails(details))
  .then((result) => console.log(result))
  .catch((error) => console.error(error));
```

---

### How async/await Solves Callback Hell

**async/await** is built on top of promises and makes asynchronous code look like synchronous code.

### Example:

```javascript
async function handleData() {
  try {
    const user = await getUser();
    const orders = await getOrders(user);
    const details = await getOrderDetails(orders);
    const result = await processDetails(details);

    console.log(result);
  } catch (error) {
    console.error(error);
  }
}
```

---

### 6. Explain Important Array Methods like `map()`, `filter()`, and `reduce()` with Use Cases

### 1. `map()` Method

The `map()` method is used to **transform each element** of an array and return a new array of the same length.

### Example:

```javascript
const numbers = [1, 2, 3];

const doubled = numbers.map((num) => num * 2);

console.log(doubled); // [2, 4, 6]
```

### Use Case:

We can use `map()` when we want to **modify or transform data**, such as converting values, formatting data, or creating UI elements from a list.

---

### 2. `filter()` Method

The `filter()` method is used to **select elements** that meet a specific condition and return a new array.

### Example:

```javascript
const numbers = [1, 2, 3, 4];

const evenNumbers = numbers.filter((num) => num % 2 === 0);

console.log(evenNumbers); // [2, 4]
```

### Use Case:

We can use `filter()` when we want to **remove unwanted data**, such as filtering active users, valid items, or specific categories.

---

### 3. `reduce()` Method

The `reduce()` method is used to **reduce an array to a single value** by applying a function on each element.

### Example:

```javascript
const numbers = [1, 2, 3, 4];

const sum = numbers.reduce((total, num) => total + num, 0);

console.log(sum); // 10
```

### Use Case:

We can use `reduce()` for tasks like **calculating totals, counting items, grouping data, or building complex results**.

---

## React.js fundamentals

### 1. What is React and How Does Virtual DOM Work?

- **React** is a popular JavaScript library used for building user interfaces, especially for single-page applications (SPAs).
- It was developed by Facebook and allows developers to create reusable UI components that make applications easier to build and maintain.

- React helps to update only the parts of the UI that change, instead of reloading the entire page, which makes applications fast and efficient.

---

### Virtual DOM

The **Virtual DOM (Document Object Model)** is a lightweight copy of the real DOM. Instead of directly updating the real DOM (which is slow), React first makes changes in the Virtual DOM.

---

### How Virtual DOM Works

The working of the Virtual DOM:

1. When the state or data of a component changes, React creates a new Virtual DOM.
2. It then compares this new Virtual DOM with the previous one. This process is called **diffing**.
3. React identifies only the parts that have changed.
4. Finally, it updates only those specific parts in the real DOM instead of updating everything.

---

### Why Virtual DOM is Fast

- Updating the real DOM directly is slow because it involves complex operations like reflow and repaint.
- The Virtual DOM reduces these operations by updating only the necessary elements.

---

### What are Components in React? Explain Functional vs Class Components

- **components** are the building blocks of a user interface. A component is a reusable piece of code that defines how a part of the UI looks and behaves.

- Instead of writing one large file for the entire UI, React helps us to break it into small, independent components such as buttons, forms, headers, and cards. This makes the code easier to manage, reuse, and maintain.

---

### Types of Components in React

There are two main types of components in React:

1. **Functional Components**
2. **Class Components**

---

### 1. Functional Components

Functional components are simple JavaScript functions that return JSX (UI structure). They are the modern and recommended way of writing components.

### Example:

```javascript
function Greeting() {
  return <h1>Hello, Karan</h1>;
}
```

---

### 2. Class Components

- Class components are ES6 classes that extend `React.Component`. They were used before hooks were introduced.
- But now we prefer functional component over class component. Because they provide all the feature like lifecycle methods after hooks introduction which was previously only provided by classs component.
- Functional components is simple and easy as compare to class components.

### Example:

```javascript
import React, { Component } from "react";

class Greeting extends Component {
  render() {
    return <h1>Hello, Karan</h1>;
  }
}
```

---

### 3. What are Props and State in React? What is the Difference Between Them?

### Props

**Props** are used to pass data from one component to another, usually from a parent component to a child component.

Props are **read-only**, which means a component cannot change the props it receives.

### Example:

```javascript
function Greeting(props) {
  return <h1>Hello, {props.name}</h1>;
}

// Usage
<Greeting name="Karan" />;
```

Here, `name` is passed as a prop to the `Greeting` component.

---

### What is State?

- **State** is used to store data that belongs to a component and can change over time.
- When the state changes, the component automatically re-renders to reflect the updated data.

### Example:

```javascript
import { useState } from "react";

function Counter() {
  const [count, setCount] = useState(0);

  return <button onClick={() => setCount(count + 1)}>Count: {count}</button>;
}
```

Here, `count` is a state variable that updates when the button is clicked.

---

### What are React Hooks? Explain Common Hooks Used in Modern React Applications

- **React Hooks** are special functions that allow you to use state and other React features inside **functional components**.

- Before hooks were introduced, these features were only available in class components. Hooks made React code simpler, cleaner, and easier to manage.

---

### Why Hooks are Important

Hooks allow you to:

- Manage state inside functional components
- Handle side effects (like API calls)
- Reuse logic across components
- Write cleaner and more readable code

---

### Commonly Used React Hooks

---

## 1. `useState`

The `useState` hook is used to create and manage state inside a component.

### Example:

```javascript
import { useState } from "react";

function Counter() {
  const [count, setCount] = useState(0);

  return <button onClick={() => setCount(count + 1)}>Count: {count}</button>;
}
```

It allows the component to store and update data.

---

### 2. `useEffect`

- The `useEffect` hook is used to handle side effects such as API calls, timers, or updating the DOM.

- It runs after the component renders.

- We also control how many times this function will run.

- If dependency array is missing in function, then function run everytime whenever component render.

- If dependency array is present and empty ([]), then run only on component mount.

- If dependency array contains value, then function run everytime whenever this value change.

### Example:

```javascript
import { useEffect } from "react";

useEffect(() => {
  console.log("Component mounted");
}, []);
```

---

### 3. `useContext`

- The `useContext` hook is used to access data from a global context without passing props manually at every level.

- It helps to avoid "prop drilling".

### Example:

```javascript
import { useContext } from "react";

const value = useContext(MyContext);
```

---

## 4. `useRef`

- The `useRef` hook is used to directly access or store references to DOM elements or values.
- It is used to focus inputs or storing values without re-rendering.

### Example:

```javascript
import { useRef } from "react";

const inputRef = useRef(null);
```

---

### 5. `useMemo`

- The `useMemo` hook is used to optimize performance by memoizing (caching) expensive calculations.
- It prevents unnecessary recalculations.

### Example:

```javascript
const result = useMemo(() => computeValue(a, b), [a, b]);
```

---

### 6. `useCallback`

The `useCallback` hook is used to memoize functions so they are not recreated on every render.

### Example:

```javascript
const handleClick = useCallback(() => {
  console.log("Clicked");
}, []);
```

---

### 7. `useReducer`

The `useReducer` hook is used for managing complex state logic.

### Example:

```javascript
const [state, dispatch] = useReducer(reducer, initialState);
```

---

### 5. How Does Conditional Rendering and List Rendering Work in React?

---

### 1. Conditional Rendering

**Conditional rendering** means showing or hiding UI elements based on a condition, just like using `if` statements in JavaScript.

---

### Using `if` Statement

We can use a normal `if` condition inside your component:

```javascript
function Greeting({ isLoggedIn }) {
  if (isLoggedIn) {
    return <h1>Welcome back!</h1>;
  } else {
    return <h1>Please log in</h1>;
  }
}
```

---

### Using Ternary Operator

For shorter conditions, we can use the ternary operator:

```javascript
<h1>{isLoggedIn ? "Welcome" : "Please log in"}</h1>
```

---

### Using Logical `&&` Operator

When we only want to render something if a condition is true:

```javascript
{
  isLoggedIn && <p>You are logged in</p>;
}
```

---

### 2. List Rendering

**List rendering** is used to display multiple items by looping over an array and rendering elements for each item.

---

### Using `map()` Method

The `map()` function is commonly used to render lists in React.

```javascript
const users = ["Karan", "Rahul", "Aman"];

function UserList() {
  return (
    <ul>
      {users.map((user, index) => (
        <li key={index}>{user}</li>
      ))}
    </ul>
  );
}
```

---

### Importance of `key`

Each item in a list must have a **unique `key`** prop. This helps React identify which items have changed, added, or removed.

```javascript
<li key={user.id}>{user.name}</li>
```

---

### 6. What Does “Lifting State Up” and why is it needed?

Normally, each component manages its own state. However, when two or more components need to use the same data, keeping separate state in each component can lead to inconsistency.

To solve this, we **move the shared state to their nearest common parent**, and then pass it down to child components using props and this pattern is called “Lifting State Up”.

---

### Example:

```javascript
function Parent() {
  const [value, setValue] = useState("");

  return (
    <>
      <Input value={value} setValue={setValue} />
      <Display value={value} />
    </>
  );
}

function Input({ value, setValue }) {
  return <input value={value} onChange={(e) => setValue(e.target.value)} />;
}

function Display({ value }) {
  return <p>{value}</p>;
}
```

Here, the state is managed in the `Parent` component and shared with both `Input` and `Display`.

---

### Why is Lifting State Up Needed?

Lifting state up is important because:

- It keeps **data consistent** across components
- It avoids duplication of state
- It allows components to **communicate with each other**
- It makes the data flow more predictable

---

## State Management

### What is State Management?

State management is the process of handling and controlling the data of an application in a way that keeps the user interface updated and consistent with that data.

---

### Why is State Management Important?

- State management becomes important as soon as your application starts growing in size and complexity.

- In larger applications, multiple components may need access to the same data. If state is not managed properly, it can lead to confusion, bugs, and inconsistent user interfaces.

- Proper state management helps in:
  - Keeping data organized and predictable
  - Ensuring that the user interface always shows the correct data
  - Making the code easier to understand, debug, and maintain
  - Improving the scalability of the application

---

### Types of State

### 1. Local State

- Local state is the data that is managed within a single component. It is used when the data does not need to be shared with other parts of the application.

- For example, a toggle button or a form input field usually uses local state.

---

### 2. Global State

- Global state is shared across multiple components in an application. This type of state is useful when different parts of the application need access to the same data.

- For example, user authentication details or application themes are often managed as global state.

---

### 3. Server State

- Server state refers to the data that comes from an external source such as a backend server or an API.

- This type of state usually involves asynchronous operations like fetching, updating, and caching data.

---

### 4. UI State

- UI state controls the visual aspects of the application.

- For example: whether a button is disabled, or whether a loader is visible or not.

---

### Common State Management Approaches

### 1. Props Drilling

- Props drilling is a method where data is passed from a parent component to child components through multiple levels.

- It works for small applications, it becomes difficult to manage as the application grows because data has to be passed through many intermediate components that may not even need it.

---

### 2. Context API

- The Context API is a built-in feature that allows us to share state across components without passing props manually at every level.

- It is a good choice for small to medium-sized applications where we need a simple global state solution.

---

### 3. Redux

- Redux is a popular state management library that provides a structured way to manage application state.

- Redux is commonly used in large applications where state management becomes complex.

It works using three main concepts:

- A store that holds the entire state
- Actions that describe what should happen
- Reducers that update the state based on actions

---

### 4. Modern Libraries (Zustand, Recoil, Jotai)

- These are modern alternatives to Redux that help to simplify state management.

- They require less boilerplate code and are generally easier to understand, making them a good choice for many modern applications.

---

### 5. React Query

- React Query is mainly used for managing server state.

- It simplifies tasks such as data fetching, caching, synchronization, and error handling, which are otherwise difficult to manage manually.

---

### Working of State Management

The flow of state management usually follows a simple pattern:

1. The user interacts with the user interface
2. An action or event is triggered
3. The state gets updated based on that action
4. The user interface re-renders to reflect the updated state

This cycle ensures that the UI always stays in sync with the data.

---

### Problems Without Proper State Management

If state is not handled properly, several issues can arise:

- Data may become inconsistent across components
- Debugging becomes difficult
- The codebase becomes messy and hard to maintain
- Performance issues may occur due to unnecessary updates

---

### Best Practices to manage the state properly

To manage state effectively, we should follow these practices:

- Keep the state as simple and minimal as possible
- Use local state whenever the data is limited to one component
- Use global state only when multiple components need the same data
- Clearly separate server state from UI state
- Avoid unnecessary re-renders by updating state efficiently

---

## Git workflow

These are the common Git commands Which we used on a daily basis.

---

## Basic Commands

1. `ls`  
   Shows all files and folders in the current directory.

2. `mkdir folderName`  
   Creates a folder in the current directory.

3. `cd folderName`  
   Moves inside the specified folder.

4. `git init`  
   Initializes a Git repository by creating a `.git` folder that stores the history of changes.

5. `ls -a`  
   Shows all files including hidden files.

6. `touch fileName`  
   Creates a new file in the current directory.

7. `git status`  
   Shows the current state of the working directory and staging area.

8. `git add .`  
   Stages all changes in the current directory.

9. `git add fileName`  
   Stages changes of a specific file.

10. `git commit -m "commit message"`  
    Saves staged changes with a commit message.

11. `vi fileName`  
    Opens the file in the editor.

12. `cat fileName`  
    Displays the content of a file.

13. `git restore --staged fileName`  
    Unstages changes from the staging area (used after `git add`).

---

## History & Undo

14. `git log`  
    Shows commit history.

15. `rm -rf fileName/folderName`  
    Deletes a file or folder.

16. `git reset commitHash`  
    Moves HEAD to a previous commit and removes commits above this commitHash from the current branch history.

---

## Stash

17. `git stash`  
    Temporarily saves uncommitted changes.

18. `git stash pop`  
    Restores the most recent stashed changes.

19. `git stash clear`  
    Removes all stashed changes.

---

## Remote Repositories

20. `git remote add origin repoUrl`  
    Connects local repository to a remote repository.

21. `git push origin branchName`  
    Pushes commits to a specific branch on GitHub.

22. `git branch branchName`  
    Creates a new branch.

23. `git checkout branchName`  
    Switches to the specified branch.

24. `git merge branchName`  
    Merges the specified branch into the current branch.

25. `git remote -v`  
    Shows all remote repository URLs.

26. `git clone repoUrl`  
    Clones an existing repository into the local system.

27. `git remote add upstream repoUrl`  
    Adds the original repository as upstream (used after forking).

---

## Sync with Upstream

28. `git fetch --all --prune`  
    Fetches all updates from remotes and removes deleted branches.

29. `git reset --hard upstream/main`  
    Resets local main branch to match upstream main.

30. `git pull upstream main`  
    Shortcut for fetching and resetting to upstream main.

---

## Rebase

31. `git rebase -i commitHash`  
    Squashes or edits commits above the specified commit.

---

## Collaboration Workflow Notes

- Avoid committing directly on the `main` branch.
- Always create a **new branch** for each feature or bug fix.
- For every feature or bug:
  - Create a new branch
  - Push the branch
  - Create a pull request
- Each pull request should handle **only one feature or bug**.
- When two developers change the same line of code in different ways and try to merge their changes into the same branch, this is called a Merge Conflict.
  - This conflict is resolved manually by edit the file to choose which changes to keep or write new code.

---

## Performance Optimization

### 1. What is Performance Optimization and Why is it Important in Frontend Development?

- **Performance optimization** refers to the process of improving how fast a website or web application loads, renders, and responds to user interactions.

- It focuses on reducing loading time, minimizing delays, and ensuring a smooth and efficient user experience.

---

### 2. Why Performance Optimization is Important

The Performance Optimization is important due to the following reason:

---

### 1. Better User Experience

A fast website feels smooth and responsive. Users can navigate easily without delays, which improves overall satisfaction.

---

### 2. Lower Bounce Rate

If a website takes too long to load, users may leave before it even opens. Optimizing performance helps keep users engaged.

---

### 3. Improved SEO Ranking

Search engines like Google consider page speed as a ranking factor. Faster websites are more likely to rank higher in search results.

---

### 4. Better Performance on All Devices

Optimized websites work well even on slower devices and networks, which is important for mobile users.

---

### 5. Reduced Resource Usage

Efficient code and optimized assets reduce CPU, memory, and bandwidth usage, making the application more scalable.

---

### 3. What are Key Performance Metrics like LCP, FCP, and TTI?

These metrics help developers understand the user experience and identify areas for improvement.

---

### 1. First Contentful Paint (FCP)

- **FCP** measures the time it takes for the first piece of content (like text, image, or SVG) to appear on the screen after the page starts loading.

- It gives users the first visual feedback that something is happening.

- The Good Value is less than **1.8 seconds**

---

### 2. Largest Contentful Paint (LCP)

- **LCP** measures the time it takes for the largest visible content element (like a large image or heading) to fully load and appear on the screen.

- It reflects how quickly the main content of the page becomes visible to the user.

- The Good Value is less than **2.5 seconds**.

---

### 3. Time to Interactive (TTI)

- **TTI** measures how long it takes for the page to become fully interactive, meaning users can click buttons, type, and interact without delays.

- A page might look ready, but if it is not interactive, it leads to a poor user experience.

- The Good Value is less than **3.8 seconds**

---

### 4. What is Lazy Loading and Code Splitting?

They help reduce the initial load time of a website by loading only what is needed at the right time.

---

### 1. Lazy Loading

**Lazy loading** is a technique where resources (like images, components, or scripts) are loaded **only when they are needed**, instead of loading everything at once.

---

### Example

```html
<img src="image.jpg" loading="lazy" alt="example" />
```

Here, the image loads only when it comes into the viewport (visible area of the screen).

---

### 2. Code Splitting

**Code splitting** is a technique where your JavaScript bundle is divided into smaller chunks, and only the required code is loaded when needed.

---

### Example:

```javascript
import { lazy, Suspense } from "react";

const About = lazy(() => import("./About"));

function App() {
  return (
    <Suspense fallback={<p>Loading...</p>}>
      <About />
    </Suspense>
  );
}
```

---

### 6. What is Debouncing and Throttling in JavaScript?

They help improve performance and prevent unnecessary function calls.

---

## ⏳ 1. Debouncing

- **Debouncing** ensures that a function is only executed **after a certain delay has passed since the last time the event was triggered**.

- This means the function runs only once when the user stops performing the action.

- It is used in Search input (API call after user stops typing), Form validation, Auto-save features.

---

### Example

```javascript
function debounce(func, delay) {
  let timer;

  return function (...args) {
    clearTimeout(timer);
    timer = setTimeout(() => {
      func.apply(this, args);
    }, delay);
  };
}
```

---

### 2. Throttling

- **Throttling** ensures that a function is executed **at most once in a specified time interval**, no matter how many times the event is triggered.

- It is used in Scroll events, Window resizing, Button click prevention.

---

### Example:

```javascript
function throttle(func, limit) {
  let lastCall = 0;

  return function (...args) {
    const now = Date.now();

    if (now - lastCall >= limit) {
      lastCall = now;
      func.apply(this, args);
    }
  };
}
```

---

## Benefits of TypeScript

**TypeScript** is a superset of JavaScript that adds **static typing** and other powerful features to make development more reliable and scalable.

---

### Key Benefits of TypeScript

### 1. Static Typing

- TypeScript allows us to define types for variables, functions, and objects.
- This helps catch errors during development instead of at runtime.

```typescript
let name: string = "Karan";
```

---

### 2. Better Code Quality

With type checking, TypeScript helps prevent common mistakes like passing wrong data types or accessing undefined properties.

---

### 3. Improved Developer Experience

TypeScript provides better support in code editors with:

- Autocomplete
- IntelliSense
- Error highlighting

---

### 4. Easier to Maintain Large Applications

In large projects, TypeScript makes code more structured and understandable, which helps teams collaborate more effectively.

---

### 5. Early Error Detection

Errors are caught during compilation rather than at runtime, reducing bugs in production.

---

### 6. Supports Modern JavaScript Features

TypeScript supports the latest JavaScript features and can compile them into older versions for better browser compatibility.

---

### 7. Better Refactoring

TypeScript makes it easier to rename variables, change structures, or update code without breaking the application.

---

### 8. Strong Community and Ecosystem

TypeScript is widely adopted and supported by major frameworks like React, Angular, and Node.js.

---

## Basic Frontend Architecture

- **Frontend architecture** refers to the way we structure, organize, and manage the code of a frontend application so that it is scalable, maintainable, and easy to understand.

- A good frontend architecture ensures that our project grows smoothly without becoming messy or hard to manage.

---

### Key Parts of Basic Frontend Architecture

---

### 1. Component-Based Structure

- Modern frontend applications (like React apps) are built using **components**, where each part of the UI is divided into reusable pieces.
- Example: Navbar, Button, Card, Form, etc.

- This makes the code modular and reusable.

---

### 2. Folder Structure

A well-organized folder structure helps developers quickly find and manage files.

### 🔸 Example Structure:

```
src/
  components/
  pages/
  hooks/
  services/
  utils/
  assets/
```

- `components/` → Reusable UI parts
- `pages/` → Different screens
- `services/` → API calls
- `utils/` → Helper functions

---

### 3. State Management

Managing data across the application is an important part of architecture.

- For Local state → `useState`
- For Global state → `useContext`, Redux, etc.

It helps to keep the data consistent across components.

---

### 4. Separation of Concerns

Each part of the application should have a clear responsibility.

- UI → Components
- Logic → Hooks / services
- Data fetching → API layer

This keeps code clean and easy to maintain.

---

### 5. Routing

- Routing defines how users navigate between different pages.
- It helps to create multi-page-like experiences in single-page applications.

```javascript
<Route path="/about" element={<About />} />
```

---

### 6. API Handling Layer

- All API calls should be managed in a separate layer (like `services/`), instead of mixing them directly in components.
- This improves reusability and maintainability.

---

### 7. Styling Strategy

Consistent styling is important. Common approaches include:

- CSS Modules
- Styled Components
- Tailwind CSS

It helps to maintain the design consistency acrosse web application.

---

### 8. Performance Optimization

Good architecture also considers performance by using:

- Lazy loading
- Code splitting
- Memoization

---

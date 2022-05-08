# Module 1 Challenge 

GIVEN a webpage meets accessibility standards 

(1) WHEN I view the source code 
    THEN I find semantic HTML elements 
EXAMPLE: 
- <header>     - Defines a header for a document or a section
- <nav>        - Defines a set of navigation links
- <main>       - Contains the main content of a document 
- <section>    - Defines a section in a document 
- <article>    - Defines an independent, self-contained content
- <aside>      - Defines content aside from the content (like a sidebar)
- <footer>     - Defines a footer for a document or a section
- <details>    - Defines additional details that the user can open and close on demand
- <summary>    - Defines a heading for the <details> element 
- <figure>     - Specifies self-contained content, like illustrations, diagrams, photos, code listings, etc. 
- <figcaption> - Defines a caption for a <figure> element
- <mark>       - Defines text that should be marked or highlighted.
- <time>       - Defines a specific time (or datetime)


(2) WHEN I view the structure of the HTML elements 
    THEN I find that the elements follow a logical structure independent of styling and positioning

- what does this mean? 
- Is this referring to "whitespace" and "indentation"? 
(Tools to visualize the relationship between elements)

EXAMPLE: 
<body>
    <p>Paragraph 1</p>
    <p>Paragraph 2</p>
</body>

(3) WHEN I view the image elements 
    THEN I find accessible alt attributes 

- <img> should include <alt>

(4) WHEN I view the heading attributes 
    THEN they fall in sequential order 

- when there is a <h1> it should list <h1> to <h6> sequentially in the document 
- Are you allowed to use heading attributes twice? So to get the same text size?

(5) WHEN I view the title element 
    THEN I find a concise, descriptive title

<title> element: 
- defines a title in the browser toolbar
- provides a title for the page when it is added to favorites 
- displays a title for the page in search-engine results 

Tips for creating good titles: 
-Go for a longer, descriptive title (avoid one- or two-word titles)
-Search engines will display about 50-60 characters of the title, so try not ot have titles longer than that 
-Do not use just a list of words as the title (this may reduce the page's position in search resuls)

**You can NOT have more than one <title> element in an HTML document 


https://kamipacanos.github.io/Module_1_Challenge-/ 

# Day 9
- The Poem
The browser sends an HTTP request message to the server
The server approves  clients request, sends a "200 OK" further
Further in the process, data packets pull an internet stunt,
Stunt with your browser sending files in small chunks
Chunks turn into a completed webpage that might look cuter
Cuter is the way HTTP sends data to your computer.

# Parsed
- The browser parses the HTML file first, and that leads to the browser recognizing any <link> element references to external CSS stylesheets and any script element references to scripts.
- As the browser parses the HTML, it sends requests back to the server for any CSS files it has found from link elements, and any JavaScript files it has found from script elements, and from those, then parses the CSS and JavaScript.
- The browser generates an in-memory DOM tree from the parsed HTML, generates an in-memory CSSOM structure from the parsed CSS, and compiles and executes the parsed JavaScript.
- As the browser builds the DOM tree and applies the styles from the CSSOM tree and executes the JavaScript, a visual representation of the page is painted to the screen, and the user sees the page content and can begin to interact with it.
# Website images
-When you find the image you want, click on the image to get an enlarged view of it.
-Right-click the image (Ctrl + click on a Mac), choose Save Image As…, and choose a safe place to save your image. Alternatively, copy the image's web address from your browser's address bar for later use.
# String vs Number
- To signify that the value is a string, enclose it in single quote marks.
- This is a number. Numbers don't have quotes around them.

# Why Variables ?
-  Variables are necessary to do anything interesting in programming. If values couldn't change, then you couldn't do anything dynamic, like personalize a greeting message or change an image displayed in an image gallery.

# Html attributes
- Attributes contain extra information about the element that won't appear in the content. In this example, the class attribute is an identifying name used to target the element with style information.

An attribute should have:

-A space between it and the element name. (For an element with more than one attribute, the attributes should be separated by spaces too.)
The attribute name, followed by an equal sign.
An attribute value, wrapped with opening and closing quote marks.

# Anatomy of HTML
- The anatomy of our element is:

-The opening tag: This consists of the name of the element (in this example, p for paragraph), wrapped in opening and closing angle brackets. This opening tag marks where the element begins or starts to take effect. In this example, it precedes the start of the paragraph text.
-The content: This is the content of the element. In this example, it is the paragraph text.
-The closing tag: This is the same as the opening tag, except that it includes a forward slash before the element name. This marks where the element ends. Failing to include a closing tag is a common beginner error that can produce peculiar results.
-The element is the opening tag, followed by content, followed by the closing tag.

# Article vs Section Element tags
- article encloses a block of related content that makes sense on its own without the rest of the page (e.g., a single blog post).
- Section is similar to article, but it is more for grouping together a single part of the page that constitutes one single piece of functionality (e.g., a mini map, or a set of article headlines and summaries), or a theme. It's considered best practice to begin each section with a heading; also note that you can break articles up into different sections, or sections up into different articles, depending on the context.

#Typical Website Elements
- Main , article, section, header, section, nav and footer.

# SEO and Metadata
-Specifying a description that includes keywords relating to the content of your page is useful as it has the potential to make your page appear higher in relevant searches performed in search engines.

# Metadata Tag
-There are a lot of different types of meta elements that can be included in your page's head, but we won't try to explain them all at this stage, as it would just get too confusing. Instead, we'll explain a few things that you might commonly see, just to give you an idea.

# First step designing a website
- Project ideation

# Most Important Question to asner
- what do i want to accomplish ?

# why H1 as a Top Heading not Span?
- span will render it to look like a top level heading, but it has no semantic value, so it will not get any extra benefits as described above. It is therefore a good idea to use the h1 HTML element for the right job.
#Benefits of Semantic tags in Html
-Search engines will consider its contents as important keywords to influence the page's search rankings (see SEO)
-Screen readers can use it as a signpost to help visually impaired users navigate a page
-Finding blocks of meaningful code is significantly easier than searching through endless divs with or without semantic or namespaced classes
-Suggests to the developer the type of data that will be populated
-Semantic naming mirrors proper custom element/component naming

# Things i want to know more about 
- 
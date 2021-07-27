# Wireframe

## Intro to Wrireframing
  - Allows designers to plan the design of a website, app, or product
  - Lets you plan the layout and interaction of your interface

## Steps to make a wireframe
  - Do your research
    - understanding who your audience is by way of user research, detailing requirements, and creating user personas
  - Prepare your research for quick reference
    - Create a cheatsheet with your business and user goals, your personas, and use cases
  - Make sure you have your user flow mapped out
    - Make sure you have concept of where your users will be coming from and where you need them to end up
  - Ask yourself these questions while drawing
    - How can you organise the content to support your users’ goals?
    - What should the user see first when arriving at the page?
    - Which buttons or touch points does the user need to complete the desired actions?
  - Add some informational details to prepare your wireframe. Think about: usability, calls to action, trust building elements
  - Start turning your wireframes into prototypes
  - Keys to a good wireframe:
    - Clarity- Your wireframe needs to answer the questions of what that site page is, what the user can do there, and if it satisfies their needs
    - Confidence- Ease of navigation through your site and clear calls-to-action increase user confidence in your brand
    - Simplicity- Too much information, copy, or links, can be distracting

# HTML basics

HTML (Hypertext Markup Language) is the code that is used to structure a web page and its content
  - The opening tag: This consists of the name of the element, wrapped in opening and closing angle brackets. This states where the element begins or starts to take effect
  - The closing tag: This is the same as the opening tag, except that it includes a forward slash before the element name. This states where the element ends.
  - The element: The opening tag, the closing tag, and the content together comprise the element.
  - Attributes contain extra information about the element that you don't want to appear in the actual content.
    - A space between it and the element name
    - The attribute name followed by an equal sign.
    - The attribute value wrapped by opening and closing quotation marks.
  - Nesting is putting other elements inside other elements
  - Empty elements- elements with no content
  - Element examples:
     - <!DOCTYPE html> — doctype. It is a required preamble. Needed to make sure your document behaves correctly.
     - <html></html> — This element wraps all the content on the entire page and is sometimes known as the root element.
     - <head></head> — This element acts as a container for all the stuff you want to include on the HTML page that isn't the content you are showing to your page's viewers.
     - <meta charset="utf-8"> — This element sets the character set your document should use to UTF-8 which includes most characters from the vast majority of written languages.
     - <title></title> — This sets the title of your page, which is the title that appears in the browser tab the page is loaded in.
     - <body></body> — This contains all the content that you want to show to web users when they visit your page,
  - Image- The <img> element embeds an image into our page in the position it appears. It does this via the src (source) attribute, which contains the path to our image file.
  - Headings- Allow you to specify that certain parts of your content are headings — or subheadings.
     - HTML contains 6 heading levels, <h1>–<h6>
  - Paragraphs- <p> elements are for containing paragraphs of text; you'll use these frequently when marking up regular text content.
  - Lists- 
    - Unordered lists are for lists where the order of the items doesn't matter, such as a shopping list. These are wrapped in a <ul> element.
    - Ordered lists are for lists where the order of the items does matter, such as a recipe. These are wrapped in an <ol> element.
  - Links- use a simple element — <a> — "a" being the short form for "anchor".
    - Choose some text.
    - Wrap the text in an <a> element
    - Give the <a> element an href attribute: href=""
    - Fill in the value of this attribute with the web address that you want the link to link to
  
# Semantics
  
  - In JavaScript, consider a function that takes a string parameter, and returns an <li> element with that string as its textContent. Would you need to look at the code to understand what the function did if it was called build('Peach'), or createLiWithContent('Peach')?
  - In CSS, consider styling a list with li elements representing different types of fruits. Would you know what part of the DOM is being selected with div > ul > li, or .fruits__item?
  - In HTML, for example, the < h1 > element is a semantic element, which gives the text it wraps around the role (or meaning) of "a top level heading on your page."
  
  
  
  

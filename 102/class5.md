# Class 5: Design web pages with CSS

1. **What is the purpose of CSS?**

    - CSS is a language for specifying how documents are presented to users — how they are styled, laid out, etc. SS can be used for very basic document text styling — for example, for changing the color and size of headings and links. It can be used to create a layout — for example, turning a single column of text into a layout with a main content area and a sidebar for related information. It can even be used for effects such as animation. Have a look at the links in this paragraph for specific examples.  
    <br>

2. **What are the three ways to insert CSS into your project?**

    - External CSS
    - Internal CSS
    - Inline CSS    
    <br>


    **External CSS**

    With an external style sheet, you can change the look of an entire website by changing just one file!Each HTML page must include a reference to the external style sheet file inside the <link> element, inside the head section. An external style sheet can be written in any text editor, and must be saved with a .css extension. The external .css file should not contain any HTML tags.

    **Internal CSS**

    An internal style sheet may be used if one single HTML page has a unique style.
    The internal style is defined inside the "style" element, inside the head section.

    **Inline CSS**

    An inline style may be used to apply a unique style for a single element.
    To use inline styles, add the style attribute to the relevant element. The style attribute can contain any CSS property.

3. **Write an example of a CSS rule that would give all <p> elements red text.**

    p {color: red;}
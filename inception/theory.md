what is emmet?
Emmet is a free add-on for your text editor that allows you to type shortcuts that are then expanded into full pieces of code.


The Differences Between
innerHTML, innerText and textContent
The innerHTML property returns:
The text content of the element, including all spacing and inner HTML tags.
The innerText property returns:
Just the text content of the element and all its children, without CSS hidden text spacing and tags, except <script> and <style> elements.
The textContent property returns:
The text content of the element and all descendaces, with spacing and CSS hidden text, but without tags.

The innerText property returns:
This element has extra spacing and contains a span element.
The innerHTML property returns:
   This element has extra spacing    and contains <span>a span element</span>.
The textContent property returns:
   This element has extra spacing    and contains a span element.

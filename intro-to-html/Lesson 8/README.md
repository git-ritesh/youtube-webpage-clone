# LESSON 8 CSS DISPLAY PROPERTY

- You might have seen that when you write paragraphs in HTML they're on top of each other but how come the text boxes and images appear on the same line ? 

![image with search bar and some para](img/lesson%208%20readme%20photo%201.png)

This happens due to display property in CSS

In HTML, There are three types of elements :

1. **block element** : takes up the entire line. Paragraph by default is a block element. 

    we can see that in our devtools by :

    _Right clicking in the browser > Inspect > Inspector button > Hover over the paragraph._ 

    you'll see that the text ends at some extent, but the paragraph extends to the end of the line. 

    Regardless of how much space they actually take up they take up the entire line. So they're forced to be on their own line.

2. **inline-block element** : only takes up as much space as needed and doesn't take up entire line. So another element can appear beside them.

     An Example of the `inline-block` element is the `<img>` element and the `<input>` element. 

3. **inline element** : inline elements are basically just text elements.They appear within a line of text.

    we have already used an element `<strong>`This element appears within a line of text
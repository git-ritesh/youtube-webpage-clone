# The `<div>` Element

In this lesson we're gonna learn about the most important HTML element i.e. the `div` element. 
for example if you see the _HTML code of Twitter.com_ you'll see lots and lots of **divs** used in the code, Another best example is Instagram if you'll look at the _Instagram HTML_, it also uses lots and lots of **divs**.

**So what actually is a div & why is it used so much ?**

- `<div>` stands for division. But an easy way to understand this is to consider, A `div` **is just a box.**

- `div` like a paragraph by default is a `block` element.

  _But like we learned in the previous lesson_ we can easily change this into an `inline-block` using the `display` property. 

- `div` just creates a box around our content.

**Why is the `div` so useful ?**

- The key feature of the `div` is that it can contain any other element inside.

- We can put _paragraphs, mages & any other elements_ inside `div`** and other divs

- **divs are meant to be containers.**

  ![div container image](img/div%20container%20example.png)
- You can see in the above image the two red boxes are the divs containing multiple elements like the images & paragraphs. 

- And if we look at our youtube design that we have in our project we use containers everywhere.

- These _containers allow us to group all elements together_. so that we can create our desired layout.

**What will happen if we put a paragraph element inside a div whose width is 300px ?**

Sol. As we know that a paragaraph is a block type element so it takes up the entire line in the page but if we put the paragraph into the div whose width is 300px, the paragraph will take the entire line but only in the div i.e. up to 300px in the whole page.

Note : _So, the way that block element actually work is that they take up the entire line in their container rather than the whole page._ 
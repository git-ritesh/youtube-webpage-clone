# LESSON-7 IMAGES AND TEXT BOXES

In this lesson we learn about : 

## Images : 

  -  `img` : used to embed an image in the webpage.

  - it is an unique element _(void element)_ which doesn't require any closing tag. 
  
  - Attributes :
    - `src` : describes which image to display on the website. it contains the filepath.

    - `alt` : describes the image in textual form for blind users

  ###  Styling an Image :
  - `width` : sets the width of an image.

  - when we alter the width of an image the height also adjusts to have the same dimensions _(have the same shape)_. So, that's one behaviour of an image.

  - if we set the height as well this will cause the image to lose its shape.

  - if we set the height of the image more than the default height of the image then the image will be stretched.

  - To overcome this problem a property `object-fit` comes into the picture. 

  - `object-fit` : determines what happens if the size we provide exceeds the image dimensions.

  - object-fit : cover : this tells the image to cover the area we had set but it also gonna keep its shape.

  - But, the area might not be big enough to show the whole image which may or may not be ok depending on what we wanna do. 

  - Now, we can adjust which part of the image we want to see using `object-position` 
  
  - `object-fit : cover;` -
    
      ![object-fit-cover illustration](img/object-fit-cover%20illustration.png)

  - `object-fit : contain;` -
  
      ![object fit contain illustration](img/object-fit-contain%20illustration.png)

## Search Box : 

  - How to create a search box ? 
  The HTML code for creating a text box is `<input>`. 

  - `<input>` is also a void element just like the `<img>` element, it also doesn't require any closing tag. 
  
  - Several attributes that we can give to `<input>` element are : 

    1. `type` : it is an attribute which specifies which type of input the element will take from the user.
      
        Syntax :- `<input type="text">`

        ![search Box](img/Search%20Box.png)

        - `type="text"` will create a text box and take text input from the user.

        - `type="checkbox"` will create a checkbox and take selection input from the user.
        
        But our need is to create a search box for youtube clone so we will use `type="text"` here.

        The next thing you can notice is that there is a word _"Search"_ inside the search box and it is known as a **Placeholder**. Let's know more about the placeholder. 

    2. `placeholder` : it is an attribute which tells the user, what to put in the text box. when we start typing in the text box the placeholder word disappears.

        we can target the placeholder in the CSS and apply some ususal CSS properties like `font-size`, `margin`, etc. So, Basically everything that we learn so far about CSS properties we can use on the search box.

# Exercises :

  ![Lesson 7 Exercises Photo](img/Leson%207%20Exercises.png)

  ![Lesson 7 Exercises Photo](img/Exercise%207%20remaining%20probs.png)
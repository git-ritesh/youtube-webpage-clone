# LESSON-7 IMAGES AND TEXT BOXES

In this lesson we learn about : 

1. Images : 

    -  `img` : used to embed an image in the webpage.

    - it is an unique element _(void element)_ which doesn't require any closing tag. 
    
    - Attributes :
      - `src` : describes which image to display on the website. it contains the filepath.

      - `alt` : describes the image in textual form for blind users

    - Styling an Image :
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


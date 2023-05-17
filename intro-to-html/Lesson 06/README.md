# LESSON 6 THE HTML FILE STRUCTURE 

In this lesson we learnt about :

1. Proper structure of HTML :
    ```html
      <!DOCTYPE html>
      <html>
        <head></head>
        <body></body>
      </html>
      ```

2. Nesting : 

    - Placing elements inside of another element is called Nesting. 

    - In the above structure you can see that `<head>` and `<body>` are inside of the parent element `<html>` This is an example of Nesting.  

3. Notes : 
    - Every file has one & only one `<html>` element and this element represents the entire webpage. 
    - `<html>` element is designed for nesting. 
    - It's designed to contain one `<head>` element and one `<body>` element. 
    - everything on our webpage is supposed to go inside the `<head>` or inside the `<body>` 
    - `<body>` contains all the elements that are visible.
    - Anything which doesn't show on page belongs to `<head>` section.

4. Features of following the structure :
    
    - `<title>`  This element doesn't actually shows on the page, it shows on the tab on the top, That's why it belongs to `<head>` section. it is the first feature we get after following the structure. 

    - The second feature we get after following the structure is the ability to automatically reload our webpage whenever we change our code.
        - So you have noticed that every time we change our code we have to go to our website and refresh the webpage. 

        - Now we can actually avoid this by following the structure by _installing a vscode extension_ **"Live Server"**.

        - Now go to the extension area in the exploer menu > Search for the extension "live server" and install the first extension you see. 

        - Now you can use "Live Server" to reload our page automatically whenever our code changes. 

        - To open the website using Live Server right click in the editor area and select the option : **Open with Live Server**

        - Now whenever we change our code and _save_ it automatically reloads our webpage without going back and forth. So that's a really useful feature for speed up the development process.

    - `<style>` : This element doesn't really create anything visible. But it could alter the styles of other elements. So this a good example of something that should go in the `<head> `element because it doesn't show up physically on the page.

    - `<link>` : it is a special element it doesn't require any closing tag. element like this are called **void elements**. some more void elements are br, hr, link, meta etc.

      - it has two attributes : 
          1. `rel` : stands for **relation** & specifies what kind of thing we are linking. for e.g. `stylesheet`

          2. `href` : this tells the link which files we're gonna link into this file.  

      - `<link rel="stylesheet" href="style.css">` is used to link the HTML file with the CSS file which contains the styles of the elements. 


      - Benefits of using :
          - Each file contains less code.

          - Each file contain one type of code.
      
      - **filepaths** : it specifies how we can locate files within our HTML code. `/` is used to go into a folder.

    - The last feature we're gonna look at, that we get from the structure of the HTML is the ability to add new fonts onto our website. 
        - websites have a set of fonts by default that we can use for e.g. one of them is called `Arial` Another one we see is called `Times New Roman` that's the font we get on a freshg website.

        - In addition to these default fonts we can load new fonts from the internet. and we're gonna learn how to do that within the structure :

        - Google actually provides a lot of great free fonts.

      <details>

        <summary> How to use google fonts in your webpage : </summary>

        - Step 1: Open the browser and Google Search for "google fonts"
        - Step 2: Open the first link from the search results 
        - Step 3: Search for your desired fonts in the "Search fonts" Search section
        - Step 4: Select the font from the search results and click on it.
        - Step 5: Select the font families you want to add in your font bucket. 
        - Step 6: After adding the fonts to the bucket list they'll appear in right side and you'll see two options `<link>` and `@import` you can add the fonts by using any of the both.
        - Step 7: if you want to add the fonts through `<link>` then you have to select it, then you have to copy the code below the `<link>` and paste in the `<head>` tag of the HTML code.
        - Step 8: if you want to add the fonts through `@import` then you have to select it, then you have to copy the code below and paste it on the top in the CSS code.
        
      </details>

## Exercises :

![Exercises for Lesson 6](lesson%206%20exercises.png)

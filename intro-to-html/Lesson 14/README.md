# Lesson-14 | CSS Position

In this lesson we're gonna learn CSS Position.

### Notes : 
- So Position helps us do things like :
  - keep the header at the top of the page 
  - And also helps us keep the sidebar at the top of the page.

- Whenever we see an element on top of another element  that's using CSS Position.

- Like, if you see in the Project, the video time on the top of the thumbnail, the notification counter on top of the icon & when you hover over icon there's a tooltip on top of the page everything is using CSS Position.

- CSS Positions add another dimensions to our page. 

So, Just Like the previous lesson we're gonna create a [position.html](https://github.com/git-ritesh/HTML-CSS_Practice/blob/master/intro-to-html/Lesson%2014/position.html) just to practice position.

## Position Properties :

- `position: static;` -> it is the default `position` of an element.

- `position: fixed;` -> This property makes an element stick to the page at some fixed area.

  ### Note : 
  - when we set `position: fixed;` to an element then it doesn't take up space on the page anymore.

  - it starts floating on the page.

- So, the position Property has 4 special properties we can use to move the element around & Those are :- 

  1. `top` : Top specifies how far away our element is, from the top of the window. 
      - we can set a `px` (pixel) measurement for e.g. `top: 0px;` will make the top of our element `0px` from the top of our browser window. if we set `top: 10px;` the top of our element will be now `10px` from the edge of the browser window.

  2. `left` : Left tells us how much space is b/w the left of our element and the browser window.

      - for e.g. if we set `left: 0px;` then the left side of our element will be on the left edge of our window or if we set `left: 50px;` then left side of our element will be `50px` away from our browser window.

  3. `bottom` : Bottom specifies how far away the bottom of the element is from the bottom of the browser window.
      - for e.g. if we set `bottom: 0px;` then the bottom of our element will be on the bottom edge of our browser window.

  4. `right` : Right tells us how much space is b/w the right of our element and the browser window.

        - for e.g. if we set `right: 0px;` then the right side of our element will stick to the right edge of our browser window.

   **Note** : **Special feature of these properties is that if we set it in the opposite direction then the element will stretch.**
  
    for e.g. if we set both the `left` and `right` properties to `0px` the element will be stretched from the left to right edge of the browser window.
    Same things happens with the `top` & `bottom`.
  
  So this is how we move the element around & resize it with position fixed.

- _Try creating header what you see in the project._
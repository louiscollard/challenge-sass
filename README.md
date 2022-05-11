# challenge-sass
Exercise for @BeCodeLiege

## The Mission
Your mission is to rewrite the example.css to a scss file with the following changes:

### Part 1

Nest the styling rules of grouped elements, like the sections in the Article or the <p> in the class messages.
Create variables for all the colors.
Make use of extend to re-use the same CSS for the "success", "error" and "warning" messages.
For the "error" message, change the background in green when you hover it. Use the nested syntax.
### Part 2
  
Make the general padding the same everywhere with one variable. But there are 2 execeptions :
The main should have a padding-top and padding-bottom to 0.
The footer h3 should have double the padding of the other elements. Use "operations" to do this. Do NOT hardcode the padding inside your scss.
Make one mixin for the 3 lines of the box-shadow styling using the color as a argument.
Write all your variables in a partial file and link it to the main file.
  
### Part 3 - the tricky part! (optional)
With the list of advantages (class "advantages"), create a gradation of color for the background and the text color. For it, you have to use a loop @for : here the documentation
  
### Link to the page
https://louiscollard.github.io/challenge-sass/

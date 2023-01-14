Hello! This is one of the very first GitHub assignments as part of The Odin Project. I alreayd have some experience in writing HTML, CSS, and JavaScript, but I'm very excited to learn about Git-related workflows. Fingers crossed!
Here's the full assignment:
#### Iteration 1: Initial Structure
Within the odin-recipes directory, create an index.html file.
Fill it out with the usual boilerplate HTML and add an h1 heading “Odin Recipes” to the body.
#### Iteration 2: Recipe Page
Create a new directory within the odin-recipes directory and name it recipes.
Create a new HTML file within the recipes directory and name it after the recipe it will contain. For example lasagna.html. You can use the name of your favorite dish or, if you need some inspiration, you can find a recipe to use here.
For now, just include an h1 heading with the recipe’s name as its content.
Back in the index.html file, add a link to the recipe page you just created. Example: Under the <h1>Odin Recipes</h1> heading, write out the link like so: <a href="recipes/recipename.html">Recipe Title</a>. The text of the link should again be the recipe name.
#### Iteration 3: Recipe Page Content
Your new recipe page should have the following content:

An image of the finished dish under the h1 heading that you added earlier. You can find images of the dish on Google or the recipe site we linked to earlier.

Under the image, it should have an appropriately sized “Description” heading followed by a paragraph or two describing the recipe.

Under the description, add an “Ingredients” heading followed by an unordered list of the ingredients needed for the recipe.

Finally, under the ingredients list, add a “Steps” heading followed by an ordered list of the steps needed for making the dish.

#### Iteration 4: Add More Recipes
Add two more recipes with identical page structures to the recipe page you’ve already created.
Don’t forget to link to the new recipes on the index page. Also, consider putting all the links in an unordered list so they aren’t all on one line.
Example:

```html
<ul>
    <li><a href="recipes/yourrecipe.html">Recipe Title 1</a></li>
    <li><a href="recipes/yourrecipe.html">Recipe Title 2</a></li>
    <li><a href="recipes/yourrecipe.html">Recipe Title 3</a></li>
</ul>
```
Your links won’t be flashy, but for now just focus on building them out.
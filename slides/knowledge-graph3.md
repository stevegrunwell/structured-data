#### Ultimate Chocolate Chip Cookies

```html
<div itemscope itemtype="http://schema.org/Recipe">
	<!-- Ingredients -->
	<ul>
		<li itemprop="ingredients">3/4 cup granulated sugar</li>
		<li itemprop="ingredients">3/4 cup packed brown sugar</li>
		<!-- ... -->
	</ul>

	<!-- Instructions -->
	<ol class="instructions">
		<li itemprop="recipeInstructions">Heat oven ...</li>
		<li itemprop="recipeInstructions">Mix sugars, ...</li>
		<!-- ... -->
	</ol>
</div>
```

Note:

Betty Crocker's markup is way too convoluted to fit onto one slide, but when we distill it down we get something like this:

A list of ingredients, each with itemprop of "ingredients", and a list of instructions where each list item has "recipeInstructions"

The whole recipe is wrapped within a div with an itemscope and a declared itemtype of "Recipe".

### With Structured Data

```html
<div itemtype="http://schema.org/Event" itemscope>
	<h1 itemprop="name">Birthday Party</h1>
	<p class="date" itemprop="startDate" content="2017-09-10">September 10, 2017</p>
	<p itemprop="description">Emily is turning two years old!</p>
</div>
```

<br>What the computer sees: <!-- .element: class="fragment" data-fragment-index="0" -->
```html
Context:
Event

Title:
Birthday Party

Date:
2017-09-10

Description:
Emily is turning two years old!
```
<!-- .element: class="fragment" data-fragment-index="0" -->

### With Structured Data

```html
<div itemtype="http://schema.org/Event" itemscope>
	<h1 itemprop="name">Birthday Party</h1>
	<p class="date" itemprop="startDate" content="2017-08-13">August 13, 2017</p>
	<p itemprop="description">Steve is turning 30, come have a beer with him!</p>
</div>
```

<br>What the computer sees: <!-- .element: class="fragment" data-fragment-index="0" -->
```html
Title:
Birthday Party

Date:
2017-08-13

Description:
Steve is turning 30, come have a beer with him!
```
<!-- .element: class="fragment" data-fragment-index="0" -->
### Schema as RDFa

```html
<div vocab="http://schema.org/" typeof="Person">
	<h1 property="name">Homer Simpson</h1>
	<p property="address" typeof="PostalAddress">
		<span property="streetAddress">742 Evergreen Terrace</span>
		<span property="addressLocality">Springfield</span>
	</p>
	<p property="telephone" content="+15555558707">555-8707</p>
</div>
```

Note:

RDFa uses the Resource Description Framework we touched on earlier to mark up the product, similar to the way that Microdata did on the previous slide.
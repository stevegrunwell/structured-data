### Schema as Microdata

```html
<div itemscope itemtype="http://schema.org/Person">
	<h1 itemprop="name">Homer Simpson</h1>
	<p itemprop="homeLocation" itemtype="http://schema.org/PostalAddress" itemscope>
		<span itemprop="streetAddress">742 Evergreen Terrace</span>
		<span itemprop="addressLocality">Springfield</span>
	</p>
	<p itemprop="telephone" content="+15555558707">555-8707</p>
</div>
```

Note:

The Microdata approach draws heavily on what Microformats had set out to do. Now, we're specifically declaring that this is a product, and calling out things like the product image, its aggregated rating, product prices at different merchants.
### Schema as JSON-LD

```html
<script type="application/ld+json">
{
  "@context": "http://schema.org",
  "@type": "Person",
  "name": "Homer Simpson",
  "homeLocation": {
  	"@type": "PostalAddress",
  	"streetAddress": "742 Evergreen Terrace",
  	"addressLocality": "Springfield"
  },
  "telephone": "+15555558707"
}
</script>
```

Note:

Finally, we have JSON with Linked Data, or JSON-LD. This lets us create a JSON representation of the object and inject it into our page, without having to touch our existing product markup.
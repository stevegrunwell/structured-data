#### Microformats

```html
<div class="vevent">
	<h2 class="summary">WordCamp Grand Rapids</h2>
	<time datetime="2016-08-26" class="dtstart">August 26</time>
	<p class="description">...</p>
</div>
```

Note:

If we wanted to create an hCalendar — microformats' structure for a calendar event — for WordCamp Grand Rapids, it might look something like this.

The contents would be wrapped in a div with class "vevent", and we'd assign class names like "summary", "dtstart", "dtend" and "description" to the event name, dates, and description.

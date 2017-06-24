#### Microformats

```html
<div class="vevent">
	<h2 class="summary">WordCamp Kent</h2>
	<time datetime="2016-06-24" class="dtstart">June 24</time>
	&ndash;
	<time datetime="2017-06-25" class="dtend">25, 2016</time>
	<p class="description">...</p>
</div>
```

Note:

If we wanted to create an hCalendar — microformats' structure for a calendar event — for WordCamp Kent, it might look something like this.

The contents would be wrapped in a div with class "vevent", and we'd assign class names like "summary", "dtstart", "dtend" and "description" to the event name, dates, and description.

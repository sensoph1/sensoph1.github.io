---
layout: page
title: Contact
permalink: /contact/
---

<form action="http://formspree.io/sensoph@gmail.com" method="POST">
    <label for="name">Name:</label>
    <input type="text" name="name">
    
    <label for="email">Email:</label>
	<input type="email" name="_replyto">
	<br>
	<label for="body">Body:</label>
	<textarea name="body"></textarea>

	<br>
    <input type="hidden" name="_subject" value="New Contact Form submission!" />
    <input type="hidden" name="_next" value="//www.jeremybarkley.com/thanks/" />
    <input type="submit" value="Send">
</form>
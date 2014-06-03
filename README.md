#Text

For this assignment you will use the text document provided to you in this repository. You will be taking this plain text and marking it up into an **HTML** document. You should be able to accomplish this task with ease after reading the second chapter of the course material regarding semantic and structural markup.

All the naughty bits
---

The finished markup should contain the exact amount shown of these specific elements.

- 1 - `<h1></h1>`
- 1 - `<h2></h2>`
- 4 - `<p></p>`
- 1 - `<hr>`
- 3 - `<strong></strong>`
- 3 - `<em></em>`
- 1 - `<blockquote></blockquote>`
- 6 - `<code></code>`
- 12 - `<abbr></abbr>`

Where we're going..we don't need code
---

Most of these elements you have already seen, but most likely you haven't seen the `<code></code>` element. 

The purpose of the code element might seem obvious enough. `<code></code>` is used to markup a piece of computer code, such as **HTML**. The code tag when used with **HTML** isn't without its own obstacles. If we were to write the following piece of code:

	<code>
		<h1>Heading Level 1</h1>
	</code>

We might expect to see the plain text representation, but instead we see a styled `<h1></h1>` element. The answer to our problem is [HTML entities](http://en.wikipedia.org/wiki/List_of_XML_and_HTML_character_entity_references). To get our code to display the way we want (a string of text), we need to use the HTML entities to "strip out" the tags.

	<code>
		&lt;h1&gt;Heading Level 1&lt;h1&gt;
	</code>

This will give us our desired result. Be sure to read up on [HTML entities](http://en.wikipedia.org/wiki/List_of_XML_and_HTML_character_entity_references) and keep a list of them handy!

TL;DR
---

One last thing before you go, your requirements for this assignment are as follows.

- 1 HTML page named index.html
- Proper number of above mentioned tags
- Content is marked up correctly

If you are interested in **bonus marks** you could try doing the following.

- Insert 1 or more relevant images in your HTML page

You may now begin writing your **HTML**. Have fun!!
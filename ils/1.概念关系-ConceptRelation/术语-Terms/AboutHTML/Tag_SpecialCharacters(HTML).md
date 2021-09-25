In the example below, there are two paragraphs:
```mp
<p>In HTML, you define a paragraph using the <p> element.</p>

<p>In HTML, you define a paragraph using the &lt;p&gt; element.</p>
```
In the live output below, you can see that the first paragraph has gone wrong. The browser interprets the second instance of `<p>` as starting a new paragraph. The second paragraph looks fine because it has angle brackets with character references.

```mp
In HTML, you define a paragraph using the

element.
```
```mp
In HTML, you define a paragraph using the <p> element.
```

# Related Resource
- https://developer.mozilla.org/en-US/docs/Learn/HTML/Introduction_to_HTML/Getting_started#entity_references_including_special_characters_in_html
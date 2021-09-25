# dl_dt_dd
```md
<dl>
  <dt>soliloquy</dt>
  <dd>In drama, where a character speaks to themselves, representing their inner thoughts or feelings and in the process relaying them to the audience (but not to other characters.)</dd>
  <dt>monologue</dt>
  <dd>In drama, where a character speaks their thoughts out loud to share them with the audience and any other characters present.</dd>
  <dt>aside</dt>
  <dd>In drama, where a character shares a comment only with the audience for humorous or dramatic effect. This is usually a feeling, thought, or piece of additional background information.</dd>
</dl>
```
Note that it is permitted to have a single term with multiple descriptions
```md
<dl>
  <dt>aside</dt>
  <dd>In drama, where a character shares a comment only with the audience for humorous or dramatic effect. This is usually a feeling, thought, or piece of additional background information.</dd>
  <dd>In writing, a section of content that is related to the current topic, but doesn't fit directly into the main flow of content so is presented nearby (often in a box off to the side.)</dd>
</dl>
```
# i_em
- [html里面 i 和 em 标签有区别吗？百度知道 (baidu.com)](https://zhidao.baidu.com/question/483428232.html)
# picture_source_img
```md
<picture>
  <source media="(max-width: 799px)" 
  		  srcset="elva-480w-close-portrait.jpg">
  <source media="(min-width: 800px)" 
  		  srcset="elva-800w.jpg">
  <img src="elva-800w.jpg" 
  	   alt="Chris standing up holding his daughter Elva">
</picture>

```
- In all cases, you must provide an `<img>` element, with `src` and `alt`, right before `</picture>`, otherwise no images will appear. This provides a default case that will apply when none of the media conditions return true (you could actually remove the second `<source>` element in this example), and a fallback for browsers that don't support the `<picture>` element.
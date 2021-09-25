# About BiliBili iframe link
```md
invalid code:

<iframe 
src="//player.bilibili.com/player.html?aid=53851218&bvid=BV1j4411W7F7&cid=94198756&page=1" scrolling="no" border="0" frameborder="no" framespacing="0" allowfullscreen="true"> </iframe>
```

```md
Modified code:

<iframe src="https://player.bilibili.com/player.html?aid=420594320&cid=411557856&page=1" scrolling="no" border="0" frameborder="no" framespacing="0" allowfullscreen="true"> </iframe>
```

<head>
  <style> iframe { border: none } </style>
</head>
<body>
  <iframe src="https://developer.mozilla.org/en-US/docs/Glossary"
          width="100%" height="500" allowfullscreen sandbox border: none>
    <p>
      <a href="/en-US/docs/Glossary">
         Fallback link for browsers that don't support iframes
      </a>
    </p>
  </iframe>
</body>

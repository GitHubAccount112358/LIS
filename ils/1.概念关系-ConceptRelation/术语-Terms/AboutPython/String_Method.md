- [[0-String]] with [[0.English/1.Glossary/ComputerScience/Python/Method(Python)/title|.title()]]
	- Change each word to title case,where each word begins with a capital letter
- [[0-String]] with [[lower|.lower()]]
	- Change a [[0-String]] to all lowercase
- [[0-String]] with [[upper|.upper()]]
	- Change a [[0-String]] to all uppercase
---
- [[0-String]] with [[lstrip|.lstrip()]]
	- strip [[0-whitespace]] from the left side of a [[0-String]]
- [[0-String]] with [[rstrip|.rstrip()]] 
	- strip [[0-whitespace]] from the right side of a [[0-String]]
- [[0-String]] with [[strip|.strip()]]
	- strip [[0-whitespace]] from the left and right side of a [[0-String]] 

`To remove the whitespace from the string permanently, you have to
associate the stripped value with the variable name:`
```md
>>> favorite_language = 'python '
>>> favorite_language = favorite_language.rstrip()
>>> favorite_language
'python'
```
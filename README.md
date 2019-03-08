## Helpful Regex
Regex statements that have helped me over time.
* Markdown link fixer:
I have entered the wrong formatting for MD urls many times so I decided to fix it with a find+replace:

```
Find incorrect format: \(([^\]]*)\)\[([^\)]*)\]*
Replace with coorrect format: [$1]($2)
```

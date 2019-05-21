## Helpful Regex
Regex statements that have helped me over time.
* Markdown link fixer:

```
incorrect format: \(([^\]]*)\)\[([^\)]*)\]*
correct format: [$1]($2)
```

* If statements conditional (can be used with $1 while replacing)

```
if\((.*)\)
```

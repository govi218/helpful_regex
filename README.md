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

* Convert a boolean array with spaces to commas
```
get the array: \[(0|1) (.|\n)*\]
get just the elements:  (0|1)\n?

replace with commas: ,$1
```

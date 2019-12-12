# wurst-texttag-bars

Easy to use and performant texttag bars with unit locking and alpha

Usage example:

```
let bar = new TexttagBar(5, "o", color(255, 255, 0), color(0, 255, 255), 255)
	..lock(CreateUnit(playerFromIndex(0), 'hmpr', 0, 0, 0), vec3(-100, -100, 100))
	..setCountLeft(2, 20)
	..fadeOut(10, vec2(0.01, 0.01))
```

PRs welcome

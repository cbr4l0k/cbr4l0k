up:: [Pasta](Pasta.md)
tags:: #recipes

# Egg Dough Pasta

> [!HINT]+ Ingredients
	
```dataview
TABLE WITHOUT ID Name, Amount_Metric, Amount_Imperial
FROM csv("Extras/CSV/recipe_egg_dough_pasta.csv")
```


```dataviewjs
const myData = await dv.io.csv("Extras/CSV/recipe_egg_dough_pasta.csv");
dv.table(["Name", "Amount_Metric", "Amount_Imperial"], myData)
```

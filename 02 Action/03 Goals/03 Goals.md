---
cssClasses: cards
banner: "https://assets.hongkiat.com/uploads/minimalist-dekstop-wallpapers/4k/original/10.jpg"
---
⠀
# Goals Dashboard
```dataview
TABLE
	string("Why: " + why) AS "Why",
	string("Value: ") + value AS "Value",
	string("Deadline: ") + deadline as "Deadline",
	string("Complete: ") + complete as "Complete"
FROM "02 Action/03 Goals"
WHERE file.name != "03 Goals"
```
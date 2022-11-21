---
cssClasses: cards
banner: "https://i.redd.it/qmm6mqqdw3k41.jpg"
banner_x: 0.5
banner_y: 0.66466
---
⠀
# Projects Dashboard
```dataview
TABLE
	string("Target: " + target) AS "Target",
	string("Goal: ") + goal AS "Goal",
	string("Deadline: ") + deadline as "Deadline",
	string("Complete: ") + complete as "Complete"
FROM "02 Action/02 Projects"
WHERE file.name != "02 Projects"
```
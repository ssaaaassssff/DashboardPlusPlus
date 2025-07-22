---
cssclasses:
  - dashboard
banner: "![[home.jpg]]"
banner_x: 0.5
banner_y: 0
---
<div class="title" style="color:white">HOME</div>

# Family
- 👨‍👩‍👦 Objectives
	- [[Family Members]
	- [[Family Calendar]]
- 🌅Cinema
	- [[Directors]]
	- [[Movies]]
	- [[Favs]] 
 # meeee
- 🏡 Home
	- [[Cooking]]
	- [[Cleaning]]
	- [[inspo]] 
 - ✍️ Hobby
	- [[Crochetting]]
        - [[Diary]]
- 📚 Learning
	- [[School]]
	- [[languages]]

# Life
- 💼 Studies
	- [[English]]
	- [[Maths]]
	- [[Social studies]]
- 👥 Friends
	- [[Lizzy]]
	- [[Natasha]]
	- [[Dasha]]
	- [[Mary]]

# Vault Info
- 🗄️ Recent file updates
 `$=dv.list(dv.pages('').sort(f=>f.file.mtime.ts,"desc").limit(4).file.link)`
- 🔖 Tagged:  favorite 
 `$=dv.list(dv.pages('#favorite').sort(f=>f.file.name,"desc").limit(4).file.link)`
- 〽️ Stats
	-  File Count: `$=dv.pages().length`
	-  Personal recipes: `$=dv.pages('"Family/Recipes"').length`

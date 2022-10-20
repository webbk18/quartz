---
banner: "![[mark-stoop-JAUFHzqZPd0-unsplash.jpg]]"
banner_y: 0.32834
tag:: bestiary
bestiary:: bestiary
cssclass: dashboard
---
<div class="title">BESTIARY</div>

| [[Home]] | [Atlas](obsidian://open?file=CAL-Wiki&file=Atlas%2FAtlas) |[Characters](obsidian://open?file=CAL-Wiki&file=Characters%2FCharacters) | [Bestiary](obsidian://open?file=CAL-Wiki&file=Bestiary%2FBestiary) | [Books](obsidian://open?file=CAL-Wiki&file=Books%2FBooks)| [Lexicon](obsidian://open?file=CAL-Wiki&file=Lexicon%2FLexicon) | 
| -------- | -------|------- | ------------ | --------- | ----------- |

-----


# Artorian's Archives

```dataview
TABLE WITHOUT ID 
file.link AS "Creature",
definition AS "Defintion" 

WHERE category = "creature" AND series = "AA" OR 
category = "creature" AND series2 = "AA" OR 
category = "creature" AND series3 = "AA"

SORT field ASC

``` 

# Completionist Chronicles

```dataview
TABLE WITHOUT ID 
file.link AS "Creature",
definition AS "Defintion" 

WHERE category = "creature" AND series = "CC" OR 
category = "creature" AND series2 = "CC" OR 
category = "creature" AND series3 = "CC"

SORT field ASC

``` 

# Divine Dungeon


```dataview
TABLE WITHOUT ID 
file.link AS "Creature",
definition AS "Defintion" 

WHERE category = "creature" AND series = "DD" OR 
category = "creature" AND series2 = "DD" OR 
category = "creature" AND series3 = "DD"

SORT field ASC

``` 


---
banner: "![[agent-j-dO1i_fWbbcw-unsplash.jpg]]"
banner_y: 0.69167
cssclass: dashboard
---
<div class="title">LION'S LINEAGE</div>


| [Home](obsidian://open?file=CAL-Wiki&file=Home) |  [Atlas](obsidian://open?file=CAL-Wiki&file=Atlas%2FAtlas)  |[Characters](obsidian://open?file=CAL-Wiki&file=Characters%2FCharacters) | [Bestiary](obsidian://open?file=CAL-Wiki&file=Bestiary%2FBestiary) |[[Books]]| [Lexicon](obsidian://open?file=CAL-Wiki&file=Lexicon%2FLexicon) |
| -------- | -------|------- | ------------ | --------- | ----------- |


blurb here



# Books

```dataview
TABLE book-number AS "Book Number", publish-year AS "Year Published", narrator AS "Narrator"
WHERE category = "book" AND series = "LL"
sort book-number
```
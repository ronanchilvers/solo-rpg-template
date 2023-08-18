---
created: 2023-07-07 11:29
---
![[Tiny Dungeon 2e - Banner.jpg]]

# Adventure seed

![[cypher-system.png|right|200]]
> [!info] Add Adventure Seed
> Add the adventure seed here. Give a rough overview of the general plot - what's happening, what the characters are supposed to do, etc

# Setting
```dataview
List 
From -"_templates"
Where contains(file.tags, "setting")
Sort file.name
```

# Mechanics
```dataview
List
From -"_templates"
Where contains(file.tags, "mechanics") 
Sort file.name
```

# Characters
```dataview
List 
From -"_templates"
Where contains(file.tags, "character")
Sort file.name
```

# Scenes
```button
name Create new scene
type command
action Quickadd: New Scene
```
^button-new-scene
```dataview
List
From -"_templates"
Where contains(file.tags, "scene") 
Sort file.name desc
```

# Creatures
```dataview
List
From -"_templates"
Where contains(file.tags, "creature") 
Sort file.name
```

# Places
```dataview
List 
From -"_templates"
Where contains(file.tags, "place")
Sort file.name
```
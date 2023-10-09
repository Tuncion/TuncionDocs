---
description: 🔧 Available since Version 1.0.1!
---

# addRank

&#x20;**📢 Event occurs when a player's rank is added**

```lua
RegisterNetEvent("tuncion_xp:log:addRank")
AddEventHandler("tuncion_xp:log:addRank", function(source, data)
    -- Do your magic here 💫
end)
```

### Returns

1. Source <mark style="color:blue;">(INT)</mark> <mark style="color:orange;">-> PlayerID</mark>
2. Data <mark style="color:blue;">(OBJECT)</mark> <mark style="color:orange;">-> true or false</mark>
   1. rank <mark style="color:blue;">(INT)</mark> <mark style="color:orange;">-> Players current rank</mark>
   2. totalXP <mark style="color:blue;">(INT)</mark> <mark style="color:orange;">-> Players current total XP</mark>


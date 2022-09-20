# R-L-stashes
R-L-stashes For QB-Core
Configurable Stashes for QBCore with options of locking to job, gang or CitizenID. Can be used for donator MLOs or businesses that requires stashes

# New Features:
QBCore Drawtext

Stash opening sound

Public Stashes

qb-target option

# Example Config

```
    ["donatorMansion1"] = {
        stashName = "donatorMansion1",
        canAnyoneOpen = false,
        coords = vector3(-96.17, 817.29, 235.72),
        requirecid = true,
        jobrequired = false,
        gangrequired = false,
        gang = "",
        job = "",
        cid = {"ENL22736", "LUS73247"},  
        stashSize = 1250000,
        stashSlots = 125, 
    },
    ["liquorBusiness"] = {
        stashName = "liquorBusiness",
        canAnyoneOpen = false,
        coords = vector3(0.05, -1818.36, 29.54),
        requirecid = false,
        jobrequired = true,
        gangrequired = false,
        gang = "",
        job = "liquor",
        cid = {},  
        stashSize = 1250000,
        stashSlots = 125, 
    },
    ["ballasExtraStash"] = {
        stashName = "ballasExtraStash",
        canAnyoneOpen = false,
        coords = vector3(-1730.5, 358.6, 88.73), 
        requirecid = true,
        jobrequired = false,
        gangrequired = true,
        gang = "ballas",
        job = "",
        cid = {},  
        stashSize = 1250000,
        stashSlots = 125, 
    },
    ["publicstash"] = {
        stashName = "publicstash",
        canAnyoneOpen = true,
        coords = vector3(-1730.5, 358.6, 88.73), 
        requirecid = false,
        jobrequired = false,
        gangrequired = false,
        gang = "",
        job = "",
        cid = {},  
        stashSize = 1250000,
        stashSlots = 125, 
    },
    
```

Issues? Make an issue on the repo.
    
# For More Info Join here https://discord.gg/BKZMnrR2q2

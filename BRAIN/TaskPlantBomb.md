---
ns: BRAIN
---
## TASK_PLANT_BOMB

```c
// 0x965FEC691D55E9BF 0x33457535
void TASK_PLANT_BOMB(Ped ped, float x, float y, float z, float heading);
```

```
This should be used after GIVE_WEAPON_TO_PED, with a weapon like a bomb.
Example:
local myPed = PlayerPedId()
local loc = GetOffsetFromEntityInWorldCoords(myPed, 0.0, 0.0, 0.0)
local heading = GetEntityHeading(myPed)
GiveWeaponToPed(myPed, GetHashKey("WEAPON_STICKYBOMB"), 1000, 1, 1)
TaskPlantBomb(myPed, loc.x, loc.y, loc.z, heading)
```

## Parameters
* **ped**: 
* **x**: 
* **y**: 
* **z**: 
* **heading**: 


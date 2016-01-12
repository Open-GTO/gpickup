# gpickup
Global pickup system

# Functions
```Pawn
GPickup_Create(model, Float:x, Float:y, Float:z, world = -1,
               respawn_time = GPICKUP_RESPAWN_TIME, bool:is_showed = true);
GPickup_Remove(id);
GPickup_IsExist(id);
GPickup_IsHidden(id);
GPickup_GetTime(id);
GPickup_SetTime(id, time);
GPickup_GetRespawnTime(id);
GPickup_SetRespawnTime(id, time);
GPickup_GetID(id);
GPickup_SetID(id, pickupid);
GPickup_GetModel(id);
GPickup_SetModel(id, model);
GPickup_GetWorld(id);
GPickup_SetWorld(id, world);
GPickup_GetPos(id, &Float:x, &Float:y, &Float:z);
GPickup_SetPos(id, Float:x, Float:y, Float:z);
```

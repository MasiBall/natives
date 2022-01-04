---
ns: VEHICLE
---
## GET_VEHICLE_NUMBER_PLATE_TEXT

```c
// 0x7CE1CCB9B293020E 0xE8522D58
char* GET_VEHICLE_NUMBER_PLATE_TEXT(Vehicle vehicle);
```

## Parameters
* **vehicle**: The target vehicle

## Return value
Returns the license plate text from a vehicle. 8 chars maximum.

## Examples
```lua
local playerPed = PlayerPedId()
local vehicle = GetVehiclePedIsIn(playerPed)
local vehiclePlate = GetVehicleNumberPlateText(vehicle)
print(vehiclePlate) --prints license plate to console
```

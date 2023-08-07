# qb-apartments
Qb Apartments With Target and Rent


this is now  made for lev_apartment shell so  follow his istall steps then with the offsets add this 
        obj[2].fridge = json.decode('{"x": -0.36, "y": -3.17699, "z": 0.960894, "h": 181.75}')
        bellow  the  stash
# qb-apartments
Apartments System With Rent for QB-Core Framework :office:

## to change the lang 
change en to the lang you use do not switch it in the fxmanifest it breaks for no reason

# License

    QBCore Framework
    Copyright (C) 2021 Joshua Eger

    This program is free software: you can redistribute it and/or modify
    it under the terms of the GNU General Public License as published by
    the Free Software Foundation, either version 3 of the License, or
    (at your option) any later version.

    This program is distributed in the hope that it will be useful,
    but WITHOUT ANY WARRANTY; without even the implied warranty of
    MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
    GNU General Public License for more details.

    You should have received a copy of the GNU General Public License
    along with this program.  If not, see <https://www.gnu.org/licenses/>

## Origial Script
Just added Target compatibility https://github.com/XxJxsperxX/qb-apartments

## Installation
### Manual
1.  Backup existing QB-Apartments
2.  Delete existing QB-Apartments
3.  Replace with this one.
4.  Add More Apartments [Optional] & Change/Add Pricing
5.  Change banking export in Server/Main.Lua to your Current Banking for Bank Account Logs.
6.  Change timer to your liking Line 630 in Client/Main.Lua [Set to withdrawl from player's account every hour.]

## Configuration Example/Preview
```
Apartments = {}
Apartments.Starting = true
Apartments.SpawnOffset = 30

-- **** IMPORTANT ****
-- UseTarget should only be set to true when using qb-target
Apartments.UseTarget = true

Apartments.Locations = {
    ["apartment1"] = {
        name = "apartment1",
        label = "South Rockford Drive",
        coords = {
            enter = vector4(-667.02, -1105.24, 14.63, 242.32),
        },
        polyzoneBoxData = {
            heading = 245,
            minZ = 13.5,
            maxZ = 16.0,
            debug = false,
            length = 1,
            width = 3,
            distance = 2.0,
            created = false
        },
        price = 600,
    },
    ["apartment2"] = {
        name = "apartment2",
        label = "Morningwood Blvd",
        coords = {
            enter = vector4(-1288.52, -430.51, 35.15, 124.81),
        },
        polyzoneBoxData = {
            heading = 124,
            minZ = 34.0,
            maxZ = 37.0,
            debug = false,
            length = 1,
            width = 3,
            distance = 2.0,
            created = false
        },
        price = 600,
    },
    ["apartment3"] = {
        name = "apartment3",
        label = "Integrity Way",
        coords = {
            enter = vector4(280.66, -652.12, 42.02, 342.31),
        },
        polyzoneBoxData = {
            heading = 250,
            minZ = 40,
            maxZ = 43.5,
            debug = false,
            length = 1,
            width = 1,
            distance = 2.0,
            created = false
        },
        price = 600,
    },
    ["apartment4"] = {
        name = "apartment4",
        label = "Tinsel Towers",
        coords = {
            enter = vector4(-621.016, 46.677, 43.591, 179.36),
        },
        polyzoneBoxData = {
            heading = 180,
            minZ = 41.0,
            maxZ = 45.5,
            debug = false,
            length = 1,
            width = 2,
            distance = 2.0,
            created = false
        },
        price = 600,
    },
    ["apartment5"] = {
        name = "apartment5",
        label = "Fantastic Plaza",
        coords = {
            enter = vector4(291.517, -1078.674, 29.405, 270.75),
        },
        polyzoneBoxData = {
            heading = 270,
            minZ = 28.5,
            maxZ = 31.0,
            debug = false,
            length = 1,
            width = 2,
            distance = 2.0,
            created = false
        },
        price = 600,
    },
}


```

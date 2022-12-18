# qb-apartments
Apartments System With Rent for QB-Core Framework :office:

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

## Original Script
https://github.com/XxJxsperxX/qb-apartments

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
Apartments.Locations = {
    ["apartment1"] = {
        name = "apartment1",
        label = "Tug Street",
        coords = {
            enter = vector4(-969.78, -1431.33, 7.68, 293.84)
        },
        polyzoneBoxData = {
            heading = 116.78,
            minZ = 30,
            maxZ = 33.5,
            debug = true,
            length = 1,
            width = 1,
            distance = 2.0,
            created = false
        },
        price = 600,
    },
    ["apartment2"] = {
        name = "apartment2",
        label = "N. Archer Ave",
        coords = {
            enter = vector4(-71.06, 142.35, 81.67, 212.8)
        },
        polyzoneBoxData = {
            heading = 116.78,
            minZ = 30,
            maxZ = 33.5,
            debug = true,
            length = 1,
            width = 1,
            distance = 2.0,
            created = false
        },
        price = 1200,
    },
}

```

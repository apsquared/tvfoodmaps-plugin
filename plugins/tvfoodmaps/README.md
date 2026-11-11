# TVFoodMaps plugin

[TVFoodMaps](https://www.tvfoodmaps.com) maps restaurants featured on food television. This plugin connects your assistant to TVFoodMaps' free, read-only MCP server and adds one skill for finding TV food stops.

## Install

```
/plugin install tvfoodmaps --marketplace apsquared/tvfoodmaps-plugin
```

## What it does

| Tool | What it returns |
| --- | --- |
| `find_tv_restaurants` | Up to 8 TV-featured restaurants in a city and state, optionally by show or cuisine |
| `plan_tv_food_stops` | A shortlist of up to 6 distinct TV food stops for a city |
| `explain_tv_restaurant` | One restaurant's recorded shows, episodes, air dates and appearance descriptions |
| `discover_food_shows` | Food shows matching the start of a name, with their show codes |

Every tool is read-only. No sign-in is needed.

## Data

The server receives only the lookup inputs the tools need: a city, state, show code, cuisine or TVFoodMaps restaurant URL. It never sees your conversation, your TVFoodMaps account or saved lists. Links back to TVFoodMaps carry referral parameters. See the [privacy policy](https://www.tvfoodmaps.com/privacy-policy).

TVFoodMaps does not provide live opening hours, menus, reservations, dietary information or driving routes. It is not affiliated with the shows, networks, hosts or restaurants in its catalog.

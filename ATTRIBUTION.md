# juju-data: sources and licences

These packs hold openly licensed source data only, cut by region and kind so a phone downloads what one film needs. They contain no
code and no keys, and nothing written by Juju. Each `.tar.zst` unpacks into a folder tree (`maps/...`); `index.json` lists every pack
with its sha256.

| Data | Where in the packs | Licence | Source |
|---|---|---|---|
| Coastlines, land, lakes, countries | `maps/data/timesets/natural-earth/`, `maps/data/ne_50m_admin_0_countries.geojson` | Public domain | Natural Earth, naturalearthdata.com |
| Heights (terrain tiles) | `maps/cache/terrarium/`, `maps/data/timesets/relief/` | Open, mixed: ETOPO1, GMTED2010, SRTM and national sets | Terrain Tiles (Mapzen) on the AWS Open Data registry; see its registry page for each source's terms |
| Output per person, people | `maps/data/timesets/maddison/mpd2023.xlsx` | CC BY 4.0 | Maddison Project Database 2023, Bolt and van Zanden (2024), Groningen Growth and Development Centre. All original papers must be cited when the data is shown in any graphical form |
| Population by country | `maps/data/timesets/owid-population.csv` | CC BY 4.0 | HYDE 3.3, Gapminder and UN WPP 2024, as published by Our World in Data |
| Energy, CO2, coffee, oil | `maps/data/timesets/owid/energy.csv`, `co2.csv`, `coffee-bean-production.csv`, `oil-production-by-country.csv` (only these four) | CC BY 4.0 | Our World in Data (from the Energy Institute and Ember, the Global Carbon Project, FAO) |
| Gold reserves | `maps/data/timesets/worldbank/` | CC BY 4.0 | World Bank, World Development Indicators FI.RES.TOTL.CD and FI.RES.XGLD.CD |
| Borders of polities through time | `maps/data/timesets/cliopatria/cliopatria.geojson` | CC BY 4.0 | Cliopatria, Seshat Global History Databank |

Films that use this data credit each source on screen and in their description.

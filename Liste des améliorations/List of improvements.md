# Styling improvements over OsmAnd's Topo

## In short

What has changed:

- Trails and paths / track in a simplified way.
- Difficulty of trails
- Visibility of the trails
- Bridges
- Useful / interesting POIs during the hike are surrounded by a white circle to highlight them
- POIs useful when passing through a hamlets / village / town, are pre-activated and surrounded by a colored circle depending on the category
- Contour lines
- Color of land and water occupations
- Symbols of land use (Shader)
- Cols and mountain pass
- Information panels
- Towns / villages / hamlets
- Text size
- Natural reserves
- Ridge lines, gorges, corridors, valleys, mountain names
- Antennas, towers (buildings), wind turbines icons
- Opaque color for routes based on OSMC symbols

### We have added additional settings:

- "Hide" settings:
  - Symbols of nature reserves
  - Color of nature reserves
  - Visibility of the trails
  - POI pre-activated
  - Land use symbols

- Contour line settings
  - Additional density
  - Extra thickness

### We have disabled:
- the quality of the surfaces (Smoothness) 




## Details:

### "Hide" settings:
- "NR" symbols of nature reserves (shader nr2)
- Color of nature reserves
- Trail visibility (`trail_visibility = *`)
- Symbols of land use (shader)
- POI pre-activated

## POI pre-activated:
- [x] ** Violet **: food (mini-market, supermarket, butcher, bakery, etc.)
- [x] ** Orange **: leisure activities (restaurant, bar, café, etc.)
- [x] ** Blue **: utility (post office, police, parking)
- [x] ** Gray **: transport (bus station, train, cash machine / bank and cemetery)
- [x] ** Red **: health (doctor, hospital, vet, dentist, etc.)
- [x] ** Green **: pharmacy
- [x] ** Brown **: hygiene (public toilet and shower)
- [x] ** White **: during the hike (refuges, shelters, cabins, lodges, hotels, viewpoint, information panels, etc.)

## Land use :
- Color changed (wood, meadow, brush, pasture, etc.)
- Darker rocky area image (shader)
- Darker scree image (shader)
- Lighter building color
- Color of the surfaces of towns / villages / hamlets lighter
- Symbols (shader)

## Contour :
- Line thickness reduced when zoomed 11-12-13
- Corrected color for light brown
- Color added (orange and black)
- Additional “H” adjustment for density (IGN France type)
- Additional "H" adjustment for the thickness (type IGN France)
- Removal of unnecessary small lines

## Text:
- Larger and thinner brown text as well as a slightly opaque white halo for mountains, ridges and corridors
- Bigger and thinner green text as well as a slightly opaque white halo for valleys and gorges
- Text size of villages, hamlets, localities adapted according to the zoom
- Text size of summits, passes, mountain pass adapted according to the zoom
- Text size of the contour lines adapted according to the zoom
- Text of the scree
- Text of the main, secondary, tertiary roads smaller and adapted according to the zoom
- Text bus / train stops from a certain zoom

## Icon:
- Tower
- Radio antenna
- Wind turbine
- Electric transformer
- Picnic table
- Car park
- POI (colors depending on the category)

## Itinerary :
- Opaque color for routes based on OSMC symbols

# Display order according to zoom:
- **Zoom 7** - 100 km
  - Regions
- **Zoom 10** - 10 km
  - Villages
- **Zoom 11** - 5 km
  - Main peaks icon
- **Zoom 12** - 2 km
  - Very thin marked trails (footpath / track / tertiary road)
  - Hamlets / localities
  - Icon summit, pass and mountain_pass + Altitude
  - Text valleys and ridges
- **Zoom 13** - 1 km
  - Trails (footpath / track / tertiary road), view of hamlets / localities
  - visibility of the trails
  - difficulty of the trails
  - Text level curve of 100 m on the curve
  - Shelters / shelters icon
  - Text + summit altitudes
- **Zoom 14** - 500 m
  - Text of refuges
  - Land use icons
  - Text level curve 100 and 50 m horizontally
  - Wind icon
  - Text of the scree
- **Zoom 15** - 200 m
  - Text level curve 100 and 50 m horizontally
  - Text of mountain_pass + altitude
  - Icon of mini markets, bar / restaurant, etc.
  - Land use icon
- **Zoom 16** - 200 m
  - Text contour line 100, 50, 20 and 10 m on the curve in bold
  - Bigger wind icon
  - Corridor text (mountain)
  - Text of sources
  - Altitudes information panels
  - Icons surrounded by a white circle for POIs spotting / interesting during the hike (ex: ruins, caves, mines, antennas, etc.)
- **Zoom 17** - 100 m
  - Contour line in solid line (better visibility in rocky areas)
  - Pass text + altitude
  - Text of information panels + altitudes
- **Zoom 18** - 50 m
  - Thicker contour lines
  - Realistic electricity pylons icon
  - Text bus / train stop
  - Disabling the visibility of the trails (only the difficulty is visible T2 / T3 / T4 / T5 / T6)
- **Zoom 19** - 20 m
  - Activation of certain texts in towns / villages / hamlets

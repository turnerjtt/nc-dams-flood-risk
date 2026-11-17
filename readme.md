# North Carolina Dams & Flood Risk

**Live map:** https://turnerjtt.github.io/nc-dams-flood-risk/

## Introduction
North Carolina has more than 3,600 dams, and nearly half are classified as **high hazard**, meaning a failure would likely cost lives. After Hurricane Helene flooded Western North Carolina in 2024, dam safety became a statewide concern. This interactive web map asks a simple question: **where do high-hazard dams sit in counties that already face high flood risk?**

## Major Functions
- **Point layer:** 3,680 dams shown with a Font Awesome water icon, colored and sized by hazard potential (High, Significant, Low), with high-hazard dams drawn on top.
- **Choropleth layer:** NC counties shaded by FEMA's inland flood risk score (0–100) in five equal-interval classes.
- **Interactivity:** click a dam for its name, river, condition, year built, and height; click a county for its flood score and dam count. Counties highlight on hover, and a layer control toggles each dam hazard class on or off.
- **Map elements:** title, legend, scale bar, and source attribution.

## Libraries
Leaflet, leaflet-ajax, chroma.js, jQuery, Font Awesome, Google Fonts (Titillium Web), and the Esri Light Gray Canvas basemap.

## Data Sources
- [USACE National Inventory of Dams](https://nid.sec.usace.army.mil/)
- [FEMA National Risk Index](https://hazards.fema.gov/nri/) (county inland flooding risk score)

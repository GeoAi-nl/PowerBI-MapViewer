# PowerBI-MapViewer

<a name="top" />

## Overview

The MapViewer Visual from [GeoAI](https://www.geoai.nl) brings the power of a highly-configurable map to your Microsoft PowerBI report. This feature-rich Visual lets you show locations in your report from Longitude and Latitude fields in your data table. Choose from a range of basemaps to provide context. Additionally, Web Mapping Service (WMS) layers can be added to enrich your map with extra information. You can create a library of your favourite WMS endpoints and your layer styling and map extent is saved within the Power BI report.

🪛🔨 The MapViewer Visual is in active development and often updated with tweaks, bug fixes, and new features.   
✔️ Be sure to update to the latest release for the most stable version.

<a name="contents" />

## Sections

[Features - Free version](#section-features-free)

[Coming soon](#section-coming-soon)

[Getting started](#section-getting-started)

<a name="section-features-free" />

## Features - Free version

- Add point data from your report using Latitude and Longitude coordinates ➡️ [show me](#feature-add-points)
- Select data using either the map or in other visuals in your report  ➡️ [show me](#feature-select)
- Zoom to your selected data ➡️ [show me](#feature-zoom-selection)
- Filter the points using a slicer ➡️ [show me](#feature-filter)
- Style the points by choosing fill colour and opacity, stroke colour, and size ➡️ [show me](#feature-style-points)
- Choose from a range of basemaps to suit your map style ➡️ [show me](#feature-basemap)
- Add up to 4 WM(T)S (Web Mapping (Tile) Service) layers ➡️ [show me](#feature-wms)
- Save your favourite WM(T)S endpoints ➡️ [show me](#feature-favourite-endpoints)
- View the Legend and Abstract of WMS layers ➡️ [show me](#feature-legend-abstract)
- Save your map configuration to your Power BI report ➡️ [show me](#feature-save)

<a name="section-coming-soon" />

## Coming soon
- Attribute-based styling for points
    - Graduated colour
    - Size
 
[Back to top](#top)

<a name="section-getting-started" />

## Getting started

<a name="section-installation" />

### Installation
- Ensure your Power BI report is in Edit mode
- In the *Visualizations* tab, click the <kbd>...</kbd> (Get more Visuals) button at the bottom of the *Build Visual* panel
- Choose *Import a visual from a file...*
- Read the warning and, if you wish to proceed, choose <img src="https://github.com/GeoAi-nl/PowerBI-MapViewer/assets/145410383/5ea93138-6fc5-48a9-b150-1051cebf81a5" width="55" />
- Browse to the MapViewerv1.x.xxx.pbiviz file and click <kbd>Open</kbd>
- The MapViewer icon <img src="https://github.com/GeoAi-nl/PowerBI-MapViewer/assets/145410383/993799fb-2636-429b-8c07-df68ab2281ca" width="15" />
 will appear below the panel of available Visuals

![mapviewer - installation](https://github.com/GeoAi-nl/PowerBI-MapViewer/assets/145410383/59724021-6f93-4146-adb8-d5381478add9)

[Back to top](#top)

<a name="section-quick-start" />

### Quick start

<a name="feature-add-points" />

#### Add point data from your report using Latitude and Longitude coordinates

![mapviewer - add points](https://github.com/GeoAi-nl/PowerBI-MapViewer/assets/145410383/1f816b2a-82d9-4a00-b879-1fbdc564bf08)

[Back to top](#top)

<a name="feature-select" />

#### Select data using either the map or in other visuals in your report  
- Use <kbd>Shift</kbd> + Click to select multiple data points

![mapviewer - select points](https://github.com/GeoAi-nl/PowerBI-MapViewer/assets/145410383/9251afaa-cf94-43cc-b25b-6f961675836d)

[Back to top](#top)

<a name="feature-zoom-selection" />

#### Zoom to your selection

![mapviewer - zoom selection](https://github.com/GeoAi-nl/PowerBI-MapViewer/assets/145410383/a8803acb-ffae-4469-8a1c-7b2f71a88abd)

[Back to top](#top)

<a name="feature-filter" />

#### Filter the points using a slicer
- Choose whether the map zooms to the sliced features by toggling the zoom lock <img src="https://github.com/GeoAi-nl/PowerBI-MapViewer/assets/145410383/3a27f8d7-38eb-4861-993e-caad7e3d1ef3" width="15" />

![mapviewer - filter](https://github.com/GeoAi-nl/PowerBI-MapViewer/assets/145410383/9311d6ee-3034-4ce0-b817-dee156228dbd)

[Back to top](#top)

<a name="feature-style-points" />

#### Style the points by choosing fill colour and opacity, stroke colour, and size
- Right-click the layer name to bring up the context menu with extra options
- Click the Style Layer button to show the styling options
  
![mapviewer - style points](https://github.com/GeoAi-nl/PowerBI-MapViewer/assets/145410383/1a3c671b-b02d-4713-9bdb-98a52fc76702)

[Back to top](#top)

<a name="feature-basemap" />

### Choose from a range of basemaps to suit your map style
- You can even choose not to show a basemap

![mapviewer - basemap](https://github.com/GeoAi-nl/PowerBI-MapViewer/assets/145410383/40f49a9e-1746-44d4-a6cd-ffa0935fdca5)

[Back to top](#top)

<a name="feature-wms" />

### Add up to 4 WM(T)S (Web Mapping (Tile) Service) layers
- Layers can be ordered by dragging and dropping them in the Layers Panel
- Adjust the opacity of the WM(T)S layers to further enrich your map design

![mapviewer - wms](https://github.com/GeoAi-nl/PowerBI-MapViewer/assets/145410383/a9fb3ea2-b58f-423a-bb88-d1fd7df5a805)

[Back to top](#top)

<a name="feature-favourite-endpoints" />

### Save your favourite WM(T)S endpoints
- Favourite endpoints can be re-ordered by dragging and dropping
- Right-Click to remove an endpoint from the favourites list

![mapviewer - favourite endpoints](https://github.com/GeoAi-nl/PowerBI-MapViewer/assets/145410383/20555da5-9138-41ae-af2f-5e806b40ffe8)

[Back to top](#top)

<a name="feature-legend-abstract" />

### View the Legend and Abstract of WMS layers
- The availability of the legend and/ or abstract depends on the service provider
- You will be notified if there is no legend or abstract information available for the layer

![mapviewer - legend](https://github.com/GeoAi-nl/PowerBI-MapViewer/assets/145410383/31fd3afc-1a42-44b1-8cd6-f59f33fea164)

[Back to top](#top)

<a name="feature-save" />

### Save your map configuration to your Power BI report
- Saving your map means users of your report will see it exactly how you intend
- Almost everything you can configure in the MapViewer Visual will be saved
    - Including the basemap, map extent, layers, layer opacity, point styling, favourite endpoints
- ⚠️ Don't forget to save the Power BI report after saving the map settings ⚠️

![mapviewer - save](https://github.com/GeoAi-nl/PowerBI-MapViewer/assets/145410383/bd343182-2fea-40c9-92d7-1e882b5ba9dd)

[Back to top](#top)

### Help to improve the MapViewer Visual

The MapViewer Visual is in active development and often updated with tweaks, bug fixes, and new features. If you experience a bug or an unexpected behaviour, please let us know 

<!---
#### Features - Pro version
- Unlimited WMS layers
- Add features using a WKT (Well-Known Text) column in your data
- Add layers from WFS (Web Feature Services)
- View feature attributes
- Query features using filters and selections across your report
-->

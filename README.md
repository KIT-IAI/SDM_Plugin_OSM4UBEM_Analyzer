# OSM4UBEM Analyzer
The **OSM4UBEM Analyzer** is a plugin for **KITModelViewer** designed to assess the fitness of OpenStreetMap (OSM) building data for Urban Building Energy Modeling (UBEM).
The tool analyzes whether available OSM building information is not only present and correctly represented, but also usable for the generation of CityGML building models and subsequent thermal simulation workflows.

<img width="1821" height="837" alt="image" src="https://github.com/user-attachments/assets/d709cc1a-f910-4a0b-8bdc-99ba0b9f3428" />


Based on a hierarchical rule-based assessment, buildings are classified into five usability levels: Optimal, Satisfactory, Acceptable, Limited, and Unusable. The results can be explored both quantitatively and spatially within KITModelViewer, while detailed checks help identify missing or unsuitable information for individual buildings.

## User Interface
The user interface is based on [wxWidgets](https://www.wxwidgets.org/) and was made with [wxFormBuilder](https://github.com/wxFormBuilder/wxFormBuilder).

## Dependencies

### Use of vcpkg:

|Package Name         |Install Command                            |
|:---                 |:---                                       |
|wxwidgets            |vcpkg install wxwidgets triplet=x64-windows|
|fmt                  |vcpkg install fmt triplet=x64-windows      |
|geographiclib 	      |vcpkg install geographiclib triplet=x64-windows|

## How to cite

```bibtex
@software{SDM_Plugin_OSM4UBEM_Analyzer,
	title        = {SDM\_Plugin\_OSM4UBEM\_Analyzer},
	author       = {{Fernanda Lourenzi}},
	url          = {https://github.com/KIT-IAI/SDM_Plugin_OSM4UBEM_Analyzer},
	date         = {2026}
}
```

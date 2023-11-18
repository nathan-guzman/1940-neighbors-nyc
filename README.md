# 1940-neighbors-nyc

1940Neighbors.nyc is a project that places person-level data from the 1940 US Census onto present day maps of NYC buildings. 

## Table of Contents

- [Usage](#usage)
- [License](#license)
- [Acknowledgements](#acknowledgements)

## Usage

"Find Your Block" page:
- Browse posts with available blocks.
- Each individual post is based on US Census Enumeration Districts, so posts may contain one or multiple city blocks.
- Posts are organized by date posted, with the most recently posted blocks at the top of the page.
- Each post includes the date posted, neighborhood, NYC borough, and the streets surrounding the block(s) in the webmap.
- Select available blocks to view interactive web maps by clicking the neighborhood text, image, or "View Map" button.

Interactive Map Pages:
- The neighborhood, NYC borough, streets surrounding the block(s), and Census Enumeration district(s) are listed above the interactive map.
- Each interactive map includes the labeled streets of the entire neighborhood surrounding the block(s), colored in dark green, as well as shapes representing all present-day buildings on the block(s).
- Each building on the map is color coded. Gray represents buildings where US Census data was not found or could not be mapped. Light green and turquoise represent buildings where US Census data was mapped based on the address, but with one distinguishing factor: light green buildings were constructed before 1940, meaning that the present-day building is the same building that was at that address in 1940, whereas turquoise buildings were constructed after 1940, meaning a different building was at that address in 1940.
- Drag map to reposition what is displayed. Click the plus or minus button in the top left to zoom in or zoom out. Toggle layers in the top right to remove or add buildings and streets.
- Click on light green or turquoise buildings to view the people who lived in that building (if light green) or at that address (if turquoise) in 1940. Each popup includes the address, the year the present-day building was constructed, and all people residing at that address based on the 1940 Census.
- People in the popups are separated into family units based on information from the Census about which individual is the "Head" of the household and thus owns, or pays rent, for their family unit. Separation into family units does not necessarily represent relation or whether individuals resided in separate quarters. Please note that people were separated into family units in an automated fashion, so slight inaccuracies may be present.
- Each individual is listed in the following format, based on information present in the 1940 Census: "Full Name (Relationship to Head of Household, Age, Place of Birth, Occupation)". Specific information omitted for individuals means this data was not found in the Census.

Request Your Block Page:
- Complete this simple form to request a NYC block to be made into an interactive map.
- Include the NYC Borough, neighborhood name, and cross streets surrounding the block.
- Optionally, provide a sentence or two about why you are requesting the block and your email address in case you need to be contacted for clarification.


## License

- The content, concept, and overall design of 1940Neighbors.nyc are protected under copyright. This content is provided for personal, non-commercial use only. Except with our express prior written permission, no part of our website may be copied, reproduced, aggregated, republished, uploaded, posted, publicly displayed, transmitted, or distributed in any form or for any purpose whatsoever.
- The source code generated by QGIS2WEB and the HTML template used in this project are subject to their respective licenses (GPL v2.0 for QGIS2WEB and Creative Commons Attribution 3.0 Unported for the HTML template).

## Acknowledgements

- NYC GIS Data used for web maps comes from three data bases found on NYC Open Data portal: [NYC Address Points](https://data.cityofnewyork.us/City-Government/NYC-Address-Points/g6pj-hd8k), [NYC Street Centerline (CSCL)](https://data.cityofnewyork.us/City-Government/NYC-Street-Centerline-CSCL-/exjm-f27b), [Building Footprints](https://data.cityofnewyork.us/Housing-Development/Building-Footprints/nqwf-w8eh).
- GIS Data manipulated and maps created using [QGIS](https://qgis.org/en/site/). Web maps generated using [QGIS2WEB](https://github.com/tomchadwin/qgis2web).
- HTML Template: This website was created by modifying the [Massively HTML template](https://html5up.net/massively) designed by HTML5 UP.
- The background image of the website is from the [WPA Federal Writers Project archive](https://nycma.lunaimaging.com/luna/servlet/RECORDSPHOTOUNITARC~25~25): "Henry Street (Manhattan) between Jefferson and Monroe Streets", NYC Municipal Archives Collection, Courtesy of the Municipal Archives, City of New York.
- Data for the interactive map is from the 1940 US Census, accessed via [Ancestry.com](https://www.ancestry.com/search/collections/2442/). 
- Census Enumeration Districts for NYC Blocks identified using the [Unified 1940 Census ED Finder](https://stevemorse.org/census/unified.html?year=1940) on stevemorse.org.
- Determination of neighborhood boundaries are made based on [locality.nyc](https://locality.nyc/)

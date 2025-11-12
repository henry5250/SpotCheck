# SpotCheck MetaData

## Data Summary
The dataset, downloaded from the iNaturalist API, consists of images of two species: Asian Lady Beetle (Harmonia axyridis) and Native Ladybug (Coccinella novemnotata). iNaturalist is a global online social network and citizen science project for recording and sharing observations of biodiversity, including the two species of interest for this project. Users can upload photos of organisms and they are tagged by species. The dataset consists of 120 .jpg files of each species for a total of 240 images. The image files were scraped, classified by species to be sorted in folders, and named by a primary key integer as a four number code. They are stored as folder:species_name/ file:####.jpg (e.g. Coccinella_novemnotata / 0120.jpg). The individual file, for example, could be “0023.jpg”

## Provenance/License
The dataset is held at the iNaturalist API citizen science observations repository. As it is a citizen science project, there are many separate contributors to the project, and many different origins of the image data from these individuals.
iNaturalist has various types of data to offer, including observation data, images, and sounds. The default license that governs all that information is the CC BY-NC (Creative Commons: Attribution-NonCommercial). This allows the content to be utilized by others as long as they properly attribute it to iNaturalist and use it for non-commercial purposes. This license additionally allows the observation data to be exported to data partners and used in most scientific publications.

## Ethical Statement
The only ethical concern would be if the user who created the image had not honestly attributed image credit an uploaded without the photographer's consent, but this is highly unlikely and moderated by iNaturalist.

## Data Dictionary
The data is stored into two zip files labeled Harmonia_axyridis.zip and Coccinella_novemtata.zip. When downloaded and opened, two corresponding folders are opened up, labeled Harmonia_axyridis and Coccinella_novemtata. Within each of those folders, a total of 120 .jpg files are shown, with each image labelled based on chronological order (0.001.jpg, 0.002.jpg, etc). 

## Exploratory Data Plots 

### 1. Pixel Intensity Histogram for Harmonia axyridis (RGB Channels)
<img width="868" height="547" alt="image" src="https://github.com/user-attachments/assets/1b0d285a-c9f9-43cc-8259-ce1e71e86ceb" />

### 2. Pixel Intensity Histogram for Coccinella novemnotata (RGB Channels)
<img width="868" height="547" alt="image" src="https://github.com/user-attachments/assets/427a2c3d-7696-4ee0-b570-dbd8fcf033fd" />




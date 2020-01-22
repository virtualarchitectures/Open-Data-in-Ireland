# Open Data in Ireland
A list of sources of Open Data in Ireland covering both the Republic and the North.

## Open Data
- [Data.gov.ie](https://data.gov.ie/) - Ireland's Open Data portal: Promoting innovation and transparency through the publication of Irish Public Sector data in open, free and reusable formats.
- [Central Statistics Office (CSO)](https://www.cso.ie/en/databases/) - The Central Statistics Office (CSO) is Ireland's national statistical office and our purpose is to impartially collect, analyse and make available statistics about Ireland’s people, society and economy. Provides Linked Open Data for the 2011 Census.
- [OpenDataNI](https://www.opendatani.gov.uk/) - Northern Ireland's Open Data Portal, developed by the Open Data Team as part of the Digital NI initiative. The portal has been created to facilitate easy access to Northern Ireland public sector data for both reuse and redistribution. The data that is available will not be of a sensitive or personal nature, but is the raw data that drives the public sector and its services.

## Spatial Data
- [AIRO Data Store](http://airo.maynoothuniversity.ie/datastore) - The All-Island Research Observatory (AIRO) is based at Maynooth University within the National Institute for Regional and Spatial Analysis (NIRSA). The AIRO Data Store has been created by the team at AIRO and NIRSA as a means of making our working data more accessible to the public. Data is currently available as .csv and .shp format.
- [OSI Open Data](https://data-osi.opendata.arcgis.com/) - Ordnance Survey Ireland are the official national mapping agency for the Republic of Ireland. The release of open data by the OSi supports the growth of the Data.gov.ie open data platform and initiative.
- [Irish OpenStreetMap Community](https://www.openstreetmap.ie/) - OpenStreetMap Ireland as an entity, provides an advocate voice for the OpenStreetMap project on the island of Ireland, in relation to interacting with other Open initiatives. Members are involved in mapping all aspects of the island under an Open Licence. To join in, you can sign up for an account on [OpenStreetMap.org](https://www.openstreetmap.org/) and start mapping what is important to you.
- [Irish Townlands](https://www.townlands.ie/) - A crowdsourcing initiative by the Irish OpenStreetMap Community which is mapping townland, civil parish & barony boundaries in Ireland. The townland system is of Gaelic origin, pre-dating the Norman invasion, and provides the smallest administrative divisions of land in Ireland. These in turn form the building blocks for higher-level administrative units. For this reason the project provides a means of using OSM data for a more fine grained level of statistical analysis than is possible with current open data for city and county boundaries. See the [Ireland/Mapping Townlands](https://wiki.openstreetmap.org/wiki/Ireland/Mapping_Townlands) wiki for further details.
- [Geoportal](https://www.geoportal.ie/geoportal/catalog/main/home.page) - This portal is a shared government resource that provides access to a network of spatial data from a wide variety of Irish public bodies and organisations for download and viewing. It has been created as part of the Irish Spatial Data Infrastructure (ISDI) project and is designed to facilitate the on-line sharing of spatial data according to the requirements of the Irish eGovernment Strategy and the EU INSPIRE Directive.

## Property Data
- [Residential Property Price Register](https://www.propertypriceregister.ie/) - The Property Services Regulatory Authority (PSRA) provide a register of all residential properties purchased in Ireland since the 1st January 2010. The dataset includes address, price and date of sale. Note that the Register is not intended as a "Property Price Index".

## Transport Data
- [Transport Infrastructure Ireland Open Data Portal](http://data.tii.ie/) - This site hosts a range of data sets published by Transport Infrastructure Ireland. The TII also provide a website featuring live traffic information including travel bulletins and images from their national network of motorway traffic cameras [https://www.tiitraffic.ie/](https://www.tiitraffic.ie/). 

#### Select Datasets
- [Transport For Ireland](https://www.transportforireland.ie/transitData/PT_Data.html) - GTFS for for Irish Rail, Bus Eireann, Dublin Bus and Luas. Read the [General Transit Feed (GTFS)](https://gtfs.org) specification for further details.
- [Irish Rail Realtime API](http://api.irishrail.ie/realtime/) - API provides the current location of train services from Iarnród Éireann's central signalling system, and the scheduled journey times from areas under local signalling control.

## Environment Data
- [Environment Protection Agency (EPA)](https://www.epa.ie/) - The EPA provide a range of reports and datasets via their [GeoPortal](http://gis.epa.ie/). The [EPA Maps](https://gis.epa.ie/EPAMaps/) portal provides a useful visualisation of available data sources.
- [OPW Water Levels](waterlevel.ie) - Website providing real-time access to the Office of Public Works (OPW) national network of hydrometric monitors. The sites features a [Real-Time Water Levels API](http://waterlevel.ie/page/api/) providing endpoints for locations of monitoring stations and latest sensor readings in GeoJSON format. Archive data for the day, week and month, can be downloaded as CSV. Archival data can be obtained via OPW's [Hydro-Data](http://waterlevel.ie/hydro-data/home.html) website.
- [Marine Institute Data Centre](https://www.marine.ie/Home/site-area/data-services/search-marine-data/access-data) - The Marine Institute provide a range of maritime data including a real-time feed of data from the [Irish National Tide Gauge Network](https://erddap.marine.ie/erddap/tabledap/IrishNationalTideGaugeNetwork.html).

# Cities
Sources of Open Data for specific cities.

## Dublin
- [Dublinked](https://data.smartdublin.ie/) - Open data for the Dublin region. Data is provided as part of the Smart Dublin initiative of the four Dublin Local Authorities. This project aims to engage with smart technology providers, researchers and citizens to solve challenges and improve city life.

#### Select Datasets
- [Real-time Passenger Information (RTPI) for Dublin Bus, Bus Eireann, Luas and Irish rail](https://data.smartdublin.ie/dataset/real-time-passenger-information-rtpi-for-dublin-bus-bus-eireann-luas-and-irish-rail) - Main page on Dublinked for the real-time transport information. Provides links to Transport For Ireland GTFS and Irish Rail Realtime API [see [Transport Data](https://github.com/virtualarchitectures/Open-Data-in-Ireland#transport-data) above]. Also provides links to Dublin Bus Realtime API and associated documentation. 
  - [Dublin Bus Realtime API Specification](https://data.smartdublin.ie/dataset/c9df9a0b-d17a-40ff-a5d4-01da0cf08617/resource/4b9f2c4f-6bf5-4958-a43a-f12dab04cf61/download/rtpirestapispecification.pdf) - The document describes RTPI REST Web Services API interface that will be available to retrieve real time bus information, timetables and bus stops.
- [Luas Forecasting API](http://luasforecasts.rpa.ie/analysis/view.aspx) - A near real-time API for estimated time of arrival of trams at each of the stops along the Red and Green Lines.
- [JCDeceaux Bike API](https://developer.jcdecaux.com/#/opendata) - International bike scheme API which can be queried for results from the Dublinbikes scheme. Requires an API key.
- [Dublinbikes BETA API by Derilinx](https://dublinbikes.staging.derilinx.com/api/v1/resources/ui/) - Dublinbikes BETA API by Derilinx which provides bike data without requiring authentication. Disclaimer: This API is a work in progress and it is served 'as is'.
- [Sonitus Systems Dublin City Noise API](http://dublincitynoise.sonitussystems.com/applications/api/api-doc.html) - Sonitus Systems API providing access to sound level readings from the Dublin City Council sound level monitoring network.

#### Intermittent / Offline
- [Dublin City Council Traffic Cameras](https://www.dublincity.ie/dublintraffic/) - Central Dublin Traffic Cam feeds. [NOTE: Offline since May 2017]
- [Dublin Multi Story Car Parking Space Availability](https://data.smartdublin.ie/dataset/multi-story-car-parking-space-availability) - Multi Story Car Parking Space Availability Dublin City Councils 'Live Parking Spaces' service gathers information from car parks around Dublin to show you what parking spaces are available. Updated every 5 mins. [NOTE: Service via XML was intermittent as of 18/10/2019]
 
## Cork
- [Cork Smart Gateway](http://data.corkcity.ie/) - The Smart Gateway aims to enhance the reputation of Cork as an attractive place to live, work, visit and invest. Here you will find Data all about Cork which is available in an open format for you to download, conduct research, develop web and mobile applications, design data visualisations and more.

# Other Useful Links
- [GeoHive](https://geohive.ie/) - GeoHive is an initiative by Ordnance Survey Ireland to provide easy access to publically available spatial data. Data can be viewed online with the interactive MapViewer application or accessed via endpoints in one of the following formats: REST, OGC (WMS) or KML.
- [IRLOGI](http://www.irlogi.ie/) - The Irish Organisation for Geographic Information (IRLOGI) is the umbrella organisation for the geographical information industry in Ireland and is a member of EUROGI – the European umbrella organisation for geographical information. IRLOGI was formed in 1995 to represent the Irish GI community. Its mission is to stimulate the development and effective use of Geographic Information in Ireland. The website includes useful links to different sources of geospatial data in Ireland.
- [UCD Library Guide to Spatial Data for Ireland](http://libguides.ucd.ie/gisguide/FindSpatialData) - University College Dublin provide a guide for finding both spatial and statistical datasets for Ireland.
- [OpenStreetMap Wiki: Ireland/Open Data](https://wiki.openstreetmap.org/wiki/Ireland/Open_Data) - A central listing of sources of open data within Ireland that documents details of permission to use the data held by these sources for the improvement of OpenStreetMap data covering the island of Ireland.
- [EU Open Data Portal](http://data.europa.eu/euodp/en/home) - The European Union Open Data Portal (EU ODP) provides access to an expanding range of data from the European Union (EU) institutions and other EU bodies. You can use and reuse these data for commercial or non-commercial purposes.

## Service Providers
- [Derilinx](https://derilinx.com/) - Derilinx provides end-to-end Open Data management for Public-Sector Bodies. Derilinx focuses on provision of Linked & Open Data solutions.

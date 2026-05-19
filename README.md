# Group Software Project
COVID-19 & Flight Data Analysis — REST API

University of Lincoln — Team Software Engineering Project

Overview
A REST API built from scratch in Python (Flask) to ingest, process, and serve comparative analysis between COVID-19 case data and global flight volume data. The API acts as the data layer for a team project, enabling the front-end to query and visualise relationships between pandemic spread and aviation activity across 2020.

Endpoints
MethodEndpointDescriptionGET/covid/<date>Returns all COVID-19 case data for a given dateGET/flight/<icao24>Returns full year flight data for an aircraft by ICAO24 identifierGET/flight/airport/<icao24>Returns flight data filtered to airport activityGET/flight/international/<icao24>Returns international flight data for an aircraftGET/covid/counties/<areaCode>Returns COVID case data broken down by county area code
All endpoints return structured JSON responses for front-end consumption.

What I Built
I designed and developed the API independently as part of a team project:

Designed the full API architecture and all endpoints from scratch using Flask
Ingested and structured two independent real-world datasets (COVID-19 cases + flight tracking data)
Exposed clean parameterised endpoints consumed by the team's front-end
Handled dynamic URL routing using Flask's variable rules (<date>, <icao24>, <areaCode>)
Delivered structured JSON responses across five distinct data slices

Data Sources

COVID-19 data — daily case data queryable by date and county area code
Flight data — aircraft tracking data using ICAO24 identifiers, segmented by full dataset, airport activity, and international routes


Skills Demonstrated

REST API design and development from scratch
Dynamic URL parameter routing
Working with real-world datasets in JSON format
Delivering a defined system component within a team project
Understanding of production considerations (debug mode, error handling, caching)



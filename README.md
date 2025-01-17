# Metro Stations and Crowd Analysis System (MSCAS)

The Metro Stations and Crowd Analysis System (MSCAS) is designed to monitor and analyze passenger traffic at metro stations across a city. It helps track crowd density, identify peak hours, and analyze metro usage patterns to enhance service efficiency, passenger safety, and resource allocation.

## Features
- **Station Management:** Maintain details of metro stations, including location, platforms, and facilities.
- **Crowd Monitoring:** Real-time tracking of crowd density using sensors or user input.
- **Crowd Patterns:** Analyze peak hours and high-traffic stations.
- **Train Schedules:** Record and display train schedules with station arrival and departure times.
- **Real-Time Alerts:** Notify authorities during overcrowding or emergencies.
- **Historical Analysis:** Study past crowd data to predict trends and optimize resource allocation.
- **Passenger Demographics:** Understand traffic trends by tracking commuter types.
- **Station Comparison:** Compare crowd density across different stations.
- **Data Visualization:** Graphical representation of traffic, peak hours, and crowd distribution.
- **Peak Hours Graph:** Generate peak hours graphs using Python and Flask, store images in AWS S3, and save their links in MongoDB for access and analysis.
- **Incident Reporting:** Log incidents, anomalies, and accidents in stations.

## Tech Stack
- **Backend:** Python, Flask, Node.js
- **Database:** MySQL (structured data), MongoDB (unstructured data)
- **Authentication:** JWT (JSON Web Token)
- **Cloud Storage:** AWS S3

## Database Architecture
### MySQL
- **Stations:** Stores station details, platforms, and facilities.
- **Train Schedules:** Maintains train arrival and departure times.
- **Crowd Data:** Tracks passenger numbers at different times.
- **Incident Reports:** Logs reported incidents and anomalies.

### MongoDB
- **Real-Time Crowd Density:** Data from sensors or user inputs.
- **Historical Data:** Past crowd records for analysis.
- **Passenger Logs:** Details on passenger movement.
- **Sensor Data:** Data from crowd density sensors.
- **Peak Hours Graph Links:** Links to peak hour graph images stored in AWS S3.


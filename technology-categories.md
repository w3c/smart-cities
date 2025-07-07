# Technology Categories: Digital Twin and Web intersection

As the [Charter](https://www.w3.org/2024/06/smart-cities/) of the Web-based Digital Twins for Smart Cities IG describes we'd like to start with survey on the existing technologies and standards for Smart Cities, e.g., possible building blocks of Digital Twin Framework and standardized Vocabularies for Smart Cities. So those two technology areas should be a good starting point of our survery.

## Possible building blocks of Digital Twin Framework

### Virtualization of Devices
- Web of Things (WoT): define the capability of physical devices so that they can be handled by applications on the digital layer

### Universal ID for Devices, Users and Services
- Decentralized Identifiers (DID): define IDs to identify devices and users on the digital layer

### Mechanism to identify credentials for Devices, Users and Services 
- Verifiable Credentials (VC): standardized description about user credentials to see what the users can/can't do with the devices on the digital layer

### Visualization
- WebGPU
- Scalable Vector Graphics
- Canvases
- Graphs
- Maps
- Charts
- AR/VR/MR/XR

### Analytics and automation
- WebNN
    - For AI models, although WebGPU can also be used for acceleration
    - e.g. to implement "prediction" function below by training a model
- Simulation
    - e.g. generate continuous 2D image from localized sensor readings of pollution, taking into account wind, etc.
- Automation rules (when this is true, do that, aka IFTTT)
    - Notifications (when this is true, signal event via this mechanism)
- Statistical analysis of historical data
    - e.g. How does current energy consumption/traffic/air quality etc. compare to this time last year?
- Predictive models/forecasts
   - Weather being the most obvious one, but also traffic, air quality, energy consumption, etc.

## Standardized Vocabularies for Smart Cities

### Basic dictionary
- [IEC Common Data Dictionary (CDD)](https://tc3.iec.ch/tc-activity/common-data-dictionary-cdd/)

### Geospatial data

### Entity/Relationship data
- Linked Data
- Property Graphs
- Ontologies
- RDF, RDF-Star, JSON-LD, SPARQL, etc.

### Time series and measurements
- SSN ontologies
- IEEE and NGSI-LD ontologies for time series data
- IoT Sensor interfacing
    - WoT



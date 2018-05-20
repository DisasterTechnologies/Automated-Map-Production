# Automated-Map-Production
Disaster Map Production Based on HIFLD Dataset. The following maps are produced through running this script:

- Cellular Towers
- Local Emergency Operations Centers (EOC)
- PSAP 911 Service Boundary Areas
- Fire Stations
- Emergency Medical Services (EMS) Stations
- Hurricane Evacuation Routes
- National Shelter System (NSS) Facilities
- Nursing Homes
- Urgent Care Facilities
- Hospitals
- EPA Facility Registry Service Power Plants
- Airport Runways

You can customize the scale and location of the maps in the production.py script:

Change line 34 "Scale" to intended parameter.
Change line 35 "location" to the x,y coordinates needed for map center.

You can change the customized template of each geospatial production by editing the prodcution.py script:

Change line 22 "templatePath" to the template that you want to use.


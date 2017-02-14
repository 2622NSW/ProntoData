# ProntoData
Two files downloaded from the Pronto open access bicycle data repository 
There are two files.
2016-12_station_data.csv
2016_12_trip_data.csv
For 2016-12_station_data.csv
-station_id: station ID number (corresponds to "from_station_id" and "to_station_id" in "2016-12_trip_data.csv")
-name: name of station
-lat: station latitude
-long: station longitude
-install_date: date that station was placed in service
-install_dockcount: number of docks at each station on the installation date
-modification_date: date that station was modified, resulting in a change in location or dock count
-current_dockcount: number of docks at each station on 12/31/2016
-decommission_date: date that station was placed out of service
For 2016_12_trip_data.csv
-trip_id: numeric ID of bike triptrip taken
-starttime: day and time trip started, in PST
-stoptime: day and time trip ended, in PST
-bikeid: ID attached to each bike
-tripduration: time of trip in seconds 
-from_station_name: name of station where trip originated
-to_station_name: name of station where trip terminated 
-from_station_id: ID of station where trip originated
-to_station_id: ID of station where trip terminated
-usertype: "Short-Term Pass Holder" is a rider who purchased a 24-Hour or 3-Day Pass; "Member" is a rider who purchased a Monthly Subscription, an Annual Subscription, or a special Pass.
-gender: gender of rider 
-birthyear: birth year of rider
Notes:
First row contains column names
* Trips that did not include a start or end date were removed from original table
* Trips of duration less than one minute or greater than eight hours were removed from original table
* Gender and birth year are only available for Annual Members
* Some stations have been renamed or moved within two blocks of their original location, all stations use current names

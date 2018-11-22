# real_estate_ETL
This project is trying to integrate all the data from different format, different file into on schema.

integrate 7 datasets into one single schema and find and fix possible problems in the data. Input and output
of this assessment are shown below:
```
COLUMN                    DESCRIPTION
Property_id               A unique id for the property
lat                       The property latitude
lng                       The property longitude
addr_street               The property address
suburb (15/100)           The property suburb. Default value: “not available”
price                     The property price
property_type             The type of the propertyyear Year of sold
bedrooms                  Number of bedrooms
bathrooms                 Number of bathrooms
parking_space             The number of parking space of the property
Shopping_center_id        The closest shopping center to the property. Default value: “not available”
Distance_to_sc            The distance from the closest shopping center to the property. Default value: 0
Train_station_id          The closest train station to the property.
Distance_to_train_station The distance from the closest train station to the property. Default value: 0
travel_min_to_CBD         The average travel time (minutes) from the closest train station to the “Flinders street” station on weekdays (i.e. Monday-Friday)
                          departing between 7 to 9 am. For example, if there are 3 trip
                          departing from the closest train station to the Flinders street
                          station on weekdays between 7-9am and each take 6, 7, and 8
                          minutes respectively, then the value of this column for the
                          property should be (6+7+8)/3. If there are direct transfers between
                          the closest station and Flinders street station, only the average of
                          direct transfers should be calculated).
Transfer_flag             A Boolean attribute indicating whether there is a direct trip to the
                          Flinders street station from the closest station between 7-9am on
                          the weekdays. This flag is 0 if there is a direct trip (i.e. no transfer
                          between trains is required to get from the closest train station to
                          the Flinders station) and 1 otherwise.
Hospital_id               The closest hospital to the property. ​Default value: “not available”
Distance_to_hospital      The distance from the closest hospital to the property. Default value: 0
Supermarket_id            The closest supermarket to the property. ​Default value: “not available”
Distance_to_supermaket    The distance from the closest supermarket to the property. Default value: 0
```

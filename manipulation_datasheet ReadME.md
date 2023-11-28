# Manipulation Datasheet 

## Description of Dataset
This dataset contains measurements taken at/for the sample points in the manipulation experiment. 

## Format of the File
The datasheet is in excel .xlsx format.

## Contact People
Poorvi N Ashok : poorvi.ashok@gmail.com
Emma Little: (?)

## Date of Data Collection
18th May 2023  - 9th June 2023

## Geographic Location of Data Collection
Silwood Park, Ascot (51-24’23.162N, 0-38’55.33W)

## Variables 
Date: Date of Measurement. In dd/mm/yy format.

Surveyor  = Name of the person surveying the sample point. Either Poorvi Ashok or Emma Little.

Sample Point = Unique ID allocated for each sample point.

Tree_ID: ID of the tree with the Audiomoth.

Long: Longitudinal data for sample point in DD format for N. Measured using a GPS at the sample point.

Lat: Latitudinal data for sample point in DD format for W. Measured using a GPS at the sample point.

Accuracy: Accuracy of GPS reading in meters. Measured from the GPS.

Distance_from_treatment: Distance of the sample point from the treatment. Determined when choosing the coordinates of the sample point using Google Maps (insert ref)

Treatment_status: Status of the treatment when measuring the light and noise values. Either on or off. 

Lux_horiz1: Repeat 1 of the Measurement of the illuminance values (in lux) in the horizontal position. Measured using a T-1 illuminance meter.

Lux_horiz2: Repeat 2 of the Measurement of the illuminance values (in lux) in the horizontal position. Measured using a T-1 illuminance meter.

Lux_vert1: Repeat 1 of the Measurement of the illuminance values (in lux) in the vertical position. Measured using a T-1 illuminance meter.

Lux_vert2: Repeat 2 of the Measurement of the illuminance values (in lux) in the vertical position. Measured using a T-1 illuminance meter.

spl: Sound pressure level measured (in decibels). Measured using Curconsa ‎SL720-B decibel SPL meter. 

Sun_rise: Time of sun set on date of measurement. Source https://www.timeanddate.com/sun/uk/reading

Sun_set: Time of sun rise on date of measurement. Source https://www.timeanddate.com/sun/uk/reading

Moon_rise: Time of moon rise on date of measurement. Source https://www.timeanddate.com/moon/uk/reading

Moon_set: Time of moon set on date of measurement. Source https://www.timeanddate.com/moon/uk/reading

Moon_illuminance: Percentage illuminance of moon when passing meridian. Source https://www.timeanddate.com/moon/phases/uk/reading

Transect: Unique ID of the transect undergoing the treatment. Either 1, 2 or 3. 

Light (On/Off): Status of the light treatment at the transect on the date of measurement. 0 for off and 1 for on. 

Sound (On/Off): Status of the sound treatment at the transect on the date of measurement. 0 for off and 1 for on.

Treatment: Treatment being done that night starting 7 pm. 1 = light, 2 = sound, 3 = light & sound, 4 = control.

Start Time: Time equipment is turned on. Measured in 24 hour time.

End Time: Time equipment is turned off. Measured in 24 hour time.


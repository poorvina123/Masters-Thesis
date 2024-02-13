# Empirical Datasheet 

## Description of Datasheet
This datasheet contains measurements taken at/for the sample points in the empirical experiment. 

## Format of the File
The datasheet is in excel .xlsx format.

## Contact People
Poorvi N Ashok : poorvi.ashok@gmail.com
Emma Little: (?)

## Date of Data Collection
2nd May 2023 - 15th May 2023

## Geographic Location of Data Collection
Silwood Park, Ascot (51-24’23.162N, 0-38’55.33W)

Barnes Common, London (51-27’36’’N, 0-14’23.9994’’W)

## Variables 
Date: Date of Measurement (in dd/mm/yy format).

Site: Site that the sample point is present in (either Silwood or Barnes).

Surveyor: Name of the person surveying the sample point (either Poorvi Ashok or Emma Little).

Sample Point: Unique ID allocated for each sample point.

Tree_ID: Species ID of the tree with the Audiomoth.

Long: Longitudinal data for sample point (in DD format for N). Measured using a GPS at the sample point.

Lat: Latitudinal data for sample point (in DD format for W). Measured using a GPS at the sample point.

Accuracy: Accuracy of GPS reading (in m). Measured using a GPS.

Distance_from_water_body: Distance to nearest water body that is not ephemeral, and larger than 20 square meters (in m).

Distance_from_building: Distance to nearest in-use building (in m).

Distance_from_woodland: Distance to nearest woodland, defined as area of unbroken canopy cover > 0.5 hectares in size and wider at all times than one tree (zero if within woodland) (in m).

Distance_from_woodland_edge: Distance to nearest edge, defined as clear boundary between woodland and other habitat or land use eg wide road parting the canopy (in m).

Distance_from_road: Distance to nearest two-way, non-dead-end road (in m).

Distance_from_rail: Distance to nearest railway line (in m).

Distance_from_any_artificial_light: Distance to nearest artificial light on consistently at night - including streetlamps (in m).

Distance_from_streetlamp: Distance to nearest streetlamp (in m).

Distance_from_nearest_light: Distance to the nearest light source either artificial light or streetlamp (in m).

Distance_from_nearest_noise: Distance to the nearest noise source either road or rail (in m).

Compass_direction_to_understorey_canopy_cover_measurement: Direction of the measurement, 5m in the direction specified (either N, S, E, or W).

Para_0_value: Number of pixels that are white in threshold adjusted photo parallel to the compass direction. Measured using ImageJ.

Para_255_value: Number of pixels that are black in threshold adjusted photo parallel to the compass direction. Measured using ImageJ.

Perp_0_value: Number of pixels that are white in threshold adjusted photo perpendicular to the compass direction. Measured using ImageJ.

Perp_255_value: Number of pixels that are black in threshold adjusted photo perpendicular to the compass direction. Measured using ImageJ.

Gap val 1: Ratio of black pixels to total number of pixels present in the parallel direction.

Gap val 2: Ratio of black pixels to total number of pixels present in the perpendicular direction.

Av gap val: Average of Gap val 1 and Gap val 2.

Quarter point: The quarter for the measurement of the nearest tree (either 1 - NE, 2 - SE, 3 - SW, 4 - NW).

Distance_nearest_tree: Using point-centred quarter method, distance to the nearest live, standing tree of >=30cm circumference at 130cm height (in cm).

Lux_positioning: The positioning of the Lux meter (Minolta Illuminance Meter T-1) for the measurement (either vertical or horizontal). 

Lux_Night_1: Illuminance measurement 1 in the night using Minolta Illuminance Meter T-1 (in lux).

Lux_Night_2: Illuminance measurement 2 in the night using Minolta Illuminance Meter T-1 (in lux).

Light_Average: Average of Lux_Night_1 and Lux_Night_2 (in lux). 

UV_Night_1: UV measurement 1 in the night using RS PRO mini pocket UV AB meter IM-213 (in milliwatts per square centimetre (mW/cm2)).

UV_Night_2: UV measurement 2 in the night using RS PRO mini pocket UV AB meter IM-213 (in milliwatts per square centimetre (mW/cm2)).

Time: Time at which the measurements were taken from the respective website.

Air_temp: Air temperature (in degrees C). Source for Barnes: Weather station 7 Washington Road, SW13 (https://wow.metoffice.gov.uk/observations/details/20230501semho4xexce65rj4rymrfqirmr) and for Silwood: Weather station Sunninghill (https://wow.metoffice.gov.uk/observations/details/?site_id=4c3f2be3-8bf2-e911-b862-0003ff599e2a!)

Wind_speed: Wind speed (in knots). Source for Barnes: Weather station 7 Washington Road, SW13  (https://wow.metoffice.gov.uk/observations/details/20230501semho4xexce65rj4rymrfqirmr) and for Silwood: Weather station Sunninghill (https://wow.metoffice.gov.uk/observations/details/?site_id=4c3f2be3-8bf2-e911-b862-0003ff599e2a!)

Rainfall_accumulation: Rainfall accumulation over whole day (in mm). Source for Barnes: Weather station 7 Washington Road, SW13  (https://wow.metoffice.gov.uk/observations/details/20230501semho4xexce65rj4rymrfqirmr) and for Silwood: Weather station Sunninghill (https://wow.metoffice.gov.uk/observations/details/?site_id=4c3f2be3-8bf2-e911-b862-0003ff599e2a!)

Rainfall_last_3hrs: Rainfall accumulation over previous 3hrs (in mm/3hrs). Source for Barnes: Weather station 7 Washington Road, SW13  (https://wow.metoffice.gov.uk/observations/details/20230501semho4xexce65rj4rymrfqirmr) and for Silwood: Weather station Sunninghill (https://wow.metoffice.gov.uk/observations/details/?site_id=4c3f2be3-8bf2-e911-b862-0003ff599e2a!)

Sun_rise: Time of sun rise on date of sample. Source for Barnes (https://www.timeanddate.com/sun/uk/london) and for Silwood  (https://www.timeanddate.com/sun/uk/reading!)

Sun_set: Time of sun set on date of sample. Source for Barnes (https://www.timeanddate.com/sun/uk/london) and for Silwood  (https://www.timeanddate.com/sun/uk/reading!)

Moon_rise: Time of moon rise on date of sample. Source for Barnes (https://www.timeanddate.com/sun/uk/london) and for Silwood  (https://www.timeanddate.com/sun/uk/reading!)

Moon_set: Time of moon set on date of sample. Source for Barnes (https://www.timeanddate.com/sun/uk/london) and for Silwood  (https://www.timeanddate.com/sun/uk/reading!)

Moon_illumination: Percentage illuminance of moon when passing meridian. Source for Barnes (https://www.timeanddate.com/sun/uk/london) and for Silwood (https://www.timeanddate.com/sun/uk/reading!)

Mean_temp_day: Mean day temperature (in degrees C), between 06:00hrs and 21:00hrs. Source for Barnes: Weather station 7 Washington Road, SW13  (https://wow.metoffice.gov.uk/observations/details/20230501semho4xexce65rj4rymrfqirmr) and for Silwood: Weather station Sunninghill (https://wow.metoffice.gov.uk/observations/details/?site_id=4c3f2be3-8bf2-e911-b862-0003ff599e2a!)

Mean_temp_night: Mean night temperature (in degrees C), between 21:00hrs and 06:00hrs. Source for Barnes: Weather station 7 Washington Road, SW13  (https://wow.metoffice.gov.uk/observations/details/20230501semho4xexce65rj4rymrfqirmr) and for Silwood: Weather station Sunninghill (https://wow.metoffice.gov.uk/observations/details/?site_id=4c3f2be3-8bf2-e911-b862-0003ff599e2a!)

Mean_wind_speed_day: Mean day wind speed (in knots), between 06:00hrs and 21:00hrs. Source for Barnes: Weather station 7 Washington Road, SW13  (https://wow.metoffice.gov.uk/observations/details/20230501semho4xexce65rj4rymrfqirmr) and for Silwood: Weather station Sunninghill (https://wow.metoffice.gov.uk/observations/details/?site_id=4c3f2be3-8bf2-e911-b862-0003ff599e2a!)

Mean_wind_speed_night: Mean night wind speed (in knots), between 21:00hrs and 06:00hrs. Source for Barnes: Weather station 7 Washington Road, SW13  (https://wow.metoffice.gov.uk/observations/details/20230501semho4xexce65rj4rymrfqirmr) and for Silwood: Weather station Sunninghill (https://wow.metoffice.gov.uk/observations/details/?site_id=4c3f2be3-8bf2-e911-b862-0003ff599e2a!)

Mean_rainfall_last_3hrs_day: Mean day rainfall accumulation over previous 3hrs (in mm/3hrs), between 06:00hrs and 21:00hrs. Source for Barnes: Weather station 7 Washington Road, SW13  (https://wow.metoffice.gov.uk/observations/details/20230501semho4xexce65rj4rymrfqirmr) and for Silwood: Weather station Sunninghill (https://wow.metoffice.gov.uk/observations/details/?site_id=4c3f2be3-8bf2-e911-b862-0003ff599e2a!)

Mean_rainfall_last_3hrs_night: Mean night rainfall accumulation over previous 3hrs (in mm/3hrs), between 21:00hrs and 06:00hrs. Source for Barnes: Weather station 7 Washington Road, SW13  (https://wow.metoffice.gov.uk/observations/details/20230501semho4xexce65rj4rymrfqirmr) and for Silwood: Weather station Sunninghill (https://wow.metoffice.gov.uk/observations/details/?site_id=4c3f2be3-8bf2-e911-b862-0003ff599e2a!)

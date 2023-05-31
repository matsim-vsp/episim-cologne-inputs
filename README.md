# Synthetic-activity-chains-for-agent-based-epidemiological-simulations-of-Cologne
 
 Release according to data protection provision "Open Data Agreement of 11.07.2022" between Senozon Deutschland and the VSP department at the TU Berlin.

EPISIM-MODEL OF THE VSP DEPARTMENT AT THE TU BERLIN:
## The usage and download of the following open available files are only allowed for an epidemiological simulation of Cologne.
## Do not use the files for other simulations.

The open availbale model includes a 25 percent sample. The code for running the simulation is also open available under: https://github.com/matsim-org/matsim-episim .
You can find more information on our website: https://covid-sim.info/ .
If you have questions, please contact covid19@vsp.tu-berlin.de 

Files:
cologne_snz_entirePopulation_emptyPlans_withDistricts_25pt_split.xml.gz:
	Population including all persons having activities in one of the events files. The person attributes are homeId, homeCoordinates, age, district of home.
	The coordinates are in grid accuracy of 500m.

cologne_snz_episim_events_sa_25pt_split.xml.gz
cologne_snz_episim_events_so_25pt_split.xml.gz
cologne_snz_episim_events_wt_25pt_split.xml.gz
	The episim events files for a weekday, Saturday and Sunday. The events files are filtered for the only necessary types of events (actend, actstart, PersonEntersVehicle, PersonLeavesVehicle).

cologne_2020-vehicles.xml.gz
	File includes a mapping of vehiclesIds to the vehilce type.

cologne_facilities_assigned_simplified_grid.xml.gz
	Including the facilities used in the evnts files. The coordinates are in grid accuracy of 500m.

cologne_until20221231_mobility_data.csv
	Daily mobility data for Cologne for the simulated period.

sha256sums:
18bc3603b19a981033e6a2b5b9f5662b1429782645eac1335bab9695bb82b6ad  cologne_snz_entirePopulation_emptyPlans_withDistricts_25pt_split_grid.xml.gz
d1c75402dbbe4d3529d7567823988d8791b9ac8388e0cff29c0611e40440b6b1  facilities_assigned_simplified_grid.xml.gz
661155d96352faf8db24b561310f81a1b29122bc0545345e011416645fd1b70d  cologne_snz_episim_events_sa_25pt_split.xml.gz
359ea5022967f2f37971992b5580de146370adf1120ec8aa2b487e8d0aed2815  cologne_snz_episim_events_so_25pt_split.xml.gz
d86d98091fb59e1412b9fb702d8f8454c5bf3045fb30892a96e789d5ca0336d9  cologne_snz_episim_events_wt_25pt_split.xml.gz
8e0209721b5bfb8596f653a998572ead6356676e3d539b4f74475e8dd2fa5e44  de_2020-vehicles.xml.gz
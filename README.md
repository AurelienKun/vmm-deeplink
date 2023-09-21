# Deeplinks for VMM

## Basics

- [Lille > Bordeaux (no constraint)](vmm://itinerary_summary/3.057256:50.62925,-0.5754952:44.8349955?itineraryType=0&vehicleType=0&distUnit=m&avoidExpressWays=false&fuelConsump=6.200000:5.200000:5.500000&wCaravan=false&avoidORC=false&avoidCCZ=false&avoidBorders=false&avoidTolls=false&fuelCost=1.80000&withTraffic=false&currency=EUR&carCategory=4)
- [Toulouse > Milan (only coodinates, no parameters)](vmm://itinerary_summary/1.444509:43.6039487,9.1881156:45.4636183)
- [Nantes > Toulouse (no constraint, only active parameters included)](vmm://itinerary_summary/-1.5571805:47.2182641,1.444509:43.6039487,6.960279:50.937531?itineraryType=0&vehicleType=0&distUnit=m&avoidExpressWays=false&fuelConsump=6.200000:5.200000:5.500000&fuelCost=1.88&currency=EUR&carCategory=4)
- [Milan > Rome (no constraint, missing vehicle)](vmm://itinerary_summary/9.1881156:45.4636183,12.4942679:41.8905568?itineraryType=0&distUnit=m&avoidExpressWays=false&wCaravan=false&avoidORC=false&avoidCCZ=false&avoidBorders=false&avoidTolls=false&fuelCost=1.80000&withTraffic=false&currency=EUR)
- [Milan > Berne (no constraint, with caravan)](vmm://itinerary_summary/9.1881156:45.4636183,7.4481304:46.9480024?itineraryType=0&vehicleType=0&distUnit=m&avoidExpressWays=false&fuelConsump=6.200000:5.200000:5.500000&wCaravan=true&avoidORC=false&avoidCCZ=false&avoidBorders=false&avoidTolls=false&fuelCost=1.80000&withTraffic=false&currency=EUR&carCategory=4)

## Constraints & other options

Based on the following route: `Lyon` > `Berne` with luxury vehicle
- [basic, no constraint nor options](vmm://itinerary_summary/4.8343065:45.7673063,7.4481304:46.9480024?itineraryType=0&vehicleType=0&distUnit=m&avoidExpressWays=false&fuelConsump=6.200000:5.200000:5.500000&wCaravan=false&avoidORC=false&avoidCCZ=false&avoidBorders=false&avoidTolls=false&fuelCost=1.80000&withTraffic=false&currency=EUR&carCategory=4)
- [tolls](vmm://itinerary_summary/4.8343065:45.7673063,7.4481304:46.9480024?itineraryType=0&vehicleType=0&distUnit=m&avoidExpressWays=false&fuelConsump=6.200000:5.200000:5.500000&wCaravan=false&avoidORC=false&avoidCCZ=false&avoidBorders=false&avoidTolls=true&fuelCost=1.80000&withTraffic=false&currency=EUR&carCategory=4)
- [motorways](vmm://itinerary_summary/4.8343065:45.7673063,7.4481304:46.9480024?itineraryType=0&vehicleType=0&distUnit=m&avoidExpressWays=true&fuelConsump=6.200000:5.200000:5.500000&wCaravan=false&avoidORC=false&avoidCCZ=false&avoidBorders=false&avoidTolls=false&fuelCost=1.80000&withTraffic=false&currency=EUR&carCategory=4)
- [vignettes](vmm://itinerary_summary/4.8343065:45.7673063,7.4481304:46.9480024?itineraryType=0&vehicleType=0&distUnit=m&avoidExpressWays=false&fuelConsump=6.200000:5.200000:5.500000&wCaravan=false&avoidORC=false&avoidCCZ=true&avoidBorders=false&avoidTolls=false&fuelCost=1.80000&withTraffic=false&currency=EUR&carCategory=4)
- [sea crossing](vmm://itinerary_summary/4.8343065:45.7673063,7.4481304:46.9480024?itineraryType=0&vehicleType=0&distUnit=m&avoidExpressWays=false&fuelConsump=6.200000:5.200000:5.500000&wCaravan=false&avoidORC=true&avoidCCZ=false&avoidBorders=false&avoidTolls=false&fuelCost=1.80000&withTraffic=false&currency=EUR&carCategory=4)
- [leaving country](vmm://itinerary_summary/4.8343065:45.7673063,7.4481304:46.9480024?itineraryType=0&vehicleType=0&distUnit=m&avoidExpressWays=false&fuelConsump=6.200000:5.200000:5.500000&wCaravan=false&avoidORC=false&avoidCCZ=false&avoidBorders=true&avoidTolls=false&fuelCost=1.80000&withTraffic=false&currency=EUR&carCategory=4)
- [tolls + vignettes](vmm://itinerary_summary/4.8343065:45.7673063,7.4481304:46.9480024?itineraryType=0&vehicleType=0&distUnit=m&avoidExpressWays=false&fuelConsump=6.200000:5.200000:5.500000&wCaravan=false&avoidORC=false&avoidCCZ=true&avoidBorders=false&avoidTolls=true&fuelCost=1.80000&withTraffic=false&currency=EUR&carCategory=4)
- [basic + caravan](vmm://itinerary_summary/4.8343065:45.7673063,7.4481304:46.9480024?itineraryType=0&vehicleType=0&distUnit=m&avoidExpressWays=false&fuelConsump=6.200000:5.200000:5.500000&wCaravan=false&avoidORC=false&avoidCCZ=false&avoidBorders=false&avoidTolls=false&fuelCost=1.80000&withTraffic=false&currency=EUR&carCategory=4)
- [basic + trafic](vmm://itinerary_summary/4.8343065:45.7673063,7.4481304:46.9480024?itineraryType=0&vehicleType=0&distUnit=m&avoidExpressWays=false&fuelConsump=6.200000:5.200000:5.500000&wCaravan=false&avoidORC=false&avoidCCZ=false&avoidBorders=false&avoidTolls=false&fuelCost=1.80000&withTraffic=true&currency=EUR&carCategory=4)
- [motorways + trafic](vmm://itinerary_summary/4.8343065:45.7673063,7.4481304:46.9480024?itineraryType=0&vehicleType=0&distUnit=m&avoidExpressWays=true&fuelConsump=6.200000:5.200000:5.500000&wCaravan=false&avoidORC=false&avoidCCZ=false&avoidBorders=false&avoidTolls=false&fuelCost=1.80000&withTraffic=true&currency=EUR&carCategory=4)
- [sea crossing + trafic + caravan](vmm://itinerary_summary/4.8343065:45.7673063,7.4481304:46.9480024?itineraryType=0&vehicleType=0&distUnit=m&avoidExpressWays=false&fuelConsump=6.200000:5.200000:5.500000&wCaravan=true&avoidORC=true&avoidCCZ=false&avoidBorders=false&avoidTolls=false&fuelCost=1.80000&withTraffic=true&currency=EUR&carCategory=4)
- [all constraints](vmm://itinerary_summary/4.8343065:45.7673063,7.4481304:46.9480024?itineraryType=0&vehicleType=0&distUnit=m&avoidExpressWays=true&fuelConsump=6.200000:5.200000:5.500000&wCaravan=true&avoidORC=true&avoidCCZ=true&avoidBorders=true&avoidTolls=true&fuelCost=1.80000&withTraffic=true&currency=EUR&carCategory=4)

## Vehicules

### Fuel type
Based on the following route: `Brest` > `Orléans` (no constraint & hatchback)

- [Hatchback, petrol](vmm://itinerary_summary/-4.487176:48.3898693,1.9039164:47.9013993?itineraryType=0&vehicleType=0&distUnit=m&avoidExpressWays=false&wCaravan=false&avoidORC=false&avoidCCZ=false&avoidBorders=false&avoidTolls=false&withTraffic=false&currency=EUR&carCategory=0&fuelConsump=6.8;5.6;5.6&fuelType=0&fuelCost=1.926)
- [Hatchback, gpl](vmm://itinerary_summary/-4.487176:48.3898693,1.9039164:47.9013993?itineraryType=0&vehicleType=0&distUnit=m&avoidExpressWays=false&wCaravan=false&avoidORC=false&avoidCCZ=false&avoidBorders=false&avoidTolls=false&withTraffic=false&currency=EUR&carCategory=0&fuelConsump=7.3;6.1;6.5&fuelType=1&fuelCost=0.98)
- [Hatchback, gasoil](vmm://itinerary_summary/-4.487176:48.3898693,1.9039164:47.9013993?itineraryType=0&vehicleType=0&distUnit=m&avoidExpressWays=false&wCaravan=false&avoidORC=false&avoidCCZ=false&avoidBorders=false&avoidTolls=false&withTraffic=false&currency=EUR&carCategory=0&fuelConsump=5.1;4.2;4.5&fuelType=2&fuelCost=1.8599)
- [Hatchback, electric(no fuel cost)](vmm://itinerary_summary/-4.487176:48.3898693,1.9039164:47.9013993?itineraryType=0&vehicleType=0&distUnit=m&avoidExpressWays=false&wCaravan=false&avoidORC=false&avoidCCZ=false&avoidBorders=false&avoidTolls=false&withTraffic=false&currency=EUR&carCategory=0&fuelConsump=12.787720:12.787720:12.787720&fuelType=3&fuelCost=)
- [Hatchback, super ethanol](vmm://itinerary_summary/-4.487176:48.3898693,1.9039164:47.9013993?itineraryType=0&vehicleType=0&distUnit=m&avoidExpressWays=false&wCaravan=false&avoidORC=false&avoidCCZ=false&avoidBorders=false&avoidTolls=false&withTraffic=false&currency=EUR&carCategory=0&fuelConsump=8.500000:7.000000:7.000000&fuelType=4&fuelCost=1.05)
- [Hatchback, compressed natural gas](vmm://itinerary_summary/-4.487176:48.3898693,1.9039164:47.9013993?itineraryType=0&vehicleType=0&distUnit=m&avoidExpressWays=false&wCaravan=false&avoidORC=false&avoidCCZ=false&avoidBorders=false&avoidTolls=false&withTraffic=false&currency=EUR&carCategory=0&fuelConsump=4.700000:3.900000:4.200000&fuelType=5&fuelCost=1.078)
- [Hatchback, hydrogen (no fuel cost)](vmm://itinerary_summary/-4.487176:48.3898693,1.9039164:47.9013993?itineraryType=0&vehicleType=0&distUnit=m&avoidExpressWays=false&wCaravan=false&avoidORC=false&avoidCCZ=false&avoidBorders=false&avoidTolls=false&withTraffic=false&currency=EUR&carCategory=0&fuelConsump=0.800000:0.800000:0.900000&fuelType=6&fuelCost=)

### Car category

Based on the following route: `Cologne` > `Dusseldorf` (no constraint & petrol)

- [Hatchback](vmm://itinerary_summary/6.960279:50.937531,6.7756691:51.224956?itineraryType=0&vehicleType=0&distUnit=m&avoidExpressWays=false&wCaravan=false&avoidORC=false&avoidCCZ=false&avoidBorders=false&avoidTolls=false&withTraffic=false&currency=EUR&carCategory=0&fuelConsump=6.8;5.6;5.6&fuelType=0&fuelCost=1.926)
- [Compact](vmm://itinerary_summary/6.960279:50.937531,6.7756691:51.224956?itineraryType=0&vehicleType=0&distUnit=m&avoidExpressWays=false&wCaravan=false&avoidORC=false&avoidCCZ=false&avoidBorders=false&avoidTolls=false&withTraffic=false&currency=EUR&carCategory=0&fuelConsump=7.900000:6.600000:7.000000&fuelType=0&fuelCost=1.926)
- [Family](vmm://itinerary_summary/6.960279:50.937531,6.7756691:51.224956?itineraryType=0&vehicleType=0&distUnit=m&avoidExpressWays=false&wCaravan=false&avoidORC=false&avoidCCZ=false&avoidBorders=false&avoidTolls=false&withTraffic=false&currency=EUR&carCategory=0&fuelConsump=9.000000:7.500000:8.000000&fuelType=0&fuelCost=1.926)
- [Sedan](vmm://itinerary_summary/6.960279:50.937531,6.7756691:51.224956?itineraryType=0&vehicleType=0&distUnit=m&avoidExpressWays=false&wCaravan=false&avoidORC=false&avoidCCZ=false&avoidBorders=false&avoidTolls=false&withTraffic=false&currency=EUR&carCategory=0&fuelConsump=11.300000:9.400000:11.400000&fuelType=0&fuelCost=1.926)
- [Luxury](vmm://itinerary_summary/6.960279:50.937531,6.7756691:51.224956?itineraryType=0&vehicleType=0&distUnit=m&avoidExpressWays=false&wCaravan=false&avoidORC=false&avoidCCZ=false&avoidBorders=false&avoidTolls=false&withTraffic=false&currency=EUR&carCategory=0&fuelConsump=15.200000:12.700000:15.400000&fuelType=0&fuelCost=1.926)

## Unit

Based on the following route: `Liège` > `Mons` (no constraint & luxury vehicle with petrol)

- [meters](vmm://itinerary_summary/5.579666:50.632557,3.9487367:50.4533334?itineraryType=0&vehicleType=0&distUnit=m&avoidExpressWays=false&wCaravan=false&avoidORC=false&avoidCCZ=false&avoidBorders=false&avoidTolls=false&withTraffic=false&currency=EUR&carCategory=0&fuelConsump=15.200000:12.700000:15.400000&fuelType=0&fuelCost=1.926)
- [miles](vmm://itinerary_summary/5.579666:50.632557,3.9487367:50.4533334?itineraryType=0&vehicleType=0&distUnit=mi&avoidExpressWays=false&wCaravan=false&avoidORC=false&avoidCCZ=false&avoidBorders=false&avoidTolls=false&withTraffic=false&currency=EUR&carCategory=0&fuelConsump=15.200000:12.700000:15.400000&fuelType=0&fuelCost=1.926)

## More than 2 cities (no constraint)

- [(2) Lille > Rouen > Rennes](vmm://itinerary_summary/3.057256:50.62925,1.0984642:49.4423985,-1.6802641:48.1117806?itineraryType=0&vehicleType=0&distUnit=m&avoidExpressWays=false&fuelConsump=6.200000:5.200000:5.500000&wCaravan=false&avoidORC=false&avoidCCZ=false&avoidBorders=false&avoidTolls=false&fuelCost=1.80000&withTraffic=false&currency=EUR&carCategory=4)
- [(3) Lille > Rouen > Rennes > Brest](vmm://itinerary_summary/3.057256:50.62925,1.0984642:49.4423985,-1.6802641:48.1117806,-4.487176:48.3898693?itineraryType=0&vehicleType=0&distUnit=m&avoidExpressWays=false&fuelConsump=6.200000:5.200000:5.500000&wCaravan=false&avoidORC=false&avoidCCZ=false&avoidBorders=false&avoidTolls=false&fuelCost=1.80000&withTraffic=false&currency=EUR&carCategory=4)
- [(4) Lille > Rouen > Rennes > Brest > Nantes](vmm://itinerary_summary/3.057256:50.62925,1.0984642:49.4423985,-1.6802641:48.1117806,-4.487176:48.3898693,-1.5571805:47.2182641?itineraryType=0&vehicleType=0&distUnit=m&avoidExpressWays=false&fuelConsump=6.200000:5.200000:5.500000&wCaravan=false&avoidORC=false&avoidCCZ=false&avoidBorders=false&avoidTolls=false&fuelCost=1.80000&withTraffic=false&currency=EUR&carCategory=4)
- [(5) Lille > Rouen > Rennes > Brest > Nantes > Niort](vmm://itinerary_summary/3.057256:50.62925,1.0984642:49.4423985,-1.6802641:48.1117806,-4.487176:48.3898693,-1.5571805:47.2182641,-0.4575836:46.3238567?itineraryType=0&vehicleType=0&distUnit=m&avoidExpressWays=false&fuelConsump=6.200000:5.200000:5.500000&wCaravan=false&avoidORC=false&avoidCCZ=false&avoidBorders=false&avoidTolls=false&fuelCost=1.80000&withTraffic=false&currency=EUR&carCategory=4)
- [(6) Lille > Rouen > Rennes > Brest > Nantes > Niort > Bordeaux](vmm://itinerary_summary/3.057256:50.62925,1.0984642:49.4423985,-1.6802641:48.1117806,-4.487176:48.3898693,-1.5571805:47.2182641,-0.4575836:46.3238567,-0.5754952:44.8349955?itineraryType=0&vehicleType=0&distUnit=m&avoidExpressWays=false&fuelConsump=6.200000:5.200000:5.500000&wCaravan=false&avoidORC=false&avoidCCZ=false&avoidBorders=false&avoidTolls=false&fuelCost=1.80000&withTraffic=false&currency=EUR&carCategory=4)
- [(7) Lille > Rouen > Rennes > Brest > Nantes > Niort > Bordeaux > Saint Sébastien](vmm://itinerary_summary/3.057256:50.62925,1.0984642:49.4423985,-1.6802641:48.1117806,-4.487176:48.3898693,-1.5571805:47.2182641,-0.4575836:46.3238567,-0.5754952:44.8349955,-1.9845145:43.320905?itineraryType=0&vehicleType=0&distUnit=m&avoidExpressWays=false&fuelConsump=6.200000:5.200000:5.500000&wCaravan=false&avoidORC=false&avoidCCZ=false&avoidBorders=false&avoidTolls=false&fuelCost=1.80000&withTraffic=false&currency=EUR&carCategory=4)
- [(8) Lille > Rouen > Rennes > Brest > Nantes > Niort > Bordeaux > Saint Sébastien > Madrid](vmm://itinerary_summary/3.057256:50.62925,1.0984642:49.4423985,-1.6802641:48.1117806,-4.487176:48.3898693,-1.5571805:47.2182641,-0.4575836:46.3238567,-0.5754952:44.8349955,-1.9845145:43.320905,-3.7003454:40.4166909?itineraryType=0&vehicleType=0&distUnit=m&avoidExpressWays=false&fuelConsump=6.200000:5.200000:5.500000&wCaravan=false&avoidORC=false&avoidCCZ=false&avoidBorders=false&avoidTolls=false&fuelCost=1.80000&withTraffic=false&currency=EUR&carCategory=4)
- [(9) Lille > Rouen > Rennes > Brest > Nantes > Niort > Bordeaux > Saint Sébastien > Madrid > Saragosse](vmm://itinerary_summary/3.057256:50.62925,1.0984642:49.4423985,-1.6802641:48.1117806,-4.487176:48.3898693,-1.5571805:47.2182641,-0.4575836:46.3238567,-0.5754952:44.8349955,-1.9845145:43.320905,-3.7003454:40.4166909,-0.8794245:41.656837?itineraryType=0&vehicleType=0&distUnit=m&avoidExpressWays=false&fuelConsump=6.200000:5.200000:5.500000&wCaravan=false&avoidORC=false&avoidCCZ=false&avoidBorders=false&avoidTolls=false&fuelCost=1.80000&withTraffic=false&currency=EUR&carCategory=4)
- [(10) Lille > Rouen > Rennes > Brest > Nantes > Niort > Bordeaux > Saint Sébastien > Madrid > Saragosse > Toulouse](vmm://itinerary_summary/3.057256:50.62925,1.0984642:49.4423985,-1.6802641:48.1117806,-4.487176:48.3898693,-1.5571805:47.2182641,-0.4575836:46.3238567,-0.5754952:44.8349955,-1.9845145:43.320905,-3.7003454:40.4166909,-0.8794245:41.656837,1.444509:43.6039487?itineraryType=0&vehicleType=0&distUnit=m&avoidExpressWays=false&fuelConsump=6.200000:5.200000:5.500000&wCaravan=false&avoidORC=false&avoidCCZ=false&avoidBorders=false&avoidTolls=false&fuelCost=1.80000&withTraffic=false&currency=EUR&carCategory=4)
- [(11) Lille > Rouen > Rennes > Brest > Nantes > Niort > Bordeaux > Saint Sébastien > Madrid > Saragosse > Toulouse > Marseille](vmm://itinerary_summary/3.057256:50.62925,1.0984642:49.4423985,-1.6802641:48.1117806,-4.487176:48.3898693,-1.5571805:47.2182641,-0.4575836:46.3238567,-0.5754952:44.8349955,-1.9845145:43.320905,-3.7003454:40.4166909,-0.8794245:41.656837,1.444509:43.6039487,5.3744868:43.2950213?itineraryType=0&vehicleType=0&distUnit=m&avoidExpressWays=false&fuelConsump=6.200000:5.200000:5.500000&wCaravan=false&avoidORC=false&avoidCCZ=false&avoidBorders=false&avoidTolls=false&fuelCost=1.80000&withTraffic=false&currency=EUR&carCategory=4)
- [(12) Lille > Rouen > Rennes > Brest > Nantes > Niort > Bordeaux > Saint Sébastien > Madrid > Saragosse > Toulouse > Marseille > Rome](vmm://itinerary_summary/3.057256:50.62925,1.0984642:49.4423985,-1.6802641:48.1117806,-4.487176:48.3898693,-1.5571805:47.2182641,-0.4575836:46.3238567,-0.5754952:44.8349955,-1.9845145:43.320905,-3.7003454:40.4166909,-0.8794245:41.656837,1.444509:43.6039487,5.3744868:43.2950213,12.4942679:41.8905568?itineraryType=0&vehicleType=0&distUnit=m&avoidExpressWays=false&fuelConsump=6.200000:5.200000:5.500000&wCaravan=false&avoidORC=false&avoidCCZ=false&avoidBorders=false&avoidTolls=false&fuelCost=1.80000&withTraffic=false&currency=EUR&carCategory=4)
- [(13) Lille > Rouen > Rennes > Brest > Nantes > Niort > Bordeaux > Saint Sébastien > Madrid > Saragosse > Toulouse > Marseille > Rome > Milan](vmm://itinerary_summary/3.057256:50.62925,1.0984642:49.4423985,-1.6802641:48.1117806,-4.487176:48.3898693,-1.5571805:47.2182641,-0.4575836:46.3238567,-0.5754952:44.8349955,-1.9845145:43.320905,-3.7003454:40.4166909,-0.8794245:41.656837,1.444509:43.6039487,5.3744868:43.2950213,12.4942679:41.8905568,9.1881156:45.4636183?itineraryType=0&vehicleType=0&distUnit=m&avoidExpressWays=false&fuelConsump=6.200000:5.200000:5.500000&wCaravan=false&avoidORC=false&avoidCCZ=false&avoidBorders=false&avoidTolls=false&fuelCost=1.80000&withTraffic=false&currency=EUR&carCategory=4)
- [(14) Lille > Rouen > Rennes > Brest > Nantes > Niort > Bordeaux > Saint Sébastien > Madrid > Saragosse > Toulouse > Marseille > Rome > Milan > Turin](vmm://itinerary_summary/3.057256:50.62925,1.0984642:49.4423985,-1.6802641:48.1117806,-4.487176:48.3898693,-1.5571805:47.2182641,-0.4575836:46.3238567,-0.5754952:44.8349955,-1.9845145:43.320905,-3.7003454:40.4166909,-0.8794245:41.656837,1.444509:43.6039487,5.3744868:43.2950213,12.4942679:41.8905568,9.1881156:45.4636183,7.6830662:45.0683751?itineraryType=0&vehicleType=0&distUnit=m&avoidExpressWays=false&fuelConsump=6.200000:5.200000:5.500000&wCaravan=false&avoidORC=false&avoidCCZ=false&avoidBorders=false&avoidTolls=false&fuelCost=1.80000&withTraffic=false&currency=EUR&carCategory=4)
- [(15) Lille > Rouen > Rennes > Brest > Nantes > Niort > Bordeaux > Saint Sébastien > Madrid > Saragosse > Toulouse > Marseille > Rome > Milan > Turin > Lyon](vmm://itinerary_summary/3.057256:50.62925,1.0984642:49.4423985,-1.6802641:48.1117806,-4.487176:48.3898693,-1.5571805:47.2182641,-0.4575836:46.3238567,-0.5754952:44.8349955,-1.9845145:43.320905,-3.7003454:40.4166909,-0.8794245:41.656837,1.444509:43.6039487,5.3744868:43.2950213,12.4942679:41.8905568,9.1881156:45.4636183,7.6830662:45.0683751,4.8343065:45.7673063?itineraryType=0&vehicleType=0&distUnit=m&avoidExpressWays=false&fuelConsump=6.200000:5.200000:5.500000&wCaravan=false&avoidORC=false&avoidCCZ=false&avoidBorders=false&avoidTolls=false&fuelCost=1.80000&withTraffic=false&currency=EUR&carCategory=4)
- [(16) Lille > Rouen > Rennes > Brest > Nantes > Niort > Bordeaux > Saint Sébastien > Madrid > Saragosse > Toulouse > Marseille > Rome > Milan > Turin > Lyon > Berne](vmm://itinerary_summary/3.057256:50.62925,1.0984642:49.4423985,-1.6802641:48.1117806,-4.487176:48.3898693,-1.5571805:47.2182641,-0.4575836:46.3238567,-0.5754952:44.8349955,-1.9845145:43.320905,-3.7003454:40.4166909,-0.8794245:41.656837,1.444509:43.6039487,5.3744868:43.2950213,12.4942679:41.8905568,9.1881156:45.4636183,7.6830662:45.0683751,4.8343065:45.7673063,7.4481304:46.9480024?itineraryType=0&vehicleType=0&distUnit=m&avoidExpressWays=false&fuelConsump=6.200000:5.200000:5.500000&wCaravan=false&avoidORC=false&avoidCCZ=false&avoidBorders=false&avoidTolls=false&fuelCost=1.80000&withTraffic=false&currency=EUR&carCategory=4)
- [(17) Lille > Rouen > Rennes > Brest > Nantes > Niort > Bordeaux > Saint Sébastien > Madrid > Saragosse > Toulouse > Marseille > Rome > Milan > Turin > Lyon > Berne > Dijon](vmm://itinerary_summary/3.057256:50.62925,1.0984642:49.4423985,-1.6802641:48.1117806,-4.487176:48.3898693,-1.5571805:47.2182641,-0.4575836:46.3238567,-0.5754952:44.8349955,-1.9845145:43.320905,-3.7003454:40.4166909,-0.8794245:41.656837,1.444509:43.6039487,5.3744868:43.2950213,12.4942679:41.8905568,9.1881156:45.4636183,7.6830662:45.0683751,4.8343065:45.7673063,7.4481304:46.9480024,5.0440412:47.3272124?itineraryType=0&vehicleType=0&distUnit=m&avoidExpressWays=false&fuelConsump=6.200000:5.200000:5.500000&wCaravan=false&avoidORC=false&avoidCCZ=false&avoidBorders=false&avoidTolls=false&fuelCost=1.80000&withTraffic=false&currency=EUR&carCategory=4)
- [(18) Lille > Rouen > Rennes > Brest > Nantes > Niort > Bordeaux > Saint Sébastien > Madrid > Saragosse > Toulouse > Marseille > Rome > Milan > Turin > Lyon > Berne > Dijon > Orléans](vmm://itinerary_summary/3.057256:50.62925,1.0984642:49.4423985,-1.6802641:48.1117806,-4.487176:48.3898693,-1.5571805:47.2182641,-0.4575836:46.3238567,-0.5754952:44.8349955,-1.9845145:43.320905,-3.7003454:40.4166909,-0.8794245:41.656837,1.444509:43.6039487,5.3744868:43.2950213,12.4942679:41.8905568,9.1881156:45.4636183,7.6830662:45.0683751,4.8343065:45.7673063,7.4481304:46.9480024,5.0440412:47.3272124,1.9039164:47.9013993?itineraryType=0&vehicleType=0&distUnit=m&avoidExpressWays=false&fuelConsump=6.200000:5.200000:5.500000&wCaravan=false&avoidORC=false&avoidCCZ=false&avoidBorders=false&avoidTolls=false&fuelCost=1.80000&withTraffic=false&currency=EUR&carCategory=4)
- [(19) Lille > Rouen > Rennes > Brest > Nantes > Niort > Bordeaux > Saint Sébastien > Madrid > Saragosse > Toulouse > Marseille > Rome > Milan > Turin > Lyon > Berne > Dijon > Orléans > Paris](vmm://itinerary_summary/3.057256:50.62925,1.0984642:49.4423985,-1.6802641:48.1117806,-4.487176:48.3898693,-1.5571805:47.2182641,-0.4575836:46.3238567,-0.5754952:44.8349955,-1.9845145:43.320905,-3.7003454:40.4166909,-0.8794245:41.656837,1.444509:43.6039487,5.3744868:43.2950213,12.4942679:41.8905568,9.1881156:45.4636183,7.6830662:45.0683751,4.8343065:45.7673063,7.4481304:46.9480024,5.0440412:47.3272124,1.9039164:47.9013993,2.3508487:48.856895?itineraryType=0&vehicleType=0&distUnit=m&avoidExpressWays=false&fuelConsump=6.200000:5.200000:5.500000&wCaravan=false&avoidORC=false&avoidCCZ=false&avoidBorders=false&avoidTolls=false&fuelCost=1.80000&withTraffic=false&currency=EUR&carCategory=4)


### Currencies
Each route is based on the following route, from `Madrid` to `Marseille` with no constraint.
- [EUR](vmm://itinerary_summary/-3.7003454:40.4166909,5.3744868:43.2950213?itineraryType=0&vehicleType=0&distUnit=m&avoidExpressWays=false&fuelConsump=6.200000:5.200000:5.500000&wCaravan=false&avoidORC=false&avoidCCZ=false&avoidBorders=false&avoidTolls=false&fuelCost=1.80000&withTraffic=false&currency=EUR&carCategory=4)
- [CHF](vmm://itinerary_summary/-3.7003454:40.4166909,5.3744868:43.2950213?itineraryType=0&vehicleType=0&distUnit=m&avoidExpressWays=false&fuelConsump=6.200000:5.200000:5.500000&wCaravan=false&avoidORC=false&avoidCCZ=false&avoidBorders=false&avoidTolls=false&fuelCost=1.80000&withTraffic=false&currency=CHF&carCategory=4)
- [CZK](vmm://itinerary_summary/-3.7003454:40.4166909,5.3744868:43.2950213?itineraryType=0&vehicleType=0&distUnit=m&avoidExpressWays=false&fuelConsump=6.200000:5.200000:5.500000&wCaravan=false&avoidORC=false&avoidCCZ=false&avoidBorders=false&avoidTolls=false&fuelCost=1.80000&withTraffic=false&currency=CZK&carCategory=4)
- [DKK](vmm://itinerary_summary/-3.7003454:40.4166909,5.3744868:43.2950213?itineraryType=0&vehicleType=0&distUnit=m&avoidExpressWays=false&fuelConsump=6.200000:5.200000:5.500000&wCaravan=false&avoidORC=false&avoidCCZ=false&avoidBorders=false&avoidTolls=false&fuelCost=1.80000&withTraffic=false&currency=DKK&carCategory=4)
- [GBP](vmm://itinerary_summary/-3.7003454:40.4166909,5.3744868:43.2950213?itineraryType=0&vehicleType=0&distUnit=m&avoidExpressWays=false&fuelConsump=6.200000:5.200000:5.500000&wCaravan=false&avoidORC=false&avoidCCZ=false&avoidBorders=false&avoidTolls=false&fuelCost=1.80000&withTraffic=false&currency=GBP&carCategory=4)
- [HUF](vmm://itinerary_summary/-3.7003454:40.4166909,5.3744868:43.2950213?itineraryType=0&vehicleType=0&distUnit=m&avoidExpressWays=false&fuelConsump=6.200000:5.200000:5.500000&wCaravan=false&avoidORC=false&avoidCCZ=false&avoidBorders=false&avoidTolls=false&fuelCost=1.80000&withTraffic=false&currency=HUF&carCategory=4)
- [NOK](vmm://itinerary_summary/-3.7003454:40.4166909,5.3744868:43.2950213?itineraryType=0&vehicleType=0&distUnit=m&avoidExpressWays=false&fuelConsump=6.200000:5.200000:5.500000&wCaravan=false&avoidORC=false&avoidCCZ=false&avoidBorders=false&avoidTolls=false&fuelCost=1.80000&withTraffic=false&currency=NOK&carCategory=4)
- [PLN](vmm://itinerary_summary/-3.7003454:40.4166909,5.3744868:43.2950213?itineraryType=0&vehicleType=0&distUnit=m&avoidExpressWays=false&fuelConsump=6.200000:5.200000:5.500000&wCaravan=false&avoidORC=false&avoidCCZ=false&avoidBorders=false&avoidTolls=false&fuelCost=1.80000&withTraffic=false&currency=PLN&carCategory=4)
- [SEK](vmm://itinerary_summary/-3.7003454:40.4166909,5.3744868:43.2950213?itineraryType=0&vehicleType=0&distUnit=m&avoidExpressWays=false&fuelConsump=6.200000:5.200000:5.500000&wCaravan=false&avoidORC=false&avoidCCZ=false&avoidBorders=false&avoidTolls=false&fuelCost=1.80000&withTraffic=false&currency=SEK&carCategory=4)
- [USD](vmm://itinerary_summary/-3.7003454:40.4166909,5.3744868:43.2950213?itineraryType=0&vehicleType=0&distUnit=m&avoidExpressWays=false&fuelConsump=6.200000:5.200000:5.500000&wCaravan=false&avoidORC=false&avoidCCZ=false&avoidBorders=false&avoidTolls=false&fuelCost=1.80000&withTraffic=false&currency=USD&carCategory=4)

## Some destination values

| City or address        | Longitude:Latitude    |
| ---------------------- | --------------------- |
| Bordeaux               | -0.5754952:44.8349955 |
| Brest                  | -4.487176:48.3898693  |
| Dijon                  | 5.0440412:47.3272124  |
| Lille                  | 3.057256:50.62925     |
| Lyon                   | 4.8343065:45.7673063  |
| Marseille              | 5.3744868:43.2950213  |
| Nantes                 | -1.5571805:47.2182641 |
| Niort                  | -0.4575836:46.3238567 |
| Orléans                | 1.9039164:47.9013993  |
| Paris                  | 2.3508487:48.856895   |
| Rennes                 | -1.6802641:48.1117806 |
| Rouen                  | 1.0984642:49.4423985  |
| Toulouse               | 1.444509:43.6039487   |
| Cologne (Allem.)       | 6.960279:50.937531    |
| Düsseldorf (Allem.)    | 6.7756691:51.224956   |
| Liège (Belg.)          | 5.579666:50.632557    |
| Mons (Belg.)           | 3.9487367:50.4533334  |
| Madrid (Esp.)          | -3.7003454:40.4166909 |
| Saint Sébastien (Esp.) | -1.9845145:43.320905  |
| Saragosse (Esp.)       | -0.8794245:41.656837  |
| Milan (Ita.)           | 9.1881156:45.4636183  |
| Rome (Ita.)            | 12.4942679:41.8905568 |
| Turin (Ita.)           | 7.6830662:45.0683751  |
| Berne (Suisse)         | 7.4481304:46.9480024  |

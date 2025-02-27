# UCC-Bikemap
GG6544_Cloud-Based GIS - QGIS - CA1+2

https://tbozzio.github.io/UCC-Bikemap/#

**Methodology:**

+ Development of the Mobile GIS survey :
  + This was created with QField - https://qfield.org/:
  + With 2 geographic features - 'BikeParking" layer as points, and "CycleLanes" layer as lines.
+ The following schemae describe the attributes & value maps for the 2 layers.
   + The base map (and schema) was created in QGIS - https://qgis.org/

```"CycleLanes" layer:

+ Description
  + Freetext
+ Photo
  + Image
+ Width in Metres
  + Integer
+ Road-facing Barrier (value map)
  + No
  + Yes - plastic pole
  + Yes - concrete lip
  + Yes - but damaged
+ Obstructed (value map)
  + No
  + Yes - roadworks
  + Yes - damaged
  + Yes - vehicle
  + Yes - street furniture
  + Yes - pedestrians
  + Yes - other
+ Closed (value map)
  + No
  + Yes - roadworks
  + Yes - damaged
  + Yes - other
+ Markings (value map)
  + None
  + Orange surface with white lines
  + Orange surface eroded
  + White lines only
  + White lines eroded
  + Markings obscured by dirt
+ Condition Overall (value map)
  + Good
  + Fair
  + Poor
  + Bad
+ Damaged (value map)
  + No
  + Yes - roadworks
  + Yes - potholes
  + Yes - other
+ Contraflow (value map)
  + Yes
  + No
+ Length in Metres
  + integer
+ Cleanliness (value map)
  + Clear
  + Muddy
  + Debris present


'BikeParking" layer

+ Sheltered (value map)
  + Yes
  + No
+ Number of berths
  + Integer
+ Berths occupied
  + Integer
```

+ There are photos for all of the "CycleLanes" layer's lines.

# UCC-Bikemap
**GG6544_Cloud-Based GIS - QGIS - CA1+2**

The map captures all of the (a) dedicated bike parking that I pass, and (b) bike paths that I cycle upon when
commuting to and from UCC.

https://tbozzio.github.io/UCC-Bikemap/#

**Methodology:**

+ Development of the Mobile GIS survey :
  + This was created with QField - https://qfield.org/:
  + With 2 geographic features - 'BikeParking" layer as points, and "CycleLanes" layer as lines.
+ The following schema describes the attributes & value maps for the 2 layers.
   + The base map (and schema) was created in QGIS - https://qgis.org/
   + There are photos for all of the "CycleLanes" layer's lines.

```
"CycleLanes" layer:

+ Description (text)
  + <Freetext description>
+ Photo (attachment)
  + <Image>
+ Width in Metres (integer)
  + <Integer Value>
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
+ Length in Metres (integer)
  + <Integer value>
+ Cleanliness (value map)
  + Clear
  + Muddy
  + Debris present


'BikeParking" layer

+ Sheltered (value map)
  + Yes
  + No
+ Number of berths (integer)
  + <Integer value>
+ Berths occupied (integer)
  + <Integer value>
```



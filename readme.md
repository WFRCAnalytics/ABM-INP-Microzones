microzones

uses:
-activity based model
-bike model
-remm?

Questions to ask:
- how will this be used for the ABM
- how will this be usded for REMM (ask Andy)
- does the zone make sense for the planning context in which its being used
- how will the socioeconomic data distribute into the zones
	- university employment
- How will the socioeconomic data aggregate into the microzones
- how will traffic within the zone access the road network


Rules of thumb:
- how many microzones per TAZ?
	- usually around 3-10 depending on TAZ side, how developed it is, and the land use mix
- the Outer boundaries of microzones should remain intact; they should not extend pass TAZ boundary where they lie
- keep the microzone shape simple, no donuts, limit extrusions

Environment:
- arcgis pro 
- github


What we need:
- taz are too coarse some applications
- create and maintain sub taz level geographic units
- aggregates up and forms taz boundaries
- other sub taz: census blocks, centers, parcels
- places to split
	- current & future land use
	- environmental constraints
	- centers types
	- taz boundaries
	- census blocks?
	- greenfield vs developed
	
What has been done:
- interactive activity with analytics group
- how they are broken depends on use case
-  using all streets network or census block didn't yield useful results land use wise
- zones based off street network, split by taz

Notes:
- there is no right or wrong answer at the moment. That fact that some thought is being put into them is enough for now
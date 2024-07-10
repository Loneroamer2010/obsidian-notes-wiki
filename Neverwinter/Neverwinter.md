```leaflet  
### Tutorial: [https://youtu.be/54EyMzJP5DU](https://youtu.be/54EyMzJP5DU)  
### id must be unique  
id: NeverwinterCityMap  
### Lock pins so they can't be moved  
lock: true  
### If true, view of map will recenter as you zoom out.  
recenter: true  
### If true, disables mouse scroll for zomming in and out of a map. Button controls still work.  
noScrollZoom: false
image: [[NeverwinterMap.png]]  
### Map Pixel Height x 1 / (Pixels between Bar Scale / 100)  
### Map Pixel Width x 1 / (Pixels between Bar Scale / 100)  
### Note that this formula requires adjustments depending on your map. The idea is to determine the number of units between your bar scale. We divide by 100 here because my bar scale measures in 100 units. If your maps scale bar measures in units of 50 them you should divide by 50 instead. The idea is to calculate how many pixels are equal to 1 unit.  
### Bounds is entered as [Height, Width]  
bounds: [[0,0], [2565.625, 3320.3125]]  
height: 550px  
width: 790px  
### This sets where the map starts by default. Set it to the middle (half) of your bounds.  
lat: 1282.8125
long: 1660.15625
### 0 is no zoom. Negative zoom steps away from the map. Positive zoom steps towards the map.  
minZoom: -2.3  
### Max zoom is 18.  
maxZoom: 0.5 
### Hover mouse over the Reset Zoom icon to see your current zoom level.  
defaultZoom: -1.8  
### How far it zooms in or out with each step. Can be in decimals.  
zoomDelta: 0.5  
### This is a string so can be any text. Change it to match your maps measurement scale.  
unit: miles  
scale: 1  
darkMode: false  
#marker: default, 1282.8125, 1660.15625
marker: Point of Interest,1361.0391345857852,905.6270100046706,Castle Never,,,
marker: Temple,1403.536256450934,1426.0576009579697,The House of Knowledge,,
marker: Temple,1104.8543779727602,736.487059313174,The Hall of Justice,,
marker: Tavern/Inn,1178.316111043189,410.1219330881975,The Moonstone Mask,,
marker: Point of Interest,2159.006925288194,181.01933598375615,Pirates’ Skyhold,,,
marker: Bridge,1355.0513743018657,1129.3986848915729,Dolphin Bridge,,-1,18
marker: Bridge,1231.4430322515566,1045.9269390811921,Winged Wyvern Bridge,,-1,18
marker: Bridge,1165.521897721095,866.9129137347072,Sleeping Dragon Bridge,,-1,18
marker: Point of Interest,410.39814667459854,237.58787847867995,Fisher’s Float,,,
marker: Tavern/Inn,1419.8704166225873,524.7257122218344,The Driftwood Tavern,,,
marker: Tavern/Inn,1401.424873322729,449.2531118736265,The Beached Leviathan,,,
marker: Shop,1046.390625,518,The Tarmalune Trade House,,,
marker: Temple,2134.2637122183933,1561.8221029457868,The Shard of the Moon,,,
marker: Point of Interest,1835.6561584472656,2545.1484375,Cloak Tower,,,
marker: Tavern/Inn,2009.3820039555887,1987.2048366826393,The Fallen Tower,,,
marker: Water,1268.969410099996,239.0020920410531,Bay of Mists,,,
marker: Water,1544.140625,2099.11328125,Neverwinter River,,,
marker: Point of Interest,1060.78125,2388,The Sealed Chasm,,,
marker: Point of Interest,785.390625,1731,Neverdeath,,,
marker: Temple,587.2024633298756,1582.107228731076,Neverdeath|Pauper's Section,,,
marker: Shop,1275.092482672472,2458.2898704254003,Brannur's Forge,,,
marker: Shop,1300.5483267951877,2480.2101806421833,Brannwyn's Sharp Edge,,,
marker: Shop,2046.92578125,1152.35546875,Priscilla’s Perfumes and Potables,,,
marker: Shop,1161.390625,2503,Swift Heart Sundries,,,
marker: Shop,916.8799515146472,2279.8558936103577,Arcane Acquisitions,,,
marker: Shop,750.4502171645917,1305.3191180703666,The Mute Lute,,,
marker: Shop,858.4442051756529,2763.2572911707393,Fuvont's Mounts and Tack,,,
marker: Point of Interest,1653.3261398487086,1298.8225745182153,Aleandius Manor,,,
marker: Temple,1664.8825073242188,1582.579345703125,Temple of Neverwinter,,-3,18
marker: Temple,2216.65625,2830.9453125,Camp of Silvanus,,-3,18

```
|Alt + Click to measure. Shift + Drag to select focus box.|

# Neverwinter
Neverwinter, the Jewel of the North, is a vibrant city encircled by a formidable wall. It is divided into five distinctive regions: The Docks, a bustling hub of commerce and trade; Bluelake District, known for its picturesque scenery and affluent residents; Chasm District, marked by a massive rift and filled with adventurers seeking its mysteries; Tower District, a blend of ancient structures and modern life; and Protector's Enclave, the heart of the city housing its government, main defences, and cultural landmarks.
# Locations of Neverwinter
### [[Arcane Acquisitions]]
An enchanting shop always glowing a shade of blue, green, or purple. This magical store sells wears that conjure the purest of magics.
### [[The Beached Leviathan|Beached Leviathan]]
Three-decked tavern that catered to sailors, smugglers, slavers, merchants, and others arriving by sea. Was built in and around the refurbished wreckage of a ship. The innkeeper is a sallow former pirate captain.
### [[Brannur's Forge]]
A cleanly smithing store selling armour.
### [[Brannwyn's Sharp Edge]]
A busy store cluttered with weapons and blades for sale.
### [[Castle Never|Castle Never]]
Castle Never stands as a monument to the city's former glory. Now it's a dangerous ruin, home for banshees and ghosts.
### [[Cloak Tower]]
Meeting place and citadel of the Many-Starred Cloak, a band of wizards.
### [[The Driftwood Tavern|Driftwood Tavern]]
Prices for room and board in this tavern are high. Home of the Graycloaks faction where they meet to discuss their plans.
### [[The Fallen Tower|Fallen Tower]]
One of the most popular taverns in Neverwinter. Deep cellars beneath the old circular tower. Was run by orcs in the past.
### [[Fisher’s Float]]
Home and workplace of fishers who have lived on this earthmote since the Spellplague. Fearless of the weather and the turbulent sea, they provide a great deal of food for the city.
### [[Fuvont's Mounts and Tack]]
A large stable smelling of all kinds of animals. 
### [[The Hall of Justice|Hall of Justice]]
Head temple of [[Gods of the Multiverse|Tyr]], located on a cliff overlooking the Sea of Swords, and one of the few buildings left almost untouched by the pyroclastic flow. Former seat of government since [[Lord Protector Neverember|Dagult Neverember]] arrived in the city.
### [[The House of Knowledge|House of Knowledge]]
A temple to [[Gods of the Multiverse|Oghma]] located at one end of the Dolphin Bridge.
### [[The Moonstone Mask|Moonstone Mask]]
Quiet inn of comfortable quality famous among sailors, it's also one of the most renowned festhalls (on the upper floor) in Neverwinter. [[The Moonstone Mask#The Mask’s Staff|Most of the staff are beautiful anonymous women with moonstone-adorned half-masks]]. A bridge between the earthmote and the docks allows visitors to enter and exit the Moonstone. The cellars of the Mask conceal a gate, but the destination reached by this magic still remains a mystery.
### [[The Mute Lute|Mute Lute]]
A charming little store in the Protector's Enclave. Beautiful music can be heard from outside, although the source cannot be found. Inside, all kinds of instruments can be found and restored.
### [[Neverdeath]]
The cruel mistress of the graveyard, called Neverdeath, is the sorceress Valindra Shadowmantle. After the cataclysm, visitors who breach Neverdeath walls came under attack from undead creatures that emerge from the ground.
### [[Pirates’ Skyhold]]
Once unassailable harbour for sky pirates in the years following the Spellplague, Pirates' Skyhold has long been abandoned.
### [[Priscilla’s Perfumes and Potables]]
A sweet smelling shop containing all kinds of cures and potions. 
### [[The Sealed Chasm|Sealed Chasm]]
After the eruption of Mount Hotenow in 1451, much of the southeastern quadrant of the city collapsed into a yawning pit, known as the Chasm, that continually spawned horrors. Neverwinter remained in ruins for decades, but thanks to [[Lord Protector Neverember|Lord Neverember]]'s efforts the city was repaired to its former glory and the Chasm has been sealed by powerful magic.
### [[The Shard of the Moon|Shard of the Moon]]
Bright tower of pristine white stone that rises high into the sky over Neverwinter. It is currently a temple for the [[Gods of the Multiverse|Mood Goddess, Selûne]].
### [[Swift Heart Sundries]]
A cosy little shop selling day-to-day items and toolkits.
### [[The Tarmalune Trade House|Tarmalune Trade House]]
Large warehouse complex next to the docks. The Tarmalune Trade House is a busy area where contacts gather, deals are made, and adventurers find their services in high demand.
### [[Temple of Neverwinter]]
The Temple of Neverwinter, a grand sanctuary that unifies diverse faiths under one roof, with twelve rooms dedicated to most deities, serves as a communal hub for worship, ceremonies, and community services.
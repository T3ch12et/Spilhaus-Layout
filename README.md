# Spilhaus One World Ocean Map
A map showcasing an unconventional yet stunning projection of the world's oceans, offering a refreshing and innovative perspective.

<img src="./Spilhaus_Layout_EmekaEmeche.jpg" img alt = "Spilhaus Layout"/>

## How It's Made:

**Tech used:** ArcGIS Pro

I got the appropriate dataset and the map opens up with a basic projection that is in black and gray colors in WGS84 coordinate system. The map has a cartoonish level of generalization which is done intentionally to show as much detail as possible without being too geographically detailed teh clutters and small-scale map. 

First off is to change the map projection to better show the story of what I am conveying. The point is to show the grand interconnectiveness of the ocean in a "Spilhaus World Ocean Map in a Square." I zoomed to the full extent of the map and double-clicked Map to open the Map Properties dialog box. In the Coordinate Systems tab, I types Spilhaus in the search field, and after going through a few options clicked the Spilhaus Ocean Map. After applying the settings, the result shows an unfamiliar look of the world. The projection that I selected, as well with all projections, distorts some geographic proerties and maintain other, depending on the purpose of the map. The Spilhaus projection presents the world's oceans as a singular, uninterrupted body of water-which they really are.

I then starting working on creating the layout that aims to visually prioritize oceans adn employ an attractive faded border to frame the ocean composition. In clicked the Insert tab on the ribbon and in the Project group, clicked the New Layout down arrow. At the bottom of the drop-down list, I chose the Custom Page Size. hen in the Layout Properties dialog box, changed the Page Units to Point. For Width and Height, I typed in 1000. The result is a new empty square layout like a fresh sheet of paper waiting for text and other map elements to be placed on it. To add the Spilhause map to the layout I went to teh Insert tab, in the Map Frames group, clicked the Map Frame down arrow and chose the thumbnail labeled Default Extent. I then dragged the sqaure on the layout that is smaller than the layout square. To remove the thin black border on the map frame, I went to the Properties by right-clicking the map frame. In the Element pane, I clicked the Display tab and under Border, changed the Symbol to 0 pt. I clciked teh Full Extent button to make the map be in full extent. I clciked the Map Frame twice and renamed it Center.

Even though the layout is a good starting point, there are just areas of the map that ends abruptly like the Gulf odf Mexico for example. I have to make four copies of the map and place them along the edges to have a repating pattern and no abrupt edges. I right-clicked the Center map frame and copied it and pasted the copy on an empty area which I then renamed the new map frame Right. I positioned the map frame to line up on the right side of the original map frame. I then rotated the Right map frame in the Propeties and in the General tab types in 90 for Rotation so that it aligns perfectly wit the Center map frame. The repeating mao frames match up along their edge so that geogrpahic area is continuous and uninterrupted. I then copied the RIght map frame and pasted it on the left side of the Center map frame renaming it Left so that the Gulf of Mexico and North America appear uninterrupted. I then copied the Left map frame and pasted it on the bottom of the layout under the Center map frame and renamed it Bottom. I followed the same steps as I did with the RIght map frame but instead did -90 on Rotation to reverse the rotation angle since it's on the bottom of the map. I copied the Bottom map frame and put the new map frame on the top of the Center map frame and renamed it Top.

Too make the map more appealing, I added a vignette overlay image to frame the ocean areas and provides a pleasant faded edge to help focus the eye of the map reader. I chose black overlay mask instead of the white since it feel like it adds more contrast. In the Insert tab, in the Graphics and Text group, I clciked the Picture button and went in the folder that held the picture data. I dragged the box over the layout to place the image and continually repositioned the image so that it's correctly placed.



## Lessons Learned:

No matter what your experience level, being an engineer means continuously learning. Every time you build something you always have those *whoa this is awesome* or *wow I actually did it!* moments. This is where you should share those moments! Recruiters and interviewers love to see that you're self-aware and passionate about growing.

## Repositories
**Profile:** [T3ch12et](https://github.com/T3ch12et)

**Cartography Repository:** [ESRI MOOC Cartography](https://github.com/T3ch12et/GIS-Data-Science-Portfolio/tree/main/ESRI-MOOC-Cartography)

**Main Repository:** [GIS Data Science Portfolio](https://github.com/T3ch12et/GIS-Data-Science-Portfolio)

## Examples:
Take a look at these couple examples that I have in my own portfolio:

**Oso Mudslide:** [Oso Mudslide](https://github.com/T3ch12et/GIS-Data-Science-Portfolio/tree/main/ESRI-MOOC-Cartography/Oso-Mudslide)

**Hurricanes since 1851:** [Hurricanes since 1851](https://github.com/T3ch12et/GIS-Data-Science-Portfolio/tree/main/ESRI-MOOC-Cartography/Hurricanes-since-1851) 

**Coral Reef Dashboard:** [Coral Reef Dashboard](https://github.com/T3ch12et/GIS-Data-Science-Portfolio/tree/main/ESRI-MOOC-GIS-for-Climate-Action/Coral-Reef-Dashboard)

**Rondonia Land Cover Change:** [Rondonia Land Cover Change from 1992 to 2020](https://github.com/T3ch12et/GIS-Data-Science-Portfolio/tree/main/ESRI-MOOC-GIS-for-Climate-Action/Rondonia-Land-Cover-Change)

**Addressing Climate Change:** [Using GIS to address climate change](https://github.com/T3ch12et/GIS-Data-Science-Portfolio/blob/main/ESRI-MOOC-GIS-for-Climate-Action/Addressing-Climate-Change/README.md)

**Shipping in 1770:** [World Shipping in 1770](https://github.com/T3ch12et/GIS-Data-Science-Portfolio/tree/main/ESRI-MOOC-Cartography/Shipping-in-1770)

**Ship Race from Spain to Puerto Rico:** [Ship Race: Spain to Puerto Rico](https://github.com/T3ch12et/GIS-Data-Science-Portfolio/tree/main/ESRI-MOOC-Cartography/Ship-Race-Spain-to-Puerto-Rico-1770)

**Map of Massachusetts:** [Map of Massachusetts](https://github.com/T3ch12et/GIS-Data-Science-Portfolio/tree/main/ESRI-MOOC-Cartography/Map-of-Massachusetts)

**Map of New York:** [Map of New York](https://github.com/T3ch12et/GIS-Data-Science-Portfolio/tree/main/ESRI-MOOC-Cartography/Map-of-New-York)

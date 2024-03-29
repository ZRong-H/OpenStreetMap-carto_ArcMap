# OSM-carto/ArcMap
An OpenStreetMap tool for ArcMap


We can utilize this Python script with arcpy library to redrawing OpenStreetMap in ArcMap with data download from OpenStreetMap offical.
  To use this tool, simply input the related paths within the script, import it into ArcMap, and execute it. This process will generate a map resembling OpenStreetMap. As the related paths, we need to input ten paths, that include: input polygon path, input line path, input point path, output polygon path, output line path, output point path, polygon's style path, line's style path, point's style path, output png's path.

You need to input the corresponding path at the location indicated in the image below：
![image](https://github.com/ZRong-H/OSM-carto-ArcMap/assets/105121100/3211c355-b12a-48f2-b150-a33373fec781)
![image](https://github.com/ZRong-H/OSM-carto-ArcMap/assets/105121100/b38aab0b-a87a-4edf-ad56-ffb1b2572c7b)
![image](https://github.com/ZRong-H/OSM-carto-ArcMap/assets/105121100/40397fed-6c95-4dfa-aa3c-8c50a361827b)
![image](https://github.com/ZRong-H/OSM-carto-ArcMap/assets/105121100/10113294-3e3f-4cee-bd25-e7a3a66b40da)

You can find the corresponding layer style's documents(.lyr) in this repository. After you input all of the paths, you can execute it, an wait just a few seconds, you will get a map resembling OpenStreetMap in ArcMap. 
However, this code may not completely restore the map to its original OpenStreetMap; sometimes, you may need to adjust the positions of the layers accordingly.

We can compare the results between OpenStreetMap and the redraw maps as follow:

## OpenStreetMap:<br>
![image](https://github.com/ZRong-H/OSM-carto-ArcMap/assets/105121100/68f5909d-db50-4b34-9253-2db6ec2a8669)

## redraw map:<br>
![2](https://github.com/ZRong-H/OSM-carto-ArcMap/assets/105121100/cbe91d74-827e-471f-a980-a27612c0d94b)

## OpenStreetMap:<br>

![image](https://github.com/ZRong-H/OSM-carto-ArcMap/assets/105121100/bf9560d8-e9bf-4de7-9402-3dd55e71aa15)

## redraw map:<br>

![1](https://github.com/ZRong-H/OSM-carto-ArcMap/assets/105121100/1f94f9d3-1d17-4e52-aea2-5e71d4e29941)

## OpenStreetMap:<br>

![image](https://github.com/ZRong-H/OSM-carto-ArcMap/assets/105121100/f4fe3432-82af-46bb-a386-dea500a7c489)

## redraw map:<br>
![3](https://github.com/ZRong-H/OSM-carto-ArcMap/assets/105121100/898ba126-928b-43f2-b7e3-dc2572544d60)

Just try it and use it in ArcMap!

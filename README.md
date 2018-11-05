# AssessmentPart1
Assessment part 1: Graphical User Interface vs. Command Line Interface
Two London open space accessibility maps has been generated and compared using both GUI (Graphical User Interface) based and CLI (Command Line Interface) based GIS software. In order to observe more legible differences, the same set of source data has been used in both maps.
GUI vs. GLI
The GUI software used here is ArcGIS. They use graphics as its main working element and both the mouse and keyboard as its primary input tools. It uses a large number of icons to identify commands, and through providing elements such as toolbar and dialog boxes to improve the intuitiveness, aesthetic and ease of use of the interface.
On the other hand, the CLI software used here is R, it mainly uses text as its working element, and keyboard as its primary input tool. The software sends commands to the computer by entering commands and parameters. The CLI operates just like a programming language, it essentially improves the efficiency of operations while doing repetitive tasks by simplifying the steps and providing batch processing options. We can save the commands as a script for future invocation or upload it to the internet so that anyone can copy and paste it directly.
In most cases, GUIs are easier to use than CLIs whereas CLIs are more efficient and has higher productivity than GUIs (Fellmann, T. and Kavakli, M., 2007). 
Using R requires users to remember all the commands and parameters that need to be used. Otherwise, they have to lookup in the manual, which requires higher skills. Conversely, ArcGIS users can find the commands they need from the hierarchy of menu. 
In addition, R users cannot do multiple tasks at the same time, only one command can be running at a time. For ArcGIS, different tasks can run at the same time, we can view the map, edit the distribution sheet and control the files at the same time. 
Data Sources
The shapefile document of London wards boundary used here was downloaded from UK data service. 
The data set used to produce the following maps are the same one (See Figure 1). The headers have been edited so that they do not have elements that ArcGIS cannot understand to avoid error. Also, the columns such as ward population has been hided since they are not essential to produce an accessibility map of open space. The four visible columns in the csv file are: Ward code, which was the most important one, used to match data with the ward code in shapefile; ward name, which includes every single ward in London; Borough name, and most important the Percentage of open space that are assessible. This data set was downloaded from London datastore.
Generated maps 
The maps produced using ArcGIS (see Figure 2) and R (see Figure 3) are quite different although same data was used. The title, legend and other elements in ArcGIS can be easily added to the map by clicking on graphics; the position, font and other features of them can be dragged and edited as well. In R, commands and parameters representing those elements needs to be typed, therefore, adding more elements makes the command much more complex. The color scheme in R has to be imported from color brewer before use, whereas ArcGIS has pre-set color schemes. The Legend for the R map has overlapped because the map tool installed in R automatically sets the background according to the map size, whereas in ArcGIS map layouts can be set easily.
 
References:

Fellmann, T. and Kavakli, M., 2007, March. A command line interface versus a graphical user interface in coding VR systems. In Proceedings of the Second IASTED International Conference on Human Computer Interaction. ACTA Press.


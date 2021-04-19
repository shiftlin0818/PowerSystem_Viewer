# PowerSystem_Viewer

Welcome to feed back issues and give suggestions in Issues.

This program is academic purpose tool for power system visualization.

How to use

Download and unzip the files.

1. Load in the case from: file->open

Note: Currently,  support the matpower case format / PSSE33 (except 3 windings transfrormer and DC line)


2. Choose a bus number and the number of tiers wanted to be viewed


3. Click search

   The one-line diagram of the sub-area will be displayed in the left side. 
   The network will be autolayout. If you do not satisfy the bus location, for example, it leads to lines cross, you can move the bus with mouse easily.
   
   
![image](https://github.com/shiftlin0818/PowerSystem_Viewer/blob/main/fig/demo.PNG)


Update log:

2021-03-22
  
      Beta version: 
      load matpower case, 
      show data in the table, 
      search sub-area, 
      display the one-line diagram, 
      auto layout one-line diagram
      calculate the power on the branch and transformer
 
2021-03-33
      fix the bug: 
           
           Can not refresh the data when load new case
 
 To do:
   click the bus, show the related inforamtion on the right side panel

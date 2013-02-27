**2/22-2/28**
This week we picked up the 3D Printer Kit from the IEEE representitive and began the assembly process. Some of the parts aren't printed yet, and since it takes about a week for them to finish, we were only able to assemble half of the printer. However, we were able to find a 3D-Printer simulation that takes Gcode and shows how the 3D printer would respond. This will be helpful because it will allow for much faster testing and will provide an interesting visual for our interim demo.

We also continued to work on the Scanning, Reconstruction and Conversion algorithms. We have written significant amount of our report on the methodology behind these three modules and will continue to work on the code in the coming weeks.

**2/15 - 2/21**
This week we found a comprehensive resource on how to correctly cut the reconstructed object into layers and describe the best path for the printer to take to recreate it. This program, Slic3r, takes in an STL format file, cuts it up into the appropriate layers, and then runs an algorithm to find the best way to fill in the empty space, including figuring out where certain areas need better support. We are going to base our algorithms off of the ones used in this code because it was one of the best implementations of a Gcode converter that we were able to find. 

Work was also done on the programs visual side, in which we added the buttons to control scanning and sliders to manipulate the settings such as depth for the kinect when scanning. Stylizing took a majority of the time with the layout as we wanted to make our application have a Windows 8 Metro theme. Each component is designed to reflect the style choices that are displayed on the Kinect for Windows website (www.microsoft.com/en-us/kinectforwindows/) and some which we determined reflected the style we wanted. We also began to look into the modelviewer simulation tools in order to reproduce the scanned object before wasting materials testing the output of our work.

**2/7 - 2/14**
This week we continued to do research into what type of applications will be required to complete our 3D reconstruction. We began by determining whether to work with C++ or C# to make our programs interface, and ultimately came to the decision to work with C# because of its superior visual tools while still having the necessary compatibility with kinect for our task. There are also some third party programs that offer reconstruction using kinect systems that we have looked into such as PCL, KinectFusion, and ReconstructMe which we are looking into utilizing portions of for our project.

We have determined that a web based gcode viewer will be used to see if our gcode compiler is working properly. We began working on the gcode converter, a lot of time was spent getting used to the syntax of c#. Once we get the framework for this module setup we began looking at the shortest path type algorithms needed to convert the 3D point cloud to the layer by layer construction of the final object.

IEEE Xplore is also being used to find research papers relevant to our project so that we can take advantage of work that has already been done. 

**1/31 - 2/7**
The main accomplishment for our first week was laying out a timeline to guide and gauge our progress through the following weeks of the project. We also established the structure of the project by creaing repositories in Git to establish the various modules of the project (https://github.com/KinectReplicator).  

We also began research on which programming language we would like to work with and how other people developed applications with the Kinect. We are deciding between C++ or C#.

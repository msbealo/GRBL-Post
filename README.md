# GRBL-Post
A post processor for CAMWorks / SolidWorks CAM for GRBL (https://github.com/grbl/grbl)

This is developed using Universal Post Generator (UPG-2) utility available from 
https://camworks.com/universal-post-generator/

It is intended to be used with GRBL CNC Routers, but with modification it could be used with other GRBL controllers.

Specifically I'm using it on a RS-CNC32 (https://www.makerfr.com/en/cnc/rs-cnc32/), similar to a Carbide 3D Shapeoko or OPENBUILDS WORKBEE.

To use, direct SolidWorks CAM or CAMWorks to the post processor in the Machine - Post Processor setup of the CAMWorks NC Manager.

To edit, open in UPG-2 and/or EC Edit-2 (on Windows)

To compile, open in UPG-2 and hit compile. The .ctl file will be deposited in the C:\CAMWorksData\UPG-2\ctl\ folder.

To test, I connect to my GRBL controller using UGS (https://winder.github.io/ugs_website/). While I don't use this method for normal operation, it's good to run test files to see GRBL's response. 

This is work in progress and might not work as you intend. Please test before walking away from your machine. 

Useful Post information:
https://wiki.shapeoko.com/index.php/G-Code#Post_Processors

This project has drawn inspiration from:
http://www.restrictedayerspace.net/cnc/grbl-postprocessor-for-solidworks/
https://github.com/gnea/grbl/issues/237
https://hawkridgesys.com/products/cam/post-processors/carbide-3d-shapeoko

However, none of these posts did what I needed or outputted gcode that my grbl controller could work with.

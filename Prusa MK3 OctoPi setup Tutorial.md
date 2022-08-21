<!-- <p align="center"> <img src="images/" alt="" width="" height=""/> </p> -->

# Guide to turning your 3D printer to a wireless printer

This tutorial will walk through the process of turning your printer into a wireless printer using a Raspberry Pi. This tutiral is for people of all knowledge levels. You can follow the tutorial regardless if you have the same printer and Raspberry Pi. Just try to have fun and keep it neat!

### Technical Requirements:

#### Links can be found in the resources section at the end of the article

- Raspberry Pi model 3B(you can use other versions of the Raspberry Pi with modifications for the case).
- 32 or 64 GB Micro SD-Card (this tutorial uses 64 GB).
- Camera module with at least 1m long flex ribbon cable.
- USB type-A to USB type-B cable.
- M3 x 12mm/16mm/20mm screws.
- Computer or laptop.
- 3D printer (this tutorial uses a Prusa MK3S).
- Access to your router.
> #### Everything you will need:
> 
> <p align="center"> <img src="images/Everything_Needed.png" alt="Everything you will need" width="750"/> </p>
>
## Steps:
> ### Step 1 (Print Needed Parts):
>> - [Download](https://github.com/amrodewedar/3D-printing/blob/main/OctoPi_Full.3mf) the file for the Raspberry Pi enclosure, camera enclosure, and camera arm.<br/>
>> - Make sure the enclosures and arm will fit your equipment before wasting precious fillament.<br/>
>> - Slice and print the parts according to your prefrences (links in the resources section contain the thingiverse 3D design model parts).
>> - Depending on your camera position prefrence, you might want to print more links. With 5 links, the camera can be positioned in-front of the print bed. Keep in mind the more links you print the shakier the camera will be.
>> 
>> <p align="center"> <img src="images/All_parts_to_print.png" alt="Parts to print" width="750"/> </p>
>>
>> .
> ### Step 2 (Arm & Camera Mount Assembly):
>> - Start by assembling the joints together using nuts and M3x20mm screws.
>> - The joints have designated holes for the screws and nuts, so make sure you are inserting them in the correct holes.
>> 
>> <p align="center"> <img src="images/Joints_screws_with_circles.png" alt="Linking the joints" width="600"><p/>
>>
>> - Next connect the arm mount to the rest of the links as such:
>> 
>> <p align="center"> <img src="images/Joints_and_arm_mount_close_up.png" alt="Arm with mount connected" width="700"/> </p>
>> 
>> - Ensure that the last link (the one that will hold the camera enclosure) has the flat side up as shown in the picture above.
>> - Now connect the camera enclosure holder and camera enclosure to the rest of the assembly.
>> 
>> <p align="center"> <img src="images/Joints_camera_and_arm_mount.png" alt="Joints with mount and camera enclosure" width="700" height="650"/> </p>
>> 
>> - The camera enclosure holder also has a nut hole but it is more difficult to place the nut in there, I used the hex-key that comes with the Prusa printer to put the nut in place. Also for the camera enclosure you can use a M3x16mm screw or ideally a M3x14mm screw.
>> - Now you can mount the arm to the Z-axis motor of the printer using a M3x20mm screw:
>> 
>> <p align="center"> <img src="images/jont_mount_screw.png" alt="Mount to Z-axis"/> </p> 
>>
>> Lastly zip-tie the Z-axis motor cable to the mount as such(disregard the ribbon cable for now): 
>> 
>> <p align="center"> <img src="images/joint_mounted_ziptie_circled.png" alt="Zip-tie the cable.png"/> </p>
>>
> ### Step 3 (Raspberry Pi Assembly & Mount):
>> - First, place the heatsinks on the Processor and the LAN chips: 
>> 
>> <p align="center"> <img src="images/Heat_Sinks_on_Pi.png" alt="heatsinks placement"/> </p>
>> 
>> - Place Pi in Case, releae the cable lock on the camera port by gently pulling on both sides of the black clip. Then connect the ribbon cable to the camera port so the contacts of the cable are touching the contacts of the Pi port:
>> 
>> <p align="center"> <img src="images/Ribbon_cable_into_pi.png" alt="Ribbon cable to Pi"/> <img src="images/Ribbon_cable_into_pi_closeup.png" alt="Ribbon Cable to Pi Closeup" width="450" height="480"/> </p>
>>
>> - Secure the cable in place by pushing on both sides of the port lock.
>> 
>> <p align="center"> <img src="images/Ribbon_cable_into_pi_clickin_circles.png" alt="Securing the cable"/> </p>
>> 
>> - Now pass the other end of the cable through the other side of the case and secure the case using 4 M3x16mm screws:
>> 
>> <p align="center"> <img src="images/Case_asembly.png" alt="Passing cable through case" width="500"/> <img src="images/Securing_case.png" alt="Securing the case" width="400" height="500"/> </p>
>> 
>> - Now mount the case to the printer using two M3x12 screws.
>> 
>> <p align="center"> <img src="images/PiCase_mount_closeup.png" alt="Mounting Pi Case" width="550" height="680"/> </p>
>> 
>> - Lastly, pass the the ribbon cable to the camera enclosure, connect the camera(through the slit in the camera enclosure), and clip the slack of the wire to the arm using the clips printed.
>> 
>> <p align="center"> <img src="images/joint_mounted_cable_passed_to_cameraCase.png" alt="Passing the cable" width="550"/> <img src="images/connecting_camera.png" alt="Connecting the camera module" width="350" height="450"/> <img src="images/Complete_assembly.png" alt="Complete setup"/> </p>
>> 
>> #### Some things to keep in mind:
>>> - If you own a different printer find a case that will mount nicely on it. 
>>> - You could pass the ribbon cable through the Prusa Ensiy compartment (the metal compartment near the Z-axis motor). But be careful as you could short the Ensiy board if you use a metal probe to fish the ribbon cable at the other side. I reccomend using a piece of filament.
>>> - If you have a different camera module or you are using a usb camera, plan for that and try to find or design the appropriate parts.
>>> 
> ### Step 4 (Installing Raspberry Pi Imager):
>> First, [download](https://www.raspberrypi.com/software/) and install the Raspberry Pi imager.
>> You should see the following after installing the imager and opening it:
>> 
>> ![imager installed](images/imager_after_installation.png)
>> 
>> .
>> 
> ### Step 4 (Install OctoPi Operating System on the Micro SD-Card):
>> blah long step
> ### Step 5 (Connect to OctoPi and Setup):
>> blah blah 
> ### Step 6 (Add Plugins):
>> blah blah
>
>

## Resources:

- [Raspberry Pi model 3B](https://www.amazon.com/ELEMENT-Element14-Raspberry-Pi-Motherboard/dp/B07P4LSDYV/ref=sr_1_3?keywords=raspberry+pi+3b&qid=1660928794&sr=8-3)
- [64 GB Micro SD-Card](https://www.amazon.com/SanDisk-Ultra-microSDHC-Memory-Adapter/dp/B08GYBBBBH/ref=sr_1_3?crid=12FLPZJBR95S2&keywords=64+gb+micro+sd+card&qid=1660928910&sprefix=64+gb+micro+sd+card%2Caps%2C114&sr=8-3)
- [Pi Camera with a extended cable](https://www.amazon.com/gp/product/B07SN8HB1R/ref=crt_ewc_title_oth_2?ie=UTF8&smid=A2IAB2RW3LLT8D&th=1)
- [USB A/B cable](https://www.amazon.com/gp/product/B000067RMY/ref=crt_ewc_title_oth_3?ie=UTF8&psc=1&smid=ATVPDKIKX0DER)
- [Box of M3 screws of various lengths](https://www.amazon.com/binifiMux-360pcs-Countersunk-Phillips-Machine/dp/B08N5XDHMW/ref=sr_1_5?crid=3LE01UJH45QOO&keywords=M3+x+16+and+M3+x+12+screws&qid=1660322970&s=industrial&sprefix=m3+x+16+and+m3+x+12+screws%2Cindustrial%2C72&sr=1-5)
- [Website to download Raspberry Pi Imager](https://www.raspberrypi.com/software/)
- [Video tutorial of OctoPi and plugins installation](https://www.youtube.com/watch?v=HBd0olxI-No)
- [Video tutorial of camera and arm installation](https://www.youtube.com/watch?v=iFhVSmMzOLg&t=960s)
- [Raspberry Pi case model](https://www.thingiverse.com/thing:3004038)
- [Camera case and arm model](https://www.thingiverse.com/thing:4631375/files)
- [Pimp your printer with extruder visualizers](https://www.thingiverse.com/search?q=prusa+extruder+visualizer&page=1&type=things&sort=relevant)

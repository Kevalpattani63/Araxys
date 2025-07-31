
## Project Name: Araxys CNC Mill
### Total Time Spent: 34.5 hours 
### Author: Keval

---
 ## July 23rd -> 4.5
the project finally took off. I had been thinking about building my own CNC for a while, but that day I finally opened Fusion 360 and got serious. I spent about 4.5 hours sketching the basic frame, trying to figure out what kind of working area would be realistic for my desk and budget. I kept it to a compact footprint but aimed for a usable cutting area that could handle PCBs and small aluminium parts. I kept checking measurements and adjusting the spacing of the linear rails and the gantry system. The Y-axis travel gave me a bit of a headache because I didn’t want the spindle to crash into the front plate. I kept rotating the model in Fusion from every angle and finally settled on a frame size that felt balanced. I designed the base to use 2040 extrusions for better stiffness and added placeholders for the linear guides.

<img width="623" height="518" alt="image" src="https://github.com/user-attachments/assets/eeb67890-6e16-4628-93f0-aade7625a2d2" />


<img width="1015" height="712" alt="image" src="https://github.com/user-attachments/assets/2e5cce70-bc08-420a-9136-089a82913e61" />


## July 24th -> 3 
I focused entirely on the Z-axis. For almost 3 hours, I iterated over different designs to make it strong but not too heavy. I chose a lead screw drive for this axis since I wanted more precision and less backlash. The hardest part was designing the mount for the stepper motor so that it lined up properly with the lead screw. I also made a custom spindle holder that would bolt directly to the Z plate and sit flush without interfering with the linear guide blocks. It was so tempting to copy existing mounts online but I forced myself to make my own just to learn. The Z-axis is always the trickiest part of any CNC and now I understand why.


<img width="410" height="736" alt="image" src="https://github.com/user-attachments/assets/c9c72f5c-fd00-4324-b1a5-4cdeab421207" />


<img width="400" height="666" alt="image" src="https://github.com/user-attachments/assets/41001ac0-b4d4-476e-87be-b25c432ff069" />

July 25th -> 2
I worked for about 2 hours modeling the X and Y axes in more detail. I added the linear rails, MGN12 style, onto the 2020 extrusions and designed the mounting plates that would hold the bearings and belt idlers. It took a lot of small tweaks to make sure everything would align in the real world. I kept visualizing the stepper motor locations, cable paths, and belt tensioning spots. At one point I even made a test assembly of the gantry in Fusion to simulate movement. I was finally feeling confident that the mechanics were going to work.


<img width="659" height="861" alt="image" src="https://github.com/user-attachments/assets/1dc31986-98bc-4b34-8788-07c687ee2d4e" />


<img width="517" height="660" alt="image" src="https://github.com/user-attachments/assets/d1e5e6a7-a1b1-453b-8b84-b4cedb02c418" />




## July 26th -> 3.5
the electronics side took over. I spent 3.5 hours figuring out how to set up the control system. I decided to go with an Arduino Uno and a CNC shield because it’s super well-supported and works great with GRBL. I started planning where the drivers would go and how I’d route all the wires without clutter. I also watched a couple of YouTube videos to understand how people wire in endstops, spindle relays, and fan controls. I drew out a full wiring diagram on paper just to get my head straight. There’s something really satisfying about laying out the electronics and imagining the data and current flowing through the machine.

<img width="1221" height="792" alt="image" src="https://github.com/user-attachments/assets/c4cf8916-aa06-473e-a64c-ef592e98acbb" />


referred video: https://www.youtube.com/watch?v=Xlkmso01vUk&t=1s




## July 27th -> 5
I went back into Fusion 360 and spent almost 5 hours working on refining the overall model. I adjusted the spindle mount design to accommodate a slightly different clamp position and added more detailed cutouts for cable pass-throughs. I also redesigned the front gantry plate to allow easier tool access and made room for better belt tensioning. While I was initially planning to source parts this day, I decided to finalise every critical mechanical part before committing to the BOM. The virtual model started looking more functional, and I made a rendering to help me visualise the final build.

<img width="152" height="303" alt="image" src="https://github.com/user-attachments/assets/9020199d-37c8-4fc6-827a-cd5a277d31bc" />



<img width="301" height="434" alt="image" src="https://github.com/user-attachments/assets/80371910-86a4-4a13-87db-166212b97d54" />



## July 28th -> 4
the building finally began. I spent 4 hours doing a dry fit of the frame. The extrusions arrived first, along with the MDF base plate and linear rails. I drilled holes in the MDF for mounting the Y-axis rails and temporarily fastened the profiles with corner brackets. Everything aligned pretty nicely, which was a huge relief. I manually pushed the gantry back and forth and it glided smoothly on the rails. The base was surprisingly rigid and I was genuinely proud of how square everything felt.


<img width="788" height="695" alt="image" src="https://github.com/user-attachments/assets/d2a34cca-a3b9-4f5e-bd20-605ab2b8e9f5" />





## July 29th -> 3
I didn’t test anything physically but instead focused entirely on refining the CAD model. I spent around 3 hours designing better mounts for the stepper motors and spindle holder. I reworked the wire routing paths and created detailed sketches for each axis assembly. Most of my time went into ensuring that every screw hole was in the right place and that I wouldn’t need to drill anything manually later. I also started making renderings for documentation.


<img width="784" height="537" alt="image" src="https://github.com/user-attachments/assets/93d1512e-2bf7-4e66-89b4-6923f5555929" />

<img width="297" height="311" alt="image" src="https://github.com/user-attachments/assets/8e48f0ec-68f3-406c-9f6e-c471001072af" />


## July 30th -> 4.5
I continued working in Fusion 360 and spent another 4.5 hours doing CAD work.  The entire virtual model was slowly turning into something that could be built with real parts, and every detail I added made me more confident that this build would be smooth once all parts arrived.


<img width="429" height="627" alt="image" src="https://github.com/user-attachments/assets/c5f1ff2a-0cc9-4664-a63d-bafee9a1de86" />


## July 31st -> 5
I had a long CAD session again, for about 5 hours. I designed a small control panel that includes a reset button, spindle switch, and USB breakout. I also laid out all components in a top-down assembly view to make sure everything would fit inside the build area. I adjusted clearances and simulated all axis travel in Fusion. At this point, the design is basically final and I’m ready to start assembling again once I get the remaining parts. No physical tests yet, but mentally everything is coming together.

<img width="773" height="580" alt="image" src="https://github.com/user-attachments/assets/2fa9622b-be77-4f17-8af9-660caa35ccfe" />


<img width="817" height="635" alt="image" src="https://github.com/user-attachments/assets/cdb694dc-62d2-4fab-9a25-b8e1ea63c1d7" />


Right now Araxys is fully designed and almost ready for the next build phase. I just need to wait for some final parts to arrive and then I can start assembling again. This machine already feels like something I can use daily for PCB prototyping, engraving and light aluminium work. From a simple Fusion sketch to a full CAD assembly, this journey has been over 34.5 hours of pure learning, problem solving and designing. Honestly, there’s no better feeling than seeing a machine come to life inside your head first, even before it touches the workbench. Araxys is just getting started.


<img width="726" height="512" alt="image" src="https://github.com/user-attachments/assets/ddf602d1-22e5-4766-8c07-ccf95f2754bc" />


<img width="656" height="556" alt="image" src="https://github.com/user-attachments/assets/93ad0669-1e32-4c2c-8d69-57ea46e92e9d" />


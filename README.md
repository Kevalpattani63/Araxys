## Araxys CNC Mill
Made by Keval

After days of scrolling through PCB designs and watching makers across India bring their dream machines to life, I finally decided that it was time I built something with real motion and muscle. That’s how the idea for Araxys CNC Mill was born. I wanted a compact, desktop friendly CNC milling machine that wasn’t just another clone of a Chinese design but something that felt personal, engineered, and optimized for our Indian maker ecosystem.


I began the journey with Fusion 360, slowly building up the frame piece by piece, testing different linear rail placements, and fine-tuning how each axis would move. I didn’t want to rely too much on expensive parts or anything that required international shipping hassles. The design is based on solid aluminium extrusions with linear guides, a NEMA 17 driven Z-axis, and a moderately powerful spindle motor that should be more than enough for PCB engraving, light aluminium cutting, and definitely wood and acrylic work. The motion system uses GT2 belts for X and Y, and a lead screw for Z, which keeps it compact while still decently accurate. I kept the base broad and flat to avoid any unnecessary vibration when milling harder materials.

The final design took several nights of tweaking, especially to get the Z-axis rigid enough while still being light. I added a proper mounting system for the spindle and made sure wiring channels were clean and not clumsy. Everything in the design is modular, so in the future, I can upgrade the stepper drivers, maybe switch to ball screws, or even mount a laser. For now though, it is exactly how I imagined—a well-balanced machine that can handle serious tasks without blowing my entire budget.


<img width="479" height="502" alt="image" src="https://github.com/user-attachments/assets/73db2881-2269-4d71-b76d-f8b77a926814" />





I kept every part source India-friendly, from the aluminium profiles and screws to the spindle and controller. No Robu.in or AliExpress, because I know how annoying customs and shipping can get. Araxys was made keeping affordability and practicality in mind, while still not compromising on quality. The cost came under 350 USD which is pretty tight for a CNC machine, especially with a rigid metal frame.



<img width="570" height="539" alt="image" src="https://github.com/user-attachments/assets/047ab0cc-5df1-491f-a073-be4c9ba33f2c" />






To build Araxys, I sourced aluminium 2020 and 2040 extrusion profiles for the main structure and gantry arms, which cost around 62 USD or ₹5200. The motion system includes three NEMA 17 stepper motors priced at about 21 USD or ₹1800 total, combined with GT2 timing pulleys, belts, and idlers for another 10 USD or ₹850. The Z-axis lead screw and nut assembly came for around 8 USD or ₹680. For the spindle, I chose a 500W brushed DC spindle with ER11 chuck, which cost about 43 USD or ₹3600, along with the spindle mount and power supply unit for another 18 USD or ₹1500. The CNC shield, A4988 stepper drivers, and Arduino Uno controller setup was around 16 USD or ₹1350. I added limit switches, couplers, wiring, and connectors, which summed up to approximately 11 USD or ₹930. The MDF base plate, 3D printed mounts, and extra fasteners and brackets added about 17 USD or ₹1400 to the total. Including a decent quality 24V power supply and USB cable for control, I managed to keep the full build just under 340 USD, which translates to roughly ₹28,000 INR at current exchange rates.

Every part is carefully selected to be easy to replace, upgrade, or fix without needing exotic tools or suppliers. Araxys is not just a project, it’s a platform that I can keep building on :)



## BOM

| **Component**         | **Description**                                | **Qty** | **Price (USD)** | **Price (INR)** | **Supplier**       |
| --------------------- | ---------------------------------------------- | ------- | --------------- | --------------- | ------------------ |
| Aluminium Extrusions  | 2020 and 2040 profiles for frame and gantry    | 1 set   | \$62.00         | ₹5200           | 3D Printronics     |
| Stepper Motors        | NEMA 17 motors for X, Y, Z axes                | 3       | \$21.00         | ₹1800           | Robocraze          |
| GT2 Belts and Pulleys | Includes pulleys, belts, idlers                | 1 set   | \$10.00         | ₹850            | Amazon             |
| Z-Axis Lead Screw     | Trapezoidal screw + brass nut                  | 1       | \$8.00          | ₹680            | Amazon             |
| Spindle Motor         | 500W spindle with ER11 chuck                   | 1       | \$43.00         | ₹3600           | Ampere Electronics |
| Spindle Mount + PSU   | Aluminium holder and 48V PSU                   | 1 set   | \$18.00         | ₹1500           | Robokits           |
| Control Electronics   | Arduino Uno + CNC Shield + 3x A4988            | 1 set   | \$16.00         | ₹1350           | Robocraze          |
| Wiring and Switches   | Endstops, wires, terminals, connectors         | 1 set   | \$11.00         | ₹930            | Amazon             |
| MDF Base + Fasteners  | Base board, T-nuts, brackets, 3D printed parts | 1 set   | \$7.75          | ₹679            | Papericious.in     |
| 24V Power Supply      | For controller and communication               | 1       | \$11.00         | ₹940            | Robocraze          |
| **Total**             |                                                |         | **\$199.80**    | **₹17,529**     |                    |



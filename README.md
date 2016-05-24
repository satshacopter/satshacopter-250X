<h1 style="font-family: courier;" align="center">satshacopter 250X</h1>
<p align="center">
<img src="media/250X_0.jpg" width="70%">
<div align="center"><i>An open source, low cost and fabbable quad X drone.</i></div>
</p>  

satshacopter 250X
--

satshacopter 250X is a quadcopter built around the **[satshakit flight controller](https://github.com/satshakit/satshakit-flight-controller)**. It is designed to be simple and cheap as much as possible, and to be easily made inside any Fab Lab.

250X specifications:

- 250mm wooden frame and supports
- open source flight controller
- MPU6050 IMU located exactly at the center
- 4 x 1900kv brushless motors
- 4 x 15A ESCs
- MultiWii compatible
- 4 channel Hobby King remote and receiver
- 1000mah 3S LiPo battery 
- costs under 100€

Here you can look about the **MultiWii pin mapping** of the satshakit flight controller board:

<img src="media/satshakit_fc_power_pin_mapping.PNG" width="70%">

And here you can che the required components in the **Bill of Material** table:

|name|description|vendor|link|price|notes|
|:---:| :---:|:---:|:---:|:---:|:---:|
|2.4Ghz4Ch TxRx V2|4ch mode 2 remote control and receiver|Hobby King|[link](http://www.hobbyking.com/hobbyking/store/__66499__Hobby_King_2_4Ghz_4Ch_Tx_Rx_V2_Mode_2_EU_Warehouse_.html)|€23.14|-|
|Zippy Compact|battery 1000mah 3s|Hobby King|[link](http://www.hobbyking.com/hobbyking/store/__36064__ZIPPY_Compact_1000mAh_3S_25C_Lipo_Pack_EU_Warehouse_.html)|€5.55|-|
|LDPOWER D250-2 Multicopter Power System|4 x 2206-1900kv motors and 4 x 15A esc|Hobby King EU|[link](http://www.hobbyking.com/hobbyking/store/__84723__LDPOWER_D250_2_Multicopter_Power_System_2206_1900kv_6_x_3_4_Pack_EU_Warehouse_.html)|€43.81|propellers Included|
|IMU 6DOF|MPU6050 Gyro + Acc IMU|Ebay|[link](http://www.ebay.de/itm/MPU-6050-GY-521-3-Achsen-Gyroskop-Accelerometer-Kreisel-Board-Sensor-Arduino-21-/121887579651)|€5.39|-|
|LiPo Charger and Balancer|800mah 3s LiPo charger|Hobby King|[link](http://www.hobbyking.com/hobbyking/store/uh_viewitem.asp?idproduct=77525)|€6.99|-|
|Fligh Controller|satshakit flight controller|various|[link](https://github.com/satshakit/satshakit-flight-controller)|€4.00-€8.00|depending on the quantity|
|Voltage regulator|Pololu step up step down 5V S7V7F5|E-shop|[link](https://www.flikto.de/products/pololu-5v-step-up-step-down-voltage-regulator-s7vf5)|€4.31|-|
||||**Total price**|89.19+4/8|-|

NOTE: prices may change over time on the respective vendors, and also is dependand on the quantity of drones you want to make.

Downloads
--

- [satshakit flight controller eagle board](https://raw.githubusercontent.com/satshacopter/satshacopter-250X/master/eagle_projects/satshakit_flight_controller/satshakit_fc_power.brd)
- [satshakit flight controller eagle sch](https://raw.githubusercontent.com/satshacopter/satshacopter-250X/master/eagle_projects/satshakit_flight_controller/satshakit_fc_power.sch)
- [satshakit flight controller internal traces png](https://raw.githubusercontent.com/satshacopter/satshacopter-250X/master/media/satshakit_fc_power_internal.png)
- [satshakit flight controller holes png](https://raw.githubusercontent.com/satshacopter/satshacopter-250X/master/media/satshakit_fc_power_holes.png)
- [satshakit flight controller cut png](https://raw.githubusercontent.com/satshacopter/satshacopter-250X/master/media/satshakit_fc_power_cut.png)
- [main frame and supports Rhino](https://github.com/satshacopter/satshacopter-250X/raw/master/design_files/main_frame_and_supports_8mm.3dm)
- [main frame and supports dxf](https://github.com/satshacopter/satshacopter-250X/raw/master/design_files/main_frame_and_supports_8mm.dxf)
- [upper frame and supports Rhino](https://github.com/satshacopter/satshacopter-250X/raw/master/design_files/upper_frame_4mm.3dm)
- [upper frame and supports dxf](https://raw.githubusercontent.com/satshacopter/satshacopter-250X/master/design_files/upper_frame_4mm.dxf)
- [foot Rhino](https://github.com/satshacopter/satshacopter-250X/raw/master/design_files/foot.3dm)
- [foot stl](https://github.com/satshacopter/satshacopter-250X/raw/master/design_files/foot.stl)
- [satshacopter 250X BOM Excel](https://github.com/satshacopter/satshacopter-250X/raw/master/docs/250X/250X_DOM.xlsx)
- [satshacopter 250X BOM Open document](https://github.com/satshacopter/satshacopter-250X/raw/master/docs/250X/250_BOM.ods)

Media
--

Some images of a built satshacopter 250X

<img src="media/250X_1.jpg" width="70%">
<img src="media/250X_4.jpg" width="70%">
<img src="media/250X_3.jpg" width="70%">
<img src="media/250X_2.jpg" width="70%">
<img src="media/250X_5.jpg" width="70%">
<img src="media/250X_6.jpg" width="70%">
<img src="media/250X_sky.jpg" width="70%">

satshacopter 250X perfomance test:

<a href="http://www.youtube.com/watch?feature=player_embedded&v=MrtPuotW08c
" target="_blank"><img src="http://img.youtube.com/vi/MrtPuotW08c/0.jpg" 
alt="http://img.youtube.com/vi/MrtPuotW08c/0.jpg" width="240" height="180" border="10" /></a>

##making step-by-step instructions

Here you can about how to **build your own satshacopter 250X**.

###making frame and foots

The main frame and the supports are made of 8mm plywood. You can easily cut these using a laser cutter:

<img src="media/main_frame_and_supports.jpg" width="70%">

The upper frame is from 4mm, also for this pretty easy cut you can use the laser cutter:

<img src="media/upper_frame.jpg" width="70%">

Foots are pretty simple 3D printed objects, is recommended to use PLA an 25% of fill:

<img src="media/foot.jpg" width="70%">

###frame assembly

First, detect wich side of the main frame must be up, you can do this by looking at this picture:

<img src="media/upside.jpg" width="70%">

Then put the upper frame on the main frame to obtain the location for the IMU as following:

<img src="media/frame_Assembly_1.jpg" width="70%">

and fix it using 8 x 12mm M3 bolts. It does not require to use nuts:

<img src="media/frame_Assembly_2.jpg" width="70%">

<img src="media/frame_assembly_3.jpg" width="70%">

Now is the turn of the motors. First be sure to pass the motor cable into the arm hole:

<img src="media/motor_assembly_1.jpg" width="70%">

You can use 2 x M3 10mm bolt each, to fix them on the arms:

<img src="media/motor_assembly_2.jpg" width="70%">

Plase adjust the position of the motor at the center before tighten the bolts:

<img src="media/motor_assembly_3.jpg" width="70%">

Finally put a little bit of glue on the 3D printed foots, and glue them fixing the in this way:

<img src="media/foots_assembly_1.jpg" width="70%">

<img src="media/foots_assembly_2.jpg" width="70%">

##making the electronics

You can easily make the **satshakit flight controller** using a little cnc machine. You can have look at the official repository here: **[satshakit flight controller](https://github.com/satshakit/satshakit-flight-controller)**

<img src="media/satshakit_fc.jpeg" width="70%">

Once you have the board ready you can program it using Arduino as ISP (follow the instructions in the flight controller repo).

[Download the latest version of MultiWii](https://code.google.com/archive/p/multiwii/), open it with **Arduino IDE** and configure it as follows in the **config.h file**:

- decomment **#define QUADX** to enable quad X configuration
- set min throttle to 1040 **#define MINTHROTTLE 1040** to match with these ESCs
- decomment **#define GY_521** to enable the IMU

Now you have to **upload the MultiWii**, you can connect in the following way an Arduino with preloaded the Arduino as ISP sketch:

<img src="media/satshakit_fc_programming.png" width="70%">

And then do **Sketch->Uploading Using a Programmer**.
Here is a video about loading the MultiWii:

<a href="http://www.youtube.com/watch?feature=player_embedded&v=ZrNh0s9pX4o
" target="_blank"><img src="http://img.youtube.com/vi/ZrNh0s9pX4o/0.jpg" 
alt="http://img.youtube.com/vi/ZrNh0s9pX4o/0.jpg" width="240" height="180" border="10" /></a>

##mounting and connecting the electronics

Fix all the ESCs to the arms using plastic strips:

<img src="media/fix_escs.jpg" width="70%">

Then connect the escs with the motor. It does not matter the order right now, so just connect them:

<img src="media/connect_motor.jpg" width="70%">

Then you can also pass the wires inside the foots holes:

<img src="media/connect_motor_foots.jpg" width="70%">

Now is time to mount the board. You have to solder some female connectors on the **GY-521** IMU. This is likely how it will be connected, but without the frame:

<img src="media/mount_board.jpg" width="70%">

Put some double side scoth tape on the back of the board and fix to the under side of the main frame. Doing so you shuold have this setup:

<img src="media/mounting_imu.jpg" width="70%">

And on the top side the male connectors for the IMU:

<img src="media/imu_location_ready.jpg" width="70%">

Now put 4 layer of **double side thick scotch tape**:

<img src="media/imu_soft.jpg" width="70%">

just under the IMU:

<img src="media/imu_location_ready.jpg" width="70%">

Now you can plug the IMU. be sure that is in flat position and that doesn't touch the wood (adjust it with your fingers):

<img src="media/imu_final_position.jpg" width="70%">

Now is time to solder some wires that you don't want to be disconnected during flight. You have to solder the white signal cables of the ESCs, their power connectors and the power plug for the battery. Also make sure that the soldering are strong and solid, most important on the outer power board. The following image shows how and where to connect all, and also identifies the position of the motors:

<img src="media/general_connections_board.png" width="70%">

Next step is to connect the remote controller. You can connect this using normal jumpers connectors. Look at the following image to understand how to connect it. 

- pink wire is **ROLL**
- yellow wire is **PITCH**
- orange wire is **THROTTLE**
- blue wire is **YAW**

<img src="media/recevier connections.png" width="70%">

Connect a ground of one of the ESCs to a free ground (near the ground of the remote controller):

<img src="media/gnd_esc.png" width="70%">



##configure MultiWii and do preliminar tests

First connect the FTDI cable as following:

##do a test flight

Mount the propellers in the right position. Remember that looking at the following picture from MultiWii:

<img src="media/QUADX_328.jpg" width="70%">

the propellers must push down the air always.

Place the drone in area without any risk of hitting someone, and stay away more than 5 meters from the drone.

Arm the drone by putting the left stick in bottom left position for more than 5 seconds:

Try to spin a little the propellers.

**Have good flights!**

Authors
--

- Daniele Ingrassia


Contact
--

- **ingrassiada@gmail.com**
- **[linkedin](http://it.linkedin.com/in/danieleingrassia)**

Thanks
--

[Fablab Kamp-Lintfort](http://fablab.hochschule-rhein-waal.de/index.php/de/)<br />
Hochschule Rhein-Waal<br />
Friedrich-Heinrich-Allee 25, 47475 Kamp-Lintfort, Germany<br />
fablab@hochschule-rhein-waal.de


License
--

This work is licensed under the terms of Attribution-NonCommercial-ShareAlike 4.0 International ([CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/)).

Disclaimer  
--

<div class="align-justify">
This hardware/software is provided "as is", and you use the hardware/software at your own risk. Under no circumstances shall any author be liable for direct, indirect, special, incidental, or consequential damages resulting from the use, misuse, or inability to use this hardware/software, even if the authors have been advised of the possibility of such damages.</div>




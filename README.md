<h1 style="font-family: courier;" align="center">satshacopter 250X</h1>
<p align="center">
<img src="media/250X_0.jpg" width="70%">
<div align="center"><i>An open source, low cost and fabbable quad X drone.</i></div>
</p>  

satshacopter 250X
--

satshacopter 250X is a quadcopter built around the **[satshakit flight controller](https://github.com/satshakit/satshakit-flight-controller)**. It is designed to be **simple and cheap as much as possible**, and to be easily made inside any **Fab Lab**.

250X specifications:

- **250mm wood frame** and supports
- **open source flight controller**
- **MPU6050 IMU** located exactly at the center
- 4 x 1900kv **brushless motors**
- 4 x 15A **ESCs**
- **MultiWii** compatible
- Hobby King 4 channel **remote and receiver**
- 1000mah 3S **LiPo battery** 
- costs under **100€**

Here you can look about the **MultiWii pin mapping** of the satshakit flight controller board:

<img src="media/satshakit_fc_power_pin_mapping.PNG" width="70%">

And here you can che the required components in the **Bill of Material** table:

|name|description|vendor|link|price|notes|
|:---:| :---:|:---:|:---:|:---:|:---:|
|2.4Ghz4Ch TxRx V2|4ch mode 2 remote control and receiver|Hobby King|[link](http://www.hobbyking.com/hobbyking/store/__66499__Hobby_King_2_4Ghz_4Ch_Tx_Rx_V2_Mode_2_EU_Warehouse_.html)|23.14€|-|
|Zippy Compact|battery 1000mah 3s|Hobby King|[link](http://www.hobbyking.com/hobbyking/store/__36064__ZIPPY_Compact_1000mAh_3S_25C_Lipo_Pack_EU_Warehouse_.html)|5.55€|-|
|LDPOWER D250-2 Multicopter Power System|4 x 2206-1900kv motors and 4 x 15A ESC|Hobby King EU|[link](http://www.hobbyking.com/hobbyking/store/__84723__LDPOWER_D250_2_Multicopter_Power_System_2206_1900kv_6_x_3_4_Pack_EU_Warehouse_.html)|43.81€|propellers Included|
|IMU 6DOF|MPU6050 Gyro + Acc IMU|Ebay|[link](http://www.ebay.de/itm/MPU-6050-GY-521-3-Achsen-Gyroskop-Accelerometer-Kreisel-Board-Sensor-Arduino-21-/121887579651)|5.39€|-|
|LiPo Charger and Balancer|800mah 3s LiPo charger|Hobby King|[link](http://www.hobbyking.com/hobbyking/store/uh_viewitem.asp?idproduct=77525)|6.99€|-|
|Fligh Controller|satshakit flight controller|various|[link](https://github.com/satshakit/satshakit-flight-controller)|4.00-8.00€|depending on the quantity|
|Voltage regulator|Pololu step up step down 5V S7V7F5|E-shop|[link](https://www.flikto.de/products/pololu-5v-step-up-step-down-voltage-regulator-s7vf5)|4.31€|-|
||||**Total price**|89.19€+4/8€|-|

NOTE: prices may change over time on the respective vendors, and also it is highly dependand on the quantity of drones you want to make.

Downloads
--

If you want to build by yourself a satshacopter 250X, please download the detailed **build manual** here:

- [satshacopter 250X detailed build manual](https://github.com/satshacopter/satshacopter-250X/raw/master/docs/250X/satshacopter-250x-building-manual.pdf)

Following you can find all the **design files** you need to make it:

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
- [satshacopter 250X detailed BOM Excel](https://github.com/satshacopter/satshacopter-250X/raw/master/docs/250X/250X_DOM.xlsx)
- [satshacopter 250X detailed BOM Open document](https://github.com/satshacopter/satshacopter-250X/raw/master/docs/250X/250_BOM.ods)

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




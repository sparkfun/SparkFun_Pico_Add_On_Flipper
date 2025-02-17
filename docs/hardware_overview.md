---
icon: material/cog
---
## Overview

This is a fairly straightforward board. The primary use for this is to provide a way to swap pins from right to left and vice versa. 

## IO Pins



## Qwiic Connector

There is a Qwiic connector available that provides power and I<sup>2</sup>C connectivity simultaneously to a wide array of our [Qwiic Sensors](https://www.sparkfun.com/qwiic). 

## Reset Button

A reset button is useful in many projects. We've added one to the edge of the board. 


## USB Silkscreen

The USB Silkscreen on the back of the board is provided for orientation purposes. 

## I2C Jumper

If you choose to use one or more Qwiic breakouts in your project, it is important to note that this board comes equipped with pull-up resistors on the clock and data pins. If you are daisy-chaining multiple Qwiic devices, you will want to cut this jumper; if multiple sensors are connected to the bus with the pull-up resistors enabled, the parallel equivalent resistance will create too strong of a pull-up for the bus to operate correctly. As a general rule of thumb, disable all but one pair of pull-up resistors if multiple devices are connected to the bus. To disable the pull up resistors, use an X-acto knife to cut the joints between theWS jumper pads highlighted below.

<figure markdown>
[![I2C Jumper](assets/img/){ width="400" }](assets/img/ "Click to enlarge")
<figcaption markdown>I2C Jumper</figcaption>
</figure>





### 3D Model

A 3D model of the board and components was exported to a STEP file using KiCad.

<script type="module" src="https://ajax.googleapis.com/ajax/libs/model-viewer/3.5.0/model-viewer.min.js"></script>

<center>
    <model-viewer src="../assets/3d_model/SparkFun_Pico_Add_On_Flipper.glb" camera-controls poster="../assets/3d_model/SparkFun_Pico_Add_On_Flipper.png" environment-image="legacy" shadow-intensity="1.58" exposure="0.64" shadow-softness="0.24" tone-mapping="neutral" camera-orbit="-46.67deg 57.14deg 153.3m" field-of-view="30deg" style="width: 750px; height: 500px;">
    </model-viewer>
</center>
<br />
<div style="text-align: center">
    <a href="../assets/3d_model/SparkFun_Pico_Add_On_Flipper.step" target="stp_file" class="md-button">Click Here for the STEP File</a>
</div>



### Board Dimensions

The board measures 1" x 2". 

<figure markdown>
[![Board Dimensions are 1" x 2"](../assets/board_files/SparkFun_Pico_Add_On_Flipper_Dimensions.png){ width="50%" }](../assets/board_files/SparkFun_Pico_Add_On_Flipper_Dimensions.png "Click to enlarge")
<figcaption markdown>Board Dimensions</figcaption>
</figure>


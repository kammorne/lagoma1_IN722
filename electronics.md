---
layout: page
title: Electronics
description: The electronics involved and any techniques used to build the robot
image: assets/images/atmega2560Wiring.jpg
nav-menu: true
---

<!-- Main -->
<div id="main" class="alt">

<!-- One -->
<section id="one">
	<div class="inner">
		<header class="major">
			<h1>Electronics</h1>
		</header>

<!-- Content -->
<h2 id="content">Techniques</h2>
  <p>Really, I could've done a lot better for this project in terms of techniques with the electronics involved in the project. I'd decided early on that there wasn't a point having the wiring being soldered, since I'd have to keep changing things up while trying to figure out how to actually achieve this project. So in the end, my robot was some disgusting amalgamation of wires surrounding the 3d printed chassis wiring everything up.</p>
  
  <p>I also had the option of at least keeping the wires tidy, but it seemed that any sort of movement with the wires that meant pulling them into a sort of bundle would make them pop out of their breadboard socket causing issues and having to find out where the cable popped out from and then putting it back in while making sure I didn't knock any other cables out of their sockets.</p>
  
<h2 id="content">Sensors</h2>
  <p>There was only one sensor I needed for the project, at least in it's early stages, that was the Accelerometer/Gyroscope Sensor. Originally, I was going to use the MPU6050 6-Axis sensor, since a lot of other people taking on this project remarked on how it was a small, lightweight yet very capable sensor. However, I was recommended the BNO055 9-Axis Sensor, and after doing a little bit of research, I figured it should still provide the same kind of functionality that the MPU6050 would have provided, but the BNO055 would end up having more use in later projects if required.</p>
  
  <p>Obviously, I couldn't just have the sensor sending raw data to the wheels of the robot, since that would cause issues when it's trying to steady itself, since the noise in the readings from it adjusting all the time would just cause it to make larger corrections up until it can no longer keep up with the movement of the ball underneath and cause the robot to tip. My solution I attempted to implement was a Kalman filter, which would take in the raw data from the sensor, and filter it so that the data going into the ATMega would be a lot closer to it's current state, so it wouldn't throw itself all over the place trying to keep itself steady.</p>
</div>
</section>
</div>

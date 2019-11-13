---
layout: page
title: Hardware
description: The hardware used for the project
image: assets/images/atmega2560.jpg
nav-menu: true
---
<!-- Main -->
<div id="main" class="alt">

<!-- One -->
<section id="one">
	<div class="inner">
		<header class="major">
			<h1>Hardware</h1>
		</header>

<!-- Content -->
<h2 id="content">Hardware Used</h2>
<p>The hardware I'm using for the robot is a simple selection of parts that I found others had used on their projects. Since the whole process of making a self-balancing ball-bot is new to me, I thought I would gather inspiration from
others who had taken on the project before.

The parts I had selected are as follows:

- ATMega Board
- ULN2003 Stepper Motor Driver x 3
- 5V Stepper Motor x 3
- 48mm Omni Wheel x 3
- 4 AA Battery Holder
- Batteries
- 3D Printed Chassis</p>

<p>I decided to go for the ATMega 2560 board as it offered enough power and digital ports for the tasks I required the robot to perform.
Most other boards I had looked at would not offer a good selection of digital ports to be able to plug in all 3 stepper motors.
Most other people who had taken on a ballbot project used boards such as a Teensy board or similar, so that they could keep the size of the hardware down which I assume would help with the balancing of the robot.
Unfortunately, I could not get inspiration on how others had wired up their robots, since I couldn't find any images of people's projects. I do feel however that the design I have made for the ballbot
is suitable for the prototype that I'm designing.</p>

<p>For the power options of the robot, I figured 4 AA batteries would be suitable for testing purposes, since it provides the required 5V for the stepper motors, although I may end up changing the power solution in the future,
as I'm concerned that the batteries won't last as long as I would like. A solution to that would be a sleep state for the board, however I'm not sure if I can implement that for this robot, since it needs to be listening
to the accelerometer/gyro at all times to keep itself balanced.</p>

<p>In retrospect, some larger wheels compared to the original 48mm ones I selected may have been better. I had to adjust the design of where the motors sat, as where they originally sat meant that the wheels did not touch the ball,
and the robot's chassis would be sitting on the ball instead, preventing movement. I originally chose the 48mm wheels as other people who had taken on the project of a ballbot had chosen similar sized wheels, although chances are
they may have had a slightly smaller chassis, or perhaps even a larger ball for the robot to sit upon.</p>

<p>The use of a 3D printed chassis was an easy choice to make, since it allowed a lot more freedom when creating the project. I figured if I could 3d print the chassis, I would be able to make minor changes to it without causing any damage to the chassis if i were to use a kit or such. I've written more about my choices in 3D printing the chassis in the Design Principles page.</p>
</div>
</section>

</div>

---
layout: page
title: Security
description: Security involved for the robot
image: assets/images/security.jpg
nav-menu: true
---

<!-- Main -->
<div id="main" class="alt">

<!-- One -->
<section id="one">
	<div class="inner">
		<header class="major">
			<h1>Security</h1>
		</header>

<!-- Content -->
<h2 id="content">Security</h2>
  <p>In terms of security for the moment, I don't have anything in place for the robot. This is because I haven't set up any way for the robot to communicate with the outside world yet, and the only way it can send data for the moment is by
  being tethered with a USB cable. Because of this, I haven't done anything in order to protect the information the robot is sending, since the only time it will be connected with a cable is during debugging. Once I can set up the robot to
  run without a tether, I can look into encoding the data for sending it over LoRa or the Things Network.

  For encoding the data, I would plan on using Base64 encoding, since it's useful enough to keep the data out of plaintext, however the main reason for using Base64 would be that it saves on packet size when sending over the network,
  compared to encoding the value with something such as SHA256 or SHA512.</p>
</div>
</div>
</section>

</div>

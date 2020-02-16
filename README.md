# laser-tripwire

Hardware Required</h4>
<div style="background-color: white; font-family: Merriweather, Georgia, serif; font-size: 16px;">
<ul style="color: #333333; font-family: &quot;Helvetica Neue&quot;, Helvetica, Arial, sans-serif; font-size: 17px; list-style-image: initial; list-style-position: initial; margin: 0px 0px 9px 25px; padding: 0px;">
<li style="line-height: normal;">Arduino Uno</li>
<li style="line-height: normal;">LED</li>
<li style="line-height: normal;">LDR (photo resistor) , Light Dependent Resistor</li>
<li style="line-height: normal;">220 and 10k ohm resistors</li>
<li style="line-height: normal;">Wires</li>
<li style="line-height: normal;">Breadboard</li>
<li style="line-height: normal;">Buzzer</li>
<li style="line-height: normal;">Laser Module</li>
</ul>
</div>
<h4 style="background-color: white; font-family: Merriweather, Georgia, serif; font-size: 16px;">
<br />Schematic diagram</h4>
<div>
  ![Maker Tutor>(https://1.bp.blogspot.com/-A7Wvk_DaVlk/Wl3EsUeVkwI/AAAAAAAA-n8/_3dj6B-DXpA47qlUUGP3WRE-gxzK35DIACLcBGAs/s1600/ldr_sensor_buzzer_bb.jpg)
<br /></div>
<h3>LED connection</h3>
LED attach to board
Resistor (220 ohm) one leg attach to LED long leg
The green wire attach to resistor's empty leg → Arduino D13
The black wire attach o LED short leg → Arduino GND

<h3>LDR Connection</h3>

LDR attach to board
Resistor (10k ohm) attach to LDR one leg
The Black wire attach to LDR other (empty) leg → Arduino Gnd
The Yellow wire attach to LDR and resistor same column → Arduino A0
The Red wire attach to resistor empty leg → Arduino 5V


<h3>Buzzer Connection</h3>
1. Buzzer + to pin 12 on Arduino<br>
2. Buzzer -  to GND on Arduino



<h3>Laser Module Connection</h3>
1. Laser module +/s to pin 7 on Arduino<br>
2. Laser module - to GND on Arduino

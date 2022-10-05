# ArduinoQuadX_Multiwii24

Using Multiwii 2.4 firmware and Multiwii GUI configuration. This is a brushed quadcopter.

<h4>Specification:</h4>
<ul>
  <li>Arduino pro mini 5v 328p</li>
  <li>mpu6050</li>
  <li>4 channel mini receiver (flysky)</li>
  <li>720 DC Syma motor</li>
  <li>3-blades propeler</li>
  <li>Syma 5xc gear set</li>
  <li>RC/TX fs-i6</li>
  <li>ESC = in5819+si2302+10k ohm</li>
  <li>1 Switch</li>
  <li>LiPo Battery 7.4v</li>
  <li>30cm super light frame</li>
  <li>red SMD led (for stand-by and Arming indicator)</li>
  </ul>
  
  <h2>Problem</h2>
  <p>Too heavy = cause: battery.</p>

<p>Watch the demo: https://www.youtube.com/watch?v=Ilx-xXX015U</p>

<h3>Config</h3>
<ul>
<li>Motor pinout: 3,9,10,11</li>
<li>Channel order (from 1st-ch): d5,d4,d2,d6</li>
<li>Led VCC pinout: pin A1</li>
</ul>

<p>For diagram, you can see Electronoobs brushed drone. I modified Config.h file in multiwii 2.4 firmware to get it work.</p>

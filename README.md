# UCRProfiles
YouTube tutorial: https://youtu.be/uZGfMhlQT7o
Written tutorial (Part One): https://garbagecorp.blogspot.com/2021/01/can-you-use-steering-wheel-in-cyberpunk_12.html
UCR Profiles you can import (using copy/paste) into your UCR context.xml file and remap to your own controllers.<br/>

"Wheel and Joystick to PS4/360 Controller profiles" tested in the following games/apps:<br/>
>Cyberpunk 2077 <br/>

Prerequisites for all:<br/>
>UCR - https://github.com/Snoothy/UCR

Prerequisites for "Wheel and Joystick to ... controller profiles":<br/>
>ViGem (Output to PS4/360 Virtual Controllers) - https://github.com/ViGEm/ViGEmBus/releases/tag/setup-v1.17.333
<br/>vJoy (Middleman/Mixer for real controllers) - http://vjoystick.sourceforge.net/site/index.php/download-a-install/download

v2.01 - toggleable antideadzone

Added a mapping in the (default G29 "Enter" button (Button 24)) to make anti-deadzone toggleable<br/>
In Cyberpunk 2077, when using mouse/keyboard, using the normal anti-deadzone causes the UI control hints to flicker; controls are unaffected but this is annoying.<br/>
Pushing the mapped button engages/disengages the anti-deadzone so you can switch to mouse/keyboard when on foot, and switch it on when using a vehicle.<br/>

(Technically, it is still sending to vJoy X (since otherwise it will lock to whatever value it was originally sending) from the wheel Axis X ,but w/o the anti-deadzone)

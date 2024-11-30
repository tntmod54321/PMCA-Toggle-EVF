# PMCA-ToggleEVF
This is a fork of PMCA-HDMICam, using the same build process outlined there  
The IR EVF sensor on my camera is damaged and doesn't work, I need to have the display mode set to LCD in the cam settings, if I set it to EVF or auto it will show the EVF until reboot, then neither display will be on. When the display is switched by an application it is restored to the system default on reboot. This makes the EVF usable for me again. I would like to bind the toggle directly to the Fn key, but I think this would not be possible without a custom firmware image.

# Functionality
When you open the app it will toggle the EVF, when you press the enter key it will toggle it again, and when you press the focus/shutter, play, or trash can buttons it will exit the app
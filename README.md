
This guide will assume you are using an XInput compatible controller, if that is not the case, there are other resources available to convert whatever you are using to XInput to make this work.

First, install Joyxoff

https://joyxoff.com/en/

Make note of the install location of the Joyxoff executable, you will need it later. The default is `C:\Program Files (x86)\Joyxoff\Joyxoff.exe` which we will call <joyxoffpath>

Next we need to enable this to run on the Login Screen

This involves some registry modification to allow, essentially adding it as an Assistive Technology application

IF you want to learn more about that see here: https://learn.microsoft.com/en-us/windows/win32/winauto/ease-of-access---assistive-technology-registration

[controller.reg](controller.reg) contains the details of the required keys or can be downloaded and merged



# CAVEATS
This does not appear to work on the Lock Screen, only the initial boot Login Screen

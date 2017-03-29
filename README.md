# FreeRTOS_Eclipse
Instructions on how to install FreeRTOS and run with Eclipse C / C++
Here is a quick updated guide on how to get FreeRTOS run with Eclipse Neon.

# What you need
- Eclipse IDE for C/C++ Developers
- FreeRTOS

Eclipse is version: Neon.3 Release (4.6.3)
FreeRTOS is version: 9.0.0

Download Eclipse from here:

https://www.eclipse.org/downloads/download.php?file=/oomph/epp/neon/R2a/eclipse-inst-linux64.tar.gz

Download FreeRTOS from here:

https://sourceforge.net/projects/freertos/files/latest/download?source=files

# Setup Eclipse
We first need to get install C / C++ GDB Hardware Debugging.
- Select 'Help' from the 'Menu' in Eclipse.
- Now select 'Install New Software'

From the dropdown-menu 'Work with' select:
CDT - http://download.eclipse.org/tools/cdt/releases/9.2

Now expand the CDT Optional Feature and select:
- C / C++ GDB Hardware Debugging.

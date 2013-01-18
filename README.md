hexbright
=========

This is the easiest way to get started with programming your hexbright.

Video Instructions
------------------

[Setting up your development environment](http://www.youtube.com/watch?v=sUbAkz_Lwxk) (development environment setup, minus driver install).

[How to share your code on github](http://www.youtube.com/watch?v=r5VUDEbd08o).

[Writing a program](http://www.youtube.com/watch?v=Q7eRACjCixE).

Text instructions
-----------------

1.  Download and install [arduino](http://arduino.cc/en/Main/Software) and the CP210x driver (Use a VCP Driver Kit from [here](http://www.silabs.com/products/mcu/Pages/USBtoUARTBridgeVCPDrivers.aspx)).  Most linux kernels come with the driver pre-built.

2.  Download this folder/repository using one of the following methods, accessible at the top of the [project page](https://github.com/dhiltonp/hexbright).
    1. Read-Only (no integrated sharing mechanism)
        *   **[ZIP](https://github.com/dhiltonp/hexbright/archive/master.zip)** Extremely easy to get started, but you will need to manually update the library for new features.
        *   **git clone git@github.com:dhiltonp/hexbright.git** Command line, read-only access.
    2. Share your code
        *   **[Fork](https://github.com/dhiltonp/hexbright/fork)** Click fork to generate your own copy of the project (requires a free account on github).
            *   **[Clone in Windows/Mac](github-windows://openRepo/https://github.com/dhiltonp/hexbright)** Great for first-time users, the command line interface is also available.
            *   **git clone git@github.com:USERNAME/hexbright.git** Command line, read-write access.

3.  Open the arduino ide, and click on 'File'->'Preferences' in the menu.

4.  Set your sketchbook location to the location of this folder (where this README file is found).

5.  Restart arduino.

6.  In arduino, click on 'Tools'->'Board'->'Hexbright' as your device type.

7.  With your hexbright unplugged, go to 'Tools'->'Serial Port' and look at the options.

8.  Now plug in your hexbright and go to 'Tools'->'Serial Port'.  Select the new option.  (On linux, there may be a delay of over a minute before the device appears.)

9.  Underneath the 'Sketch' and 'Tools' menu options, there is an up arrow (to open a program).  Click on it, go to 'programs', and select a program.

Overview
-----------------

*   'temperature_calibration' is one of the simplest programs you could write.

*   'functional' is a basic example of how a program might have multiple modes.

*   'down_light' contains an example of using the accelerometer.

*   libraries/hexbright/hexbright.h has a list of all available methods in the api, and is fairly well commented.


I have translated most of the original sample programs to the library here: https://github.com/dhiltonp/samples

---

Be aware that this library is a work in progress.  In particular, the accelerometer api may change, and it is not yet optimized.

Enjoy!

README.txt

SAS Data Acquisition
1. newRunSAS is to replace the old RunSAS
2. newTemp is the temperature data function (SubVI)
3. CoordinateSave is saving system coordinates to CSV (SubVI)
4. InitTrack is function that moves linear track to min vertical height (SubVI)
5. Main is the same but has the newRunSAS and enables serial connections
6. NumSteps calculates the number of steps of the motor (SubVI)
7. Re-Init reinitializes the linear track and turntable (SubVI)
8. SysParamsSave save system parameters (SubVI)

Motion Control
1. MotionControl is the function being called in newRunSAS
2. MotionVI is the GUI for the motion control from Main (SubVI)

Kinect Control
1. KinectVI streams the video and depth maps
2. PixelDistance calculates how many pixels are in one square centimeter on turntable (SubVI)
3. imgToHDF5 is storing images as HDF5 files (SubVI)

All other VIs not mentioned have not been changed.
I also included the documentation that I had compiled thus far in addition to a folder with pictures.

Thank you for a great summer! :)
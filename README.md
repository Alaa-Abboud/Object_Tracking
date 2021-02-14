# Object_Tracking
Tracks a moving a object inside your camera / webcam view using Python and OpenCV.

Use the trackbar option inside the code to find the proper "Hue", "Saturation", and "Value" values/intensities to do a proper masking for the object being tracked.
You can tweek them to work for any colorspace that fits your case (RGB, Grayscale, etc.).

The code will draws a rectangle around the conhe rectangle moves with the object. if you want to use the tracked object for further processing, you can easily get
the pixel locations of the contours of your object or of the bounding rectangle (Region of Interest - ROI) and then apply the processing step only on the ROI !

If you have any questions about the code, contact me and I'd be happy to discuss / explain !

Also, if you have any ideas to improve the code, creatively or algorithmically, contact me ! I'd love to share ideas and learn =)

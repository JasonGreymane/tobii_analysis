# tobii_analysis
A suite of Python packages for analysing data from the Tobii Pro Glasses 3, including screen detection.

This package does the following:
- Detects screens within user field of view based on image processing factors (e.g. brightness). This enables accurate eye-tracking to be conducted.
- Maps eye tracking coordinates onto the detected sceen (e.g. treating times where the user is not looking at the screen as an outlier)
- Calculates angular quantities such as velcoity, acceleration, etc.
- Uses the IDT algorithm to detect and quantify fixations (and saccades)
- Plots fixations, saccades, and other data on a background image (e.g. the image shown on screen)

There is additional code to operate the Tobii Pro Glasses 3 using the Python API and a wireless connection.

This repo is a work-in-progress which was created for my PhD research. I am currently polishing the code to publish.

If you are interested in using and/or assisting with this repo and no code is available (i.e. it hasn't been published yet), please contact me at humanenvironments@deakin.edu.au.

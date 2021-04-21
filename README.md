# Hidden Palette
Python Flask web application that generates the most commnly used colors in an uploaded image. 
The app then makes associated hex codes available for download as a text file.

Program uses PIL and numpy to generaye RGB arrays from the images, which are then converted into a (long) list of hex codes.
Using the collections / Counter library, we can identify the most common hex codes, and then usedpickle to store as a file for use in the app.
The Library html page generates Bootstrap cards with the palettes, using the unpickeled (ha ha) hex code lists and makes these available for download. 

![app_screenshot](https://github.com/Holly-Transport/Hidden_Palette/blob/master/screenshots/c_app1.png)

![app_screenshot](https://github.com/Holly-Transport/Hidden_Palette/blob/master/screenshots/c_app2.png)

![app_screenshot](https://github.com/Holly-Transport/Hidden_Palette/blob/master/screenshots/c_app3.png)

# Hidden Palette
Python Flask web application that generates the most commnly used colors in an uploaded image. 
The app then makes associated hex codes available for download as a text file.

Program uses PIL and numpy to generate RGB arrays from the images, which are then converted into (long) lists of hex codes.
Using the [Collections library](https://docs.python.org/3/library/collections.html), we can identify the most common hex codes, and then use [pickle](https://docs.python.org/3/library/pickle.html#:~:text=%E2%80%9CPickling%E2%80%9D%20is%20the%20process%20whereby,back%20into%20an%20object%20hierarchy.) (wonderful name!) to store as a file for use in the app. 

The Library html page generates Bootstrap cards with the derived hex palettes, using the unpickeled (ha ha) hex code lists. 

![app_screenshot](https://github.com/Holly-Transport/Hidden_Palette/blob/master/screenshots/c_app1.png)

![app_screenshot](https://github.com/Holly-Transport/Hidden_Palette/blob/master/screenshots/c_app2.png)

![app_screenshot](https://github.com/Holly-Transport/Hidden_Palette/blob/master/screenshots/c_app3.png)

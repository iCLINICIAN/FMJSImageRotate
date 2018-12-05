# FMJSImageRotate
Rotate or crop a container image in FileMaker without the need for plugins

FMJSImageRotate is a simple proof of concept for basic image manipulation of FileMaker container images without the need for plugins.

It uses the darkroom.js JavaScript library by Matt Ketmo https://github.com/MattKetmo/darkroomjs to enable rotation and cropping of container images via a Web Viewer.

The process I've followed is:

1.	Import an image to a container field and make a copy of this to a second container field to enable restoration of the original image

2.	Click the Edit Image icon button to set the image to the webviewer

3.	Make your rotation/cropping adjustments

4.	Convert the web viewer image data back into an image file and save back to the original container

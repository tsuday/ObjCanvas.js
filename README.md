# ObjCanvas
Load and draw *.obj file on Canvas, and download as image.

1.Relate div area to ObjCanvas object by calling constructor

2.Load *.obj file and draw it on canvas by calling ObjCanvas#loadObjFile

3.Save scenes drawn on canvas as image by calling ObjCanvas#save or ObjCanvas#autoSave

This project contains sample application "SampleApp" for reference.
SampleApp needs to be run on application server(e.g. Apache Tomcat).

ObjCanvas requires:
* Three.js

SampleApp requires:
* FileSaver.js
* Canvas-toBlob.js

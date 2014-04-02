Android - AugmentedReality using markers
=========================

Simple use of AndAR library for Android.
Fixed some bugs (light and texturing).

To use your own models:

- Open Blender
- Do your stuff (better if you decimate your model due to low memory budget)
- Save it as an .obj with these flags

       ![GitHub Logo](http://s28.postimg.org/dijmm4o2l/Schermata_del_2014_03_20_17_28_14.png) 

- Insert it into 'asset' folder
- Use this Marker https://andar.googlecode.com/files/AndARMarker.pdf

**WARNING:** Start the app in portrait mode or *nothing* will be rendered.

**WARNING_2:** AndAR is currently using and old GL10 render. Better if you upgrade to GLES20.


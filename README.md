Android - AugmentedReality using markers
=========================

Simple use of AndAR library for Android.
Fixed some bugs (light and texturing).

To use a your own models:

- Open Blender
- Do your stuff (better if you decimate you model due to low memory budget)
- Save it with these flags
- Insert them into 'asset' folder

       ![GitHub Logo](http://s28.postimg.org/dijmm4o2l/Schermata_del_2014_03_20_17_28_14.png)

- Run it then use this Marker https://andar.googlecode.com/files/AndARMarker.pdf

**WARNING:** Start the app in portrait mode or *nothing* will be rendered.

**WARNING_2:** AndAR is currently using and old GL10 render. Better if you upgrade to GLES20.


# JHead-android
head is a command line driven program for manipulating the non-image parts of Exif flavour JPEG files that most digital cameras produce.
Windows / Mac users: Jhead has no Graphical User Interface. Clicking on it with the mouse from Windows or Mac OS-X won't do anything for you - you have to use it from the Command prompt
</br>
</br>
How to use:
This is android jni library.
</br>
</br>
-Compile it with android-ndk or take prebuild binary files in /libs/<arch></br>
-Put JHead.java to your project, edit const char *classPathName in exify_JHead.c</br>
-Call JHead class, (example: jhead mi = new JHead(); Map<String, String> imageInfo = JHead.getImageInfo(filePath);)</br>
</br>
</br>
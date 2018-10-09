# HDF5-conversion

A simple app for batch converting the HDF5 files that are produced by the TA software. If you wish to use this app on a PC other than the Lab PC, you'll need to save the files to your PC and change the paths in the .bat file accordingly. Obviously you'll need python and the appropriate packages installed. Please note that the app is designed specifically to convert the TA HDF5 files. It won't work for any other random HDF5 files you have knocking around!

### Current Usage

Double click the shortcut HDF5 on the desktop to open the UI. At the moment this is a shortcut to a windows batch file that runs `python app.py' to launch the app. Eventually I'll package the whole thing up into an executable.

Wait for the app to load (may take a little while). Drag and drop your HDF5 file(s) into the file list. Once you're happy with the list click "load all". Browse for a folder to save the converted data to, choose which parts of the data you want to save using the checkboxes and hit "convert".


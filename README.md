# Stream 
This is a very nieche distribution system that is desgined specifically for macOS to create a netflix, disney+, hbo max, youtube and other "applications" through the use of google chrome.  

## How To Use
1) To create your first application, first add work.html to your home directory.  You may wish to hide it from users by renaming it with a "." at the beginig of its name.  
2) open `maker.scpt` with the application `Text Editor` and change the `THE_USER` in the location string to your username.  
3) `work.html` is already configured to open some windows to specific locations depending on the query provided by the user (the strings after the `?` in the URL).  If you wish for it to go to another location that is not defined, then you will need to add it within the main `<script> ` tag and use the `win` function.  
4) Finally, go to file > export, select the app file format for your application, and rename your app accordingly.  
5) Once it is complete, you can run your application and it will produice a dedicated window through google chrome for a singular website (netflix, hbo, youtube, etc).  


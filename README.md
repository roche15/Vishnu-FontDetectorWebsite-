# Vishnu-FontDetectorWebsite-
This is a laravel project which is a website that detecs font from a picture and save that data to the server if you are log on.

patch 001 note : 
1. we didnt do much as to put resources to this project yet. Since we still researching on how to put image to our PHP Server. this is some of the resources:
 - https://stackoverflow.com/questions/4234589/validation-of-file-extension-before-uploading-file
 - https://www.w3schools.com/jsref/dom_obj_fileupload.asp
2. for the font detection we willbe using Vasile Peste 's Typefont that uses java script and JSON :
 - https://github.com/Vasile-Peste/Typefont
3. to see the project, just change the branch to the recent branches one

patch 002 note : 
1. we already implement the javascript for face detection using default images, if you open the console on your browser
   you could see some data are accepted and decline, we can take the first data (the most likely font) and show it on our website.
2. if you want to try the website download it and run laravel but don't open it on Microsoft Edge.

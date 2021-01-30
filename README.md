# graphicsReader
A program to allow the print impared to explore infographics and other documents where percieving position is necessary

This program is the reader part of a solution that allows blind people to explore graphics.
The program works by loading the image to be described into a window and having corresponding detected objects i with their coordinates in an ascii file. 
The user moves around the screen using the arrow keys. When the user reaches the coordinates of a detected object, the description of the object is spoken.
There is a python script that generates the ascii file which contains the coordinates and names of detected objects.
In addition, OCR is also available and follows the above principle so blind users can explore text along with the position of said text.

To run the program, grab the jar file and activate it. You will be prompted for the relevant files. Once the image and description file have been loaded, you are free to explore.

Yes, you can load the wrong image and wrong ascii file but the program as of now has no way to detect this. 

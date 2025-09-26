Project: music-organizer-v1. A project to collect audio files.
Authors: David J. Barnes and Michael Kölling

This project is part of the material for the book

   Objects First with Java - A Practical Introduction using BlueJ
   Seventh edition
   David J. Barnes and Michael Kölling

It is discussed in chapter 4.

To start:

Create a MusicOrganizer object on the object bench.
Use its methods to add, show, and remove files.
----------------------------------------------------------------------------------------------------------------------------
Question 2: 
Since the "if" check is there, no error appears. (as seen in the following line)
        if(index >= 0 && index < files.size()) {
            files.remove(index);
        }

Question 3: 
Removing the first File(0) will transfer the second File(1) to its place. ArrayList is designed to always store its elements without any gaps, which is why the second file slid down into position 0.

Question 4:

##Can you copy the foo.txt file to slash temp?

First I would create the foo.txt by entering **touch foo.txt** in the command line. Then to move that file, I would 
enter **cp foo.txt temp/** 

**Robocopy** Robocopy, or "Robust File Copy", is a command-line directory and/or file replication command. 
Robocopy functionally replaces Xcopy, with more options. Robocopy does not copy open files, even Robocopy's backup mode 
will not touch those files. 

##Use the cp -r command to copy more directories with file in them. 

I used this command to move files from both the **something/** and **things** directory that i created.
A little confusing in the beginning but it all made sense towards the end. 

##Copy a file to your home or desktop directory##

Copied the awesome.txt and foo.txt files into my desktop folder... cp awesome.txt Desktop/

I found these files in finder, and when I opened them in text editor it was as expected, and empty txt file. 


##I moved the files that were in something/ to temp/##

Updated the **copy foo.txt** into the /tmp directory** 

>Omars-MacBook:tmp OC$ cp foo.txt /tmp/

>Omars-MacBook:tmp OC$ ls 
foo.txt

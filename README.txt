Group Members:
David Pedroza 

Email:
krazydave65@csu.fullerton.edu

CWID:
899326458
-----------------------------------

======= PART1 =================================
The "copy" command in Windows concatenates the Binary of two files and saves them into a new file.
The "/b" is a command that takes the binary of the files 
The gif and 7zip files binaries are concatenated and saved into a file named "result"

When we rename the file extension to ".gif" the result file displays the gif image
..but when we rename the file extension to ".7z" the result file can then be used to extract the worm

Using the copy command hides the worm file within the gif image file

This technique is not the best at avoiding detection from anti-virus tools.
The anti-virus can possibly access the 7z file which is not encrypted. 

====== PART2 ===================================
When running binder.py with large parameter execuatables, such as /bin/ls and /bin/pwd, it may
take from 1-3 mins... so please be patient. :) 


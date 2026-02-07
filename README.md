# GLUG-R2

level 0
learned ssh and its properties.
used ssh bandit0@bandit.labs.overthewire.org -p 2220
and bandit0 as password

level 0 -1 <br>
used ls to list file - readme
used file to get is properties it was ascii text.
used less readme <br>
  Congratulations on your first steps into the bandit game!! <br>
  Please make sure you have read the rules at https://overthewire.org/rules/ <br>
  If you are following a course, workshop, walkthrough or other educational activity,
  please inform the instructor about the rules as well and encourage them to
  contribute to the OverTheWire community so we can keep these games free!
<br>
  The password you are looking for is: ZjLjTmM6FvvyRnrb2rfNWOZOTa6ip5If
pressed q.
recieved password. then logout.


level 1 - 2 <br>
instruction was that password is in file named - . <br>
 "-" didnot work normally because it is to avail options. <br>
then i found it's ways used file ./- to get is property. <br>
then used less ./- <br>
copied and logout.

level 2 - 3 <br>
it contained space and - <br>
thats it was needed <br>
less ./"./--spaces in this filename--" <br>

level 3 - 4 <br>
it was a hidden file hence easily come out with ls -a. <br>

<br>
level 4 -5 <br>
it was based on file type it is. as in linux last extension to file does not provide full guarantee to be of that file. hence we need to check which one is txt file.
and it has "-" starting file and ./- was required with file to gets its property.

<br>
level 5-6 <br>
it is a bunch of files in which this file is hidden. tried du -h to find size. <br>
later tried find . -size 1033c. 
and got only one option
and thats it. it was little confusiong but soon realised it also hidden by dot at first.
later i found and made less ./.file2 <br>

level 6-7 <br>



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
it has a file with owner and group on server anywhere. thats why i performed search on / directory. 
used  find -user bandit7 -group bandit6 -size 33c
and found /var/lib/dpkg/info/bandit7.password which allowed to display and lied in. in that file i got password.
<br>

level 7-8 <br>
in this task it was to use grep as it helps finding to specific lines in which word contain.<br>
cat data.txt | grep millionth
then got password next to this word. <br>
<br>

level 8-9 <br>
in this i was needed to see which one is only once occured hence used sort data.txt |uniq -c
to sort first then count and show how many each elemetns counts. <br>

level 9-10 <br>
in this it was required to find unique binary. using strings it was possible as it simplfied and made me analyse to get its password.
<br>

level 10-11 <br>
as per instruction, it was file encode with base64. hence used base64 -d data.txt | less
 to get its password.
<br>

 level 11-12 <br>

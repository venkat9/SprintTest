# SprintTest

links

https://stackoverflow.com/questions/6307648/change-global-setting-for-logger-instances/6308286#6308286

https://sourcemaking.com/design_patterns/composite/cpp/1

https://www.concretepage.com/

Move files Example
https://stackoverflow.com/questions/4645242/how-to-move-file-from-one-location-to-another-location-in-java
http://www.baeldung.com/java-how-to-rename-or-move-a-file

https://en.wikipedia.org/wiki/Block_Elements#Character_table



find . -name "*.csv" 
tree . // to know the hirarcy
find . -maxdepth 1 -name "*.csv"
rm -r another_folder/

Locate: is faster than Find but we need to update the database using[ sudo updatedb]

grep does not look for information about file it rather search for contents of a file 

find /etc -name *.conf
[/etc where to start]

grep SERVERNAME /etc/* -r   //SERVERNAME- this is text we are looking for, /etc/* this is where we are trying to look for, -r recursive looking

---
https://www.youtube.com/watch?v=u4I6Fhc_00s

find where cretiria{permission, type, name, time} what-to-do
 example: //.(dot) meaning current directory // size of 0, access time more than 10days
 
find /temp -size 0 -atime +10 -exec ls -1 {} \; > ./chckold.txt
find=where=criteria==========whattodo=

with specific name:
-iname  "abc.txt" search with specific name
-o meaning or
-maxdepth
-type f meaning file types
-type d meaning directory type
-empty files which are empty
-size  +1M -size -2M
find . -user bob

---
/Users/venkatdesu/Desktop
/Users/venkatdesu/Desktop/Study/unix


----

diff command prints the lines that are different in two lines


Showing progress
https://www.youtube.com/watch?v=xIfsdW6ripo

-pv (pipe view command)

pv 

----

awk 'NF' file

this command will remove empty lines in a text file 

https://stackoverflow.com/questions/16414410/delete-empty-lines-using-sed


--
move files

https://unix.stackexchange.com/questions/402728/how-to-move-files-specified-in-a-text-file-to-another-directory-on-bash?noredirect=1&lq=1


Function declarations
https://stackoverflow.com/questions/6212219/passing-parameters-to-a-bash-function

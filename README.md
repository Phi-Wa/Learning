# Learning

https://missing.csail.mit.edu/2020/course-shell/

2 Create a new directory called missing under /tmp.

Solution

mkdir /tmp/missing


3 Look up the touch program. The man program is your friend.

Solution

man touch


4 Use touch to create a new file called semester in missing.

Solution

touch 

5 Write the following into that file, one line at a time:

#!/bin/sh

curl --head --silent https://missing.csail.mit.edu

Solution
 echo '#!/bin/sh'> /tmp/missing/semester
 echo "curl --head --silent https://missing.csail.mit.edu" >> /tmp/missing/semester

6
Solution
ls -l /tmp/missing/semester

sh /tmp/missing/semester







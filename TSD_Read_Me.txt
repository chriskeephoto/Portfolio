TSD.cgi Read Me

Developer: Chris Kee

URL: students.cse.unt.edu/~crk0087/CSCE_4410/TSD.cgi

TSD or Television Show Dataminer is a web application that
allows users to search television shows through a bit torrent
search engine and then allow users to organize which episodes
have been downloaded.

For the puposes of this app as it is, it queries a 
php site developed by Professor Don Ratzlef that has saved
specific xml data from the torrentz.net.  This is because 
torrent.z after time blocked requests from our school web
server.

http://www.cse.unt.edu/~donr/courses/4410/13summer/project/getXMLfake.php?query

where query is one of the following predefined show searches:

q=crossing+lines+s01
q=csi+s10
q=fringe+s01
q=fringe+s05
q=graceland+s01
q=how+i+met+your+mother+s05
q=king+and+maxwell+s01
q=major+crimes+s02
q=motive+s01
q=true+blood+s04

These are the only quieries that the script recognizes — 
the instructor made each of these specific queries and saved the 
output in local files that are accessed when you run the script. 
No other parameters will be recognized.



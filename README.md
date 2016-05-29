# transmission.d-lib
###PHP Library for interacting with the *nix transmission-daemon

####Usage:

put transmission credentials into authentication.php then include 'transd-lib.php' into your application.


**example usage:**
  
  $torrents[1]->start();         //Start torrent #1
  
  $torrents[1]->stop();          //Stop torrent #1
  
  $torrents[1]->info();          //Retrieve all info for torrent #1
  
  $torrents[1]->getName();       //Retrieve the name of the torrent
  
  addTorrent("/tmp/myTorrent.tor"); //Adds via magnetlink or local file
  
  setSpeed(1000,200);               //Sets upload/download speed limit. 0 = no limit
  
  
  
**Torrent file properties:**
  
![test](http://i.imgur.com/YliXOnF.png?2)

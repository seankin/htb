# htb

Delivery was a excellent starting machine. 

![Parcel](Delivery/delivery.jpg)

Enumeration and explotation of a ticketing system to create an internal account with granted access to a internat chat system (Mattermost). A open conversation had details of the server login and password. By SSH into the server (first flag), we could get a list of the SQL database login. From there we logged on the SQL server to get the hash password of the 'root' user and used HashCat and John the ripper to crack the password. This lead to root access on the server (second flag). 



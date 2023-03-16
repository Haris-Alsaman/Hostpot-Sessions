## FEATURES


Saving the process of logging in with MAC, Hostname, and the specified time.
Monitoring the card breaches and thefts.
Monitoring the customers and when the peak time is.
Tracking the status of the cards and when the login and logout occurred with precision.
Detecting if the cards have been breached, for example, if a specific Hostname is used to log in and a different Hostname is used to log out.



## installation

First, we put the following command in the on-login user profile:
/import alssman;

Secondly, we put the following command in the on-logout user profile:
/import alrahp

Thirdly, we put the following commands in the new terminal:

/system identity print file=("Reports_user2")
delay 2s
/file set ("Reports_user2") contents=("")


## images

<img src="https://github.com/Haris-Alsaman/Hostpot-Sessions/blob/main/80.PNG" width="440">

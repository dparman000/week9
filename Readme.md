## HoneyPot Challenge

## Hours Spent: 10

## Which Honeypot(s) you deployed: Ubuntu - Dionaea with HTTP

----------------------------------------------------------------------
## Any issues you encountered
Issue 1
https://github.com/RedolentSun/mhn.git Installing from this Repo did not work 
 https://github.com/HurricaneLabs/pyev/ repsoitory not found so can  not install
 i had to fork  https://github.com/RedolentSun/mhn.git to my git and then change link for pyev
 to : https://github.com/gabrielfalcao/pyev.git#egg=pye
 
 Issue 2:
Google cloud did not provide default firewall to open http https port and no instructions provided.

 Issue 3:
To Download session.json provided command:gcloud compute scp mhn-admin:~/session.json ./session.json  Did not work
Changed to:  gcloud compute scp mhn-admin:session.json ./session.json This worked
-----------------------------------------------------------------------

## A summary of the data collected: 
Number of attacks: 4266

## Any unresolved questions raised by the data collected
No

# Guacamole Setup
For this install, I completely used the following repo:<br>
```https://github.com/boschkundendienst/guacamole-docker-compose```

A copy of this repo can be found in this directory.

This method has run reliably in my homelab for almost a year now (as of November 2025).

 ## Notes
Within the repo's README, there is no explicit instruction to run ```docker compose up -d``` after running ```./prepare.sh```. When first using this repo, I assumed that the Bash script autoexecuted the docker compose command.


After running ```docker ps``` and seeing that ```guacamole_compose```, ```nginx_guacamole_compose```, ```guacd_compose``` and ```postfres_guacamole_compose``` are all healthy, you may go to ```https://<machine-ip>:8443``` and log in with the default credentials.

Default username: ```guacadmin```
Default password: ```guacadmin```

Personal IaC playbook for setting up a home media server. This is my first IaC project, so it's going to be a bit rough around the edges, I wouldn't recommend using this for anything other than inspiration or especially using it anywhere exposed to the internet.  
Feel free to open an issue if you have a recommendation or question, or if you spot some glaring issue I've missed.

Script assumes a fresh non-LTS ubuntu server with ssh keys already set up. (installer allows pulling public keys from github, very convenient)  

TODO
- [x] Get connected to server
- [x] Essentials
  - [x] Update/Upgrade
  - [x] Passwordless sudo
  - [x] Users/Groups
- [ ] Docker
- [ ] Ngnix ssl reverse proxy
- [ ] Pi-hole
- [ ] Backups
- [ ] arr suite
- [ ] Jellyfin
Painless install.

Few notes:
- to run just do `ansible-playbook main.yaml`
- tested on ubuntu 20lts with nifi14
  - if you do not use ubuntu, pls change java pkg name in inventory vars
- Network:
  - nifi will be available at 0.0.0.0:8080
  - take care to open ports in firewall

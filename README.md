# Setup my Fedora workstation

## pre-requisites
* Download ICAReciever from the Citrix website into the projects root folder.
* Install ansible

``` bash
sudo dnf install ansible
```

### Run setup
``` bash
ansible-playbook playbook.yml -K
```

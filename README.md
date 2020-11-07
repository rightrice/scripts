# scripts

The intent of this repo is to share my .yml files and what I found using playbooks, containers and VM's as a whole.

---

Virtual Machines or VM's:
VM's have been a rather interesting experience. We started out with local VM's through Vagrant but we then moved on to Microsoft Azure VM's which were a lot more fun and in depth than the Vagrant VM's. Within Azure we created VM's, built network firewalls and created files and tasks within these VM's. One of the tasks we needed to do was create a Kabana server. This was a relatively simple task which didnt get complicated until it was time to collect docker logs. All in all, creating the repo was the hardest part of the porject. 

---

Playbooks or .YML files
The playbooks were sometimes easy and sometimes complicated. It seemed like everyone had their own form of an issue. Whether it be an IP, or a miss configured .YML file or if they didnt have the VM running. It seems like .YML files could be prone to being an error in the process. The playbooks are what the user uses to do a certain amount of given tasks at once. In short, it makes the startup of a script a lot quicker and smoother is all is setup properly. We used premade playbooks, and only had to change the users and IP's for the playbooks. .YML files are incredibly picky on how they are written. 

---

Containers
The containers were tricky. Containers were within the VM's and at points it was tricky to know which playbook you should be in and when. The containers are within the docker program and are a VM within a VM in a sense. Within the container is where we ran the playbooks originally.

---

Kabana
We used Kabana, as mentioned earlier, to view if logs were able to be uploaded to the server properly. Kabana was run on a seperate VM than the VM where the play books were run.


steps to run a test build this repo locally using docker container: 
========================================================================

<br>

### Prerequisites: 

<br> 

* do a ```git pull``` or ```git clone``` to obtain latest version of this repo 


<br>

### Pull the dependencies

<br>

```sh 
cd ./roles 
ansible-galaxy -f -r requirements.yml -p `pwd` install  

```

or manually, using git. 



[root@localhost /] # cd /srv/ansible && ansible-playbook -i localhost playbook-docker.yml

```


*** 



# Vagrant

###  Description
In this project we are going to install vagrant and to learn how to work with it as a part of the curriculum of software engineering for holbertonschool-zero_day module at Holberton School.


### Usage
- First of all we need to install git as follow on the terminal:



      $ sudo apt-get update
	  $ sudo apt-get upgrade
	  $ sudo apt-get install git



- Then we [install](https://www.vagrantup.com "install") vagrant.

Vagrant provides easy to configure, reproducible, and portable work environments built on top of industry-standard technology and controlled by a single consistent workflow to help maximize the productivity and flexibility of you and your team.

- Open a terminal and run vagrant box list will print the list of boxes available on the computers.

`$ vagrant box list`

- To initialize vagrant (create a Vagrantfile) run the following command: vagrant init.

`$ vagrant init`

Open the file Vagrantfile with your favorite editor (probably Emacs or vi). Find the config.vm.box variable and replace base or any other value with your Ubuntu VM name, in this case ubuntu/trusty64.

It should look something like this when you open the Vagrantfile for the fist time:


> Every Vagrant development environment requires a box. You can search for
boxes at https://atlas.hashicorp.com/search.
> config.vm.box = "base"



- Save your Vagrantfile and go back to your shell. Run vagrant up to start the virtual machine.


`$ vagrant up`

- In order to go into your VM, run the vagrant ssh command.

`$ vagrant ssh`

###### Now we are  in our Ubuntu VM. Now we are  in our Ubuntu VM.

###Basic usage
At the end of this project you should be able to reproduce and understand these command lines:


```
      $ git clone <repo>
	  $ touch test
	  $ git add test
	  $ git commit -m "Initial commit"
	  $ git push origin main

```

### Tasks :
|  Task | Description  |
| :------------: | :------------: |
| Task 0  | Create and to setup the git and the github account |
| Task 1  | Create a new directory with it's readme file |










[![Holberton school](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcT8g8Cvqw9Z7Rx9IHGq9gKYneeM1U4_KvUNTeaCBkX2L5pFE3Ihw-5uNGs9xPSmUb5kXA&usqp=CAU)](https://www.holbertonschool.com/tn/en/ "Holberton school")



Project made for [Holberton school](https://www.holbertonschool.com/tn/en/ "Holberton school") by  [Rim Joudi](https://github.com/RimJoudi "Rim Joudi").
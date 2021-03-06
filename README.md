# setUpVMusingVagrant

## What's inside setUpVMusingVagrant.sh?
With this script we will create <br/>

- workspace for our VM
- initialize a vagrant box
- a index.html file and run that using apache2 in our VM
- a bootstrap.sh file and provision it to Vagrantfile automatically.
- reload the VM after provisioning and vagrant ssh to run index.html file

## How to use
Make sure you have virtual box installed in your system <br/>
(You can skip this if already installed)<br/>
> run sh ./install-virtualbox.sh <br/> 
--------------------------------------------------------------------------------------
Once virtual box installed you can run script to create VM, <br/>
(Make sure to edit vm box name from https://app.vagrantup.com/boxes/search) <br/>
> run sh ./setUpVMusingVagrant.sh </br> 

- There is a sample workspace created inside this script, you would need to modify according to your need. Like for example in this script we are doing cd to ubuntu, you would need to create directory and cd to that according to your use-case.<br/>

## Screenshot
![vagranttechhub-1](https://user-images.githubusercontent.com/76727343/144647566-ef03cb87-55ee-4860-b4a5-bd464ec45ebc.png)

You can get more info about Vagrant from **What-and-why-of-Vagrant.md** and commands from **vagrant-commands.md** <br/>

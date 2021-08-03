# vagrant
Some Vagrantfile to dev.

## Usage
Example to Vagranfile_splunk  

```bash
$ cd CURRENT/WORKDIR/VAGRANT

$ ls 
Vagrantfile_splunk

$ VAGFILE=Vagrantfile_*
mv ${VAGFILE} ${VAGFILE%_*}

$ ls
Vagrantfile

$ vagrant up
```

## Vagrantfile_splunk
Setup a box with Splunk.  
Need modify the path and RPM name of Splunk.  
Aka :  
  - vm1.vm.provision "file", source: "~/Downloads/splunk-8.0.6-152fb4b2bb96-linux-2.6-x86_64.rpm", destination: "/vagrant/"
  - sudo yum localinstall /vagrant/splunk-8.0.6-152fb4b2bb96-linux-2.6-x86_64.rpm -y

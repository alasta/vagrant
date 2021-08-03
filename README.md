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

# mikrotikrouterpingutiltiyapt
mikrotikrouterpingutiltiyapt 2.0 upload

In case you have an older version of the utility installed remove that by running the following command before installing this current version of mikrotikapiping apt package

<b>sudo apt-get remove mikrotikapiping</b>

If the enviornment (VM) is ready, along with the necessary resources (KeyVault, StorageAccount/Blob) MikrotikAPI tool by running the following commands

$ wget -qO - https://raw.githubusercontent.com/komalashrafsyed/mikrotikapipingutilityapt/master/PUBLIC.KEY | sudo apt-key add -
$ echo "deb https://raw.githubusercontent.com/komalashrafsyed/mikrotikapipingutilityapt/master bionic main" | sudo tee /etc/apt/sources.list.d/mikrotikapiping.list
$ sudo apt-get update
$ sudo apt-get install mikrotikapiping
$ export PING_HOME=/opt/ksyed/mikrotikapiping/MikrotikAPIPing.dll

At this stage the Ping Utilty is installed in your system ready to be used!

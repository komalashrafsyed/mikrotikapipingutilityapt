# mikrotikapipingutilityapt
mikrotikrouterpingutiltiyapt 2.0 upload

$ wget -qO - https://raw.githubusercontent.com/komalashrafsyed/mikrotikapipingutilityapt/master/PUBLIC.KEY | sudo apt-key add -
$ echo "deb https://raw.githubusercontent.com/komalashrafsyed/mikrotikapipingutilityapt/master bionic main" | sudo tee /etc/apt/sources.list.d/mikrotikapiping.list
$ sudo apt-get update
$ sudo apt-get install mikrotikapiping
$ export PING_HOME=/opt/ksyed/mikrotikapiping/MikrotikAPIPing.dll

$ sudo dotnet $PING_HOME

At this stage the Mikrotik Ping UtiltyUtiltiy is installed in your system ready to be used!

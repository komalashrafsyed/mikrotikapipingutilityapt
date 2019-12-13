# mikrotikapipingutilityapt
mikrotikrouterpingutiltiyapt 2.0 upload

In case you have an older version of the utility installed remove that by running the following command

<b>sudo apt-get remove mikrotikapiping</b></br>

$ wget -qO - https://raw.githubusercontent.com/komalashrafsyed/mikrotikapipingutilityapt/master/PUBLIC.KEY | sudo apt-key add - </br>
$ echo "deb https://raw.githubusercontent.com/komalashrafsyed/mikrotikapipingutilityapt/master bionic main" | sudo tee /etc/apt/sources.list.d/mikrotikapiping.list  </br>
$ sudo apt-get update </br>
$ sudo apt-get install mikrotikapiping </br>
$ export PING_HOME=/opt/ksyed/mikrotikapiping/MikrotikAPIPing.dll </br>

$ sudo dotnet $PING_HOME </br>

At this stage the Mikrotik Ping UtiltyUtiltiy is installed in your system ready to be used! </br>

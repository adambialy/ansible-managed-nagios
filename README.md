ansible managed nagios
======================

I know, I know nagios is old, nagios must die, everything needs to be virtual, grafana, kibana etc...

However some of us still use it at home, and I created this to quickly deploy nagios on deb systems. 

Currently it's only generating hosts/services config. Will do the rest soon (I mean installing and configuring nagios)


Requirements
------------

runinng nagios4
TODO: 


Dependencies
------------

Clone some repos with nagios checks

```git clone https://github.com/willixix/naglio-plugins.git     /opt/WL-Nagios-Plugins 
 git clone https://github.com/JasonRivers/nagios-plugins.git  /opt/JR-Nagios-Plugins  
 git clone https://github.com/justintime/nagios-plugins.git   /opt/JE-Nagios-Plugins  
 git clone https://github.com/nagiosenterprises/check_mssql_collection.git   /opt/nagios-mssql  
 git clone https://github.com/jpmens/check-mqtt.git           /opt/jpmens-mqtt        
 git clone https://github.com/danfruehauf/nagios-plugins.git  /opt/DF-Nagios-Plugins``` 

wget https://gitlab.com/6uellerBpanda/check_pve/-/archive/master/check_pve-master.zip

License
-------

GPL

Author Information
------------------


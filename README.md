Suricata-Logstash-Templates
===========================

Templates/Dashboards for Kibana to use with Suricata IDPS


This repository provides 12 templates for the Kibana interface of Logstash
for use with Suricata IDS/IPS - Intrusion Detection and Prevention System.

These dashboards are for use with Suricata and ELK - Elasticsearch, Logstash, 
Kibana. You can install all of them following the guide here:

https://redmine.openinfosecfoundation.org/projects/suricata/wiki/_Logstash_Kibana_and_Suricata_JSON_output  

or you can just try them out ready to use with SELKS:

https://www.stamus-networks.com/open-source/


The templates found in the Templates directory:

- ALL  
- ALERTS 
- DNS  
- FILE Transactions  
- FLOW  
- HTTP  
- HTTP-Extended-Custom  
- PRIVACY
- SMTP
- SSH  
- TLS
- VLAN




==========
How to use
==========

     apt-get install git-core
     git clone https://github.com/pevma/Suricata-Logstash-Templates

That will create a directory - Suricata-Logstash-Templates - holding the templates.

 - Open your Kibana web interface
 - Right upper corner, Load -> Advanced -> Browse
 - Load the desired template(s)

NOTE:  
In order to use the HTTP-Extended-Custom template you need to set up Suricata as
explained here - http://www.pevma.blogspot.se/2014/06/http-header-fields-extended-logging.html  

NOTE:  
In order to use the VLAN template, make sure you have enabled vlan tracking in suricata.yaml -

     vlan:
       use-for-tracking: true

NOTE:  
For best user experience use with 1680 x 1050 screen resolution!!  

Do not hesitate to contribute !

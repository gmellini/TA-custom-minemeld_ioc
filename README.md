# TA-custom-minemeld_ioc
Technology Addon to parse MineMeld miners events (eg. IoC updates, withdraw)

Have a look at my blog post to configure Splunk/MineMeld integration
 http://wp.me/p6LD4A-9f

Possible TA Tuning:
- change timezone in default/props.conf to your TZ (see https://en.wikipedia.org/wiki/List_of_tz_database_time_zones)
- change eventually sourcetype and index in default/inputs.conf
- if sourcetype is changed adjust stanza name in default/props.conf 
- change tcp listening port in default/inputs.conf

Note: you can edit default/\*.conf files or add your changes to the same files to be created in local/ dir

*IMPORTANT*
Install the TA in the Splunk forwarder(s), the servers that receive MineMeld JSON data.

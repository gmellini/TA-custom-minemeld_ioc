# TA-custom-minemeld_ioc
Technology Addon to parse MineMeld miners events (eg. IoC updates, withdraw)

Have a look at this blog post to configure Splunk/MineMeld integration
 http://wp.me/p6LD4A-9f

TA Tuning:
- change timezone in default/props.conf to your TZ (see https://en.wikipedia.org/wiki/List_of_tz_database_time_zones)
- change sourcetype and index in default/inputs.conf
- change tcp listening port in default/inputs.conf

# TA-bro_json

**Derived from https://splunkbase.splunk.com/app/1617/ to accommodate bro logging in json format.**

Bro logging can be changed from the default of TSV output to json by modifying the ascii.bro file as follows:

_Default location: /opt/bro/share/bro/base/frameworks/logging/writers/ascii.bro_

`const use_json = T &redef;` 

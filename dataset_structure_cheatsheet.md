# Dataset structure cheatsheet
Dataset data structure.

`amun.events.json`, `gastopf.events.json` and `snort.alerts.json` are data files created by splitting the main `honeypot.json` dataset into separate files by channel and extracting payload field \(this is one of the labs in the workshop\).

Not all the events will contain all the fields.

## honeypot.json
* _id
  * $oid
* ident
* timestamp
  * $date
* normalized
* payload
* channel

## amun.events.json
* timestamp
* connectionType
* attackerID
* attackerIP
* attackerPort
* victimPort
* victimIP
* downloadMethod
* vulnName
* shellcodeName

## glastopf.events.json
* time
* pattern
* filename
* request_raw
* request_url
* source \(array of IP and port\)

## snort.alerts.json
* date
* classification
* priority
* header
* signature
* sensor
* proto
* source_ip
* source_port
* destination_ip
* destination_port
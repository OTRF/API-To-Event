# API-To-Event

A repo focused primarily on documenting the relationships between API functions and security events that get generated when using such functions. This project leverages other projects to be able to validate and abstract the use of those apis:

* Windows
    * [PSReflect-Functions](https://github.com/jaredcatkinson/PSReflect-Functions)
    * [PurpleSharp](https://github.com/mvelazc0/PurpleSharp)
* AWS
    * [Boto3](https://github.com/boto/boto3)
    * [Pacu](https://github.com/RhinoSecurityLabs/pacu)

In addition, any dataset generated while testing and validating events will be stored in the [Mordor](https://github.com/Cyb3rWard0g/mordor) project.

# Goals

* Share lists of API functions mapped to security events
* Help security analysts to understand what it is that can trigger specific security events
* Enhance detections adding context on API functionality

# Getting Started

* [List of API-To-Events](https://docs.google.com/spreadsheets/d/1Y3MHsgDWj_xH4qrqIMs4kYJq1FSuqv4LqIrcX24L10A/edit?usp=sharing)

# Authors

* Roberto Rodriguez [@Cyb3rWard0g](https://twitter.com/Cyb3rWard0g)

# Contributing

There are a few things that we would like to accomplish with this repo as shown in the To-Do list below. Share new API functions mapped to security events.

# License: GPL-3.0

[ API-To-Event's GNU General Public License](https://github.com/Cyb3rWard0g/API-to-Event/blob/master/LICENSE)

# To-Do

- [ ] Map project mappings to Mordor datasets (ATT&CK)
- [ ] Document AWS APIs to CloudTrail Logs

More coming soon...

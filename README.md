# API-To-Event

A repo focused primarily on documenting the relationships between Windows API functions and security events that get generated when using such functions. This project leverages on-demand PowerShell functions from the [PSReflect-Functions](https://github.com/jaredcatkinson/PSReflect-Functions) project to abstract Win32 API functions and the [Mordor](https://github.com/Cyb3rWard0g/mordor) project to validate the generation of events and store the data sets generated.

# Goals

* Share a list of Windows API functions mapped to security events
* Help security analysts to understand what it is that can trigger specific security events
* Enhance detections focusing on the Windows API functions used in adversarial tooling

# Authors

* Roberto Rodriguez [@Cyb3rWard0g](https://twitter.com/Cyb3rWard0g)

# Contributors

# Contributing

There are a few things that we would like to accomplish with this repo as shown in the To-Do list below. Share new API functions mapped to security events.

# License: GPL-3.0

[ API-To-Event's GNU General Public License](https://github.com/Cyb3rWard0g/API-to-Event/blob/master/LICENSE)

# To-Do

- [ ] Map project mappings to Mordor datasets (ATT&CK)
- [ ] Document AWS APIs to CloudTrail Logs

More coming soon...

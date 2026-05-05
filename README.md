## signal

[![CI](https://github.com/Oefenweb/ansible-signal/workflows/CI/badge.svg)](https://github.com/Oefenweb/ansible-signal/actions?query=workflow%3ACI)
[![Ansible Galaxy](http://img.shields.io/badge/ansible--galaxy-signal-blue.svg)](https://galaxy.ansible.com/Oefenweb/signal)

Set up [signal](https://signal.org/download/linux/) in Debian-like systems.

#### Requirements

* `software-properties-common` (will be installed)
* `dirmngr` (will be installed)
* `apt-transport-https` (will be installed)
* `wget` (will be installed)

#### Variables

None

## Dependencies

None

#### Example

```yaml
---
- hosts: all
  roles:
    - oefenweb.signal
```

#### License

MIT

#### Author Information

Mischa ter Smitten

#### Feedback, bug-reports, requests, ...

Are [welcome](https://github.com/Oefenweb/ansible-signal/issues)!

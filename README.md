# ad_hoc_archiver

*ad hoc* data logging for APS beam lines

CONTENTS

- [ad_hoc_archiver](#ad_hoc_archiver)
  - [Examples](#examples)
  - [Goals](#goals)

## Goals

- [ ] Run from read-only location
- [ ] Single script for server: initialize, start (resumes logging), stop
- [ ] Server is run by unprivileged user (such as instrument account)
- [ ] Configuration is saved locally
- [ ] Bulk import of PVs is possible
- [ ] credentials: LDAP & TLS?
- [ ] web interface
  - [ ] status
  - [ ] search
  - [ ] visualization
  - [ ] export

## Examples

- [CSS Channel Archiver](#examples) : installed on `/APSshare` (...)
- [EPICS Archiver Appliance](./epicsarchiver_appliance.md)

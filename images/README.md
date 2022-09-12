# Images

First successful image of working EPICS Archive Appliance (used QuickStart):

- ![working archappl](./2022-09-09%20archiver%20appliance%20working.png "working archappl")
  - Started a monitor on `gp:m1` (a motor record), waited until the archiver appliance
    reported an observation, then ran three Bluesky scans across a "peak".
    The lower window shows a plot of detector (`noisy`) vs. `gp:m1` position, the
    upper window tracks the `gp:m1` position as each scan progressed.

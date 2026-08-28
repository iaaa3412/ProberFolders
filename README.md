# ProberFolders backup

A periodic backup of `\prober\M\ETL\proberautomation`'s `GUI System`
folder (instrument profiles/addresses) and every `*ATA` project folder
(wafer maps, recipes, probe cards). Not the labviewtest code repo -
that lives at https://github.com/iaaa3412/Probe08 (moved to
https://github.com/iaaa3412/Prober).

To refresh: robocopy each of `GUI System` and the `*ATA` folders from
proberautomation over this directory, then commit and push.

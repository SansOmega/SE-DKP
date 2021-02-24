# SE-DKP
DKP Parser for Sovereign eternity

I created this parser to adapt SEs specific DKP strategy to the DKP tracking system.

I was unable to automate looking up raid events or loot so there are hardcoded string tables.

The codes is addmitedly a mess.  I hacked this together to get it working and like most things not professional my work stopped there.

There are actualy 2 tools:
-One to consume log files and raid dumps to formt he DKP upload which has a crappy half finished UI I havent replaced with a CLI.
-One to consume a log file and distill out only the loot rewards so that I dont have to get private log information from other splits.

The loot distiller is supposed to compile as a single exe but wont at the moment.

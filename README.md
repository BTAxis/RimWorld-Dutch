# RimWorld Dutch
This is the Dutch translation data for RimWorld.

See this page for license info:
http://ludeon.com/forums/index.php?topic=2933.0

## Status 14-01-2021

Current build version 1.2.2753

The Dutch translation still needs a lot of work, but progress has been made in the past year. Unfortunately, with a new expansion and many updates also coming out, the total amount of work has not gone down by much. 

A summary from the translation report tool:
Translation report for Dutch
- General load errors (0)
- Def-injected translations load errors (0)
- Backstories load errors (0)
- Missing keyed translations (213)
- Def-injected translations missing (2605)
- Backstory translations missing (1799)
- Unnecessary def-injected translations (marked as NoTranslate) (0)
- Def-injected translations using old, renamed defs (fixed automatically but can break in the next RimWorld version) (0)
- Argument count mismatches (may or may not be incorrect) (0)
- Unnecessary keyed translations (will never be used) (0)
- Keyed translations matching English (maybe ok) (101)
- Backstory translations matching English (maybe ok) (34)

This is a long list (the report is over 10100 lines long). If you want to start helping you can do so, follow the steps in http://ludeon.com/forums/index.php?topic=2933.0
Run the report tool once and it will give you pointers where to start exactly.

## Tips for contributors
- We recently changed the file format to have linux line endings (LF), if you work directly from this repository that should not affect you
- When running the cleanup from Rimworld, line endings are converted to Windows format (CRLF), be careful when checking in that you convert them back, for example using `find . -name *.xml -type f -print0 | xargs -0 dos2unix -m`
- When running the cleanup from Rimworld after an update, Background stories may get rearranged or renumbered, to avoid problems with this, we are using "Subtranslator", created by the Russian translator Elevator89: https://github.com/Elevator89/RimWorld-Subtranslator
- When running the cleanup from Rimworld, make sure you have Royalty installed as well, some strings end up in a different location otherwise.

## Official Translators:
**Active**
- BTAxis
- erenes

**Inactive (since November 2019)**
- Bas-Korver
- ConfusedWings
- datdenkikniet
- FabianReinshagen
- Gangleider
- Geertje123
- Gleb-spa
- ILxCAPO
- SaKenyi
- Sebasbongers
- Ser-Geeves
- Sjohn21

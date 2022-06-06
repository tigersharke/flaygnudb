# Flay GNU database
They say "There's more than one way to skin a cat" so there is surely many ways to take care of GNU.
## Synopsis
This idea is a mysql database of patches used in the FreeBSD ports system to ease further porting.

### Present concept
- Process, parse all of the patches within the files directory of ports which have them, necessarily automated. (over 32000 patches already)
- Organize in a useful table so that additional context can assist with discovering how to solve incompatibilities between Linux and FreeBSD (often hardcoded).

### Future planning
- How will this be provided, just the mysql database? Include the Makefile and automation script(s)?

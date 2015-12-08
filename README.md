openttd-tweaker
===============

A collection of tools that makes it easier to programatically create and modify OpenTTD maps and scenarios. No need for deep C++ knowledge or bit skills. Basic JSON knowledge is enough! :-)

This is free software - released as public domain.

Written by Johannes Lundberg.

## Getting started

    $ git checkout https://github.com/Hack46/openttd-tweaker
    $ ./openttd-tweaker debug test.scn

    openttd-tweaker.. yay, let's go! :-)

    Loading test.scn... done.
    Decompresssing.. done.
    Parsing chunks.. done.

    Scenario statistics
    ===================

    ...


## Projects

Projects know to be using openttd-tweaker:

[OpenTTD-Sweden](https://github.com/Hack46/OpenTTD-Sweden) - Visualisation of public transporation in Sweden

## TODO

- [ ] Decompress SCN scenario files with LZMA from OTTX to OTTN
- [ ] Scenario chunk loading
- [ ] Map parsing (MAPT, MAPH, MAPO, M3LO, M3HI, MAP5, MAPE, MAP7)
- [ ] Debug command
- [ ] Debug statistics
- [ ] Scenario saving
- [ ] Compressed SCN writing
- [ ] Basic JSON specification of an OpenTTD scenario

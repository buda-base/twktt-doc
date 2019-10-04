# Trent Walker Khmer-Tai Transliteration documentation

This repository contains the documentation of the *Trent Walker Khmer-Tai Transliteration*, or in short **twktt** (pronounced [twakt]).

## History

#### Why a new transliteration

The transliterations that have been designed so far are oriented towards one main objective: representing Khmer and Tai data in a publication. Unfortunately, this leaves some room for interpretation in corner cases, which makes them difficult to be used programmatically. Most of them are also more specifically focused on one script or do not provide encoding for rare symbols.

This new transliteration aims at being fully complete and reversible in both directions (original script <-> transliteration).

## Documentation

- the file [chartable.md](chartable.md) contains the main character table, mapping transliteration and Unicode
- the file [doc.md](doc.md) contains details of some aspects of the transliteration (stacking, spacing, etc.)
- the [images/](images/) folder contains images used to represent characters not currently available in Unicode (for the Khom and Tham scripts)

## Bibliography

## Systems and software using twktt

[BDRC](https://www.tbrc.org/) is using twktt for its metadata.

## License and Copyright

No patent has been filled for the transliteration and if copyright need to be claimed, it is:

Copyright (C) Trent Walker, [CC0 License](http://creativecommons.org/publicdomain/zero/1.0/).

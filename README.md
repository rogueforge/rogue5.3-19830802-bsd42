# Rogue 5.3

Reconstructed source for Rogue 5.3 (Toy, Arnold, Wichman; Berkeley 1983).
Compiled with a modified 4.2BSD toolchain, it byte-exactly reproduces
`4.2/usr/src/games/rogue/distmod.obj`
(md5 `cd189328b43b3cbc5967d09be605abd6`) and the installed binary
`4.2/usr/games/rogue` (md5 `21e41b154a09b52f437846657b66a7cc`) from CSRG
Archive CD-ROM Disc 1. `rogue.me` is the guide source
(`4.2/usr/src/games/rogue/rogue.doc`,
md5 `8cb239a28b76fb3504555cf702d868ab`). `rogue.6` is the manual page from
4.2BSD (`usr/man/man6/rogue.6`, md5 `6f5fc22d4a7c8e1555828cbc03812363`).

The binary object retained a full symbol table, so identifier names are
recovered from it; comments and whitespace are inferred from available
sources, as is most of the Makefile.

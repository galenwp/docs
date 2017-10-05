---
navhome: /docs
next: True
sort: 2
title: Boot
---

# Boot your urbit

On disk your urbit is an append-only log and a checkpoint. Or, in
simpler terms, a directory where we keep your urbit’s state. We call
this a ‘pier’.

## Initialize

To create an urbit, we need an identity. This identity is both a network
address and a memorable name.

You are probably creating one of two kinds of urbit: a 32-bit "planet"
or a 128-bit "comet." For a quick terminology guide and high-level
refresher, refer to this [handy reference sheet](/docs/about/glossary).

If you have an Urbit invitation, you'll have a planet like
`~fintud-macrep` and `~fortyv-tombyt-tabsen-sonres`. To create your
pier:

    $ urbit -w fintud-macrep -t fortyv-tombyt-tabsen-sonres

This will create a directory `fintud-macrep/` and begin building your
urbit. This may take a few minutes.

If you do not have a ticket, you can still make a 'comet', a wild urbit
drifting through cyberspace. Pick your own directory name, it doesn't
matter:

    $ urbit -c mycomet

This will create the directory `mycomet/` and generate a 128-bit
identity for your urbit.

When your urbit is finished booting you should see a `dojo>` prompt.
Welcome!

o learn more about using the system, let's keep going:

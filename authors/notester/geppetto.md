---
title: geppetto
description: a lil midi control modulator
published: true
date: 2023-03-26T16:19:24.923Z
tags: midi, norns
editor: markdown
dateCreated: 2023-03-26T16:19:24.923Z
---

## screenshots

![geppetto.png](/community/notester/geppetto.png)

## description

Geppetto sends program change messages and modulates CC along a configurable LFO. In its current state it allows for the control of a single device using a single CC pinned to a single LFO (clocked to the system). It will likely grow with time.

Device configurations are user supplied in the `code/geppetto/lib/devices` directory. Two example configs are provided. The format: 

```
return {
  make = str,
  model = str,
  program_zero_indexed = bool,
  control = tbl { [int] = str },
  program = tbl { [int] = str }
}
```
PRs with additional device configs are welcome and encouraged.

## install

from maiden type
`;install https://github.com/cachilders/geppetto.git`

## links

- [view on llllllll](https://llllllll.co/t/geppetto/61551)
- [view on github](https://github.com/cachilders/geppetto)
{.links-list}

---
navhome: /docs/
sort: 23
title: Hoon cheatsheet
---

## A Hoon cheatsheet

##### `~rovnys-ricfer`

<br />

*Original `fora` post* [*here*](https://urbit.org/~~/fora/posts/~2017.9.18..22.31.06..24d5~/).

Here's a Hoon cheat sheet: [_.pdf_](https://storage.googleapis.com/media.urbit.org/hoon-cheat-sheet-08-26-17.pdf)

It's missing a few of the literal syntaxes (Hoon is rather spectacularly baroque
with its literals), but it covers the most common ones. This also does not list 
any of the `%ford` runes, although there is now at least some documentation for 
those [here](../../arvo/internals/ford/runes). 

The following runes also exist, but are currently undocumented and not listed in the cheat sheet:

```
!:  ::  turn on debugging printfs
!.  ::  turn off debugging printfs
!;  ::  using the "type of type", emit the type for an expression
!,  ::  emit AST of expression
$*  ::  bunt (irregular form is *)
^.  ::  use gate to transform type
^&  ::  zinc (covariant) -- see the advanced types doc
```

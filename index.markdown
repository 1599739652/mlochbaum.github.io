---
layout: page
title:  "Repositories"
---

This page is a resume-like overview of my open-source work. It describes
the purpose of each project and the extent of my contributions. Most
projects also have an adequate README file, but these are intended for a
typical user of the project and may require niche knowledge (e.g. of J)
to understand.

# Personal projects

All code designed and written by me.

## ILanguage
I is an experimental (avant-garde, even) programming language inspired by
J. <!-- TODO -->

## JtoLaTeX
This is a half-compiler, half-preprocessor which creates LaTeX using J
code. It replaces J operations with symbolic counterparts to build a
syntax tree, and then turns the tree into LaTeX code. A particular design
goal is to make the output code look natural even when the input is
idiomatic J. The converter uses knowledge about order of operations and
mathematical convention to parenthesize only when necessary, and it is
very rare to need to add or remove parentheses while using JtoLaTeX.
Addons provide other utilities like matrix handling, uncertainty
calculation, greek and other symbols, and set notation.

The base code and the more important addons are well-documented in the
`doc` folder.

## JSound
These are the utilities I use for music mixing and mastering, as well as
some other tools for working with sound. Features include a tool for
reading and writing wave files, a large collection of IIR filters, and
sound synthesis tools.

## JScripts
Various J scripts not large enough to merit an entire repository.

## vim-earl-grey
Earl Grey is a compile-to-Javascript language with (in my opinion) a very
elegant design. I hope to work with it more in the future. This repository
is a vimscript code for highlighting it. Harder than it sounds, since the
grammar used from highlighting is far from context-free!


# Collaborations

Projects that I have contributed to significantly. My contributions are
noted.

## J programming language
J is my programming language of choice, and I am one of a handful of
people who work with the source code at the moment. Although J has been
open source since 2012, various problems made it impossible to contribute
to the project until much more recently (early 2016).

### jsource/jsource
The official Github mirror of J's source. Most of my contributions should
appear here eventually.

### unbox
A fork of the J source code. I prefer to work with it over the official J
source since the build system is nicer, and my changes appear here first.

### openj/core
Defunct. I keep it around because there are still some changes which I
have not added to unbox.

## htmllint
A school project that I and three other students designed for a class at
UNC, with input from a small team at IBM. I am now the sole active
maintainer. This does not mean I want to work in web dev.


# Forks

Projects that I have changed, but only to a small extent.

## exafmm
A project which aims to unify research on the fast multipole method so
that variations on the algorithm (in particular, different kernels) are
easily comparable. I made several modifications to exafmm for my master's
thesis and am working on merging some of them back in.

## st
The terminal I use. The only significant change from the code distributed
by suckless is the addition of xft font rendering.
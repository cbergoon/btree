# BTree implementation for Go

Fork adds support for itype which allows type data to be included throughout logic. This specifically allows sharing of Item across trees while maintaining different ordering. 

![Travis CI Build Status](https://api.travis-ci.org/google/btree.svg?branch=master)

This package provides an in-memory B-Tree implementation for Go, useful as
an ordered, mutable data structure.

The API is based off of the wonderful
http://godoc.org/github.com/petar/GoLLRB/llrb, and is meant to allow btree to
act as a drop-in replacement for gollrb trees.

See http://godoc.org/github.com/google/btree for documentation.

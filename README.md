# BTree implementation for Go

Fork adds support for itype which allows type data to be propogated to Less() as a sort of context from the tree contruction. This allows for different orderings of the tree.

![Travis CI Build Status](https://api.travis-ci.org/google/btree.svg?branch=master)

This package provides an in-memory B-Tree implementation for Go, useful as
an ordered, mutable data structure.

The API is based off of the wonderful
http://godoc.org/github.com/petar/GoLLRB/llrb, and is meant to allow btree to
act as a drop-in replacement for gollrb trees.

See http://godoc.org/github.com/google/btree for documentation.

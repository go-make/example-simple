# example-simple

This repo is a super-simple example of how to use [go-make](https://github.com/go-make/make).

## Building the code

Since it's all about makefiles, try this:

```
make
```

## Exploring

Various files in this repo have been generated automatically by the go-make scaffolding.

Try the following:

```
go get github.com/go-make/make/...
go-make init -f
```

The second line there should force recreation of all files that have been auto-created.
With luck, you'll find that `git status` reports no changes!

You can also try removing them to see what's left:

```
rm -f $(go-make manifest)
git status
```

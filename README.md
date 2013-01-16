# Specter

Specter is an implementation of [GenTiradentes' TinyVM][tvm] in Go (the original is written in C).

This is very much to learn about virtual machines (this is my first attempt at a VM, so huge thanks to GenTiradentes for making a minimal one, easy to grasp).

It runs all examples available in TinyVM's repository, at [roughly 25% slower than C][bench].

## License

The [BSD 3-Clause license][bsd].

[bsd]: http://opensource.org/licenses/BSD-3-Clause
[tvm]: https://github.com/GenTiradentes/tinyvm
[bench]: https://github.com/PuerkitoBio/specter/tree/master/bench

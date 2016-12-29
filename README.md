Sil example repo
==================

This is a repository of live sil code.

The contents can be referenced from any
other sil module using the url `//frobnitzem.twenty_seventeen/<commit hash>`,
where `<commit hash>` is the git hash-code for this commit.

The results from running the code can be downloaded
from the main sil server,
`http://sque.predictivestatmech.org/api/v1/completed/<ast hash>`
where `<ast hash>` is the contents of this repo's `sil.sha1` file.

Sil has a simple commit hook that does a compile pass and then
ships the new source code to the main server for evaluation.

Sil is pure functional code, so all builds are parallel.


Get Involved
============

Sil is much bigger than this example.  It is an extensible,
distributed, parallel build system with built-in version control,
package management, and data distribution.
It makes collaboration possible like never before.

We are in the process of building modules for packed arrays
and scientific computing.  Our main focus is big data processing
using open data sets and algorithms.

You can contribute in many ways:

* Run a sil build-bot (shipping soon as a native client app in Chrome).
* Develop and publish your own sil code.
* Improve the sil compiler experience by developing on sil's own source.
* Send a feature request or suggestion for improvement!


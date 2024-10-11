This demonstrates that *.MODULE.bazel patterned files are not checked for dependencies

The project contains a file (in a real project this would be referenced by a MODULE.bazel - not shown):
- jfrog_deps.MODULE.bazel

Yet this file is ignored.

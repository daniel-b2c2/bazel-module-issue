This demonstrates that *.MODULE.bazel patterned files are not checked for dependencies

The project contains two files (in a real project these would be referenced by MODULE.bazel):
- jfrog_deps.MODULE.bazel
- maven_deps.MODULE.bazel

Yet these files are ignored.

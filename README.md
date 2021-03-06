# Bazel Homebrew Tap
This repository contains a collection of Homebrew (aka, Brew) "formulae" for Bazel

## Installing Bazel

```
$ brew tap bazelbuild/tap
$ brew tap-pin bazelbuild/tap
$ brew install bazel
```

or alternatively you can refer to formula by its full name

```
$ brew install bazelbuild/tap/bazel
```

Please note that if an older version of bazel from homebrew-core is being installed, you will need to uninstall that and specifically install the bazelbuild/tap version, with:

```
$ brew uninstall bazel
$ brew install bazelbuild/tap/bazel
```

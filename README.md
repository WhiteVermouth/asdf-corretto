# asdf-java

[![Build Status](https://travis-ci.com/WhiteVermouth/asdf-java.svg?branch=master)](https://travis-ci.com/WhiteVermouth/asdf-java)

[Java](https://www.java.com/en/) plugin for the [asdf](https://github.com/asdf-vm/asdf) version manager.

## Install

After installing [asdf](https://github.com/asdf-vm/asdf),
you can add this plugin like this:

```bash
asdf plugin-add java https://github.com/WhiteVermouth/asdf-java.git
```

and install new versions like this:

```bash
asdf install java corretto-8.212
```

and switch versions like this:

```bash
asdf global java corretto-8.212
```

## Reading

Read the [asdf readme](https://github.com/asdf-vm/asdf)
for instructions on how to install and manage versions of any language.

If you have trouble with any expected features,
have any feature requests or want to contribute,
please [do an issue](https://github.com/skotchpine/asdf-java/issues).

## Homage

This plugin wouldn't be possible without the current Java version managers.
Here's a list of repos with similar affects that were heavily referenced here:

- [jabba](https://github.com/hsyiko/jabba)
- [sdkman](https://github.com/sdkman/sdkman-cli)
- [Arch's JDK](https://aur.archlinux.org/packages/jdk/)

## Development

- asdf's [creating-plugins.md](https://github.com/asdf-vm/asdf/blob/master/docs/creating-plugins.md)
- [Bash Hackers Wiki](http://wiki.bash-hackers.org/)

# SlackBuild for brise

Rime schema repository

This software package contains a collection of configuration and data files used by Rime to support popular Chinese input methods.

A Rime input schema, which defines a specific input method in Rime's DSL, consists of a schema file named `*.schema.yaml` where `*` is the schema ID, and optionally an affiliated Rime dictionary file `*.dict.yaml`. In the following lists of Rime schemata, only schema IDs are listed for brevity.

## dependencies

* [librime](https://github.com/nnnewb/librime-slackbuild)

## usage

```
wget https://github.com/rime/librime/archive/rime-1.2.9.tar.gz
git clone https://github.com/slackwarecn/brise-slackbuild
cd brise-slackbuild
ln -s ../brise-0.35.tar.gz .
sudo sh brise.SlackBuild
```

# WAT

Automation of the automation to build zimbra.

Simply uses [ianw1974/zimbra-build-scripts](https://github.com/ianw1974/zimbra-build-scripts) (all the credits to Ian!) to automate a build
using github actions. Publishing the build to github releases for direct download. 

Should be an easy starter to automate the builds for all of us. 

Currently builind (can be easily extended, since we use matrix builds)
- Ubuntu 20.04

What it will be not:

- create patches for Zimbra of any sort (not the right repo)
- harm or violate Zimbra's Terms


## Usage

Either use the build artifacts (you should not IMHO), or clone this repo and do your own builds or whatever.

So just either see the builds under [.github/workflows](.github/workflows) and do what ever you like with it

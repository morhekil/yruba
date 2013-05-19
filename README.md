# Yruba

This is a github copy of the original project by Harald Kirsch, which is available [on his website](http://pifpafpuf.de/Yruba/). This copy was created with his permission, but all the credit still goes to the original author.

## Why Rules for Bash?

... because it's cool!

Yruba provides a rule system similar to make or ant for the shell. Compared to make there is no hairy mix of syntaxes, because everything is written in shell syntax. Compared to ant you don't have to rely on the ant developers to reinvent all the wheels that are so easily available from the shell. Compared to both, there is a clear separation between

- a list of dependencies that must be up-to-date before the current task can be performed,
- an explicit test that checks whether the target is really out-of-date, and
- a command that finally makes the target.

## Compatibility

Despite the name I would like yruba to work with POSIX shells. The current version is being developed with bash. I invite you to send me patches that remove dependence on specific bash features.

## Installation

There is nothing to install, really. Just download the script into a file called yruba, change the access rights to executable and run it. If you are running a Debian based system, you may prefer the debian package. In addition to the script, it also contains the html documentation for offline reading.

## Documentation

Please read the comprehensive [user guide](#).

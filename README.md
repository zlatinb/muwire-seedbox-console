The GitHub repo is a read-only mirror of the [I2P GitLab](https://i2pgit.org/zlatinb/muwire-seedbox-console) repo.

# MuWire Seedbox Console

Web console that manages one or more MuWire seedbox daemons.

Status: planning

## Motivation

Users may wish to deploy severl MuWire seedbox daemons - one needs to run on each seedbox - and have a central management console for all those instances.

## Features

The console will show basic stats for each managed daemon and will allow the operator to view advanced stats for each shared file on each seedbox daemon.  The console itself will not connect to the MuWire network, it will use the JSON-RPC interfaces of the daemons.


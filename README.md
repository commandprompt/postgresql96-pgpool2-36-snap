# postgresql96-pgpool2_36-snap

This is a collection of snapcraft recipes for Pgpool-II that can be used to create Pgpool-II snap packages.

The packages are maintained as a service to the community by Command Prompt, Inc. A PostgreSQL and Linux Professional services company.
You can find Command Prompt on the web at https://commandprompt.com

## Get binaries

If you don't want to build the binaries but instead just want to install the
packages, run this command:

`$ sudo snap install postgresql96-pgpool2_36`

## Build

Snapcraft recipes for each Pgpool-II version are found in separate branches. To build a specific Pgpool-II version simply check out a branch that corresponds to the version you need and run `snapcraft` in a root of that branch checkout.

## Install

To install a local build of a snap package run this command:

`$ sudo snap install --force-dangerous postgresql96-pgpool2-36_3.6.0_amd64.snap`

To install from Ubuntu Store simply run:

`$ sudo snap install postgresql96-pgpool2-36`

## Configuration

Refer to official documentation that explains how to configure Pgpool-II.


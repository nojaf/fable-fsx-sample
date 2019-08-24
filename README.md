# Fable 2.2 ~ Compiling script 

[![Build Status](https://travis-ci.org/nojaf/fable-fsx-sample.svg?branch=master)](https://travis-ci.org/nojaf/fable-fsx-sample)

## Requirements

Paket should be installed as global cli tool:

> dotnet tool install -g Paket

## Installation

> npm i

Installs both `node_modules` and `paket references`.
Generates `.paket/load/netstandard2.0/main.group.fsx` afterwards.

## Build

> npx webpack

## Run

> npx webpack-dev-server
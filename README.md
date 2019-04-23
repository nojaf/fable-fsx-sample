# Fable 2.2 ~ Compiling script

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
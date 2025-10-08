# sharelist-collection
This is a collection repo for sharelist project

## Submodules

This repository contains the following sharelist-related repositories as git submodules:

- **sharelist** - Main sharelist website
- **sharelist-client** - Vue-based client application
- **sharelist-cordova** - Cordova mobile app
- **sharelist-electron** - Electron desktop application
- **sharelist-server** - Backend server application

## Getting Started

To clone this repository with all submodules:

```bash
git clone --recursive https://github.com/antipro/sharelist-collection.git
```

If you've already cloned the repository without submodules, initialize them with:

```bash
git submodule update --init --recursive
```

## Updating Submodules

To update all submodules to their latest commits:

```bash
git submodule update --remote
```

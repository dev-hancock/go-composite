# go-composite

An experimental project to learn about Wayland compositors, written in Go.

## Goals

- Understand the architecture of Wayland compositors
- Explore how to use wlroots from Go via cgo
- Build a minimal working Wayland compositor in Go
- Experiment with window management, input handling, and rendering

## Status

Currently setting up a basic compositor loop using wlroots.

## Requirements

- Arch Linux or other Linux distribution with Wayland support
- Go 1.20 or newer
- wlroots (>= 0.17 recommended)
- wayland, wayland-protocols, libdrm, mesa, libinput
- (Optional) XWayland support for X11 apps

## Usage

```bash
go build -o go-composite
./go-composite

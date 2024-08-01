# godot-src-ctrl-test

## Description

A quick test repo to figure out how source control works for a Godot game engine project.

## How to load

1. Clone down this repository using `git clone https://github.com/jmcgorey/godot-src-ctrl-test.git`

2. Open the `project.godot` file using the Godot editor

    - You may also be able to import this project from the Godot project manager

3. Press "Run". You should see the basic tile map in the scene that opens.

## Src Control Notes

This really works like any other git repository. Once you make a change in the Godot editor and hit save, the file is marked as changed by git. You can use an interactive Git client (like Visual Studio Code or the Github desktop app) or the CLI to commit these changes to a branch and push them to remote.

## TODOS

-   Test: Do you need to reload the project if switching a branch or pulling down changes?

-   Consider using plugin instead of using external tools for VCS: https://github.com/godotengine/godot-git-plugin/wiki/Git-plugin-v3

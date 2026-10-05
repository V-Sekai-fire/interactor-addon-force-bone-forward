# interactor-addon-force-bone-forward

A Godot editor addon that re-rests an imported skeleton so each bone points toward its children.

## What it is for

It registers a scene post-import plugin that rotates every bone's rest pose to aim along one axis toward the centroid of its children, and corrects the skins' bind poses to match, so the meshes stay where they were.

## Install

Copy the repository into a project's `addons/force_bone_forward/` folder and enable the addon in the project settings; scenes imported afterward pass through it.

## Licence

MIT; see `LICENSE`.

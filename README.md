# Graal Level Viewer

**Graal Level Viewer** is a preserved Windows C# / Windows Forms tool for viewing **GraalOnline level files**. It is maintained as a historical development reference and experimental fork, with documented build requirements and upstream credit.

[Explore GraalOnline tools](https://rice2k.github.io/rice2k-startdeck/projects/?category=GraalOnline) · [View this repository](https://github.com/rice2k/Graal-Level-Viewer)

## Upstream attribution

This repository is a fork of **Deph0/Graal-Level-Viewer**. Credit for the original project belongs to the upstream project and its contributors. This fork is being preserved and documented for reference and continued experimentation.

## Project status

This is an older project preserved for reference and continued experimentation with Graal level tooling.

## Requirements

- Windows
- Visual Studio with .NET Framework 4.5 support
- Tao Framework/OpenGL assemblies used by the project

## Build notes

Open `GraalLevelViewer.csproj` in Visual Studio and restore or update the Tao library references before building. The original project file points to Tao DLLs through machine-specific local paths, so those references may need to be changed on a new computer.

The Release configuration outputs to `bin/Release/`.

## Repository notes

The project uses Windows Forms and includes the main application form, a level viewer control, project resources, and configuration files.

## Graal Online

This repository is a community/archival development project and is not an official Graal Online product.

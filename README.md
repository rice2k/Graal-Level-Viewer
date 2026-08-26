# Graal Level Viewer

A Windows desktop viewer for Graal Online level files, built in C# with Windows Forms.

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

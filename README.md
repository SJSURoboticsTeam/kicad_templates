# KiCad Templates for new projects

This is a set of templates for projects in KiCad.

## How to install

1. Press the green code button, and download this as a zip file.

2. Go to your KiCad Documents template directory.
  - On Windows this is Documents/KiCad/8.0/template
  - On MacOS this is ~/Documents/KiCad/8.0/template

3. Unzip the zip file such that the template directories (JLCPCB_1-2Layer, etc)
are directly inside of the template directory.

## Updating new projects

1. Open the PCB editor.
2. Go to File > Board Setup...
3. In the bottom left corner of the opened window, there is a Import Settings from another board.
4. Select all, then import.

## Usage

When creating a new project, there is a "Create project from Template" option. Go to "User templates,"
then choose the template depending on context. (For most of our projects, we use JLCPCB 1-2 Layer / JLCPCB 4 Layer)

## Purpose

Provides a number of additional Board and production house templates for KiCad EDA.

The templates here serve two purposes:
1. They provide the outline, standard position and shared components for common adapters
2. They setup basic board parameters such as DRC limits and preferred track widths

# CM32

Small C compiler (CM32) for the MMURTL OS that emits 80386 assembly for the DASM assembler.

## Overview
- Origin: Part of MMURTL by Richard A. Burgess (see header comments in `CM32.c` for original authorship and license notes).
- Scope: This repository contains a single-file port of the compiler: `CM32.c`. Non-library headers are in-lined to make reading easier.

## Repository layout
- `CM32.c` — single-file compiler and in-lined headers.
- `CM32.slnx`, `CM32.vcxproj*`, — Visual Studio project files.
- `README.md` — this file.

## Building
Recommended: Open the `CM32.slnx` in Visual Studio 2026 Community Edition.
- From the top menu, select `Build` -> `Build Solution`.
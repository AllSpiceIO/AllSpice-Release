## 0.6.0 (2020-12-14)
[SCH] Highlight diff items on hover
[SCH][PCB] Add loading spinner while processing diff
[GIT][BUG] Generate git history for files even if they aren't in root
[GIT] Lazy-load git history
v0.4.0 backend:
[SCH] Add object IDs to svg elements
[SCH] Fix bug causing crash on non-ascii component parameter names
[SCH] Add linecaps to schematics

## 0.5.9 (2020-10-24)
[PCB] Align PCB diff if board outline changes
[UI] Separate diff component text into part number, description

## 0.5.8 (2020-10-7)
[FIX] Fix PCB error causing board cutouts to fail
[FIX] Remove infinite loop causing high CPU usage

## 0.5.7 (2020-9-29)
[FIX] Increase timeout on back-end calls to allow more complex PCBs
[PERF] Filter CSS fade animation tag
[PCB] Optimize linejoing and linecap attributes for PCB svgs

## 0.5.6 (2020-9-24)
[PCB] Add render support for regions
[PCB] Add render support for holes in pad
[PCB] Add render support for advanced pad shapes
[PCB] Add render support for rotated pads

## 0.5.5 (2020-8-17)
[FIX|PCB] Allow PCB diff against null (added)
[FIX] check empty file diff (TortoiseGit fails on added files)

## 0.5.4 (2020-8-17)
[PCB] Pad support
[REF] PCB support in welcome screen

## 0.5.2 (2020-8-16)
[PCB] Support outline of PCB
[PCB] Via support
[FEAT] Loading spinner

## 0.5.0 (2020-7-20)
[FEAT] Collapse component attributes in diff
[PCB] [PERF] Join polylines
[PERF] More efficient JSON output
[BUG] Fix indentation on JSON output

## 0.4.3 (2020-6-23)

* [Fix] preserve multiple file extensions

## 0.4.2 (2020-6-23)

* [PCB] Tracks and Arcs Support
* [Schematic] Support Text Frames
* [Fix] Null file reference handled in diff

## 0.4.1 (2020-6-19)

* [Ref] Bump rev

## 0.4.0 (2020-6-17)

* [Feat] Check for updates

## 0.3.5 (2020-6-16)

* [Fix] '.schdoc' in filename causing TortoiseSVG to crash
* [Schematic] Allow net labels to rotate 180 degrees

## 0.7.0 (2021-11-11)
[SECURITY] Escape CSS selectors
v0.5.2 backend:
[FIX] Internal CI fixes
v0.5.1 backend:
[FIX] Fix KeyError during diff
[FIX] Security improvements related to external images
v0.5.0 backend:
[UTIL] Add --version
[PERF] Compress svg class names
v0.4.8 backend:
[BUG] Handle multi-order polinomial beziers
[REF] Outline region diff
[PERF] Diff color attributes to layer
[PERF] Move color attributes to layers
[FEAT] Add layers to pcbs
v0.4.7 backend:
[FEAT] Use more accurate linewidth enumeration
[FEAT] Display port direction
[FIX] Don't display hidden parameters in bottom left
[FEAT] Harness support
[FIX] Use correct owner in Altium properties in Addition Streams
v0.4.6 backend:
[FEAT] Schematic sheet entry support
[FIX] Negative radius warning in SVGs
v0.4.5 backend:
[FIX] Fix so that exit code is non-zero when there's an error
0.4.4 backend:
[FIX] Fix font style attributes from leaking across diffs
[FIX] Fix text alignment in labels and textframes
[PERF] Remove mask for pad holes
[PERF] Reduce SVG precision from default 6 to 5
0.4.3 backend:
[PERF] Internal performance improvements

## 0.6.1 (2021-04-17)
v0.4.2 backend:
[FIX] Support Altium 21
[FIX] Show schematic markers in Firefox
[SECURITY] Escape all text strings

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

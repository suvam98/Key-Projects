# CAD Automation Projects
### Calibre based Signal Tracer for specified signal
- Wrote a SVRF runset to trace the input Signals and dump it in stream-in Library.
- Uses SPF to get the signal coordinate for hierarchal signals using Python.
### Floating Net Check(Not Connected to base layer)
- Calibre runset based flow to highlight all the floating nets(in any hierarchy) except dummy fill.
- Python based parsing to extract all the floating nets(ln_*) from SPF file.
### Finding Available Routing Area
- Calibre runset based flow to highlight the available routing area for particular metals.
### Metal Cell Generation of a module for starRC run(In any hierarchy)
- SKILL + SVRF runset based flow to create layout & schematic View of Metal Cell.
- Extract all metals which are crossing over the Module from top-level design to module-level.
### LVS Extraction Report Update to add comment on text_open_merge error
- SKILL-based utility to identify text_open_merge & text_open_merge_inst errors and classify each error as PIN/NET in CSV file.
- Uses ".LAYOUT_ERROR" file to parse the text_open_merge error and Modifyed the pydb report database using synopsys ICV command.
### Text short on specified net
- SKILL + SVRF runset based flow to trace the net and extract all overlapping labels, and report them in a DFM RDB.
### Metal Patch cell generation for DRC Error Fix
- SVRF runset based utility to generate metal patch cell GDS for specific metal run-length DRC error and dump the GDS in stream-in Library.
### STD Cell Power Sharing to reduce layout Area
- SKILL-based utility to identify and highlight standard cells eligible for power sharing.
### Calibre CTO(Check text overwrite) File Generation & Optimization
- CTO File: Configuring Calibre RVE rule-check to display relevant layer specific to rule check & disabling others and categorizing rule checks for efficient debug.
- Developed csh script to run Calibre for CTO file extraction and optimize layer based Rule Check categories using Python.
### Label & SPF based signal Mark Net and Reporting
- SKILL + Python-based flow to mark nets using layout labels or SPF signal coordinates.
- Generated signal-wise reports of metal-layer width and length, along with via count.

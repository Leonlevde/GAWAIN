README — GAWAIN Calculation in ImageJ/Fiji (Macro Workflow)
Overview

This workflow uses two ImageJ/Fiji macros to calculate GAWAIN from a fundus image by combining (1) a user-defined foveal reference point and (2) manually outlined geographic atrophy (GA) areas.



Setup

Open ImageJ/Fiji.

Load the macros:

Go to Plugins → Macros → Install… (or open the macro editor and load them).

Open the image you want to analyze.

In the macro code, manually enter the foveal location:

Set the X and Y coordinates for the fovea

Run Macro 1.

This macro initializes the required regions/annuli based on the foveal coordinates.

Step 2 — Manually outline GA lesions

Select the Polygon Selection Tool.

Carefully outline a GA area.

After closing the polygon, click Delete (as instructed in your workflow) to apply the intended mask/operation.

Repeat for all GA areas in the image.

Step 3 — Run Macro 2 (calculation + output)

Run Macro 2.

This macro performs the GAWAIN calculation and prepares the output.

Export results to Excel

After Macro 2 finishes, the results are already selected and copied.

Paste directly into your Excel sheet (e.g., Ctrl+V / Cmd+V).

Done

You have now calculated GAWAIN for the image.

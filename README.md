# EJM_A_input_files
This repository stores the ABAQUS .inp files for all the simulations for the FE paper titled ``Through-thickness resolution, stress oscillations and residual stress in cold rolling"

Element types: CPE4R, CPE4 and CPE4I

Solver types: implicit and explicit

Number of elements through thickness: If Ne=30, this means that there are 30 elements through the half-thickness of the sheet, or 2Ne=60 elements through the full thickness.

Epsilon is h0/L, the ratio between the half thickness h0 and the horizontal length of the contact zone L

SlipTol is gamma in the paper

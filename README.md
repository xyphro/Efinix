# Efinix library

The intention of this repository is to share an Autodesk (Cadsoft) Eagle library done for all Efinix Trion (tm) FPGAs, including all package variants (WLCSP80, FBGA49, FPBGA81, FBGA169, FBGA256, FBGA324, FBGA400, FBGA484, FBGA576, LQFP144)

The library was autogenerated using a selfmade Python script using Efinix Pinout Excel sheets as available at 15th of August 2021 on their website. Some inconsistencies were found and addressed (e.g. WLCSP80 package column labels were not correct in Efinix package user guide).

The included .STEP files match the packages and can be assigned to the component using Eagle.

The library was done for Eagle 6.6, but is compatible with newer versions.

Disclaimer: Not the full library is tested - use it at own risk.

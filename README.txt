--------------------------------------------------------------------
Mobile Joint Operator (MoJO)
v1.0 - Oct. 2023
Maerz Lab, Department of Orthopaedic Surgery, University of Michigan
Primary Contact: Mike Newton (nemichae@med.umich.edu)
--------------------------------------------------------------------

This package includes:

- .STEP files for all custom parts of the MoJO platform
- A folder of photos and renders of the platform for reference
- .DOCX explanation of the mouse ACL rupture model
- .TMT file containing the ACL rupture loading profile
   * Built on UniVert software ver 12.28 (CellScale, Inc.)

Notes:

This platform was built for compatibility with the CellScale UniVert S2 uniaxial testing system with a 20N load cell. As of 2023, it is crucially important to select the S2 performance upgrade because the base UniVert model cannot accelerate to the 10 mm/s velocity required for the rupture displacement.

The knee bump, paw fixture, and top/bottom load cell adapter pieces were 3D printed using a Formlabs Form 3B printer out of Tough 2000 resin. Fixture designs were exported as .STEP files from Autodesk Fusion, converted to .STL files, imported into PreForm software, and sent directly to the printer. We utilized default print settings and 0.100 mm layer thickness.

Connections between parts were achieved using M3 and M5 bolts, along with brass tapping inserts (McMaster Part #s: 93722A204E308 and 93722A212E309). These inserts were threaded into 3D printed parts.

Other 3D printing technologies, such as filament-based printers, could also be used to print these fixtures. In this case, we would recommend a strong and durable filament such as ABS or nylon be used.

In our implementation of this platform, all pieces of the animal bed were fabricated from stainless steel and connected using M5 bolts. These pieces could also be 3D printed, though slight changes to hole diameters may need to be made to accomodate threaded inserts.

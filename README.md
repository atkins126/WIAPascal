# WIAPascal
WIA features for Lazarus (Free Pascal) and Delphi

# Installation

WIAPascal is a runtime library. There are no visual components that have to be installed. 
Just add the package to dependancy/required of your Lazarus/Delphi Application and start using it.

The library was created from scratch by Massimo Magnano since there was nothing written in Pascal about it.


# Library design

- VCL and LCL support (Windows-only).
- WIAPascal is not a TComponent descendand. 
  You have to use it from code only and free it by yourself (see the examples).
  For Lazarus use wiapascal_pkg.lpk package, 
  For Delphi use wiapascal_dpkg.dpk package (will be written and tested in the near future),
- Supported Compilers:
  Lazarus / Free Pascal
  VCL: (will be written and tested in the near future)

See the changelog.txt file for Change Log

Massimo Magnano (c) 2024

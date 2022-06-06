# ffp
Unofficial mirror of Fortran Function Parser from http://www.labfit.net/functionparser.htm

### General Information
 
* Creators: Wilton and Ivomar
* Version: 3.2
* Date added: 10/01/2007
* Date of the last update: 10/01/2007
* License: Free


### Fortran Function Parser Description

This code receives a string containing a mathematical expression that can be formed by 

- Numbers;
- Brackets;
- Functions (sin, cos, tan, asin, acos, atan, sinh, cosh, tanh, sind, cosd,
                  tand, log, log10, nint, anint, aint, exp, sqrt, abs, floor);
- Variables;

and returns the appropriate numeric answer.

See [Report](http://www.labfit.net/report.htm) with comparative analysis of the three existing open source functions parser in Fortran. To execute this code, create a workspace, unzip the zipped file and insert the following files at the project: 

- test.f90
- interpreter.f90

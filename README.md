
## tbdiag

This package provides functions for working with TB diagnostics data.
At the moment, it includes two families of functions: one for the
interpretation of Cellestis Quantiferon Gold In-Tube results, and one for 
interpreting Oxford Immunotec T.SPOT results.  These function-families can
interpret by the manufacturers' criteria for North America and at least one
non-American country (e.g., one QFT criteria set excludes the nil/mitogen
indeterminate and one T.SPOT criteria set excludes the borderline category).
More criteria will be added shortly; users can also extend the functions by 
creating new S3 methods for the qft.criteria and tspot.criteria functions.
 
### Results Validation

I've compared the results of these functions to several thousand lab-reported 
Quantiferon and T.SPOT results, and hand-calculated the correct results when 
faced with discrepancies.  While I believe that the current versions of these 
functions are very robust, they are provided with no warranty and I strongly 
encourage users to investigate any unusual results (and report back!)

### Acknowledgements

Special thanks to Randall Reves, MD and Bob Belknap, MD of the Denver 
Metropolitan Tuberculosis Clinic and the CDC's Tuberculosis Epidemiologic 
Studies Consortium (TBESC) for supporting the development of this package.

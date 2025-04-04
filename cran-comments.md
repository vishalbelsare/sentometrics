
## resubmission (version 1.0.1) [03/04/2025]

- removed one faulty URL --->

<!--- ## submission (version 1.0.1) [02/04/2025]

- fixed NOTEs about Rd files with link targets missing package anchors --->

<!--- ## resubmission (version 1.0.0) [17/08/2021]

- adjusted one URL --->

<!--- ## submission (version 1.0.0) [17/08/2021]

- version bump associated with release of JSS publication; the DOI in the CITATION is for a new JSS publication that will be registered after publication on CRAN --->

<!--- ## resubmission (version 0.8.4) [19/04/2021]

- adjusted one URL, dropped one test (resulted in minor differences only on Debian), added three packages to Suggests --->

<!--- ## submission (version 0.8.4) [17/04/2021]

**new**: internal compliance fixes related to newest quanteda API (resolves CRAN significant warnings) --->

<!--- ## resubmission (version 0.8.3) [17/02/2021]

- adjusted some URL and doi links that gave redirects (devtools::check_win_devel() revealed no remaining NOTEs) --->

<!--- ## submission (version 0.8.3) [13/02/2021]

**new**: minor bug and documentation fixes

- replacement of some order() calls, to get package back on CRAN --->

<!--- ## resubmission (version 0.8.2) [25/06/2020]

- modified invalid doi markup in CITATION file --->

<!--- ## submission (version 0.8.2) [24/06/2020]

**new**: minor bug and documentation fixes, release of website

- solves open CRAN errors on some platforms --->

<!--- ## submission (version 0.8.1) [11/03/2020]

**new**: compliance fixes related to new quanteda release --->

<!--- ## submission (version 0.8) [13/01/2020]

**new**: minor improvements --->

<!--- ## submission (version 0.7.6) [31/10/2019]

- fixed memory leak bug --->

<!--- ## submission (version 0.7.5) [30/10/2019]

**new**: slight bug, documentation and consistency fixes --->

<!--- ## submission (version 0.7) [12/09/2019]

**new**: increased the flexibility in the sentiment calculation (sentence-level calculation and more weighting schemes), simplified certain functionalities to allow for a more R-based workflow, added a Shiny application --->

<!--- ## submission (version 0.5.6) [17/12/2018]

**new**: very minor update (one function change and a few documentation fixes) --->

<!--- ## submission (version 0.5.5) [15/11/2018]

**new**: minor additions and simplifications

- resolved failing test for old R version 3.4.4
- diminished the number of Imports --->

<!--- ## submission (version 0.5.1) [20/09/2018]

**new**: minor modifications, mainly to resolve CRAN check issues

- set number of default threads used to 1, to avoid UBSAN warnings coming from usage of RcppParallel
- modified C++ code to avoid Solaris error --->

<!--- ## submission (version 0.5) [18/09/2018]

**new**: reimplementation of sentiment calculation code in C++, final set of API changes for better overall clarity, small bug and documentation fixes

- installed size > 5Mb, due to more compiled code
- examples now run significantly faster because of speed improvements --->

<!--- ## resubmission (version 0.4) [28/05/2018]

- modified example that took too long (to pass pre-test) --->

<!--- ## submission (version 0.4) [28/05/2018]

**new**: several additional functions and functionalities, and a few API changes --->

<!--- ## submission (version 0.3.5) [26/03/2018]

**new**: minor but necessary patches in to_global() and compute_sentiment() functions --->

<!--- ## resubmission (version 0.3) [18/03/2018]

- some examples modified to diminish elapsed time (to pass pre-test)
- R depends now >= 3.3.0, import of sentimentr omitted --->

<!--- ## submission (version 0.3) [18/03/2018]

**new**: several additional functions and arguments, small bug fixes and clarifications in documentation

- marked UTF-8 strings will remain; this is intentional and comes from the built-in French (mostly) and Dutch word lists --->

<!--- ## resubmission (version 0.2) [12/11/2017]

- added reference to vignette paper in 'Description' field of DESCRIPTION file
- we relocated the code to the GitHub repo 'sborms/sentometrics' 
- changed quanteda::tokenize() to quanteda::tokens() due to errors in automatic checks by CRAN --->


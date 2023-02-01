## Resubmission
This is a resubmission. In this version I have:

* Added two references describing the methods in DESCRIPTION file.

* Reduced simulation number from "sim = 100" to "sim = 10" for the examples in functions ("OneSampleBernoulli", "OneSampleNormal1", "OneSampleNormal2", "OneSamplePoisson", "TwoSampleBernoulli"), and unwrapped these examples in \donttest{}.

* Allowed R generate objects that can be used to extract the information a user is interested in, and then print that object.

## Test environments
- R-hub windows-x86_64-devel (r-devel)
- R-hub ubuntu-gcc-release (r-release)
- R-hub fedora-clang-devel (r-devel)

## R CMD check results
❯ On windows-x86_64-devel (r-devel), ubuntu-gcc-release (r-release), fedora-clang-devel (r-devel)
  checking CRAN incoming feasibility ...  NOTE
  
  New submission
  Maintainer: 'Chen Wang <wangc10@vcu.edu>'
  
0 errors ✔ | 0 warnings ✔ | 1 note ✖

* This is a new release.


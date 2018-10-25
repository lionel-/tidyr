# abjutils

Version: 0.2.1

## In both

*   checking package dependencies ... ERROR
    ```
    Package required but not available: ‘devtools’
    
    See section ‘The DESCRIPTION file’ in the ‘Writing R Extensions’
    manual.
    ```

# ActisoftR

Version: 0.0.2

## In both

*   checking re-building of vignette outputs ... WARNING
    ```
    Error in re-building vignettes:
      ...
    Quitting from lines 29-30 (ActisoftR.Rmd) 
    Error: processing vignette 'ActisoftR.Rmd' failed with diagnostics:
    there is no package called 'devtools'
    Execution halted
    ```

*   checking package dependencies ... NOTE
    ```
    Package suggested but not available for checking: ‘devtools’
    ```

# afex

Version: 0.22-1

## In both

*   checking Rd cross-references ... NOTE
    ```
    Packages unavailable to check Rd xrefs: ‘ez’, ‘ascii’
    ```

# ahpsurvey

Version: 0.2.2

## In both

*   checking re-building of vignette outputs ... WARNING
    ```
    Error in re-building vignettes:
      ...
    pandoc-citeproc: when expecting a product (:*:), encountered Object instead
    Error running filter /usr/local/bin/pandoc-citeproc:
    Filter returned error status 1
    Error: processing vignette 'my-vignette.Rmd' failed with diagnostics:
    pandoc document conversion failed with error 83
    Execution halted
    ```

*   checking dependencies in R code ... NOTE
    ```
    Namespaces in Imports field not imported from:
      ‘knitr’ ‘tidyr’
      All declared Imports should be used.
    ```

# aire.zmvm

Version: 0.6.1

## In both

*   checking data for non-ASCII characters ... NOTE
    ```
      Note: found 52 marked UTF-8 strings
    ```

# ALA4R

Version: 1.6.0

## In both

*   checking re-building of vignette outputs ... WARNING
    ```
    Error in re-building vignettes:
      ...
    gcc-8 -I"/Library/Frameworks/R.framework/Resources/include" -DNDEBUG   -I/usr/local/include   -fPIC  -mtune=core2  -O3 -c data2hill.c -o data2hill.o
    gfortran-7   -fPIC  -g -O2  -c decorana.f -o decorana.o
    make: gfortran-7: No such file or directory
    make: *** [decorana.o] Error 1
    ERROR: compilation failed for package ‘vegan’
    ```

*   checking package dependencies ... NOTE
    ```
    Package suggested but not available for checking: ‘vegan’
    ```

# alphavantager

Version: 0.1.0

## In both

*   checking package dependencies ... ERROR
    ```
    Package required but not available: ‘devtools’
    
    See section ‘The DESCRIPTION file’ in the ‘Writing R Extensions’
    manual.
    ```

# AMR

Version: 0.4.0

## In both

*   checking dependencies in R code ... NOTE
    ```
    Namespace in Imports field not imported from: ‘hms’
      All declared Imports should be used.
    ```

*   checking data for non-ASCII characters ... NOTE
    ```
      Note: found 67 marked UTF-8 strings
    ```

# amt

Version: 0.0.5.0

## In both

*   checking re-building of vignette outputs ... WARNING
    ```
    ...
    Attaching package: 'sp'
    
    The following object is masked from 'package:amt':
    
        bbox
    
    
    Attaching package: 'raster'
    
    The following object is masked from 'package:amt':
    
        select
    
    Warning in random_steps.steps_xy(., n = 15) :
      Step-lengths or turning angles contained NA, which were removed.
    Warning in random_steps.steps_xy(., n = 15) :
      Step-lengths or turning angles contained NA, which were removed.
    Quitting from lines 144-145 (p4_SSF.Rmd) 
    Error: processing vignette 'p4_SSF.Rmd' failed with diagnostics:
    there is no package called 'devtools'
    Execution halted
    ```

*   checking package dependencies ... NOTE
    ```
    Package suggested but not available for checking: ‘devtools’
    ```

*   checking dependencies in R code ... NOTE
    ```
    Namespaces in Imports field not imported from:
      ‘Rcpp’ ‘magrittr’
      All declared Imports should be used.
    ```

# anomalize

Version: 0.1.1

## In both

*   checking re-building of vignette outputs ... WARNING
    ```
    Error in re-building vignettes:
      ...
    Quitting from lines 15-24 (anomalize_methods.Rmd) 
    Error: processing vignette 'anomalize_methods.Rmd' failed with diagnostics:
    there is no package called 'devtools'
    Execution halted
    ```

*   checking package dependencies ... NOTE
    ```
    Package suggested but not available for checking: ‘devtools’
    ```

*   checking installed package size ... NOTE
    ```
      installed size is  5.6Mb
      sub-directories of 1Mb or more:
        help   4.7Mb
    ```

# anomalyDetection

Version: 0.2.5

## In both

*   checking tests ...
    ```
     ERROR
    Running the tests in ‘tests/testthat.R’ failed.
    Last 13 lines of output:
      33: tryCatchList(expr, classes, parentenv, handlers)
      34: tryCatch(withCallingHandlers({    eval(code, test_env)    if (!handled && !is.null(test)) {        skip_empty()    }}, expectation = handle_expectation, skip = handle_skip, warning = handle_warning,     message = handle_message, error = handle_error), error = handle_fatal,     skip = function(e) {    })
      35: test_code(NULL, exprs, env)
      36: source_file(path, new.env(parent = env), chdir = TRUE, wrap = wrap)
      37: force(code)
      38: with_reporter(reporter = reporter, start_end_reporter = start_end_reporter,     {        lister$start_file(basename(path))        source_file(path, new.env(parent = env), chdir = TRUE,             wrap = wrap)        end_context()    })
      39: FUN(X[[i]], ...)
      40: lapply(paths, test_file, env = env, reporter = current_reporter,     start_end_reporter = FALSE, load_helpers = FALSE, wrap = wrap)
      41: force(code)
      42: with_reporter(reporter = current_reporter, results <- lapply(paths,     test_file, env = env, reporter = current_reporter, start_end_reporter = FALSE,     load_helpers = FALSE, wrap = wrap))
      43: test_files(paths, reporter = reporter, env = env, stop_on_failure = stop_on_failure,     stop_on_warning = stop_on_warning, wrap = wrap)
      44: test_dir(path = test_path, reporter = reporter, env = env, filter = filter,     ..., stop_on_failure = stop_on_failure, stop_on_warning = stop_on_warning,     wrap = wrap)
      45: test_package_dir(package = package, test_path = test_path, filter = filter,     reporter = reporter, ..., stop_on_failure = stop_on_failure,     stop_on_warning = stop_on_warning, wrap = wrap)
      46: test_check("anomalyDetection")
      An irrecoverable exception occurred. R is aborting now ...
    ```

*   checking dependencies in R code ... NOTE
    ```
    Namespace in Imports field not imported from: ‘caret’
      All declared Imports should be used.
    ```

# arena2r

Version: 1.0.0

## In both

*   checking dependencies in R code ... NOTE
    ```
    Namespaces in Imports field not imported from:
      ‘purrr’ ‘shinyBS’ ‘shinydashboard’ ‘shinyjs’
      All declared Imports should be used.
    ```

# auctestr

Version: 1.0.0

## In both

*   checking dependencies in R code ... NOTE
    ```
    Namespace in Imports field not imported from: ‘tidyr’
      All declared Imports should be used.
    ```

# auk

Version: 0.3.0

## In both

*   checking examples ... ERROR
    ```
    ...
    > ### Title: Lookup species in eBird taxonomy
    > ### Aliases: ebird_species
    > 
    > ### ** Examples
    > 
    > # mix common and scientific names, case-insensitive
    > species <- c("Blackburnian Warbler", "Poecile atricapillus",
    +              "american dipper", "Caribou")
    > # note that species not in the ebird taxonomy return NA
    > ebird_species(species)
    [1] "Setophaga fusca"      "Poecile atricapillus" "Cinclus mexicanus"   
    [4] NA                    
    > 
    > # use taxonomy_version to query older taxonomy versions
    > ebird_species("Cordillera Azul Antbird")
    [1] "Myrmoderus eowilsoni"
    > ebird_species("Cordillera Azul Antbird", taxonomy_version = 2017)
    Error in curl::curl_fetch_memory(url, handle = handle) : 
      Timeout was reached: Connection timed out after 10007 milliseconds
    Calls: ebird_species ... request_fetch -> request_fetch.write_memory -> <Anonymous>
    Execution halted
    ```

*   checking tests ...
    ```
     ERROR
    Running the tests in ‘tests/testthat.R’ failed.
    Last 13 lines of output:
      11: ebird_species(species, type = "all", taxonomy_version = taxonomy_version) at /Users/lionel/Desktop/tidyr/revdep/checks.noindex/auk/new/auk.Rcheck/00_pkg_src/auk/R/auk-species.r:60
      12: get_ebird_taxonomy(version = taxonomy_version) at /Users/lionel/Desktop/tidyr/revdep/checks.noindex/auk/new/auk.Rcheck/00_pkg_src/auk/R/ebird-species.r:43
      13: httr::GET(url, query = q) at /Users/lionel/Desktop/tidyr/revdep/checks.noindex/auk/new/auk.Rcheck/00_pkg_src/auk/R/get-ebird-taxonomy.r:44
      14: request_perform(req, hu$handle$handle)
      15: request_fetch(req$output, req$url, handle)
      16: request_fetch.write_memory(req$output, req$url, handle)
      17: curl::curl_fetch_memory(url, handle = handle)
      
      ══ testthat results  ═══════════════════════════════════════════════════════════
      OK: 374 SKIPPED: 20 FAILED: 2
      1. Error: ebird_species handles versions correctly (@test_ebird-species.r#49) 
      2. Error: auk_species (@test_filters.r#38) 
      
      Error: testthat unit tests failed
      Execution halted
    ```

*   checking data for non-ASCII characters ... NOTE
    ```
      Note: found 552 marked UTF-8 strings
    ```

# banter

Version: 0.9.3

## In both

*   checking dependencies in R code ... NOTE
    ```
    Namespace in Imports field not imported from: ‘ranger’
      All declared Imports should be used.
    ```

# basecallQC

Version: 1.4.0

## In both

*   checking installed package size ... NOTE
    ```
      installed size is  5.1Mb
      sub-directories of 1Mb or more:
        doc       1.8Mb
        extdata   2.8Mb
    ```

# BayesMallows

Version: 0.1.1

## In both

*   checking re-building of vignette outputs ... WARNING
    ```
    ...
    
    The following objects are masked from 'package:base':
    
        intersect, setdiff, setequal, union
    
    Computing Mallows model with 1 clusters.
    Computing Mallows model with 2 clusters.
    Computing Mallows model with 3 clusters.
    Computing Mallows model with 4 clusters.
    Computing Mallows model with 5 clusters.
    Computing Mallows model with 6 clusters.
    Computing Mallows model with 7 clusters.
    Computing Mallows model with 8 clusters.
    Computing Mallows model with 9 clusters.
    Computing Mallows model with 10 clusters.
    pandoc-citeproc: when expecting a product (:*:), encountered Object instead
    Error running filter /usr/local/bin/pandoc-citeproc:
    Filter returned error status 1
    Error: processing vignette 'BayesMallowsPackage.Rmd' failed with diagnostics:
    pandoc document conversion failed with error 83
    Execution halted
    ```

# baystability

Version: 0.1.0

## In both

*   checking dependencies in R code ... NOTE
    ```
    Namespaces in Imports field not imported from:
      ‘ggfortify’ ‘ggplot2’ ‘matrixStats’ ‘reshape2’ ‘scales’
      All declared Imports should be used.
    ```

# BgeeDB

Version: 2.6.2

## In both

*   checking whether package ‘BgeeDB’ can be installed ... ERROR
    ```
    Installation failed.
    See ‘/Users/lionel/Desktop/tidyr/revdep/checks.noindex/BgeeDB/new/BgeeDB.Rcheck/00install.out’ for details.
    ```

## Installation

### Devel

```
* installing *source* package ‘BgeeDB’ ...
** R
** data
** inst
** byte-compile and prepare package for lazy loading
Error : package ‘GO.db’ required by ‘topGO’ could not be found
ERROR: lazy loading failed for package ‘BgeeDB’
* removing ‘/Users/lionel/Desktop/tidyr/revdep/checks.noindex/BgeeDB/new/BgeeDB.Rcheck/BgeeDB’

```
### CRAN

```
* installing *source* package ‘BgeeDB’ ...
** R
** data
** inst
** byte-compile and prepare package for lazy loading
Error : package ‘GO.db’ required by ‘topGO’ could not be found
ERROR: lazy loading failed for package ‘BgeeDB’
* removing ‘/Users/lionel/Desktop/tidyr/revdep/checks.noindex/BgeeDB/old/BgeeDB.Rcheck/BgeeDB’

```
# bib2df

Version: 1.0.1

## In both

*   checking tests ...
    ```
     ERROR
    Running the tests in ‘tests/testthat.R’ failed.
    Last 13 lines of output:
      > library("testthat")
      > library("bib2df")
      > test_check("bib2df")
      ── 1. Failure: bib2df() throws error messages (@tests.R#70)  ───────────────────
      `bib2df("https://www.example.com/data/x.bib")` threw an error with unexpected message.
      Expected match: "Invalid URL: File is not readable."
      Actual message: "Could not resolve host: www.example.com"
      
      ══ testthat results  ═══════════════════════════════════════════════════════════
      OK: 19 SKIPPED: 0 FAILED: 1
      1. Failure: bib2df() throws error messages (@tests.R#70) 
      
      Error: testthat unit tests failed
      Execution halted
    ```

# biobroom

Version: 1.12.1

## In both

*   checking re-building of vignette outputs ... WARNING
    ```
    ...
    
    The following object is masked from 'package:dplyr':
    
        count
    
    Loading required package: BiocParallel
    
    Attaching package: 'DelayedArray'
    
    The following objects are masked from 'package:matrixStats':
    
        colMaxs, colMins, colRanges, rowMaxs, rowMins, rowRanges
    
    The following objects are masked from 'package:base':
    
        aperm, apply
    
    Quitting from lines 134-139 (biobroom_vignette.Rmd) 
    Error: processing vignette 'biobroom_vignette.Rmd' failed with diagnostics:
    there is no package called 'airway'
    Execution halted
    ```

*   checking package dependencies ... NOTE
    ```
    Package suggested but not available for checking: ‘airway’
    ```

*   checking dependencies in R code ... NOTE
    ```
    'library' or 'require' call to ‘DESeq2’ in package code.
      Please use :: or requireNamespace() instead.
      See section 'Suggested packages' in the 'Writing R Extensions' manual.
    Missing or unexported object: ‘dplyr::tbl_dt’
    ```

*   checking R code for possible problems ... NOTE
    ```
    ...
    tidy.qvalue: no visible binding for global variable ‘smoothed’
      (/Users/lionel/Desktop/tidyr/revdep/checks.noindex/biobroom/new/biobroom.Rcheck/00_pkg_src/biobroom/R/qvalue_tidiers.R:65-66)
    tidy.qvalue: no visible binding for global variable ‘pi0’
      (/Users/lionel/Desktop/tidyr/revdep/checks.noindex/biobroom/new/biobroom.Rcheck/00_pkg_src/biobroom/R/qvalue_tidiers.R:65-66)
    tidy.qvalue: no visible binding for global variable ‘lambda’
      (/Users/lionel/Desktop/tidyr/revdep/checks.noindex/biobroom/new/biobroom.Rcheck/00_pkg_src/biobroom/R/qvalue_tidiers.R:65-66)
    tidy_matrix: no visible binding for global variable ‘value’
      (/Users/lionel/Desktop/tidyr/revdep/checks.noindex/biobroom/new/biobroom.Rcheck/00_pkg_src/biobroom/R/limma_tidiers.R:197-199)
    tidy_matrix: no visible binding for global variable ‘gene’
      (/Users/lionel/Desktop/tidyr/revdep/checks.noindex/biobroom/new/biobroom.Rcheck/00_pkg_src/biobroom/R/limma_tidiers.R:197-199)
    Undefined global functions or variables:
      . DGEList calcNormFactors colData counts design end estimate
      estimateSizeFactors exprs<- fData<- gene gr is lambda model.matrix
      p.adjust pData pData<- pi0 protein rowRanges sample.id seqnames
      setNames smoothed start tbl_dt term value voom voomWithQualityWeights
    Consider adding
      importFrom("methods", "is")
      importFrom("stats", "end", "model.matrix", "p.adjust", "setNames",
                 "start")
    to your NAMESPACE file (and ensure that your DESCRIPTION Imports
    field contains 'methods').
    ```

# bisect

Version: 0.9.0

## In both

*   checking examples ... ERROR
    ```
    Running examples in ‘bisect-Ex.R’ failed
    The error most likely occurred in:
    
    > ### Name: bisect_semi_suprevised
    > ### Title: Add together two numbers.
    > ### Aliases: bisect_semi_suprevised
    > 
    > ### ** Examples
    > 
    > ## Randomly choose samples to be used as known
    > n_known_samples <- 50
    > known_samples_indices <- sample.int(nrow(baseline_GSE40279), size = n_known_samples)
    > known_samples <- as.matrix(baseline_GSE40279[known_samples_indices, ])
    > 
    > ## Fit a dirichlet distribution to known samples to use as prior
    > fit_dirichlet <- sirt::dirichlet.mle(as.matrix(known_samples))
    Error in loadNamespace(i, c(lib.loc, .libPaths()), versionCheck = vI[[i]]) : 
      there is no package called ‘vegan’
    Calls: :: ... tryCatch -> tryCatchList -> tryCatchOne -> <Anonymous>
    Execution halted
    ```

*   checking re-building of vignette outputs ... WARNING
    ```
    Error in re-building vignettes:
      ...
    Quitting from lines 122-125 (bisect_vignette.Rmd) 
    Error: processing vignette 'bisect_vignette.Rmd' failed with diagnostics:
    there is no package called 'vegan'
    Execution halted
    ```

# blkbox

Version: 1.0

## In both

*   checking package dependencies ... NOTE
    ```
    Package suggested but not available for checking: ‘bigrf’
    ```

*   checking dependencies in R code ... NOTE
    ```
    Unable to find any JVMs matching version "(null)".
    No Java runtime present, try --request to install.
    Namespaces in Imports field not imported from:
      ‘glmnet’ ‘gtools’ ‘knitr’ ‘nnet’ ‘parallel’ ‘rJava’ ‘reshape’
      ‘rmarkdown’ ‘shinyjs’
      All declared Imports should be used.
    Missing or unexported object: ‘xgboost::predict’
    ```

# BloodCancerMultiOmics2017

Version: 1.0.2

## In both

*   checking package dependencies ... ERROR
    ```
    Package required but not available: ‘devtools’
    
    Package suggested but not available for checking: ‘org.Hs.eg.db’
    
    See section ‘The DESCRIPTION file’ in the ‘Writing R Extensions’
    manual.
    ```

# blorr

Version: 0.1.0

## In both

*   checking dependencies in R code ... NOTE
    ```
    Namespace in Imports field not imported from: ‘descriptr’
      All declared Imports should be used.
    ```

*   checking Rd cross-references ... NOTE
    ```
    Package unavailable to check Rd xrefs: ‘lmtest’
    ```

# bootnet

Version: 1.1.0

## In both

*   checking dependencies in R code ... NOTE
    ```
    Namespace in Imports field not imported from: ‘psych’
      All declared Imports should be used.
    ```

# bossMaps

Version: 0.1.0

## In both

*   checking dependencies in R code ... NOTE
    ```
    Namespaces in Imports field not imported from:
      ‘rgdal’ ‘tidyr’
      All declared Imports should be used.
    ```

# breathtestcore

Version: 0.4.5

## In both

*   checking Rd cross-references ... NOTE
    ```
    Package unavailable to check Rd xrefs: ‘breathteststan’
    ```

# breathteststan

Version: 0.4.6

## Newly broken

*   checking for GNU extensions in Makefiles ... NOTE
    ```
    GNU make is a SystemRequirements.
    ```

## Newly fixed

*   checking whether package ‘breathteststan’ can be installed ... ERROR
    ```
    Installation failed.
    See ‘/Users/lionel/Desktop/tidyr/revdep/checks.noindex/breathteststan/old/breathteststan.Rcheck/00install.out’ for details.
    ```

## Installation

### Devel

```
* installing *source* package ‘breathteststan’ ...
** package ‘breathteststan’ successfully unpacked and MD5 sums checked
** libs
"/Library/Frameworks/R.framework/Resources/bin/Rscript" -e "source(file.path('..', 'tools', 'make_cc.R')); make_cc(commandArgs(TRUE))" stan_files/breath_test_1.stan
"/Library/Frameworks/R.framework/Resources/bin/Rscript" -e "source(file.path('..', 'tools', 'make_cc.R')); make_cc(commandArgs(TRUE))" stan_files/breath_test_group_1.stan
clang++ -std=gnu++14 -I"/Library/Frameworks/R.framework/Resources/include" -DNDEBUG -I"../inst/include" -I"`"/Library/Frameworks/R.framework/Resources/bin/Rscript" -e "cat(system.file('include', 'src', package = 'StanHeaders'))"`" -DBOOST_DISABLE_ASSERTS -DEIGEN_NO_DEBUG -DBOOST_MATH_OVERFLOW_ERROR_POLICY=errno_on_error -I"/Users/lionel/Desktop/tidyr/revdep/library.noindex/breathteststan/StanHeaders/include" -I"/Users/lionel/Desktop/tidyr/revdep/library.noindex/breathteststan/rstan/include" -I"/Users/lionel/Desktop/tidyr/revdep/library.noindex/tidyr/new/BH/include" -I"/Users/lionel/Desktop/tidyr/revdep/library.noindex/tidyr/new/Rcpp/include" -I"/Users/lionel/Desktop/tidyr/revdep/library.noindex/breathteststan/RcppEigen/include" -I/usr/local/include   -fPIC  -Wall -g -O2 -c init.cpp -o init.o
Wrote C++ file "stan_files/breath_test_group_1.cc"
Wrote C++ file "stan_files/breath_test_1.cc"
clang++ -std=gnu++14 -I"/Library/Frameworks/R.framework/Resources/include" -DNDEBUG -I"../inst/include" -I"`"/Library/Frameworks/R.framework/Resources/bin/Rscript" -e "cat(system.file('include', 'src', package = 'StanHeaders'))"`" -DBOOST_DISABLE_ASSERTS -DEIGEN_NO_DEBUG -DBOOST_MATH_OVERFLOW_ERROR_POLICY=errno_on_error -I"/Users/lionel/Desktop/tidyr/revdep/library.noindex/breathteststan/StanHeaders/include" -I"/Users/lionel/Desktop/tidyr/revdep/library.noindex/breathteststan/rstan/include" -I"/Users/lionel/Desktop/tidyr/revdep/library.noindex/tidyr/new/BH/include" -I"/Users/lionel/Desktop/tidyr/revdep/library.noindex/tidyr/new/Rcpp/include" -I"/Users/lionel/Desktop/tidyr/revdep/library.noindex/breathteststan/RcppEigen/include" -I/usr/local/include   -fPIC  -Wall -g -O2 -c stan_files/breath_test_group_1.cc -o stan_files/breath_test_group_1.o
clang++ -std=gnu++14 -I"/Library/Frameworks/R.framework/Resources/include" -DNDEBUG -I"../inst/include" -I"`"/Library/Frameworks/R.framework/Resources/bin/Rscript" -e "cat(system.file('include', 'src', package = 'StanHeaders'))"`" -DBOOST_DISABLE_ASSERTS -DEIGEN_NO_DEBUG -DBOOST_MATH_OVERFLOW_ERROR_POLICY=errno_on_error -I"/Users/lionel/Desktop/tidyr/revdep/library.noindex/breathteststan/StanHeaders/include" -I"/Users/lionel/Desktop/tidyr/revdep/library.noindex/breathteststan/rstan/include" -I"/Users/lionel/Desktop/tidyr/revdep/library.noindex/tidyr/new/BH/include" -I"/Users/lionel/Desktop/tidyr/revdep/library.noindex/tidyr/new/Rcpp/include" -I"/Users/lionel/Desktop/tidyr/revdep/library.noindex/breathteststan/RcppEigen/include" -I/usr/local/include   -fPIC  -Wall -g -O2 -c stan_files/breath_test_1.cc -o stan_files/breath_test_1.o
In file included from stan_files/breath_test_group_1.cc:3:
In file included from stan_files/breath_test_group_1.hpp:5:
In file included from /Users/lionel/Desktop/tidyr/revdep/library.noindex/breathteststan/rstan/include/rstan/rstaninc.hpp:3:
In file included from /Users/lionel/Desktop/tidyr/revdep/library.noindex/breathteststan/rstan/include/rstan/stan_fit.hpp:34:
In file included from /Users/lionel/Desktop/tidyr/revdep/library.noindex/breathteststan/StanHeaders/include/src/stan/services/diagnose/diagnose.hpp:10:
In file included from /Users/lionel/Desktop/tidyr/revdep/library.noindex/breathteststan/StanHeaders/include/src/stan/model/test_gradients.hpp:7:
In file included from /Users/lionel/Desktop/tidyr/revdep/library.noindex/breathteststan/StanHeaders/include/src/stan/model/log_prob_grad.hpp:4:
In file included from /Users/lionel/Desktop/tidyr/revdep/library.noindex/breathteststan/StanHeaders/include/stan/math/rev/mat.hpp:4:
In file included from /Users/lionel/Desktop/tidyr/revdep/library.noindex/breathteststan/StanHeaders/include/stan/math/rev/core.hpp:14:
In file included from /Users/lionel/Desktop/tidyr/revdep/library.noindex/breathteststan/StanHeaders/include/stan/math/rev/core/matrix_vari.hpp:4:
In file included from /Users/lionel/Desktop/tidyr/revdep/library.noindex/breathteststan/StanHeaders/include/stan/math/rev/mat/fun/Eigen_NumTraits.hpp:4:
In file included from /Users/lionel/Desktop/tidyr/revdep/library.noindex/breathteststan/StanHeaders/include/stan/math/prim/mat/fun/Eigen.hpp:4:
In file included from /Users/lionel/Desktop/tidyr/revdep/library.noindex/breathteststan/RcppEigen/include/Eigen/Dense:1:
In file included from /Users/lionel/Desktop/tidyr/revdep/library.noindex/breathteststan/RcppEigen/include/Eigen/Core:531:
/Users/lionel/Desktop/tidyr/revdep/library.noindex/breathteststan/RcppEigen/include/Eigen/src/Core/util/ReenableStupidWarnings.h:10:30: warning: pragma diagnostic pop could not pop, no matching push [-Wunknown-pragmas]
In file included from stan_files/breath_test_1.cc:3:
In file included from stan_files/breath_test_1.hpp:5:
In file included from /Users/lionel/Desktop/tidyr/revdep/library.noindex/breathteststan/rstan/include/rstan/rstaninc.hpp:3:
In file included from /Users/lionel/Desktop/tidyr/revdep/library.noindex/breathteststan/rstan/include/rstan/stan_fit.hpp:34:
In file included from /Users/lionel/Desktop/tidyr/revdep/library.noindex/breathteststan/StanHeaders/include/src/stan/services/diagnose/diagnose.hpp:10:
In file included from /Users/lionel/Desktop/tidyr/revdep/library.noindex/breathteststan/StanHeaders/include/src/stan/model/test_gradients.hpp:7:
In file included from /Users/lionel/Desktop/tidyr/revdep/library.noindex/breathteststan/StanHeaders/include/src/stan/model/log_prob_grad.hpp:4:
In file included from /Users/lionel/Desktop/tidyr/revdep/library.noindex/breathteststan/StanHeaders/include/stan/math/rev/mat.hpp:4:
In file included from /Users/lionel/Desktop/tidyr/revdep/library.noindex/breathteststan/StanHeaders/include/stan/math/rev/core.hpp:14:
In file included from /Users/lionel/Desktop/tidyr/revdep/library.noindex/breathteststan/StanHeaders/include/stan/math/rev/core/matrix_vari.hpp:4:
In file included from /Users/lionel/Desktop/tidyr/revdep/library.noindex/breathteststan/StanHeaders/include/stan/math/rev/mat/fun/Eigen_NumTraits.hpp:4:
In file included from /Users/lionel/Desktop/tidyr/revdep/library.noindex/breathteststan/StanHeaders/include/stan/math/prim/mat/fun/Eigen.hpp:4:
In file included from /Users/lionel/Desktop/tidyr/revdep/library.noindex/breathteststan/RcppEigen/include/Eigen/Dense:1:
In file included from /Users/lionel/Desktop/tidyr/revdep/library.noindex/breathteststan/RcppEigen/include/Eigen/Core:531:
/Users/lionel/Desktop/tidyr/revdep/library.noindex/breathteststan/RcppEigen/include/Eigen/src/Core/util/ReenableStupidWarnings.h:10:30: warning: pragma diagnostic pop could not pop, no matching push [-Wunknown-pragmas]
    #pragma clang diagnostic pop
                             ^
    #pragma clang diagnostic pop
                             ^
In file included from stan_files/breath_test_group_1.cc:3:
In file included from stan_files/breath_test_group_1.hpp:5:
In file included from /Users/lionel/Desktop/tidyr/revdep/library.noindex/breathteststan/rstan/include/rstan/rstaninc.hpp:3:
In file included from /Users/lionel/Desktop/tidyr/revdep/library.noindex/breathteststan/rstan/include/rstan/stan_fit.hpp:34:
In file included from /Users/lionel/Desktop/tidyr/revdep/library.noindex/breathteststan/StanHeaders/include/src/stan/services/diagnose/diagnose.hpp:10:
In file included from /Users/lionel/Desktop/tidyr/revdep/library.noindex/breathteststan/StanHeaders/include/src/stan/model/test_gradients.hpp:7:
In file included from /Users/lionel/Desktop/tidyr/revdep/library.noindex/breathteststan/StanHeaders/include/src/stan/model/log_prob_grad.hpp:4:
In file included from /Users/lionel/Desktop/tidyr/revdep/library.noindex/breathteststan/StanHeaders/include/stan/math/rev/mat.hpp:4:
In file included from /Users/lionel/Desktop/tidyr/revdep/library.noindex/breathteststan/StanHeaders/include/stan/math/rev/core.hpp:14:
In file included from /Users/lionel/Desktop/tidyr/revdep/library.noindex/breathteststan/StanHeaders/include/stan/math/rev/core/matrix_vari.hpp:In file included from stan_files/breath_test_1.cc:3:
In file included from stan_files/breath_test_1.hpp:5:
In file included from /Users/lionel/Desktop/tidyr/revdep/library.noindex/breathteststan/rstan/include/rstan/rstaninc.hpp:3:
4:
In file included from /Users/lionel/Desktop/tidyr/revdep/library.noindex/breathteststan/StanHeaders/include/stan/math/rev/mat/fun/Eigen_NumTraits.hpp:4In file included from /Users/lionel/Desktop/tidyr/revdep/library.noindex/breathteststan/rstan/include/rstan/stan_fit.hpp:34:
In file included from /Users/lionel/Desktop/tidyr/revdep/library.noindex/breathteststan/StanHeaders/include/src/stan/services/diagnose/diagnose.hpp:10:
In file included from /Users/lionel/Desktop/tidyr/revdep/library.noindex/breathteststan/StanHeaders/include/src/stan/model/test_gradients.hpp:7:
:
In file included from In file included from /Users/lionel/Desktop/tidyr/revdep/library.noindex/breathteststan/StanHeaders/include/src/stan/model/log_prob_grad.hpp:4:
In file included from /Users/lionel/Desktop/tidyr/revdep/library.noindex/breathteststan/StanHeaders/include/stan/math/rev/mat.hpp:4:
In file included from /Users/lionel/Desktop/tidyr/revdep/library.noindex/breathteststan/StanHeaders/include/stan/math/rev/core.hpp:14:
In file included from /Users/lionel/Desktop/tidyr/revdep/library.noindex/breathteststan/StanHeaders/include/stan/math/rev/core/matrix_vari.hpp:4:
In file included from /Users/lionel/Desktop/tidyr/revdep/library.noindex/breathteststan/StanHeaders/include/stan/math/rev/mat/fun/Eigen_NumTraits.hpp:4:
In file included from /Users/lionel/Desktop/tidyr/revdep/library.noindex/breathteststan/StanHeaders/include/stan/math/prim/mat/fun/Eigen.hpp:4:
In file included from /Users/lionel/Desktop/tidyr/revdep/library.noindex/breathteststan/RcppEigen/include/Eigen/Dense:2:
In file included from /Users/lionel/Desktop/tidyr/revdep/library.noindex/breathteststan/RcppEigen/include/Eigen/LU:47:
/Users/lionel/Desktop/tidyr/revdep/library.noindex/breathteststan/RcppEigen/include/Eigen/src/Core/util/ReenableStupidWarnings.h:10:30: warning: pragma diagnostic pop could not pop, no matching push [-Wunknown-pragmas]
/Users/lionel/Desktop/tidyr/revdep/library.noindex/breathteststan/StanHeaders/include/stan/math/prim/mat/fun/Eigen.hpp:4:
In file included from /Users/lionel/Desktop/tidyr/revdep/library.noindex/breathteststan/RcppEigen/include/Eigen/Dense:2:
In file included from /Users/lionel/Desktop/tidyr/revdep/library.noindex/breathteststan/RcppEigen/include/Eigen/LU:47:
/Users/lionel/Desktop/tidyr/revdep/library.noindex/breathteststan/RcppEigen/include/Eigen/src/Core/util/ReenableStupidWarnings.h:10:30: warning: pragma diagnostic pop could not pop, no matching push [-Wunknown-pragmas]
    #pragma clang diagnostic pop
                             ^
    #pragma clang diagnostic pop
                             ^
In file included from stan_files/breath_test_1.cc:3:
In file included from stan_files/breath_test_1.hpp:5:
In file included from /Users/lionel/Desktop/tidyr/revdep/library.noindex/breathteststan/rstan/include/rstan/rstaninc.hpp:3:
In file included from /Users/lionel/Desktop/tidyr/revdep/library.noindex/breathteststan/rstan/include/rstan/stan_fit.hpp:34:
In file included from /Users/lionel/Desktop/tidyr/revdep/library.noindex/breathteststan/StanHeaders/include/src/stan/services/diagnose/diagnose.hpp:10:
In file included from /Users/lionel/Desktop/tidyr/revdep/library.noindex/breathteststan/StanHeaders/include/src/stan/model/test_gradients.hpp:7:
In file included from /Users/lionel/Desktop/tidyr/revdep/library.noindex/breathteststan/StanHeaders/include/src/stan/model/log_prob_grad.hpp:4:
In file included from /Users/lionel/Desktop/tidyr/revdep/library.noindex/breathteststan/StanHeaders/include/stan/math/rev/mat.hpp:4:
In file included from In file included from /Users/lionel/Desktop/tidyr/revdep/library.noindex/breathteststan/StanHeaders/include/stan/math/rev/core.hpp:14:
In file included from /Users/lionel/Desktop/tidyr/revdep/library.noindex/breathteststan/StanHeaders/include/stan/math/rev/core/matrix_vari.hpp:4:
In file included from /Users/lionel/Desktop/tidyr/revdep/library.noindex/breathteststan/StanHeaders/include/stan/math/rev/mat/fun/Eigen_NumTraits.hpp:4:
In file included from /Users/lionel/Desktop/tidyr/revdep/library.noindex/breathteststan/StanHeaders/include/stan/math/prim/mat/fun/Eigen.hpp:stan_files/breath_test_group_1.cc4:
In file included from /Users/lionel/Desktop/tidyr/revdep/library.noindex/breathteststan/RcppEigen/include/Eigen/Dense:3:
In file included from /Users/lionel/Desktop/tidyr/revdep/library.noindex/breathteststan/RcppEigen/include/Eigen/Cholesky:12:
In file included from /Users/lionel/Desktop/tidyr/revdep/library.noindex/breathteststan/RcppEigen/include/Eigen/Jacobi:29:
/Users/lionel/Desktop/tidyr/revdep/library.noindex/breathteststan/RcppEigen/include/Eigen/src/Core/util/ReenableStupidWarnings.h:10:30::3:
 warning: pragma diagnostic pop could not pop, no matching push [-Wunknown-pragmas]
    #pragma clang diagnostic pop
In file included from stan_files/breath_test_group_1.hpp:5:
In file included from /Users/lionel/Desktop/tidyr/revdep/library.noindex/breathteststan/rstan/include/rstan/rstaninc.hpp:3:
In file included from /Users/lionel/Desktop/tidyr/revdep/library.noindex/breathteststan/rstan/include/rstan/stan_fit.hpp:34:
In file included from /Users/lionel/Desktop/tidyr/revdep/library.noindex/breathteststan/StanHeaders/include/src/stan/services/diagnose/diagnose.hpp:10:
                             ^
In file included from /Users/lionel/Desktop/tidyr/revdep/library.noindex/breathteststan/StanHeaders/include/src/stan/model/test_gradients.hpp:7:
In file included from /Users/lionel/Desktop/tidyr/revdep/library.noindex/breathteststan/StanHeaders/include/src/stan/model/log_prob_grad.hpp:4:
In file included from /Users/lionel/Desktop/tidyr/revdep/library.noindex/breathteststan/StanHeaders/include/stan/math/rev/mat.hpp:4:
In file included from /Users/lionel/Desktop/tidyr/revdep/library.noindex/breathteststan/StanHeaders/include/stan/math/rev/core.hpp:14:
In file included from /Users/lionel/Desktop/tidyr/revdep/library.noindex/breathteststan/StanHeaders/include/stan/math/rev/core/matrix_vari.hpp:4:
In file included from /Users/lionel/Desktop/tidyr/revdep/library.noindex/breathteststan/StanHeaders/include/stan/math/rev/mat/fun/Eigen_NumTraits.hpp:4:
In file included from /Users/lionel/Desktop/tidyr/revdep/library.noindex/breathteststan/StanHeaders/include/stan/math/prim/mat/fun/Eigen.hpp:4:
In file included from /Users/lionel/Desktop/tidyr/revdep/library.noindex/breathteststan/RcppEigen/include/Eigen/Dense:3:
In file included from /Users/lionel/Desktop/tidyr/revdep/library.noindex/breathteststan/RcppEigen/include/Eigen/Cholesky:12:
In file included from /Users/lionel/Desktop/tidyr/revdep/library.noindex/breathteststan/RcppEigen/include/Eigen/Jacobi:29:
/Users/lionel/Desktop/tidyr/revdep/library.noindex/breathteststan/RcppEigen/include/Eigen/src/Core/util/ReenableStupidWarnings.h:10:30: warning: pragma diagnostic pop could not pop, no matching push [-Wunknown-pragmas]
    #pragma clang diagnostic pop
                             ^
In file included from stan_files/breath_test_1.cc:3:
In file included from stan_files/breath_test_1.hpp:5:
In file included from /Users/lionel/Desktop/tidyr/revdep/library.noindex/breathteststan/rstan/include/rstan/rstaninc.hpp:3:
In file included from /Users/lionel/Desktop/tidyr/revdep/library.noindex/breathteststan/rstan/include/rstan/stan_fit.hpp:34:
In file included from /Users/lionel/Desktop/tidyr/revdep/library.noindex/breathteststan/StanHeaders/include/src/stan/services/diagnose/diagnose.hpp:10:
In file included from /Users/lionel/Desktop/tidyr/revdep/library.noindex/breathteststan/StanHeaders/include/src/stan/model/test_gradients.hpp:7:
In file included from /Users/lionel/Desktop/tidyr/revdep/library.noindex/breathteststan/StanHeaders/include/src/stan/model/log_prob_grad.hpp:4:
In file included from /Users/lionel/Desktop/tidyr/revdep/library.noindex/breathteststan/StanHeaders/include/stan/math/rev/mat.hpp:4:
In file included from /Users/lionel/Desktop/tidyr/revdep/library.noindex/breathteststan/StanHeaders/include/stan/math/rev/core.hpp:14:
In file included from /Users/lionel/Desktop/tidyr/revdep/library.noindex/breathteststan/StanHeaders/include/stan/math/rev/core/matrix_vari.hpp:4:
In file included from /Users/lionel/Desktop/tidyr/revdep/library.noindex/breathteststan/StanHeaders/include/stan/math/rev/mat/fun/Eigen_NumTraits.hpp:4:
In file included from /Users/lionel/Desktop/tidyr/revdep/library.noindex/breathteststan/StanHeaders/include/stan/math/prim/mat/fun/Eigen.hpp:4:
In file included from /Users/lionel/Desktop/tidyr/revdep/library.noindex/breathteststan/RcppEigen/include/Eigen/Dense:3:
In file included from /Users/lionel/Desktop/tidyr/revdep/library.noindex/breathteststan/RcppEigen/include/Eigen/Cholesky:43:
/Users/lionel/Desktop/tidyr/revdep/library.noindex/breathteststan/RcppEigen/include/Eigen/src/Core/util/ReenableStupidWarnings.h:10:30: warning: pragma diagnostic pop could not pop, no matching push [-Wunknown-pragmas]
    #pragma clang diagnostic pop
                             ^
In file included from stan_files/breath_test_group_1.cc:3:
In file included from stan_files/breath_test_group_1.hpp:5:
In file included from /Users/lionel/Desktop/tidyr/revdep/library.noindex/breathteststan/rstan/include/rstan/rstaninc.hpp:3:
In file included from /Users/lionel/Desktop/tidyr/revdep/library.noindex/breathteststan/rstan/include/rstan/stan_fit.hpp:34:
In file included from /Users/lionel/Desktop/tidyr/revdep/library.noindex/breathteststan/StanHeaders/include/src/stan/services/diagnose/diagnose.hpp:10:
In file included from /Users/lionel/Desktop/tidyr/revdep/library.noindex/breathteststan/StanHeaders/include/src/stan/model/test_gradients.hpp:7:
In file included from /Users/lionel/Desktop/tidyr/revdep/library.noindex/breathteststan/StanHeaders/include/src/stan/model/log_prob_grad.hpp:4:
In file included from /Users/lionel/Desktop/tidyr/revdep/library.noindex/breathteststan/StanHeaders/include/stan/math/rev/mat.hpp:4:
In file included from /Users/lionel/Desktop/tidyr/revdep/library.noindex/breathteststan/StanHeaders/include/stan/math/rev/core.hpp:14:
In file included from /Users/lionel/Desktop/tidyr/revdep/library.noindex/breathteststan/StanHeaders/include/stan/math/rev/core/matrix_vari.hpp:4:
In file included from /Users/lionel/Desktop/tidyr/revdep/library.noindex/breathteststan/StanHeaders/include/stan/math/rev/mat/fun/Eigen_NumTraits.hpp:4:
In file included from /Users/lionel/Desktop/tidyr/revdep/library.noindex/breathteststan/StanHeaders/include/stan/math/prim/mat/fun/Eigen.hpp:4:
In file included from /Users/lionel/Desktop/tidyr/revdep/library.noindex/breathteststan/RcppEigen/include/Eigen/Dense:3:
In file included from /Users/lionel/Desktop/tidyr/revdep/library.noindex/breathteststan/RcppEigen/include/Eigen/Cholesky:43:
/Users/lionel/Desktop/tidyr/revdep/library.noindex/breathteststan/RcppEigen/include/Eigen/src/Core/util/ReenableStupidWarnings.h:10:30: warning: pragma diagnostic pop could not pop, no matching push [-Wunknown-pragmas]
    #pragma clang diagnostic pop
                             ^
In file included from stan_files/breath_test_1.cc:3:
In file included from stan_files/breath_test_1.hpp:5:
In file included from /Users/lionel/Desktop/tidyr/revdep/library.noindex/breathteststan/rstan/include/rstan/rstaninc.hpp:3:
In file included from /Users/lionel/Desktop/tidyr/revdep/library.noindex/breathteststan/rstan/include/rstan/stan_fit.hpp:34:
In file included from /Users/lionel/Desktop/tidyr/revdep/library.noindex/breathteststan/StanHeaders/include/src/stan/services/diagnose/diagnose.hpp:10:
In file included from /Users/lionel/Desktop/tidyr/revdep/library.noindex/breathteststan/StanHeaders/include/src/stan/model/test_gradients.hpp:7:
In file included from /Users/lionel/Desktop/tidyr/revdep/library.noindex/breathteststan/StanHeaders/include/src/stan/model/log_prob_grad.hpp:4:
In file included from /Users/lionel/Desktop/tidyr/revdep/library.noindex/breathteststan/StanHeaders/include/stan/math/rev/mat.hpp:4:
In file included from /Users/lionel/Desktop/tidyr/revdep/library.noindex/breathteststan/StanHeaders/include/stan/math/rev/core.hpp:14:
In file included from /Users/lionel/Desktop/tidyr/revdep/library.noindex/breathteststan/StanHeaders/include/stan/math/rev/core/matrix_vari.hpp:4:
In file included from /Users/lionel/Desktop/tidyr/revdep/library.noindex/breathteststan/StanHeaders/include/stan/math/rev/mat/fun/Eigen_NumTraits.hpp:4:
In file included from /Users/lionel/Desktop/tidyr/revdep/library.noindex/breathteststan/StanHeaders/include/stan/math/prim/mat/fun/Eigen.hpp:4:
In file included from /Users/lionel/Desktop/tidyr/revdep/library.noindex/breathteststan/RcppEigen/include/Eigen/Dense:4:
In file included from /Users/lionel/Desktop/tidyr/revdep/library.noindex/breathteststan/RcppEigen/include/Eigen/QR:17:
In file included from /Users/lionel/Desktop/tidyr/revdep/library.noindex/breathteststan/RcppEigen/include/Eigen/Householder:27:
/Users/lionel/Desktop/tidyr/revdep/library.noindex/breathteststan/RcppEigen/include/Eigen/src/Core/util/ReenableStupidWarnings.h:10:30: warning: pragma diagnostic pop could not pop, no matching push [-Wunknown-pragmas]
    #pragma clang diagnostic pop
                             ^
In file included from stan_files/breath_test_group_1.cc:3:
In file included from stan_files/breath_test_group_1.hpp:5:
In file included from /Users/lionel/Desktop/tidyr/revdep/library.noindex/breathteststan/rstan/include/rstan/rstaninc.hpp:3:
In file included from /Users/lionel/Desktop/tidyr/revdep/library.noindex/breathteststan/rstan/include/rstan/stan_fit.hpp:34:
In file included from /Users/lionel/Desktop/tidyr/revdep/library.noindex/breathteststan/StanHeaders/include/src/stan/services/diagnose/diagnose.hpp:10:
In file included from /Users/lionel/Desktop/tidyr/revdep/library.noindex/breathteststan/StanHeaders/include/src/stan/model/test_gradients.hpp:7:
In file included from /Users/lionel/Desktop/tidyr/revdep/library.noindex/breathteststan/StanHeaders/include/src/stan/model/log_prob_grad.hpp:4:
In file included from /Users/lionel/Desktop/tidyr/revdep/library.noindex/breathteststan/StanHeaders/include/stan/math/rev/mat.hpp:4:
In file included from /Users/lionel/Desktop/tidyr/revdep/library.noindex/breathteststan/StanHeaders/include/stan/math/rev/core.hpp:14:
In file included from /Users/lionel/Desktop/tidyr/revdep/library.noindex/breathteststan/StanHeaders/include/stan/math/rev/core/matrix_vari.hpp:4:
In file included from /Users/lionel/Desktop/tidyr/revdep/library.noindex/breathteststan/StanHeaders/include/stan/math/rev/mat/fun/Eigen_NumTraits.hpp:4:
In file included from /Users/lionel/Desktop/tidyr/revdep/library.noindex/breathteststan/StanHeaders/include/stan/math/prim/mat/fun/Eigen.hpp:4:
In file included from /Users/lionel/Desktop/tidyr/revdep/library.noindex/breathteststan/RcppEigen/include/Eigen/Dense:4:
In file included from /Users/lionel/Desktop/tidyr/revdep/library.noindex/breathteststan/RcppEigen/include/Eigen/QR:17:
In file included from /Users/lionel/Desktop/tidyr/revdep/library.noindex/breathteststan/RcppEigen/include/Eigen/Householder:27:
/Users/lionel/Desktop/tidyr/revdep/library.noindex/breathteststan/RcppEigen/include/Eigen/src/Core/util/ReenableStupidWarnings.h:10:30: warning: pragma diagnostic pop could not pop, no matching push [-Wunknown-pragmas]
    #pragma clang diagnostic pop
                             ^
In file included from stan_files/breath_test_1.cc:3:
In file included from stan_files/breath_test_1.hpp:5:
In file included from /Users/lionel/Desktop/tidyr/revdep/library.noindex/breathteststan/rstan/include/rstan/rstaninc.hpp:3:
In file included from /Users/lionel/Desktop/tidyr/revdep/library.noindex/breathteststan/rstan/include/rstan/stan_fit.hpp:34:
In file included from /Users/lionel/Desktop/tidyr/revdep/library.noindex/breathteststan/StanHeaders/include/src/stan/services/diagnose/diagnose.hpp:10:
In file included from /Users/lionel/Desktop/tidyr/revdep/library.noindex/breathteststan/StanHeaders/include/src/stan/model/test_gradients.hpp:7:
In file included from /Users/lionel/Desktop/tidyr/revdep/library.noindex/breathteststan/StanHeaders/include/src/stan/model/log_prob_grad.hpp:4:
In file included from /Users/lionel/Desktop/tidyr/revdep/library.noindex/breathteststan/StanHeaders/include/stan/math/rev/mat.hpp:4:
In file included from /Users/lionel/Desktop/tidyr/revdep/library.noindex/breathteststan/StanHeaders/include/stan/math/rev/core.hpp:14:
In file included from /Users/lionel/Desktop/tidyr/revdep/library.noindex/breathteststan/StanHeaders/include/stan/math/rev/core/matrix_vari.hpp:4:
In file included from /Users/lionel/Desktop/tidyr/revdep/library.noindex/breathteststan/StanHeaders/include/stan/math/rev/mat/fun/Eigen_NumTraits.hpp:4:
In file included from /Users/lionel/Desktop/tidyr/revdep/library.noindex/breathteststan/StanHeaders/include/stan/math/prim/mat/fun/Eigen.hpp:4:
In file included from /Users/lionel/Desktop/tidyr/revdep/library.noindex/breathteststan/RcppEigen/include/Eigen/Dense:5:
In file included from /Users/lionel/Desktop/tidyr/revdep/library.noindex/breathteststan/RcppEigen/include/Eigen/SVD:48:
/Users/lionel/Desktop/tidyr/revdep/library.noindex/breathteststan/RcppEigen/include/Eigen/src/Core/util/ReenableStupidWarnings.h:10:30: warning: pragma diagnostic pop could not pop, no matching push [-Wunknown-pragmas]
    #pragma clang diagnostic pop
                             ^
In file included from stan_files/breath_test_group_1.cc:3:
In file included from stan_files/breath_test_group_1.hpp:5:
In file included from /Users/lionel/Desktop/tidyr/revdep/library.noindex/breathteststan/rstan/include/rstan/rstaninc.hpp:3:
In file included from /Users/lionel/Desktop/tidyr/revdep/library.noindex/breathteststan/rstan/include/rstan/stan_fit.hpp:34:
In file included from /Users/lionel/Desktop/tidyr/revdep/library.noindex/breathteststan/StanHeaders/include/src/stan/services/diagnose/diagnose.hpp:10:
In file included from /Users/lionel/Desktop/tidyr/revdep/library.noindex/breathteststan/StanHeaders/include/src/stan/model/test_gradients.hpp:7:
In file included from /Users/lionel/Desktop/tidyr/revdep/library.noindex/breathteststan/StanHeaders/include/src/stan/model/log_prob_grad.hpp:4:
In file included from /Users/lionel/Desktop/tidyr/revdep/library.noindex/breathteststan/StanHeaders/include/stan/math/rev/mat.hpp:4:
In file included from /Users/lionel/Desktop/tidyr/revdep/library.noindex/breathteststan/StanHeaders/include/stan/math/rev/core.hpp:14:
In file included from /Users/lionel/Desktop/tidyr/revdep/library.noindex/breathteststan/StanHeaders/include/stan/math/rev/core/matrix_vari.hpp:4:
In file included from /Users/lionel/Desktop/tidyr/revdep/library.noindex/breathteststan/StanHeaders/include/stan/math/rev/mat/fun/Eigen_NumTraits.hpp:4:
In file included from /Users/lionel/Desktop/tidyr/revdep/library.noindex/breathteststan/StanHeaders/include/stan/math/prim/mat/fun/Eigen.hpp:4:
In file included from /Users/lionel/Desktop/tidyr/revdep/library.noindex/breathteststan/RcppEigen/include/Eigen/Dense:5:
In file included from /Users/lionel/Desktop/tidyr/revdep/library.noindex/breathteststan/RcppEigen/include/Eigen/SVD:48:
/Users/lionel/Desktop/tidyr/revdep/library.noindex/breathteststan/RcppEigen/include/Eigen/src/Core/util/ReenableStupidWarnings.h:10:30: warning: pragma diagnostic pop could not pop, no matching push [-Wunknown-pragmas]
    #pragma clang diagnostic pop
                             ^
In file included from stan_files/breath_test_1.cc:3:
In file included from stan_files/breath_test_1.hpp:5:
In file included from /Users/lionel/Desktop/tidyr/revdep/library.noindex/breathteststan/rstan/include/rstan/rstaninc.hpp:3:
In file included from /Users/lionel/Desktop/tidyr/revdep/library.noindex/breathteststan/rstan/include/rstan/stan_fit.hpp:34:
In file included from /Users/lionel/Desktop/tidyr/revdep/library.noindex/breathteststan/StanHeaders/include/src/stan/services/diagnose/diagnose.hpp:10:
In file included from /Users/lionel/Desktop/tidyr/revdep/library.noindex/breathteststan/StanHeaders/include/src/stan/model/test_gradients.hpp:7:
In file included from /Users/lionel/Desktop/tidyr/revdep/library.noindex/breathteststan/StanHeaders/include/src/stan/model/log_prob_grad.hpp:4:
In file included from /Users/lionel/Desktop/tidyr/revdep/library.noindex/breathteststan/StanHeaders/include/stan/math/rev/mat.hpp:4:
In file included from /Users/lionel/Desktop/tidyr/revdep/library.noindex/breathteststan/StanHeaders/include/stan/math/rev/core.hpp:14:
In file included from /Users/lionel/Desktop/tidyr/revdep/library.noindex/breathteststan/StanHeaders/include/stan/math/rev/core/matrix_vari.hpp:4:
In file included from /Users/lionel/Desktop/tidyr/revdep/library.noindex/breathteststan/StanHeaders/include/stan/math/rev/mat/fun/Eigen_NumTraits.hpp:4:
In file included from /Users/lionel/Desktop/tidyr/revdep/library.noindex/breathteststan/StanHeaders/include/stan/math/prim/mat/fun/Eigen.hpp:4:
In file included from /Users/lionel/Desktop/tidyr/revdep/library.noindex/breathteststan/RcppEigen/include/Eigen/Dense:6:
In file included from /Users/lionel/Desktop/tidyr/revdep/library.noindex/breathteststan/RcppEigen/include/Eigen/Geometry:58:
/Users/lionel/Desktop/tidyr/revdep/library.noindex/breathteststan/RcppEigen/include/Eigen/src/Core/util/ReenableStupidWarnings.h:10:30: warning: pragma diagnostic pop could not pop, no matching push [-Wunknown-pragmas]
    #pragma clang diagnostic pop
                             ^
In file included from stan_files/breath_test_group_1.cc:3:
In file included from stan_files/breath_test_group_1.hpp:5:
In file included from /Users/lionel/Desktop/tidyr/revdep/library.noindex/breathteststan/rstan/include/rstan/rstaninc.hpp:3:
In file included from /Users/lionel/Desktop/tidyr/revdep/library.noindex/breathteststan/rstan/include/rstan/stan_fit.hpp:34:
In file included from /Users/lionel/Desktop/tidyr/revdep/library.noindex/breathteststan/StanHeaders/include/src/stan/services/diagnose/diagnose.hpp:10:
In file included from /Users/lionel/Desktop/tidyr/revdep/library.noindex/breathteststan/StanHeaders/include/src/stan/model/test_gradients.hpp:7:
In file included from /Users/lionel/Desktop/tidyr/revdep/library.noindex/breathteststan/StanHeaders/include/src/stan/model/log_prob_grad.hpp:4:
In file included from /Users/lionel/Desktop/tidyr/revdep/library.noindex/breathteststan/StanHeaders/include/stan/math/rev/mat.hpp:4:
In file included from /Users/lionel/Desktop/tidyr/revdep/library.noindex/breathteststan/StanHeaders/include/stan/math/rev/core.hpp:14:
In file included from /Users/lionel/Desktop/tidyr/revdep/library.noindex/breathteststan/StanHeaders/include/stan/math/rev/core/matrix_vari.hpp:4:
In file included from /Users/lionel/Desktop/tidyr/revdep/library.noindex/breathteststan/StanHeaders/include/stan/math/rev/mat/fun/Eigen_NumTraits.hpp:4:
In file included from /Users/lionel/Desktop/tidyr/revdep/library.noindex/breathteststan/StanHeaders/include/stan/math/prim/mat/fun/Eigen.hpp:4:
In file included from /Users/lionel/Desktop/tidyr/revdep/library.noindex/breathteststan/RcppEigen/include/Eigen/Dense:6:
In file included from /Users/lionel/Desktop/tidyr/revdep/library.noindex/breathteststan/RcppEigen/include/Eigen/Geometry:58:
/Users/lionel/Desktop/tidyr/revdep/library.noindex/breathteststan/RcppEigen/include/Eigen/src/Core/util/ReenableStupidWarnings.h:10:30: warning: pragma diagnostic pop could not pop, no matching push [-Wunknown-pragmas]
    #pragma clang diagnostic pop
                             ^
In file included from stan_files/breath_test_1.cc:3:
In file included from stan_files/breath_test_1.hpp:5:
In file included from /Users/lionel/Desktop/tidyr/revdep/library.noindex/breathteststan/rstan/include/rstan/rstaninc.hpp:3:
In file included from /Users/lionel/Desktop/tidyr/revdep/library.noindex/breathteststan/rstan/include/rstan/stan_fit.hpp:34:
In file included from /Users/lionel/Desktop/tidyr/revdep/library.noindex/breathteststan/StanHeaders/include/src/stan/services/diagnose/diagnose.hpp:10:
In file included from /Users/lionel/Desktop/tidyr/revdep/library.noindex/breathteststan/StanHeaders/include/src/stan/model/test_gradients.hpp:7:
In file included from /Users/lionel/Desktop/tidyr/revdep/library.noindex/breathteststan/StanHeaders/include/src/stan/model/log_prob_grad.hpp:4:
In file included from /Users/lionel/Desktop/tidyr/revdep/library.noindex/breathteststan/StanHeaders/include/stan/math/rev/mat.hpp:4:
In file included from /Users/lionel/Desktop/tidyr/revdep/library.noindex/breathteststan/StanHeaders/include/stan/math/rev/core.hpp:14:
In file included from /Users/lionel/Desktop/tidyr/revdep/library.noindex/breathteststan/StanHeaders/include/stan/math/rev/core/matrix_vari.hpp:4:
In file included from /Users/lionel/Desktop/tidyr/revdep/library.noindex/breathteststan/StanHeaders/include/stan/math/rev/mat/fun/Eigen_NumTraits.hpp:4:
In file included from /Users/lionel/Desktop/tidyr/revdep/library.noindex/breathteststan/StanHeaders/include/stan/math/prim/mat/fun/Eigen.hpp:4:
In file included from /Users/lionel/Desktop/tidyr/revdep/library.noindex/breathteststan/RcppEigen/include/Eigen/Dense:7:
In file included from /Users/lionel/Desktop/tidyr/revdep/library.noindex/breathteststan/RcppEigen/include/Eigen/Eigenvalues:58:
/Users/lionel/Desktop/tidyr/revdep/library.noindex/breathteststan/RcppEigen/include/Eigen/src/Core/util/ReenableStupidWarnings.h:10:30: warning: pragma diagnostic pop could not pop, no matching push [-Wunknown-pragmas]
    #pragma clang diagnostic pop
                             ^
In file included from stan_files/breath_test_group_1.cc:3:
In file included from stan_files/breath_test_group_1.hpp:5:
In file included from /Users/lionel/Desktop/tidyr/revdep/library.noindex/breathteststan/rstan/include/rstan/rstaninc.hpp:3:
In file included from /Users/lionel/Desktop/tidyr/revdep/library.noindex/breathteststan/rstan/include/rstan/stan_fit.hpp:34:
In file included from /Users/lionel/Desktop/tidyr/revdep/library.noindex/breathteststan/StanHeaders/include/src/stan/services/diagnose/diagnose.hpp:10:
In file included from /Users/lionel/Desktop/tidyr/revdep/library.noindex/breathteststan/StanHeaders/include/src/stan/model/test_gradients.hpp:7:
In file included from /Users/lionel/Desktop/tidyr/revdep/library.noindex/breathteststan/StanHeaders/include/src/stan/model/log_prob_grad.hpp:4:
In file included from /Users/lionel/Desktop/tidyr/revdep/library.noindex/breathteststan/StanHeaders/include/stan/math/rev/mat.hpp:4:
In file included from /Users/lionel/Desktop/tidyr/revdep/library.noindex/breathteststan/StanHeaders/include/stan/math/rev/core.hpp:14:
In file included from /Users/lionel/Desktop/tidyr/revdep/library.noindex/breathteststan/StanHeaders/include/stan/math/rev/core/matrix_vari.hpp:4:
In file included from /Users/lionel/Desktop/tidyr/revdep/library.noindex/breathteststan/StanHeaders/include/stan/math/rev/mat/fun/Eigen_NumTraits.hpp:4:
In file included from /Users/lionel/Desktop/tidyr/revdep/library.noindex/breathteststan/StanHeaders/include/stan/math/prim/mat/fun/Eigen.hpp:4:
In file included from /Users/lionel/Desktop/tidyr/revdep/library.noindex/breathteststan/RcppEigen/include/Eigen/Dense:7:
In file included from /Users/lionel/Desktop/tidyr/revdep/library.noindex/breathteststan/RcppEigen/include/Eigen/Eigenvalues:58:
/Users/lionel/Desktop/tidyr/revdep/library.noindex/breathteststan/RcppEigen/include/Eigen/src/Core/util/ReenableStupidWarnings.h:10:30: warning: pragma diagnostic pop could not pop, no matching push [-Wunknown-pragmas]
    #pragma clang diagnostic pop
                             ^
In file included from stan_files/breath_test_group_1.cc:3:
In file included from stan_files/breath_test_group_1.hpp:5:
In file included from /Users/lionel/Desktop/tidyr/revdep/library.noindex/breathteststan/rstan/include/rstan/rstaninc.hpp:3:
In file included from /Users/lionel/Desktop/tidyr/revdep/library.noindex/breathteststan/rstan/include/rstan/stan_fit.hpp:34:
In file included from /Users/lionel/Desktop/tidyr/revdep/library.noindex/breathteststan/StanHeaders/include/src/stan/services/diagnose/diagnose.hpp:10:
In file included from /Users/lionel/Desktop/tidyr/revdep/library.noindex/breathteststan/StanHeaders/include/src/stan/model/test_gradients.hpp:7:
In file included from /Users/lionel/Desktop/tidyr/revdep/library.noindex/breathteststan/StanHeaders/include/src/stan/model/log_prob_grad.hpp:4:
In file included from /Users/lionel/Desktop/tidyr/revdep/library.noindex/breathteststan/StanHeaders/include/stan/math/rev/mat.hpp:12:
In file included from /Users/lionel/Desktop/tidyr/revdep/library.noindex/breathteststan/StanHeaders/include/stan/math/prim/mat.hpp:96:
In file included from /Users/lionel/Desktop/tidyr/revdep/library.noindex/breathteststan/StanHeaders/include/stan/math/prim/mat/fun/csr_extract_u.hpp:6:
In file included from /Users/lionel/Desktop/tidyr/revdep/library.noindex/breathteststan/RcppEigen/include/Eigen/Sparse:26:
In file included from /Users/lionel/Desktop/tidyr/revdep/library.noindex/breathteststan/RcppEigen/include/Eigen/SparseCore:66:
/Users/lionel/Desktop/tidyr/revdep/library.noindex/breathteststan/RcppEigen/include/Eigen/src/Core/util/ReenableStupidWarnings.h:10:30: warning: pragma diagnostic pop could not pop, no matching push [-Wunknown-pragmas]
    #pragma clang diagnostic pop
                             ^
In file included from stan_files/breath_test_1.cc:3:
In file included from stan_files/breath_test_1.hpp:5:
In file included from /Users/lionel/Desktop/tidyr/revdep/library.noindex/breathteststan/rstan/include/rstan/rstaninc.hpp:3:
In file included from /Users/lionel/Desktop/tidyr/revdep/library.noindex/breathteststan/rstan/include/rstan/stan_fit.hpp:34:
In file included from /Users/lionel/Desktop/tidyr/revdep/library.noindex/breathteststan/StanHeaders/include/src/stan/services/diagnose/diagnose.hpp:10:
In file included from /Users/lionel/Desktop/tidyr/revdep/library.noindex/breathteststan/StanHeaders/include/src/stan/model/test_gradients.hpp:7:
In file included from /Users/lionel/Desktop/tidyr/revdep/library.noindex/breathteststan/StanHeaders/include/src/stan/model/log_prob_grad.hpp:4:
In file included from /Users/lionel/Desktop/tidyr/revdep/library.noindex/breathteststan/StanHeaders/include/stan/math/rev/mat.hpp:12:
In file included from /Users/lionel/Desktop/tidyr/revdep/library.noindex/breathteststan/StanHeaders/include/stan/math/prim/mat.hpp:96:
In file included from /Users/lionel/Desktop/tidyr/revdep/library.noindex/breathteststan/StanHeaders/include/stan/math/prim/mat/fun/csr_extract_u.hpp:6:
In file included from /Users/lionel/Desktop/tidyr/revdep/library.noindex/breathteststan/RcppEigen/include/Eigen/Sparse:26:
In file included from /Users/lionel/Desktop/tidyr/revdep/library.noindex/breathteststan/RcppEigen/include/Eigen/SparseCore:66:
/Users/lionel/Desktop/tidyr/revdep/library.noindex/breathteststan/RcppEigen/include/Eigen/src/Core/util/ReenableStupidWarnings.h:10:30: warning: pragma diagnostic pop could not pop, no matching push [-Wunknown-pragmas]
    #pragma clang diagnostic pop
                             ^
In file included from stan_files/breath_test_group_1.cc:3:
In file included from stan_files/breath_test_group_1.hpp:5:
In file included from /Users/lionel/Desktop/tidyr/revdep/library.noindex/breathteststan/rstan/include/rstan/rstaninc.hpp:3:
In file included from /Users/lionel/Desktop/tidyr/revdep/library.noindex/breathteststan/rstan/include/rstan/stan_fit.hpp:34:
In file included from /Users/lionel/Desktop/tidyr/revdep/library.noindex/breathteststan/StanHeaders/include/src/stan/services/diagnose/diagnose.hpp:10:
In file included from /Users/lionel/Desktop/tidyr/revdep/library.noindex/breathteststan/StanHeaders/include/src/stan/model/test_gradients.hpp:7:
In file included from /Users/lionel/Desktop/tidyr/revdep/library.noindex/breathteststan/StanHeaders/include/src/stan/model/log_prob_grad.hpp:4:
In file included from /Users/lionel/Desktop/tidyr/revdep/library.noindex/breathteststan/StanHeaders/include/stan/math/rev/mat.hpp:12:
In file included from /Users/lionel/Desktop/tidyr/revdep/library.noindex/breathteststan/StanHeaders/include/stan/math/prim/mat.hpp:96:
In file included from /Users/lionel/Desktop/tidyr/revdep/library.noindex/breathteststan/StanHeaders/include/stan/math/prim/mat/fun/csr_extract_u.hpp:6:
In file included from /Users/lionel/Desktop/tidyr/revdep/library.noindex/breathteststan/RcppEigen/include/Eigen/Sparse:27:
In file included from /Users/lionel/Desktop/tidyr/revdep/library.noindex/breathteststan/RcppEigen/include/Eigen/OrderingMethods:71:
/Users/lionel/Desktop/tidyr/revdep/library.noindex/breathteststan/RcppEigen/include/Eigen/src/Core/util/ReenableStupidWarnings.h:10:30: warning: pragma diagnostic pop could not pop, no matching push [-Wunknown-pragmas]
    #pragma clang diagnostic pop
                             ^
In file included from stan_files/breath_test_1.cc:3:
In file included from stan_files/breath_test_1.hpp:5:
In file included from /Users/lionel/Desktop/tidyr/revdep/library.noindex/breathteststan/rstan/include/rstan/rstaninc.hpp:3:
In file included from /Users/lionel/Desktop/tidyr/revdep/library.noindex/breathteststan/rstan/include/rstan/stan_fit.hpp:34:
In file included from /Users/lionel/Desktop/tidyr/revdep/library.noindex/breathteststan/StanHeaders/include/src/stan/services/diagnose/diagnose.hpp:10:
In file included from /Users/lionel/Desktop/tidyr/revdep/library.noindex/breathteststan/StanHeaders/include/src/stan/model/test_gradients.hpp:7:
In file included from /Users/lionel/Desktop/tidyr/revdep/library.noindex/breathteststan/StanHeaders/include/src/stan/model/log_prob_grad.hpp:4:
In file included from /Users/lionel/Desktop/tidyr/revdep/library.noindex/breathteststan/StanHeaders/include/stan/math/rev/mat.hpp:12:
In file included from /Users/lionel/Desktop/tidyr/revdep/library.noindex/breathteststan/StanHeaders/include/stan/math/prim/mat.hpp:96:
In file included from /Users/lionel/Desktop/tidyr/revdep/library.noindex/breathteststan/StanHeaders/include/stan/math/prim/mat/fun/csr_extract_u.hpp:6:
In file included from /Users/lionel/Desktop/tidyr/revdep/library.noindex/breathteststan/RcppEigen/include/Eigen/Sparse:27:
In file included from /Users/lionel/Desktop/tidyr/revdep/library.noindex/breathteststan/RcppEigen/include/Eigen/OrderingMethods:71:
/Users/lionel/Desktop/tidyr/revdep/library.noindex/breathteststan/RcppEigen/include/Eigen/src/Core/util/ReenableStupidWarnings.h:10:30: warning: pragma diagnostic pop could not pop, no matching push [-Wunknown-pragmas]
    #pragma clang diagnostic pop
                             ^
In file included from stan_files/breath_test_group_1.cc:3:
In file included from stan_files/breath_test_group_1.hpp:5:
In file included from /Users/lionel/Desktop/tidyr/revdep/library.noindex/breathteststan/rstan/include/rstan/rstaninc.hpp:3:
In file included from /Users/lionel/Desktop/tidyr/revdep/library.noindex/breathteststan/rstan/include/rstan/stan_fit.hpp:34:
In file included from /Users/lionel/Desktop/tidyr/revdep/library.noindex/breathteststan/StanHeaders/include/src/stan/services/diagnose/diagnose.hpp:10:
In file included from /Users/lionel/Desktop/tidyr/revdep/library.noindex/breathteststan/StanHeaders/include/src/stan/model/test_gradients.hpp:7:
In file included from /Users/lionel/Desktop/tidyr/revdep/library.noindex/breathteststan/StanHeaders/include/src/stan/model/log_prob_grad.hpp:4:
In file included from /Users/lionel/Desktop/tidyr/revdep/library.noindex/breathteststan/StanHeaders/include/stan/math/rev/mat.hpp:12:
In file included from /Users/lionel/Desktop/tidyr/revdep/library.noindex/breathteststan/StanHeaders/include/stan/math/prim/mat.hpp:96:
In file included from /Users/lionel/Desktop/tidyr/revdep/library.noindex/breathteststan/StanHeaders/include/stan/math/prim/mat/fun/csr_extract_u.hpp:6:
In file included from /Users/lionel/Desktop/tidyr/revdep/library.noindex/breathteststan/RcppEigen/include/Eigen/Sparse:29:
In file included from /Users/lionel/Desktop/tidyr/revdep/library.noindex/breathteststan/RcppEigen/include/Eigen/SparseCholesky:43:
/Users/lionel/Desktop/tidyr/revdep/library.noindex/breathteststan/RcppEigen/include/Eigen/src/Core/util/ReenableStupidWarnings.h:10:30: warning: In file included from stan_files/breath_test_1.cc:3:
In file included from stan_files/breath_test_1.hpp:5:
In file included from /Users/lionel/Desktop/tidyr/revdep/library.noindex/breathteststan/rstan/include/rstan/rstaninc.hpp:3:
In file included from /Users/lionel/Desktop/tidyr/revdep/library.noindex/breathteststan/rstan/include/rstan/stan_fit.hpp:34:
In file included from /Users/lionel/Desktop/tidyr/revdep/library.noindex/breathteststan/StanHeaders/include/src/stan/services/diagnose/diagnose.hpp:10:
In file included from /Users/lionel/Desktop/tidyr/revdep/library.noindex/breathteststan/StanHeaders/include/src/stan/model/test_gradients.hpp:7:
In file included from /Users/lionel/Desktop/tidyr/revdep/library.noindex/breathteststan/StanHeaders/include/src/stan/model/log_prob_grad.hpp:4:
In file included from /Users/lionel/Desktop/tidyr/revdep/library.noindex/breathteststan/StanHeaders/include/stan/math/rev/mat.hpp:12:
In file included from /Users/lionel/Desktop/tidyr/revdep/library.noindex/breathteststan/StanHeaders/include/stan/math/prim/mat.hpp:96:
In file included from /Users/lionel/Desktop/tidyr/revdep/library.noindex/breathteststan/StanHeaders/include/stan/math/prim/mat/fun/csr_extract_u.hpp:6:
In file included from /Users/lionel/Desktop/tidyr/revdep/library.noindex/breathteststan/RcppEigen/include/Eigen/Sparse:29:
In file included from /Users/lionel/Desktop/tidyr/revdep/library.noindex/breathteststan/RcppEigen/include/Eigen/SparseCholesky:43:
/Users/lionel/Desktop/tidyr/revdep/library.noindex/breathteststan/RcppEigen/include/Eigen/src/Core/util/ReenableStupidWarnings.h:10:30: warning: pragma diagnostic pop could not pop, no matching push [-Wunknown-pragmas]
pragma diagnostic pop could not pop, no matching push [-Wunknown-pragmas]    #pragma clang diagnostic pop
                             ^

    #pragma clang diagnostic pop
                             ^
In file included from stan_files/breath_test_group_1.cc:3:
In file included from stan_files/breath_test_group_1.hpp:5:
In file included from /Users/lionel/Desktop/tidyr/revdep/library.noindex/breathteststan/rstan/include/rstan/rstaninc.hpp:3:
In file included from /Users/lionel/Desktop/tidyr/revdep/library.noindex/breathteststan/rstan/include/rstan/stan_fit.hpp:34:
In file included from /Users/lionel/Desktop/tidyr/revdep/library.noindex/breathteststan/StanHeaders/include/src/stan/services/diagnose/diagnose.hpp:10:
In file included from /Users/lionel/Desktop/tidyr/revdep/library.noindex/breathteststan/StanHeaders/include/src/stan/model/test_gradients.hpp:7:
In file included from /Users/lionel/Desktop/tidyr/revdep/library.noindex/breathteststan/StanHeaders/include/src/stan/model/log_prob_grad.hpp:4:
In file included from /Users/lionel/Desktop/tidyr/revdep/library.noindex/breathteststan/StanHeaders/include/stan/math/rev/mat.hpp:12:
In file included from /Users/lionel/Desktop/tidyr/revdep/library.noindex/breathteststan/StanHeaders/include/stan/math/prim/mat.hpp:96:
In file included from /Users/lionel/Desktop/tidyr/revdep/library.noindex/breathteststan/StanHeaders/include/stan/math/prim/mat/fun/csr_extract_u.hpp:6:
In file included from /Users/lionel/Desktop/tidyr/revdep/library.noindex/breathteststan/RcppEigen/include/Eigen/Sparse:32:
In file included from /Users/lionel/Desktop/tidyr/revdep/library.noindex/breathteststan/RcppEigen/include/Eigen/SparseQR:35:
/Users/lionel/Desktop/tidyr/revdep/library.noindex/breathteststan/RcppEigen/include/Eigen/src/Core/util/ReenableStupidWarnings.h:10:30: warning: pragma diagnostic pop could not pop, no matching push [-Wunknown-pragmas]
    #pragma clang diagnostic pop
                             ^
In file included from stan_files/breath_test_1.cc:3:
In file included from stan_files/breath_test_1.hpp:5:
In file included from /Users/lionel/Desktop/tidyr/revdep/library.noindex/breathteststan/rstan/include/rstan/rstaninc.hpp:3:
In file included from /Users/lionel/Desktop/tidyr/revdep/library.noindex/breathteststan/rstan/include/rstan/stan_fit.hpp:34:
In file included from /Users/lionel/Desktop/tidyr/revdep/library.noindex/breathteststan/StanHeaders/include/src/stan/services/diagnose/diagnose.hpp:10:
In file included from /Users/lionel/Desktop/tidyr/revdep/library.noindex/breathteststan/StanHeaders/include/src/stan/model/test_gradients.hpp:7:
In file included from /Users/lionel/Desktop/tidyr/revdep/library.noindex/breathteststan/StanHeaders/include/src/stan/model/log_prob_grad.hpp:4:
In file included from /Users/lionel/Desktop/tidyr/revdep/library.noindex/breathteststan/StanHeaders/include/stan/math/rev/mat.hpp:12:
In file included from /Users/lionel/Desktop/tidyr/revdep/library.noindex/breathteststan/StanHeaders/include/stan/math/prim/mat.hpp:96:
In file included from /Users/lionel/Desktop/tidyr/revdep/library.noindex/breathteststan/StanHeaders/include/stan/math/prim/mat/fun/csr_extract_u.hpp:6:
In file included from /Users/lionel/Desktop/tidyr/revdep/library.noindex/breathteststan/RcppEigen/include/Eigen/Sparse:32:
In file included from /Users/lionel/Desktop/tidyr/revdep/library.noindex/breathteststan/RcppEigen/include/Eigen/SparseQR:35:
/Users/lionel/Desktop/tidyr/revdep/library.noindex/breathteststan/RcppEigen/include/Eigen/src/Core/util/ReenableStupidWarnings.h:10:30: warning: pragma diagnostic pop could not pop, no matching push [-Wunknown-pragmas]
    #pragma clang diagnostic pop
                             ^
In file included from stan_files/breath_test_1.cc:3:
In file included from stan_files/breath_test_1.hpp:5:
In file included from /Users/lionel/Desktop/tidyr/revdep/library.noindex/breathteststan/rstan/include/rstan/rstaninc.hpp:3:
In file included from /Users/lionel/Desktop/tidyr/revdep/library.noindex/breathteststan/rstan/include/rstan/stan_fit.hpp:34:
In file included from /Users/lionel/Desktop/tidyr/revdep/library.noindex/breathteststan/StanHeaders/include/src/stan/services/diagnose/diagnose.hpp:10:
In file included from /Users/lionel/Desktop/tidyr/revdep/library.noindex/breathteststan/StanHeaders/include/src/stan/model/test_gradients.hpp:7:
In file included from /Users/lionel/Desktop/tidyr/revdep/library.noindex/breathteststan/StanHeaders/include/src/stan/model/log_prob_grad.hpp:4:
In file included from /Users/lionel/Desktop/tidyr/revdep/library.noindex/breathteststan/StanHeaders/include/stan/math/rev/mat.hpp:12:
In file included from /Users/lionel/Desktop/tidyr/revdep/library.noindex/breathteststan/StanHeaders/include/stan/math/prim/mat.hpp:96:
In file included from /Users/lionel/Desktop/tidyr/revdep/library.noindex/breathteststan/StanHeaders/include/stan/math/prim/mat/fun/csr_extract_u.hpp:6:
In file included from /Users/lionel/Desktop/tidyr/revdep/library.noindex/breathteststan/RcppEigen/include/Eigen/Sparse:33:
In file included from /Users/lionel/Desktop/tidyr/revdep/library.noindex/breathteststan/RcppEigen/include/Eigen/IterativeLinearSolvers:46:
/Users/lionel/Desktop/tidyr/revdep/library.noindex/breathteststan/RcppEigen/include/Eigen/src/Core/util/ReenableStupidWarnings.h:10:30: warning: pragma diagnostic pop could not pop, no matching push [-Wunknown-pragmas]
    #pragma clang diagnostic pop
                             ^
In file included from stan_files/breath_test_group_1.cc:3:
In file included from stan_files/breath_test_group_1.hpp:5:
In file included from /Users/lionel/Desktop/tidyr/revdep/library.noindex/breathteststan/rstan/include/rstan/rstaninc.hpp:3:
In file included from /Users/lionel/Desktop/tidyr/revdep/library.noindex/breathteststan/rstan/include/rstan/stan_fit.hpp:34:
In file included from /Users/lionel/Desktop/tidyr/revdep/library.noindex/breathteststan/StanHeaders/include/src/stan/services/diagnose/diagnose.hpp:10:
In file included from /Users/lionel/Desktop/tidyr/revdep/library.noindex/breathteststan/StanHeaders/include/src/stan/model/test_gradients.hpp:7:
In file included from /Users/lionel/Desktop/tidyr/revdep/library.noindex/breathteststan/StanHeaders/include/src/stan/model/log_prob_grad.hpp:4:
In file included from /Users/lionel/Desktop/tidyr/revdep/library.noindex/breathteststan/StanHeaders/include/stan/math/rev/mat.hpp:12:
In file included from /Users/lionel/Desktop/tidyr/revdep/library.noindex/breathteststan/StanHeaders/include/stan/math/prim/mat.hpp:96:
In file included from /Users/lionel/Desktop/tidyr/revdep/library.noindex/breathteststan/StanHeaders/include/stan/math/prim/mat/fun/csr_extract_u.hpp:6:
In file included from /Users/lionel/Desktop/tidyr/revdep/library.noindex/breathteststan/RcppEigen/include/Eigen/Sparse:33:
In file included from /Users/lionel/Desktop/tidyr/revdep/library.noindex/breathteststan/RcppEigen/include/Eigen/IterativeLinearSolvers:46:
/Users/lionel/Desktop/tidyr/revdep/library.noindex/breathteststan/RcppEigen/include/Eigen/src/Core/util/ReenableStupidWarnings.h:10:30: warning: pragma diagnostic pop could not pop, no matching push [-Wunknown-pragmas]
    #pragma clang diagnostic pop
                             ^
In file included from stan_files/breath_test_group_1.cc:3:
In file included from stan_files/breath_test_group_1.hpp:5:
In file included from /Users/lionel/Desktop/tidyr/revdep/library.noindex/breathteststan/rstan/include/rstan/rstaninc.hpp:3:
In file included from /Users/lionel/Desktop/tidyr/revdep/library.noindex/breathteststan/rstan/include/rstan/stan_fit.hpp:34:
In file included from /Users/lionel/Desktop/tidyr/revdep/library.noindex/breathteststan/StanHeaders/include/src/stan/services/diagnose/diagnose.hpp:10:
In file included from /Users/lionel/Desktop/tidyr/revdep/library.noindex/breathteststan/StanHeaders/include/src/stan/model/test_gradients.hpp:7:
In file included from /Users/lionel/Desktop/tidyr/revdep/library.noindex/breathteststan/StanHeaders/include/src/stan/model/log_prob_grad.hpp:4:
In file included from /Users/lionel/Desktop/tidyr/revdep/library.noindex/breathteststan/StanHeaders/include/stan/math/rev/mat.hpp:4:
In file included from /Users/lionel/Desktop/tidyr/revdep/library.noindex/breathteststan/StanHeaders/include/stan/math/rev/core.hpp:44:
/Users/lionel/Desktop/tidyr/revdep/library.noindex/breathteststan/StanHeaders/include/stan/math/rev/core/set_zero_all_adjoints.hpp:14:13: warning: unused function 'set_zero_all_adjoints' [-Wunused-function]
static void set_zero_all_adjoints() {
            ^
In file included from stan_files/breath_test_group_1.cc:3:
In file included from stan_files/breath_test_group_1.hpp:5:
In file included from /Users/lionel/Desktop/tidyr/revdep/library.noindex/breathteststan/rstan/include/rstan/rstaninc.hpp:3:
In file included from /Users/lionel/Desktop/tidyr/revdep/library.noindex/breathteststan/rstan/include/rstan/stan_fit.hpp:34:
In file included from /Users/lionel/Desktop/tidyr/revdep/library.noindex/breathteststan/StanHeaders/include/src/stan/services/diagnose/diagnose.hpp:10:
In file included from /Users/lionel/Desktop/tidyr/revdep/library.noindex/breathteststan/StanHeaders/include/src/stan/model/test_gradients.hpp:7:
In file included from /Users/lionel/Desktop/tidyr/revdep/library.noindex/breathteststan/StanHeaders/include/src/stan/model/log_prob_grad.hpp:4:
In file included from /Users/lionel/Desktop/tidyr/revdep/library.noindex/breathteststan/StanHeaders/include/stan/math/rev/mat.hpp:12:
In file included from /Users/lionel/Desktop/tidyr/revdep/library.noindex/breathteststan/StanHeaders/include/stan/math/prim/mat.hpp:70:
/Users/lionel/Desktop/tidyr/revdep/library.noindex/breathteststan/StanHeaders/include/stan/math/prim/mat/fun/autocorrelation.hpp:18:8: warning: function 'fft_next_good_size' is not needed and will not be emitted [-Wunneeded-internal-declaration]
size_t fft_next_good_size(size_t N) {
       ^
In file included from stan_files/breath_test_1.cc:3:
In file included from stan_files/breath_test_1.hpp:5:
In file included from /Users/lionel/Desktop/tidyr/revdep/library.noindex/breathteststan/rstan/include/rstan/rstaninc.hpp:3:
In file included from /Users/lionel/Desktop/tidyr/revdep/library.noindex/breathteststan/rstan/include/rstan/stan_fit.hpp:34:
In file included from /Users/lionel/Desktop/tidyr/revdep/library.noindex/breathteststan/StanHeaders/include/src/stan/services/diagnose/diagnose.hpp:10:
In file included from /Users/lionel/Desktop/tidyr/revdep/library.noindex/breathteststan/StanHeaders/include/src/stan/model/test_gradients.hpp:7:
In file included from /Users/lionel/Desktop/tidyr/revdep/library.noindex/breathteststan/StanHeaders/include/src/stan/model/log_prob_grad.hpp:4:
In file included from /Users/lionel/Desktop/tidyr/revdep/library.noindex/breathteststan/StanHeaders/include/stan/math/rev/mat.hpp:4:
In file included from /Users/lionel/Desktop/tidyr/revdep/library.noindex/breathteststan/StanHeaders/include/stan/math/rev/core.hpp:44:
/Users/lionel/Desktop/tidyr/revdep/library.noindex/breathteststan/StanHeaders/include/stan/math/rev/core/set_zero_all_adjoints.hpp:14:13: warning: unused function 'set_zero_all_adjoints' [-Wunused-function]
static void set_zero_all_adjoints() {
            ^
In file included from stan_files/breath_test_1.cc:3:
In file included from stan_files/breath_test_1.hpp:5:
In file included from /Users/lionel/Desktop/tidyr/revdep/library.noindex/breathteststan/rstan/include/rstan/rstaninc.hpp:3:
In file included from /Users/lionel/Desktop/tidyr/revdep/library.noindex/breathteststan/rstan/include/rstan/stan_fit.hpp:34:
In file included from /Users/lionel/Desktop/tidyr/revdep/library.noindex/breathteststan/StanHeaders/include/src/stan/services/diagnose/diagnose.hpp:10:
In file included from /Users/lionel/Desktop/tidyr/revdep/library.noindex/breathteststan/StanHeaders/include/src/stan/model/test_gradients.hpp:7:
In file included from /Users/lionel/Desktop/tidyr/revdep/library.noindex/breathteststan/StanHeaders/include/src/stan/model/log_prob_grad.hpp:4:
In file included from /Users/lionel/Desktop/tidyr/revdep/library.noindex/breathteststan/StanHeaders/include/stan/math/rev/mat.hpp:12:
In file included from /Users/lionel/Desktop/tidyr/revdep/library.noindex/breathteststan/StanHeaders/include/stan/math/prim/mat.hpp:70:
/Users/lionel/Desktop/tidyr/revdep/library.noindex/breathteststan/StanHeaders/include/stan/math/prim/mat/fun/autocorrelation.hpp:18:8: warning: function 'fft_next_good_size' is not needed and will not be emitted [-Wunneeded-internal-declaration]
size_t fft_next_good_size(size_t N) {
       ^
15 warnings generated.
15 warnings generated.
clang++ -std=gnu++14 -dynamiclib -Wl,-headerpad_max_install_names -undefined dynamic_lookup -single_module -multiply_defined suppress -L/Library/Frameworks/R.framework/Resources/lib -L/usr/local/lib -o breathteststan.so stan_files/breath_test_1.o stan_files/breath_test_group_1.o init.o -F/Library/Frameworks/R.framework/.. -framework R -Wl,-framework -Wl,CoreFoundation
rm stan_files/breath_test_1.cc stan_files/breath_test_group_1.cc
installing to /Users/lionel/Desktop/tidyr/revdep/checks.noindex/breathteststan/new/breathteststan.Rcheck/breathteststan/libs
** R
** inst
** byte-compile and prepare package for lazy loading
** help
*** installing help indices
** building package indices
** testing if installed package can be loaded
* DONE (breathteststan)

```
### CRAN

```
* installing *source* package ‘breathteststan’ ...
** package ‘breathteststan’ successfully unpacked and MD5 sums checked
** libs
"/Library/Frameworks/R.framework/Resources/bin/Rscript" -e "source(file.path('..', 'tools', 'make_cc.R')); make_cc(commandArgs(TRUE))" stan_files/breath_test_1.stan
"/Library/Frameworks/R.framework/Resources/bin/Rscript" -e "source(file.path('..', 'tools', 'make_cc.R')); make_cc(commandArgs(TRUE))" stan_files/breath_test_group_1.stan
clang++ -std=gnu++14 -I"/Library/Frameworks/R.framework/Resources/include" -DNDEBUG -I"../inst/include" -I"`"/Library/Frameworks/R.framework/Resources/bin/Rscript" -e "cat(system.file('include', 'src', package = 'StanHeaders'))"`" -DBOOST_DISABLE_ASSERTS -DEIGEN_NO_DEBUG -DBOOST_MATH_OVERFLOW_ERROR_POLICY=errno_on_error -I"/Users/lionel/Desktop/tidyr/revdep/library.noindex/breathteststan/StanHeaders/include" -I"/Users/lionel/Desktop/tidyr/revdep/library.noindex/breathteststan/rstan/include" -I"/Users/lionel/Desktop/tidyr/revdep/library.noindex/tidyr/old/BH/include" -I"/Users/lionel/Desktop/tidyr/revdep/library.noindex/tidyr/old/Rcpp/include" -I"/Users/lionel/Desktop/tidyr/revdep/library.noindex/breathteststan/RcppEigen/include" -I/usr/local/include   -fPIC  -Wall -g -O2 -c init.cpp -o init.o
Wrote C++ file "stan_files/breath_test_1.cc"
Wrote C++ file "stan_files/breath_test_group_1.cc"
Error in readRDS("/var/folders/b9/1vbq6rn93_1fk71sn95dqb8r0000gn/T//Rtmp6TvDAr/filebf624b5a3582") : 
  error reading from connection
Calls: .Last -> readRDS
Execution halted
make: *** [stan_files/breath_test_group_1.cc] Error 1
make: *** Waiting for unfinished jobs....
rm stan_files/breath_test_1.cc stan_files/breath_test_group_1.cc
ERROR: compilation failed for package ‘breathteststan’
* removing ‘/Users/lionel/Desktop/tidyr/revdep/checks.noindex/breathteststan/old/breathteststan.Rcheck/breathteststan’

```
# broom.mixed

Version: 0.2.3

## In both

*   checking package dependencies ... NOTE
    ```
    Package suggested but not available for checking: ‘glmmADMB’
    ```

# caffsim

Version: 0.2.2

## In both

*   checking dependencies in R code ... NOTE
    ```
    Namespace in Imports field not imported from: ‘markdown’
      All declared Imports should be used.
    ```

# capm

Version: 0.13.5

## In both

*   checking data for non-ASCII characters ... NOTE
    ```
      Note: found 59 marked UTF-8 strings
    ```

# CATALYST

Version: 1.4.2

## In both

*   R CMD check timed out
    

*   checking for hidden files and directories ... NOTE
    ```
    Found the following hidden files and directories:
      .travis.yml
    These were most likely included in error. See section ‘Package
    structure’ in the ‘Writing R Extensions’ manual.
    ```

*   checking installed package size ... NOTE
    ```
      installed size is 11.1Mb
      sub-directories of 1Mb or more:
        R      2.1Mb
        data   3.6Mb
        doc    5.1Mb
    ```

*   checking R code for possible problems ... NOTE
    ```
    plotDiffHeatmap,matrix-SummarizedExperiment: no visible binding for
      global variable ‘cluster_id’
      (/Users/lionel/Desktop/tidyr/revdep/checks.noindex/CATALYST/new/CATALYST.Rcheck/00_pkg_src/CATALYST/R/plotDiffHeatmap.R:136)
    plotDiffHeatmap,matrix-SummarizedExperiment: no visible binding for
      global variable ‘sample_id’
      (/Users/lionel/Desktop/tidyr/revdep/checks.noindex/CATALYST/new/CATALYST.Rcheck/00_pkg_src/CATALYST/R/plotDiffHeatmap.R:136)
    Undefined global functions or variables:
      cluster_id sample_id
    ```

# ccfa

Version: 1.1.0

## In both

*   checking dependencies in R code ... NOTE
    ```
    Namespaces in Imports field not imported from:
      ‘doParallel’ ‘foreach’
      All declared Imports should be used.
    ```

# CDECRetrieve

Version: 0.1.2

## In both

*   checking dependencies in R code ... NOTE
    ```
    Namespaces in Imports field not imported from:
      ‘lazyeval’ ‘purrr’ ‘roxygen2’
      All declared Imports should be used.
    ```

# childsds

Version: 0.6.7

## In both

*   checking dependencies in R code ... NOTE
    ```
    Namespace in Imports field not imported from: ‘gamlss.dist’
      All declared Imports should be used.
    ```

*   checking data for non-ASCII characters ... NOTE
    ```
      Note: found 20 marked UTF-8 strings
    ```

# chromswitch

Version: 1.2.1

## In both

*   checking package dependencies ... NOTE
    ```
    Package suggested but not available for checking: ‘devtools’
    ```

# clusterProfiler

Version: 3.8.1

## In both

*   checking package dependencies ... ERROR
    ```
    Package required but not available: ‘GO.db’
    
    Packages suggested but not available for checking: ‘KEGG.db’ ‘org.Hs.eg.db’
    
    See section ‘The DESCRIPTION file’ in the ‘Writing R Extensions’
    manual.
    ```

# CNPBayes

Version: 1.10.0

## In both

*   checking Rd \usage sections ... WARNING
    ```
    Undocumented arguments in documentation object 'marginal_lik'
      ‘value’
    
    Functions with \usage entries need to have the appropriate \alias
    entries, and all their arguments documented.
    The \usage entries must correspond to syntactically valid R code.
    See chapter ‘Writing R documentation files’ in the ‘Writing R
    Extensions’ manual.
    ```

*   checking re-building of vignette outputs ... WARNING
    ```
    Error in re-building vignettes:
      ...
    pandoc-citeproc: when expecting a product (:*:), encountered Object instead
    Error running filter /usr/local/bin/pandoc-citeproc:
    Filter returned error status 1
    Error: processing vignette 'Convergence.Rmd' failed with diagnostics:
    pandoc document conversion failed with error 83
    Execution halted
    ```

*   checking installed package size ... NOTE
    ```
      installed size is  8.7Mb
      sub-directories of 1Mb or more:
        R      3.1Mb
        doc    3.4Mb
        libs   1.3Mb
    ```

*   checking R code for possible problems ... NOTE
    ```
    copyNumber,SingleBatchCopyNumber: no visible binding for global
      variable ‘theta.star’
      (/Users/lionel/Desktop/tidyr/revdep/checks.noindex/CNPBayes/new/CNPBayes.Rcheck/00_pkg_src/CNPBayes/R/copynumber-models.R:148-149)
    copyNumber,SingleBatchCopyNumber: no visible binding for global
      variable ‘theta.star’
      (/Users/lionel/Desktop/tidyr/revdep/checks.noindex/CNPBayes/new/CNPBayes.Rcheck/00_pkg_src/CNPBayes/R/copynumber-models.R:150-151)
    Undefined global functions or variables:
      theta.star
    ```

# CNVScope

Version: 1.9.7

## In both

*   checking package dependencies ... ERROR
    ```
    Package required but not available: ‘BSgenome.Hsapiens.UCSC.hg19’
    
    See section ‘The DESCRIPTION file’ in the ‘Writing R Extensions’
    manual.
    ```

# cocktailApp

Version: 0.2.0

## In both

*   checking data for non-ASCII characters ... NOTE
    ```
      Note: found 14661 marked UTF-8 strings
    ```

# codebook

Version: 0.6.3

## In both

*   checking dependencies in R code ... NOTE
    ```
    Namespaces in Imports field not imported from:
      ‘graphics’ ‘pander’
      All declared Imports should be used.
    ```

*   checking data for non-ASCII characters ... NOTE
    ```
      Note: found 65 marked UTF-8 strings
    ```

# codified

Version: 0.2.0

## In both

*   checking package dependencies ... NOTE
    ```
    Package suggested but not available for checking: ‘devtools’
    ```

*   checking dependencies in R code ... NOTE
    ```
    Namespaces in Imports field not imported from:
      ‘methods’ ‘readr’
      All declared Imports should be used.
    ```

# compareDF

Version: 1.7.0

## In both

*   checking dependencies in R code ... NOTE
    ```
    Namespaces in Imports field not imported from:
      ‘magrittr’ ‘stringr’
      All declared Imports should be used.
    ```

# COMPASS

Version: 1.18.1

## In both

*   checking re-building of vignette outputs ... WARNING
    ```
    Error in re-building vignettes:
      ...
    Quitting from lines 39-41 (SimpleCOMPASS.Rmd) 
    Error: processing vignette 'SimpleCOMPASS.Rmd' failed with diagnostics:
    there is no package called 'readxl'
    Execution halted
    ```

*   checking package dependencies ... NOTE
    ```
    Package suggested but not available for checking: ‘devtools’
    ```

*   checking dependencies in R code ... NOTE
    ```
    Namespaces in Imports field not imported from:
      ‘BiocStyle’ ‘rmarkdown’
      All declared Imports should be used.
    ':::' call which should be '::': ‘flowWorkspace:::.getNodeInd’
      See the note in ?`:::` about the use of this operator.
    ```

*   checking R code for possible problems ... NOTE
    ```
    COMPASSfitToCountsTable: no visible binding for global variable
      ‘population’
      (/Users/lionel/Desktop/tidyr/revdep/checks.noindex/COMPASS/new/COMPASS.Rcheck/00_pkg_src/COMPASS/R/utils.R:193)
    COMPASSfitToCountsTable: no visible binding for global variable ‘Count’
      (/Users/lionel/Desktop/tidyr/revdep/checks.noindex/COMPASS/new/COMPASS.Rcheck/00_pkg_src/COMPASS/R/utils.R:193)
    COMPASSfitToCountsTable: no visible binding for global variable
      ‘population’
      (/Users/lionel/Desktop/tidyr/revdep/checks.noindex/COMPASS/new/COMPASS.Rcheck/00_pkg_src/COMPASS/R/utils.R:194)
    COMPASSfitToCountsTable: no visible binding for global variable ‘Count’
      (/Users/lionel/Desktop/tidyr/revdep/checks.noindex/COMPASS/new/COMPASS.Rcheck/00_pkg_src/COMPASS/R/utils.R:194)
    COMPASSfitToCountsTable: no visible binding for global variable ‘id’
      (/Users/lionel/Desktop/tidyr/revdep/checks.noindex/COMPASS/new/COMPASS.Rcheck/00_pkg_src/COMPASS/R/utils.R:200)
    COMPASSfitToCountsTable: no visible binding for global variable ‘id’
      (/Users/lionel/Desktop/tidyr/revdep/checks.noindex/COMPASS/new/COMPASS.Rcheck/00_pkg_src/COMPASS/R/utils.R:206)
    Undefined global functions or variables:
      Count id population
    ```

*   checking for unstated dependencies in vignettes ... NOTE
    ```
    'library' or 'require' calls not declared from:
      ‘ggplot2’ ‘readxl’
    ```

# congressbr

Version: 0.1.3

## In both

*   checking examples ... ERROR
    ```
    Running examples in ‘congressbr-Ex.R’ failed
    The error most likely occurred in:
    
    > ### Name: sen_bills
    > ### Title: Downloads and tidies information on the legislation in the
    > ###   Federal Senate
    > ### Aliases: sen_bills
    > 
    > ### ** Examples
    > 
    > pls_5_2010 <- sen_bills(type = "PLS", number = 5, year = 2010)
    Error: Column `bill_indexing` must be a 1d atomic vector or a list
    Execution halted
    ```

*   checking package dependencies ... NOTE
    ```
    Package suggested but not available for checking: ‘devtools’
    ```

*   checking data for non-ASCII characters ... NOTE
    ```
      Note: found 187 marked UTF-8 strings
    ```

# countyfloods

Version: 0.1.0

## In both

*   checking dependencies in R code ... NOTE
    ```
    Namespace in Imports field not imported from: ‘maps’
      All declared Imports should be used.
    ```

# countyweather

Version: 0.1.0

## In both

*   checking re-building of vignette outputs ... WARNING
    ```
    ...
    The following objects are masked from 'package:stats':
    
        filter, lag
    
    The following objects are masked from 'package:base':
    
        intersect, setdiff, setequal, union
    
    
    Attaching package: 'lubridate'
    
    The following object is masked from 'package:base':
    
        date
    
    pandoc-citeproc: when expecting a product (:*:), encountered Object instead
    Error running filter /usr/local/bin/pandoc-citeproc:
    Filter returned error status 1
    Error: processing vignette 'countyweather.Rmd' failed with diagnostics:
    pandoc document conversion failed with error 83
    Execution halted
    ```

*   checking data for non-ASCII characters ... NOTE
    ```
      Note: found 1 marked UTF-8 string
    ```

# coxed

Version: 0.2.0

## In both

*   checking Rd cross-references ... NOTE
    ```
    Package unavailable to check Rd xrefs: ‘mediation’
    ```

# crawl

Version: 2.2.1

## In both

*   checking dependencies in R code ... NOTE
    ```
    Namespaces in Imports field not imported from:
      ‘gdistance’ ‘raster’
      All declared Imports should be used.
    ```

# crypto

Version: 1.0.3

## In both

*   checking dependencies in R code ... NOTE
    ```
    Namespace in Imports field not imported from: ‘yaml’
      All declared Imports should be used.
    ```

# curatedMetagenomicData

Version: 1.10.2

## In both

*   checking examples ... ERROR
    ```
    ...
    Running examples in ‘curatedMetagenomicData-Ex.R’ failed
    The error most likely occurred in:
    
    > ### Name: ExpressionSet2phyloseq
    > ### Title: Convert an ExpressionSet object to a phyloseq object
    > ### Aliases: ExpressionSet2phyloseq
    > 
    > ### ** Examples
    > 
    > eset <- LomanNJ_2013.metaphlan_bugs_list.stool()
    snapshotDate(): 2018-04-27
    see ?curatedMetagenomicData and browseVignettes('curatedMetagenomicData') for documentation
    downloading 0 resources
    loading from cache 
        ‘/Users/lionel//.ExperimentHub/1278’
    > ExpressionSet2phyloseq(eset)
    Loading required namespace: phyloseq
    Failed with error:  ‘there is no package called ‘vegan’’
    Error in ExpressionSet2phyloseq(eset) : 
      Please install the 'phyloseq' package to make phyloseq objects
    Execution halted
    ```

*   checking tests ...
    ```
     ERROR
    Running the tests in ‘tests/testthat.R’ failed.
    Last 13 lines of output:
             return(eset)
         }) at /Users/lionel/Desktop/tidyr/revdep/checks.noindex/curatedMetagenomicData/new/curatedMetagenomicData.Rcheck/00_pkg_src/curatedMetagenomicData/R/curatedMetagenomicData.R:61
      3: FUN(X[[i]], ...)
      4: ExpressionSet2phyloseq(eset) at /Users/lionel/Desktop/tidyr/revdep/checks.noindex/curatedMetagenomicData/new/curatedMetagenomicData.Rcheck/00_pkg_src/curatedMetagenomicData/R/curatedMetagenomicData.R:69
      5: stop("Please install the 'phyloseq' package to make phyloseq objects") at /Users/lionel/Desktop/tidyr/revdep/checks.noindex/curatedMetagenomicData/new/curatedMetagenomicData.Rcheck/00_pkg_src/curatedMetagenomicData/R/ExpressionSet2phyloseq.R:52
      
      ══ testthat results  ═══════════════════════════════════════════════════════════
      OK: 23 SKIPPED: 0 FAILED: 4
      1. Error: ExpressionSet2phyloseq returns phyloseq class object (@test-ExpressionSet2phyloseq.R#4) 
      2. Error: ExpressionSet2phyloseq works with phylogenetictree = TRUE (@test-ExpressionSet2phyloseq.R#13) 
      3. Error: ExpressionSet2phyloseq returns the same numerical data with simplify=TRUE/FALSE (@test-ExpressionSet2phyloseq.R#23) 
      4. Error: curatedMetagenomicData works (@test-curatedMetagenomicData.R#28) 
      
      Error: testthat unit tests failed
      Execution halted
    ```

*   checking re-building of vignette outputs ... WARNING
    ```
    ...
    downloading 0 resources
    loading from cache 
        '/Users/lionel//.ExperimentHub/1278'
    Working on BritoIL_2016.metaphlan_bugs_list.oralcavity
    snapshotDate(): 2018-04-27
    see ?curatedMetagenomicData and browseVignettes('curatedMetagenomicData') for documentation
    downloading 0 resources
    loading from cache 
        '/Users/lionel//.ExperimentHub/1179'
    Working on Castro-NallarE_2015.metaphlan_bugs_list.oralcavity
    snapshotDate(): 2018-04-27
    see ?curatedMetagenomicData and browseVignettes('curatedMetagenomicData') for documentation
    downloading 0 resources
    loading from cache 
        '/Users/lionel//.ExperimentHub/391'
    convert: profile 'icc': 'RGB ': RGB color space not permitted on grayscale PNG `curatedMetagenomicData_files/figure-html/unnamed-chunk-18-1.png' @ warning/png.c/MagickPNGWarningHandler/1656.
    Quitting from lines 221-223 (curatedMetagenomicData.Rmd) 
    Error: processing vignette 'curatedMetagenomicData.Rmd' failed with diagnostics:
    package or namespace load failed for 'phyloseq' in loadNamespace(j <- i[[1L]], c(lib.loc, .libPaths()), versionCheck = vI[[j]]):
     there is no package called 'vegan'
    Execution halted
    ```

*   checking package dependencies ... NOTE
    ```
    Package suggested but not available for checking: ‘devtools’
    ```

*   checking installed package size ... NOTE
    ```
      installed size is  5.7Mb
      sub-directories of 1Mb or more:
        doc    1.4Mb
        help   2.7Mb
    ```

# d3r

Version: 0.8.4

## In both

*   checking package dependencies ... NOTE
    ```
    Packages which this enhances but not available for checking:
      ‘igraph’ ‘partykit’ ‘treemap’ ‘V8’
    ```

# DAPAR

Version: 1.12.11

## In both

*   checking whether package ‘DAPAR’ can be installed ... ERROR
    ```
    Installation failed.
    See ‘/Users/lionel/Desktop/tidyr/revdep/checks.noindex/DAPAR/new/DAPAR.Rcheck/00install.out’ for details.
    ```

## Installation

### Devel

```
* installing *source* package ‘DAPAR’ ...
** R
** inst
** byte-compile and prepare package for lazy loading
Warning in fun(libname, pkgname) :
  mzR has been built against a different Rcpp version (0.12.16)
than is installed on your system (0.12.19). This might lead to errors
when loading mzR. If you encounter such issues, please send a report,
including the output of sessionInfo() to the Bioc support forum at 
https://support.bioconductor.org/. For details see also
https://github.com/sneumann/mzR/wiki/mzR-Rcpp-compiler-linker-issue.
Error in loadNamespace(j <- i[[1L]], c(lib.loc, .libPaths()), versionCheck = vI[[j]]) : 
  there is no package called ‘DO.db’
ERROR: lazy loading failed for package ‘DAPAR’
* removing ‘/Users/lionel/Desktop/tidyr/revdep/checks.noindex/DAPAR/new/DAPAR.Rcheck/DAPAR’

```
### CRAN

```
* installing *source* package ‘DAPAR’ ...
** R
** inst
** byte-compile and prepare package for lazy loading
Warning in fun(libname, pkgname) :
  mzR has been built against a different Rcpp version (0.12.16)
than is installed on your system (0.12.19). This might lead to errors
when loading mzR. If you encounter such issues, please send a report,
including the output of sessionInfo() to the Bioc support forum at 
https://support.bioconductor.org/. For details see also
https://github.com/sneumann/mzR/wiki/mzR-Rcpp-compiler-linker-issue.
Error in loadNamespace(j <- i[[1L]], c(lib.loc, .libPaths()), versionCheck = vI[[j]]) : 
  there is no package called ‘DO.db’
ERROR: lazy loading failed for package ‘DAPAR’
* removing ‘/Users/lionel/Desktop/tidyr/revdep/checks.noindex/DAPAR/old/DAPAR.Rcheck/DAPAR’

```
# dartR

Version: 1.0.5

## In both

*   checking package dependencies ... ERROR
    ```
    Package required but not available: ‘vegan’
    
    See section ‘The DESCRIPTION file’ in the ‘Writing R Extensions’
    manual.
    ```

# DChIPRep

Version: 1.10.0

## In both

*   checking whether package ‘DChIPRep’ can be installed ... ERROR
    ```
    Installation failed.
    See ‘/Users/lionel/Desktop/tidyr/revdep/checks.noindex/DChIPRep/new/DChIPRep.Rcheck/00install.out’ for details.
    ```

## Installation

### Devel

```
* installing *source* package ‘DChIPRep’ ...
** R
** data
*** moving datasets to lazyload DB
Warning: namespace ‘DChIPRep’ is not available and has been replaced
by .GlobalEnv when processing object ‘testData’
Warning: namespace ‘DChIPRep’ is not available and has been replaced
by .GlobalEnv when processing object ‘testData’
** exec
** inst
** byte-compile and prepare package for lazy loading
Error in loadNamespace(i, c(lib.loc, .libPaths()), versionCheck = vI[[i]]) : 
  there is no package called ‘GO.db’
ERROR: lazy loading failed for package ‘DChIPRep’
* removing ‘/Users/lionel/Desktop/tidyr/revdep/checks.noindex/DChIPRep/new/DChIPRep.Rcheck/DChIPRep’

```
### CRAN

```
* installing *source* package ‘DChIPRep’ ...
** R
** data
*** moving datasets to lazyload DB
Warning: namespace ‘DChIPRep’ is not available and has been replaced
by .GlobalEnv when processing object ‘testData’
Warning: namespace ‘DChIPRep’ is not available and has been replaced
by .GlobalEnv when processing object ‘testData’
** exec
** inst
** byte-compile and prepare package for lazy loading
Error in loadNamespace(i, c(lib.loc, .libPaths()), versionCheck = vI[[i]]) : 
  there is no package called ‘GO.db’
ERROR: lazy loading failed for package ‘DChIPRep’
* removing ‘/Users/lionel/Desktop/tidyr/revdep/checks.noindex/DChIPRep/old/DChIPRep.Rcheck/DChIPRep’

```
# DeepBlueR

Version: 1.6.0

## In both

*   R CMD check timed out
    

*   checking Rd files ... NOTE
    ```
    prepare_Rd: deepblue_enrich_regions_fast.Rd:35-38: Dropping empty section \examples
    ```

# DEGreport

Version: 1.16.0

## In both

*   checking for hidden files and directories ... NOTE
    ```
    Found the following hidden files and directories:
      .travis.yml
    These were most likely included in error. See section ‘Package
    structure’ in the ‘Writing R Extensions’ manual.
    ```

*   checking DESCRIPTION meta-information ... NOTE
    ```
    Package listed in more than one of Depends, Imports, Suggests, Enhances:
      ‘knitr’
    A package should be listed in only one of these fields.
    ```

*   checking R code for possible problems ... NOTE
    ```
    ...
      (/Users/lionel/Desktop/tidyr/revdep/checks.noindex/DEGreport/new/DEGreport.Rcheck/00_pkg_src/DEGreport/R/methods.R:274-282)
    degMV: no visible binding for global variable ‘max_sd’
      (/Users/lionel/Desktop/tidyr/revdep/checks.noindex/DEGreport/new/DEGreport.Rcheck/00_pkg_src/DEGreport/R/methods.R:274-282)
    degPatterns: no visible global function definition for ‘rowMedians’
      (/Users/lionel/Desktop/tidyr/revdep/checks.noindex/DEGreport/new/DEGreport.Rcheck/00_pkg_src/DEGreport/R/clustering.R:785-787)
    degPatterns: no visible binding for global variable ‘genes’
      (/Users/lionel/Desktop/tidyr/revdep/checks.noindex/DEGreport/new/DEGreport.Rcheck/00_pkg_src/DEGreport/R/clustering.R:816-821)
    degPlotWide : <anonymous>: no visible binding for global variable
      ‘count’
      (/Users/lionel/Desktop/tidyr/revdep/checks.noindex/DEGreport/new/DEGreport.Rcheck/00_pkg_src/DEGreport/R/genePlots.R:155-158)
    significants,TopTags: no visible binding for global variable ‘FDR’
      (/Users/lionel/Desktop/tidyr/revdep/checks.noindex/DEGreport/new/DEGreport.Rcheck/00_pkg_src/DEGreport/R/AllMethods.R:147-151)
    significants,TopTags: no visible binding for global variable ‘logFC’
      (/Users/lionel/Desktop/tidyr/revdep/checks.noindex/DEGreport/new/DEGreport.Rcheck/00_pkg_src/DEGreport/R/AllMethods.R:147-151)
    significants,list : <anonymous>: no visible binding for global variable
      ‘gene’
      (/Users/lionel/Desktop/tidyr/revdep/checks.noindex/DEGreport/new/DEGreport.Rcheck/00_pkg_src/DEGreport/R/AllMethods.R:225)
    Undefined global functions or variables:
      .x FDR base_mean comp compare count counts covar enrichGO gene genes
      keys log2FoldChange log2fc logFC max_sd min_median ratios rowMedians
      simplify
    ```

# DEP

Version: 1.2.0

## In both

*   checking installed package size ... NOTE
    ```
      installed size is  6.0Mb
      sub-directories of 1Mb or more:
        R      1.2Mb
        data   1.4Mb
        doc    3.1Mb
    ```

# destiny

Version: 2.10.2

## In both

*   checking running R code from vignettes ...
    ```
    ...
      When tangling ‘Diffusion-Map-recap.ipynbmeta’:
    Error: Either IPython 3+ or Jupyter has to be installed, but neither could be called.
    Execution halted
    when running code in ‘Diffusion-Maps.ipynbmeta’
      ...
    
      When tangling ‘Diffusion-Maps.ipynbmeta’:
    Error: Either IPython 3+ or Jupyter has to be installed, but neither could be called.
    Execution halted
    when running code in ‘Global-Sigma.ipynbmeta’
      ...
    
      When tangling ‘Global-Sigma.ipynbmeta’:
    Error: Either IPython 3+ or Jupyter has to be installed, but neither could be called.
    Execution halted
    when running code in ‘tidyverse.ipynbmeta’
      ...
    
      When tangling ‘tidyverse.ipynbmeta’:
    Error: Either IPython 3+ or Jupyter has to be installed, but neither could be called.
    Execution halted
    ```

*   checking package dependencies ... NOTE
    ```
    Package which this enhances but not available for checking: ‘rgl’
    ```

*   checking installed package size ... NOTE
    ```
      installed size is  7.0Mb
      sub-directories of 1Mb or more:
        R     2.0Mb
        doc   4.3Mb
    ```

*   checking DESCRIPTION meta-information ... NOTE
    ```
    Package listed in more than one of Depends, Imports, Suggests, Enhances:
      ‘SingleCellExperiment’
    A package should be listed in only one of these fields.
    'LinkingTo' for ‘grDevices’ is unused as it has no 'include' directory
    ```

*   checking Rd cross-references ... NOTE
    ```
    Package unavailable to check Rd xrefs: ‘rgl’
    ```

*   checking Rd \usage sections ... NOTE
    ```
    S3 methods shown with full name in documentation object 'plot.DPT':
      ‘plot.DPT’
    
    S3 methods shown with full name in documentation object 'plot.DiffusionMap':
      ‘plot.DiffusionMap’
    
    The \usage entries for S3 methods should use the \method markup and
    not their full name.
    See chapter ‘Writing R documentation files’ in the ‘Writing R
    Extensions’ manual.
    ```

*   checking for unstated dependencies in vignettes ... NOTE
    ```
    '::' or ':::' imports not declared from:
      ‘gridExtra’ ‘viridis’
    'library' or 'require' calls not declared from:
      ‘IRdisplay’ ‘IRkernel’ ‘base64enc’ ‘forcats’ ‘readxl’ ‘repr’
      ‘tidyverse’
    ```

*   checking re-building of vignette outputs ... NOTE
    ```
    Error in re-building vignettes:
      ...
    Error: processing vignette 'DPT.ipynbmeta' failed with diagnostics:
    Either IPython 3+ or Jupyter has to be installed, but neither could be called.
    Execution halted
    ```

# dexter

Version: 0.8.1

## In both

*   checking re-building of vignette outputs ... WARNING
    ```
    Error in re-building vignettes:
      ...
    no column `person_id` provided, automatically generating unique person id's
    no column `person_id` provided, automatically generating unique person id's
    no column `person_id` provided, automatically generating unique person id's
    pandoc-citeproc: when expecting a product (:*:), encountered Object instead
    Error running filter /usr/local/bin/pandoc-citeproc:
    Filter returned error status 1
    Error: processing vignette 'Equating.Rmd' failed with diagnostics:
    pandoc document conversion failed with error 83
    Execution halted
    ```

# dextergui

Version: 0.1.4

## In both

*   checking dependencies in R code ... NOTE
    ```
    Unexported objects imported by ':::' calls:
      ‘dexter:::get_resp_data’ ‘dexter:::qcolors’
      See the note in ?`:::` about the use of this operator.
    ```

# dexterMST

Version: 0.1.0

## In both

*   checking re-building of vignette outputs ... WARNING
    ```
    Error in re-building vignettes:
      ...
    Warning in engine$weave(file, quiet = quiet, encoding = enc) :
      The vignette engine knitr::rmarkdown is not available, because the rmarkdown package is not installed. Please install it.
    Quitting from lines 44-66 (multistage_fundamentals.Rmd) 
    Error: processing vignette 'multistage_fundamentals.Rmd' failed with diagnostics:
    package or namespace load failed for 'mirt' in loadNamespace(i, c(lib.loc, .libPaths()), versionCheck = vI[[i]]):
     there is no package called 'vegan'
    Execution halted
    ```

# DiagrammeR

Version: 1.0.0

## In both

*   checking installed package size ... NOTE
    ```
      installed size is  6.8Mb
      sub-directories of 1Mb or more:
        R             3.0Mb
        htmlwidgets   3.0Mb
    ```

*   checking data for non-ASCII characters ... NOTE
    ```
      Note: found 1 marked UTF-8 string
    ```

# diffcyt

Version: 1.0.10

## In both

*   checking re-building of vignette outputs ... WARNING
    ```
    Error in re-building vignettes:
      ...
    Quitting from lines 127-144 (diffcyt_workflow.Rmd) 
    Error: processing vignette 'diffcyt_workflow.Rmd' failed with diagnostics:
    there is no package called 'HDCytoData'
    Execution halted
    ```

*   checking package dependencies ... NOTE
    ```
    Package suggested but not available for checking: ‘HDCytoData’
    ```

*   checking R code for possible problems ... NOTE
    ```
    ...
      (/Users/lionel/Desktop/tidyr/revdep/checks.noindex/diffcyt/new/diffcyt.Rcheck/00_pkg_src/diffcyt/R/calcMedians.R:133-136)
    calcMediansByClusterMarker: no visible binding for global variable
      ‘cluster_id’
      (/Users/lionel/Desktop/tidyr/revdep/checks.noindex/diffcyt/new/diffcyt.Rcheck/00_pkg_src/diffcyt/R/calcMediansByClusterMarker.R:123-126)
    calcMediansByClusterMarker: no visible binding for global variable
      ‘marker’
      (/Users/lionel/Desktop/tidyr/revdep/checks.noindex/diffcyt/new/diffcyt.Rcheck/00_pkg_src/diffcyt/R/calcMediansByClusterMarker.R:123-126)
    calcMediansByClusterMarker: no visible binding for global variable
      ‘value’
      (/Users/lionel/Desktop/tidyr/revdep/checks.noindex/diffcyt/new/diffcyt.Rcheck/00_pkg_src/diffcyt/R/calcMediansByClusterMarker.R:123-126)
    calcMediansBySampleMarker: no visible binding for global variable
      ‘sample_id’
      (/Users/lionel/Desktop/tidyr/revdep/checks.noindex/diffcyt/new/diffcyt.Rcheck/00_pkg_src/diffcyt/R/calcMediansBySampleMarker.R:119-122)
    calcMediansBySampleMarker: no visible binding for global variable
      ‘marker’
      (/Users/lionel/Desktop/tidyr/revdep/checks.noindex/diffcyt/new/diffcyt.Rcheck/00_pkg_src/diffcyt/R/calcMediansBySampleMarker.R:119-122)
    calcMediansBySampleMarker: no visible binding for global variable
      ‘value’
      (/Users/lionel/Desktop/tidyr/revdep/checks.noindex/diffcyt/new/diffcyt.Rcheck/00_pkg_src/diffcyt/R/calcMediansBySampleMarker.R:119-122)
    Undefined global functions or variables:
      cluster_id marker sample_id value
    ```

# dimRed

Version: 0.1.0

## In both

*   checking examples ... ERROR
    ```
    Running examples in ‘dimRed-Ex.R’ failed
    The error most likely occurred in:
    
    > ### Name: nMDS-class
    > ### Title: Non-Metric Dimensional Scaling
    > ### Aliases: nMDS-class nMDS
    > 
    > ### ** Examples
    > 
    > dat <- loadDataSet("3D S Curve", n = 1000)
    > 
    > ## using the S4 classes:
    > nmds <- nMDS()
    > emb <- nmds@fun(dat, nmds@stdpars)
    Error in chckpkg("vegan") : 
      require 'vegan' package, install it using install.packages('vegan')
    Calls: <Anonymous> -> chckpkg
    Execution halted
    ```

*   checking tests ...
    ```
     ERROR
    Running the tests in ‘tests/testthat.R’ failed.
    Last 13 lines of output:
      sigma=0.001 kernel=rbfdot lambda=100 nblocks=4 ( 0.2445303 )
      sigma=0.01 kernel=rbfdot lambda=100 nblocks=4 ( 0.2446128 )
      sigma=0.1 kernel=rbfdot lambda=100 nblocks=4 ( 0.240947 )
      sigma=1 kernel=rbfdot lambda=100 nblocks=4 ( 0.2356961 )
      sigma=10 kernel=rbfdot lambda=100 nblocks=4 ( 0.2379904 )
      sigma=100 kernel=rbfdot lambda=100 nblocks=4 ( 0.2396507 )
      sigma=1000 kernel=rbfdot lambda=100 nblocks=4 ( 0.2405228 )
      sigma=10000 kernel=rbfdot lambda=100 nblocks=4 ( 0.2408275 )
      ══ testthat results  ═══════════════════════════════════════════════════════════
      OK: 112 SKIPPED: 0 FAILED: 2
      1. Error: high level functions working? (@test_all.R#18) 
      2. Error: check vs vegan isomap (@test_isomap.R#14) 
      
      Error: testthat unit tests failed
      Execution halted
    ```

*   checking package dependencies ... NOTE
    ```
    Package suggested but not available for checking: ‘vegan’
    ```

*   checking Rd cross-references ... NOTE
    ```
    Package unavailable to check Rd xrefs: ‘vegan’
    ```

# disto

Version: 0.2.0

## In both

*   checking dependencies in R code ... NOTE
    ```
    Namespaces in Imports field not imported from:
      ‘dplyr’ ‘proxy’
      All declared Imports should be used.
    ```

# DLMtool

Version: 5.2.3

## In both

*   checking package dependencies ... ERROR
    ```
    Package required but not available: ‘devtools’
    
    See section ‘The DESCRIPTION file’ in the ‘Writing R Extensions’
    manual.
    ```

# dlookr

Version: 0.3.2

## In both

*   checking installed package size ... NOTE
    ```
      installed size is  5.1Mb
      sub-directories of 1Mb or more:
        doc   4.2Mb
    ```

*   checking dependencies in R code ... NOTE
    ```
    Namespaces in Imports field not imported from:
      ‘dbplyr’ ‘randomForest’
      All declared Imports should be used.
    ```

# dplyrAssist

Version: 0.1.0

## In both

*   checking dependencies in R code ... NOTE
    ```
    Namespaces in Imports field not imported from:
      ‘tidyr’ ‘tidyverse’
      All declared Imports should be used.
    ```

# DSAIDE

Version: 0.7.0

## In both

*   checking re-building of vignette outputs ... WARNING
    ```
    Error in re-building vignettes:
      ...
    pandoc-citeproc: when expecting a product (:*:), encountered Object instead
    Error running filter /usr/local/bin/pandoc-citeproc:
    Filter returned error status 1
    Error: processing vignette 'DSAIDE.Rmd' failed with diagnostics:
    pandoc document conversion failed with error 83
    Execution halted
    ```

*   checking installed package size ... NOTE
    ```
      installed size is  5.4Mb
      sub-directories of 1Mb or more:
        media       2.2Mb
        shinyapps   2.6Mb
    ```

*   checking dependencies in R code ... NOTE
    ```
    Namespaces in Imports field not imported from:
      ‘knitr’ ‘rmarkdown’ ‘utils’
      All declared Imports should be used.
    ```

# DSAIRM

Version: 0.4.0

## In both

*   checking re-building of vignette outputs ... WARNING
    ```
    Error in re-building vignettes:
      ...
    Loading required package: shiny
    Welcome to the DSAIRM package. Type dsairmmenu() to get started.
    pandoc-citeproc: when expecting a product (:*:), encountered Object instead
    Error running filter /usr/local/bin/pandoc-citeproc:
    Filter returned error status 1
    Error: processing vignette 'DSAIRM.Rmd' failed with diagnostics:
    pandoc document conversion failed with error 83
    Execution halted
    ```

*   checking dependencies in R code ... NOTE
    ```
    Namespaces in Imports field not imported from:
      ‘knitr’ ‘rmarkdown’
      All declared Imports should be used.
    ```

# dynutils

Version: 1.0.0

## In both

*   checking package dependencies ... ERROR
    ```
    Package required but not available: ‘devtools’
    
    See section ‘The DESCRIPTION file’ in the ‘Writing R Extensions’
    manual.
    ```

# edgarWebR

Version: 1.0.0

## In both

*   checking package dependencies ... NOTE
    ```
    Package suggested but not available for checking: ‘devtools’
    ```

# eechidna

Version: 1.1

## In both

*   checking installed package size ... NOTE
    ```
      installed size is  6.6Mb
      sub-directories of 1Mb or more:
        data   5.1Mb
        doc    1.2Mb
    ```

# eemR

Version: 0.1.5

## In both

*   checking re-building of vignette outputs ... WARNING
    ```
    Error in re-building vignettes:
      ...
    
    Attaching package: 'dplyr'
    
    The following objects are masked from 'package:stats':
    
        filter, lag
    
    The following objects are masked from 'package:base':
    
        intersect, setdiff, setequal, union
    
    pandoc-citeproc: when expecting a product (:*:), encountered Object instead
    Error running filter /usr/local/bin/pandoc-citeproc:
    Filter returned error status 1
    Error: processing vignette 'introduction.Rmd' failed with diagnostics:
    pandoc document conversion failed with error 83
    Execution halted
    ```

# eesim

Version: 0.1.0

## In both

*   checking re-building of vignette outputs ... WARNING
    ```
    ...
    
        intersect, setdiff, setequal, union
    
    
    Attaching package: 'gridExtra'
    
    The following object is masked from 'package:dplyr':
    
        combine
    
    This is dlnm 2.3.6. For details: help(dlnm) and vignette('dlnmOverview').
    This function may take a minute or two to run, especially if you
    are creating lots of replications (`n_reps`).
    This function may take a minute or two to run, especially if you
    are creating lots of replications (`n_reps`).
    pandoc-citeproc: when expecting a product (:*:), encountered Object instead
    Error running filter /usr/local/bin/pandoc-citeproc:
    Filter returned error status 1
    Error: processing vignette 'eesim.Rmd' failed with diagnostics:
    pandoc document conversion failed with error 83
    Execution halted
    ```

# EFDR

Version: 0.1.1

## In both

*   checking R code for possible problems ... NOTE
    ```
    ...
      (/Users/lionel/Desktop/tidyr/revdep/checks.noindex/EFDR/new/EFDR.Rcheck/00_pkg_src/EFDR/R/EFDR_functions.R:686)
    .relist.dwt: no visible global function definition for ‘as’
      (/Users/lionel/Desktop/tidyr/revdep/checks.noindex/EFDR/new/EFDR.Rcheck/00_pkg_src/EFDR/R/EFDR_functions.R:686)
    .std.wav.coeff : <anonymous>: no visible global function definition for
      ‘mad’
      (/Users/lionel/Desktop/tidyr/revdep/checks.noindex/EFDR/new/EFDR.Rcheck/00_pkg_src/EFDR/R/EFDR_functions.R:698)
    regrid: no visible global function definition for ‘predict’
      (/Users/lionel/Desktop/tidyr/revdep/checks.noindex/EFDR/new/EFDR.Rcheck/00_pkg_src/EFDR/R/EFDR_functions.R:391-396)
    regrid: no visible global function definition for ‘var’
      (/Users/lionel/Desktop/tidyr/revdep/checks.noindex/EFDR/new/EFDR.Rcheck/00_pkg_src/EFDR/R/EFDR_functions.R:406)
    regrid: no visible global function definition for ‘medpolish’
      (/Users/lionel/Desktop/tidyr/revdep/checks.noindex/EFDR/new/EFDR.Rcheck/00_pkg_src/EFDR/R/EFDR_functions.R:427)
    Undefined global functions or variables:
      as mad medpolish pnorm predict relist rnorm var
    Consider adding
      importFrom("methods", "as")
      importFrom("stats", "mad", "medpolish", "pnorm", "predict", "rnorm",
                 "var")
      importFrom("utils", "relist")
    to your NAMESPACE file (and ensure that your DESCRIPTION Imports
    field contains 'methods').
    ```

# ENCODExplorer

Version: 2.6.0

## In both

*   checking installed package size ... NOTE
    ```
      installed size is 74.0Mb
      sub-directories of 1Mb or more:
        data     24.1Mb
        doc       1.5Mb
        extdata  48.0Mb
    ```

*   checking R code for possible problems ... NOTE
    ```
    ...
    step6_target: no visible binding for global variable ‘target’
      (/Users/lionel/Desktop/tidyr/revdep/checks.noindex/ENCODExplorer/new/ENCODExplorer.Rcheck/00_pkg_src/ENCODExplorer/R/prepare_data.R:354-355)
    step7: no visible binding for global variable ‘organism’
      (/Users/lionel/Desktop/tidyr/revdep/checks.noindex/ENCODExplorer/new/ENCODExplorer.Rcheck/00_pkg_src/ENCODExplorer/R/prepare_data.R:424-425)
    step8: no visible binding for global variable ‘investigated_as’
      (/Users/lionel/Desktop/tidyr/revdep/checks.noindex/ENCODExplorer/new/ENCODExplorer.Rcheck/00_pkg_src/ENCODExplorer/R/prepare_data.R:436-437)
    step8: no visible binding for global variable ‘target’
      (/Users/lionel/Desktop/tidyr/revdep/checks.noindex/ENCODExplorer/new/ENCODExplorer.Rcheck/00_pkg_src/ENCODExplorer/R/prepare_data.R:439-440)
    step9: no visible binding for global variable ‘organism’
      (/Users/lionel/Desktop/tidyr/revdep/checks.noindex/ENCODExplorer/new/ENCODExplorer.Rcheck/00_pkg_src/ENCODExplorer/R/prepare_data.R:449-450)
    Undefined global functions or variables:
      . Experiment Value accession antibody_caption
      antibody_characterization antibody_target assay
      biological_replicate_number biosample_name biosample_type col_name
      controls data date_released download.file encode_df file_accession
      file_format href investigated_as lab nucleic_acid_term organism
      platform project replicate_antibody replicate_library server status
      submitted_by target technical_replicate_number treatment ui value
    Consider adding
      importFrom("utils", "data", "download.file")
    to your NAMESPACE file.
    ```

*   checking data for non-ASCII characters ... NOTE
    ```
      Note: found 771 marked UTF-8 strings
    ```

# epiphy

Version: 0.3.4

## In both

*   checking re-building of vignette outputs ... WARNING
    ```
    Error in re-building vignettes:
      ...
    pandoc-citeproc: when expecting a product (:*:), encountered Object instead
    Error running filter /usr/local/bin/pandoc-citeproc:
    Filter returned error status 1
    Error: processing vignette 'defs-and-eqns.Rmd' failed with diagnostics:
    pandoc document conversion failed with error 83
    Execution halted
    ```

*   checking package dependencies ... NOTE
    ```
    Package suggested but not available for checking: ‘vegan’
    ```

*   checking Rd cross-references ... NOTE
    ```
    Package unavailable to check Rd xrefs: ‘vegan’
    ```

# epitable

Version: 0.1.2

## In both

*   checking dependencies in R code ... NOTE
    ```
    Namespaces in Imports field not imported from:
      ‘magrittr’ ‘readr’
      All declared Imports should be used.
    ```

# epos

Version: 0.1.0

## In both

*   checking dependencies in R code ... NOTE
    ```
    Namespaces in Imports field not imported from:
      ‘dplyr’ ‘testthat’ ‘tidyr’
      All declared Imports should be used.
    ```

# eurostat

Version: 3.2.9

## In both

*   checking data for non-ASCII characters ... NOTE
    ```
      Note: found 596 marked UTF-8 strings
    ```

# ExPanDaR

Version: 0.3.0

## In both

*   checking package dependencies ... NOTE
    ```
    Package suggested but not available for checking: ‘devtools’
    ```

# eyetrackingR

Version: 0.1.7

## In both

*   checking re-building of vignette outputs ... WARNING
    ```
    ...
      ...
    Warning: Removed 37 rows containing non-finite values (stat_summary).
    Warning: Removed 37 rows containing non-finite values (stat_summary).
    Warning: Removed 37 rows containing non-finite values (stat_summary).
    Warning: Removed 37 rows containing non-finite values (stat_summary).
    Warning: Removed 37 rows containing non-finite values (stat_summary).
    Warning: Removed 37 rows containing non-finite values (stat_summary).
    Warning: Removed 37 rows containing non-finite values (stat_summary).
    Warning: Removed 37 rows containing non-finite values (stat_summary).
    Warning in make_onset_data(response_window_clean, onset_time = 15500, fixation_window_length = 1,  :
      Very few trials have a legitimate first AOI! Possible incorrect onset time?
    Warning in max(SwitchAOI) :
      no non-missing arguments to max; returning -Inf
    Warning in min(SwitchAOI) :
      no non-missing arguments to min; returning Inf
    Warning in max(df_plot$.Time) :
      no non-missing arguments to max; returning -Inf
    Quitting from lines 91-93 (onset_contingent_analysis_vignette.Rmd) 
    Error: processing vignette 'onset_contingent_analysis_vignette.Rmd' failed with diagnostics:
    replacement has 1 row, data has 0
    Execution halted
    ```

# factoextra

Version: 1.0.5

## In both

*   checking Rd cross-references ... NOTE
    ```
    Package unavailable to check Rd xrefs: ‘NbClust’
    ```

# fastR2

Version: 1.2.1

## In both

*   checking installed package size ... NOTE
    ```
      installed size is  5.0Mb
      sub-directories of 1Mb or more:
        snippet   3.7Mb
    ```

# fingertipscharts

Version: 0.0.2

## In both

*   R CMD check timed out
    

*   checking dependencies in R code ... NOTE
    ```
    Namespace in Imports field not imported from: ‘mapproj’
      All declared Imports should be used.
    ```

# fold

Version: 0.2.6

## In both

*   checking examples ... ERROR
    ```
    Running examples in ‘fold-Ex.R’ failed
    The error most likely occurred in:
    
    > ### Name: boxplot.folded
    > ### Title: Boxplot Method for Folded
    > ### Aliases: boxplot.folded
    > 
    > ### ** Examples
    > 
    > data(eventsf)
    > boxplot(eventsf, SEX, WT, ref = 68)
    Error in get(fun, mode = "function", envir = parent.frame()) : 
      object 'boxplot_panel' of mode 'function' was not found
    Calls: boxplot ... <Anonymous> -> bwplot.formula -> %in% -> formals -> get
    Execution halted
    ```

# futureheatwaves

Version: 1.0.3

## In both

*   checking re-building of vignette outputs ... WARNING
    ```
    Error in re-building vignettes:
      ...
    pandoc-citeproc: when expecting a product (:*:), encountered Object instead
    Error running filter /usr/local/bin/pandoc-citeproc:
    Filter returned error status 1
    Error: processing vignette 'futureheatwaves.Rmd' failed with diagnostics:
    pandoc document conversion failed with error 83
    Execution halted
    ```

# GA4GHshiny

Version: 1.2.0

## In both

*   checking tests ...
    ```
     ERROR
    Running the tests in ‘tests/testthat.R’ failed.
    Last 13 lines of output:
      2: stop(txt, domain = NA)
      
      ══ testthat results  ═══════════════════════════════════════════════════════════
      OK: 2 SKIPPED: 0 FAILED: 8
      1. Error: app works (@test-app.R#5) 
      2. Error: getGene works (@test-getGene.R#4) 
      3. Error: getGeneSymbols works (@test-getGeneSymbols.R#4) 
      4. Error: initializeReferences works (@test-initializeReferences.R#6) 
      5. Error: initializeVariantSet works (@test-initializeVariantSet.R#6) 
      6. Error: (unknown) (@test-searchVariantsByGeneSymbol.R#3) 
      7. Error: tidyVariants works with searchVariants output (@test-tidyVariants.R#6) 
      8. Error: tidyVariants works with searchVariantsByGeneSymbol output (@test-tidyVariants.R#16) 
      
      Error: testthat unit tests failed
      Execution halted
    ```

*   checking re-building of vignette outputs ... WARNING
    ```
    Error in re-building vignettes:
      ...
    pandoc-citeproc: when expecting a product (:*:), encountered Object instead
    Error running filter /usr/local/bin/pandoc-citeproc:
    Filter returned error status 1
    Error: processing vignette 'GA4GHshiny.Rmd' failed with diagnostics:
    pandoc document conversion failed with error 83
    Execution halted
    ```

*   checking package dependencies ... NOTE
    ```
    Packages suggested but not available for checking:
      ‘org.Hs.eg.db’ ‘TxDb.Hsapiens.UCSC.hg19.knownGene’
    ```

*   checking for hidden files and directories ... NOTE
    ```
    Found the following hidden files and directories:
      .travis.yml
    These were most likely included in error. See section ‘Package
    structure’ in the ‘Writing R Extensions’ manual.
    ```

# gaiah

Version: 0.0.2

## In both

*   checking dependencies in R code ... NOTE
    ```
    Namespaces in Imports field not imported from:
      ‘ggplot2’ ‘maptools’ ‘rgeos’ ‘stringr’ ‘tidyr’
      All declared Imports should be used.
    ```

# GEOquery

Version: 2.48.0

## In both

*   R CMD check timed out
    

*   checking installed package size ... NOTE
    ```
      installed size is 13.9Mb
      sub-directories of 1Mb or more:
        extdata  12.8Mb
    ```

*   checking whether the namespace can be loaded with stated dependencies ... NOTE
    ```
    Warning: no function found corresponding to methods exports from ‘GEOquery’ for: ‘show’
    
    A namespace must be able to be loaded with just the base namespace
    loaded: otherwise if the namespace gets loaded by a saved object,
    the session will be unable to start.
    
    Probably some imports need to be declared in the NAMESPACE file.
    ```

*   checking dependencies in R code ... NOTE
    ```
    Namespace in Imports field not imported from: ‘httr’
      All declared Imports should be used.
    Package in Depends field not imported from: ‘methods’
      These packages need to be imported from (in the NAMESPACE file)
      for when this namespace is loaded but not attached.
    ```

*   checking R code for possible problems ... NOTE
    ```
    ...
      (/Users/lionel/Desktop/tidyr/revdep/checks.noindex/GEOquery/new/GEOquery.Rcheck/00_pkg_src/GEOquery/R/parseGEO.R:531-539)
    parseGSEMatrix: no visible binding for global variable ‘accession’
      (/Users/lionel/Desktop/tidyr/revdep/checks.noindex/GEOquery/new/GEOquery.Rcheck/00_pkg_src/GEOquery/R/parseGEO.R:531-539)
    parseGSEMatrix: no visible binding for global variable ‘accession’
      (/Users/lionel/Desktop/tidyr/revdep/checks.noindex/GEOquery/new/GEOquery.Rcheck/00_pkg_src/GEOquery/R/parseGEO.R:541-542)
    parseGSEMatrix: no visible global function definition for ‘new’
      (/Users/lionel/Desktop/tidyr/revdep/checks.noindex/GEOquery/new/GEOquery.Rcheck/00_pkg_src/GEOquery/R/parseGEO.R:568)
    parseGSEMatrix: no visible global function definition for ‘new’
      (/Users/lionel/Desktop/tidyr/revdep/checks.noindex/GEOquery/new/GEOquery.Rcheck/00_pkg_src/GEOquery/R/parseGEO.R:590)
    parseGSEMatrix: no visible global function definition for ‘new’
      (/Users/lionel/Desktop/tidyr/revdep/checks.noindex/GEOquery/new/GEOquery.Rcheck/00_pkg_src/GEOquery/R/parseGEO.R:606-610)
    parseGSEMatrix: no visible global function definition for ‘as’
      (/Users/lionel/Desktop/tidyr/revdep/checks.noindex/GEOquery/new/GEOquery.Rcheck/00_pkg_src/GEOquery/R/parseGEO.R:606-610)
    Undefined global functions or variables:
      . MA accession as characteristics k kvpair new read.delim read.table
      v
    Consider adding
      importFrom("methods", "as", "new")
      importFrom("utils", "read.delim", "read.table")
    to your NAMESPACE file (and ensure that your DESCRIPTION Imports
    field contains 'methods').
    ```

# GerminaR

Version: 1.2

## In both

*   checking dependencies in R code ... NOTE
    ```
    Namespaces in Imports field not imported from:
      ‘DT’ ‘shinydashboard’
      All declared Imports should be used.
    ```

# getTBinR

Version: 0.5.5

## In both

*   checking tests ...
    ```
     ERROR
    Running the tests in ‘tests/testthat.R’ failed.
    Last 13 lines of output:
      > library(getTBinR)
      > 
      > test_check("getTBinR")
      ── 1. Failure: map_tb_burden can have a custom legend specified. (@test-map_tb_b
      plot$labels$fill not equal to `test_label`.
      1/1 mismatches
      x[1]: "`test (test - test)`"
      y[1]: "test (test - test)"
      
      ══ testthat results  ═══════════════════════════════════════════════════════════
      OK: 75 SKIPPED: 29 FAILED: 1
      1. Failure: map_tb_burden can have a custom legend specified. (@test-map_tb_burden.R#62) 
      
      Error: testthat unit tests failed
      Execution halted
    ```

*   checking package dependencies ... NOTE
    ```
    Package suggested but not available for checking: ‘devtools’
    ```

# gfer

Version: 0.1.10

## In both

*   checking dependencies in R code ... NOTE
    ```
    Namespace in Imports field not imported from: ‘tidyr’
      All declared Imports should be used.
    ```

# ggedit

Version: 0.3.0

## In both

*   checking dependencies in R code ... NOTE
    ```
    Namespace in Imports field not imported from: ‘magrittr’
      All declared Imports should be used.
    ```

# ggeffects

Version: 0.6.0

## In both

*   checking Rd cross-references ... NOTE
    ```
    Package unavailable to check Rd xrefs: ‘ordinal’
    ```

# ggfan

Version: 0.1.2

## In both

*   checking dependencies in R code ... NOTE
    ```
    Namespaces in Imports field not imported from:
      ‘colorspace’ ‘grid’ ‘rstan’
      All declared Imports should be used.
    ```

# ggformula

Version: 0.9.0

## In both

*   checking installed package size ... NOTE
    ```
      installed size is  7.0Mb
      sub-directories of 1Mb or more:
        R     3.1Mb
        doc   2.7Mb
    ```

*   checking dependencies in R code ... NOTE
    ```
    Namespace in Imports field not imported from: ‘tidyr’
      All declared Imports should be used.
    ```

*   checking Rd cross-references ... NOTE
    ```
    Package unavailable to check Rd xrefs: ‘quantreg’
    ```

# ggfortify

Version: 0.4.5

## In both

*   checking installed package size ... NOTE
    ```
      installed size is  5.8Mb
      sub-directories of 1Mb or more:
        R     2.0Mb
        doc   3.5Mb
    ```

# ggiraphExtra

Version: 0.2.9

## In both

*   checking dependencies in R code ... NOTE
    ```
    Namespaces in Imports field not imported from:
      ‘ggforce’ ‘webshot’ ‘ztable’
      All declared Imports should be used.
    ```

# ggmcmc

Version: 1.1

## In both

*   checking re-building of vignette outputs ... WARNING
    ```
    ...
      no font could be found for family "Source Sans Pro"
    Warning in grid.Call.graphics(C_text, as.graphicsAnnot(x$label), x$x, x$y,  :
      no font could be found for family "Source Sans Pro"
    Warning in grid.Call.graphics(C_text, as.graphicsAnnot(x$label), x$x, x$y,  :
      no font could be found for family "Source Sans Pro"
    Warning in grid.Call.graphics(C_text, as.graphicsAnnot(x$label), x$x, x$y,  :
      no font could be found for family "Source Sans Pro"
    Warning in grid.Call.graphics(C_text, as.graphicsAnnot(x$label), x$x, x$y,  :
      no font could be found for family "Source Sans Pro"
    Warning in grid.Call.graphics(C_text, as.graphicsAnnot(x$label), x$x, x$y,  :
      no font could be found for family "Source Sans Pro"
    Warning in grid.Call.graphics(C_text, as.graphicsAnnot(x$label), x$x, x$y,  :
      no font could be found for family "Source Sans Pro"
    Warning in grid.Call.graphics(C_text, as.graphicsAnnot(x$label), x$x, x$y,  :
      no font could be found for family "Source Sans Pro"
    Warning in grid.Call(C_textBounds, as.graphicsAnnot(x$label), x$x, x$y,  :
      no font could be found for family "Source Sans Pro"
    Quitting from lines 142-143 (using_ggmcmc.Rmd) 
    Error: processing vignette 'using_ggmcmc.Rmd' failed with diagnostics:
    polygon edge not found
    Execution halted
    ```

# ggpubr

Version: 0.1.8

## In both

*   checking Rd cross-references ... NOTE
    ```
    Package unavailable to check Rd xrefs: ‘FactoMineR’
    ```

# ggquickeda

Version: 0.1.1

## In both

*   checking dependencies in R code ... NOTE
    ```
    Namespaces in Imports field not imported from:
      ‘DT’ ‘Formula’ ‘Hmisc’ ‘colourpicker’ ‘dplyr’ ‘ggpmisc’ ‘ggrepel’
      ‘grDevices’ ‘gridExtra’ ‘lazyeval’ ‘markdown’ ‘plotly’ ‘quantreg’
      ‘rlang’ ‘shinyjs’ ‘table1’ ‘tidyr’
      All declared Imports should be used.
    ```

# ggRandomForests

Version: 2.0.1

## In both

*   checking dependencies in R code ... NOTE
    ```
    Namespace in Imports field not imported from: ‘randomForest’
      All declared Imports should be used.
    ```

# ggspatial

Version: 1.0.1

## In both

*   checking examples ... ERROR
    ```
    ...
    > ggplot() +
    + 
    +   # annotation_spatial() layers don't train the scales, so data stays central
    +   annotation_spatial(longlake_roadsdf, size = 2, col = "black") +
    +   annotation_spatial(longlake_roadsdf, size = 1.6, col = "white") +
    + 
    +   # raster layers train scales and get projected automatically
    +   layer_spatial(longlake_depth_raster, aes(alpha = stat(band1)), fill = "darkblue") +
    +   scale_alpha_continuous(na.value = 0) +
    + 
    +   # layer_spatial() layers train the scales
    +   layer_spatial(longlake_depthdf, aes(col = DEPTH.M)) +
    + 
    +   # spatial-aware automagic scale bar
    +   annotation_scale(location = "tl") +
    + 
    +   # spatial-aware automagic north arrow
    +   annotation_north_arrow(location = "br", which_north = "true")
    Error in FUN(X[[i]], ...) : object 'DEPTH.M' not found
    Calls: <Anonymous> ... <Anonymous> -> f -> scales_add_defaults -> lapply -> FUN
    Execution halted
    ```

*   checking tests ...
    ```
     ERROR
    Running the tests in ‘tests/testthat.R’ failed.
    Last 13 lines of output:
      8: f(..., self = self) at /private/var/folders/b9/1vbq6rn93_1fk71sn95dqb8r0000gn/T/RtmpTJTl2s/R.INSTALLc36766c2b064/ggplot2/R/ggproto.r:177
      9: scales_add_defaults(plot$scales, data, aesthetics, plot$plot_env) at /private/var/folders/b9/1vbq6rn93_1fk71sn95dqb8r0000gn/T/RtmpTJTl2s/R.INSTALLc36766c2b064/ggplot2/R/layer.r:218
      10: lapply(aesthetics[new_aesthetics], rlang::eval_tidy, data = data) at /private/var/folders/b9/1vbq6rn93_1fk71sn95dqb8r0000gn/T/RtmpTJTl2s/R.INSTALLc36766c2b064/ggplot2/R/scales-.r:99
      11: FUN(X[[i]], ...)
      
      ══ testthat results  ═══════════════════════════════════════════════════════════
      OK: 112 SKIPPED: 0 FAILED: 5
      1. Error: deprecated tests run without error (@test-deprecated.R#23) 
      2. Error: old stat project works (@test-deprecated.R#109) 
      3. Error: deprecated OSM tiles work (@test-deprecated.R#147) 
      4. Error: geom_spatial_* geoms work properly (@test-geom_spatial.R#26) 
      5. Error: layer_spatial() works as intended (@test-layer-spatial.R#6) 
      
      Error: testthat unit tests failed
      Execution halted
    ```

*   checking re-building of vignette outputs ... WARNING
    ```
    Error in re-building vignettes:
      ...
    Quitting from lines 36-39 (ggspatial.Rmd) 
    Error: processing vignette 'ggspatial.Rmd' failed with diagnostics:
    object 'DEPTH.M' not found
    Execution halted
    ```

*   checking dependencies in R code ... NOTE
    ```
    Namespace in Imports field not imported from: ‘tidyr’
      All declared Imports should be used.
    ```

# ggstatsplot

Version: 0.0.6

## In both

*   checking re-building of vignette outputs ... WARNING
    ```
    ...
    The following objects are masked from 'package:base':
    
        intersect, setdiff, setequal, union
    
    -------------------------------------------------------------------------
    You have loaded plyr after dplyr - this is likely to cause problems.
    If you need functions from both plyr and dplyr, please load plyr first, then dplyr:
    library(plyr); library(dplyr)
    -------------------------------------------------------------------------
    
    Attaching package: 'plyr'
    
    The following objects are masked from 'package:dplyr':
    
        arrange, count, desc, failwith, id, mutate, rename, summarise,
        summarize
    
    Quitting from lines 231-233 (combine_plots.Rmd) 
    Error: processing vignette 'combine_plots.Rmd' failed with diagnostics:
    there is no package called 'devtools'
    Execution halted
    ```

*   checking package dependencies ... NOTE
    ```
    Package suggested but not available for checking: ‘devtools’
    ```

*   checking installed package size ... NOTE
    ```
      installed size is  5.4Mb
      sub-directories of 1Mb or more:
        doc    2.6Mb
        help   2.3Mb
    ```

# ggthemes

Version: 4.0.1

## In both

*   checking data for non-ASCII characters ... NOTE
    ```
      Note: found 138 marked UTF-8 strings
    ```

# ggtree

Version: 1.12.7

## In both

*   checking re-building of vignette outputs ... WARNING
    ```
    Error in re-building vignettes:
      ...
    pandoc-citeproc: when expecting a product (:*:), encountered Object instead
    Error running filter /usr/local/bin/pandoc-citeproc:
    Filter returned error status 1
    Error: processing vignette 'ggtree.Rmd' failed with diagnostics:
    pandoc document conversion failed with error 83
    Execution halted
    ```

*   checking installed package size ... NOTE
    ```
      installed size is 10.9Mb
      sub-directories of 1Mb or more:
        R          2.0Mb
        doc        4.9Mb
        examples   3.7Mb
    ```

# ggwordcloud

Version: 0.3.0

## In both

*   checking data for non-ASCII characters ... NOTE
    ```
      Note: found 102 marked UTF-8 strings
    ```

# googlesheets

Version: 0.3.0

## In both

*   checking dependencies in R code ... NOTE
    ```
    Namespace in Imports field not imported from: ‘tibble’
      All declared Imports should be used.
    ```

# graphTweets

Version: 0.5.0

## In both

*   checking dependencies in R code ... NOTE
    ```
    Namespace in Imports field not imported from: ‘utils’
      All declared Imports should be used.
    ```

# gravity

Version: 0.8.5

## In both

*   checking re-building of vignette outputs ... WARNING
    ```
    Error in re-building vignettes:
      ...
    pandoc-citeproc: when expecting a product (:*:), encountered Object instead
    Error running filter /usr/local/bin/pandoc-citeproc:
    Filter returned error status 1
    Error: processing vignette 'creating-gravity-datasets.Rmd' failed with diagnostics:
    pandoc document conversion failed with error 83
    Execution halted
    ```

# gutenbergr

Version: 0.1.4

## In both

*   checking data for non-ASCII characters ... NOTE
    ```
      Note: found 13617 marked UTF-8 strings
    ```

# hdme

Version: 0.2.1

## In both

*   checking re-building of vignette outputs ... WARNING
    ```
    ...
        expand
    
    The following object is masked from 'package:igraph':
    
        crossing
    
    Loading required package: lattice
    Loading required package: MASS
    
    Attaching package: 'MASS'
    
    The following object is masked from 'package:dplyr':
    
        select
    
    pandoc-citeproc: when expecting a product (:*:), encountered Object instead
    Error running filter /usr/local/bin/pandoc-citeproc:
    Filter returned error status 1
    Error: processing vignette 'hdme-package.Rmd' failed with diagnostics:
    pandoc document conversion failed with error 83
    Execution halted
    ```

# highcharter

Version: 0.5.0

## In both

*   checking installed package size ... NOTE
    ```
      installed size is 16.9Mb
      sub-directories of 1Mb or more:
        doc          13.7Mb
        htmlwidgets   1.8Mb
    ```

# HTSSIP

Version: 1.4.0

## In both

*   checking package dependencies ... ERROR
    ```
    Package required but not available: ‘vegan’
    
    See section ‘The DESCRIPTION file’ in the ‘Writing R Extensions’
    manual.
    ```

# HURDAT

Version: 0.2.0

## In both

*   checking package dependencies ... NOTE
    ```
    Package suggested but not available for checking: ‘devtools’
    ```

# hurricaneexposure

Version: 0.0.1

## In both

*   checking package dependencies ... NOTE
    ```
    Package suggested but not available for checking: ‘hurricaneexposuredata’
    ```

# iadf

Version: 0.1.0

## In both

*   checking re-building of vignette outputs ... WARNING
    ```
    Error in re-building vignettes:
      ...
    pandoc-citeproc: when expecting a product (:*:), encountered Object instead
    Error running filter /usr/local/bin/pandoc-citeproc:
    Filter returned error status 1
    Error: processing vignette 'falsering-proportion.Rmd' failed with diagnostics:
    pandoc document conversion failed with error 83
    Execution halted
    ```

# iCNV

Version: 1.0.0

## In both

*   checking whether package ‘iCNV’ can be installed ... ERROR
    ```
    Installation failed.
    See ‘/Users/lionel/Desktop/tidyr/revdep/checks.noindex/iCNV/new/iCNV.Rcheck/00install.out’ for details.
    ```

## Installation

### Devel

```
* installing *source* package ‘iCNV’ ...
** R
** data
*** moving datasets to lazyload DB
** inst
** byte-compile and prepare package for lazy loading
Error : package ‘BSgenome.Hsapiens.UCSC.hg19’ required by ‘CODEX’ could not be found
ERROR: lazy loading failed for package ‘iCNV’
* removing ‘/Users/lionel/Desktop/tidyr/revdep/checks.noindex/iCNV/new/iCNV.Rcheck/iCNV’

```
### CRAN

```
* installing *source* package ‘iCNV’ ...
** R
** data
*** moving datasets to lazyload DB
** inst
** byte-compile and prepare package for lazy loading
Error : package ‘BSgenome.Hsapiens.UCSC.hg19’ required by ‘CODEX’ could not be found
ERROR: lazy loading failed for package ‘iCNV’
* removing ‘/Users/lionel/Desktop/tidyr/revdep/checks.noindex/iCNV/old/iCNV.Rcheck/iCNV’

```
# idealstan

Version: 0.2.7

## In both

*   checking installed package size ... NOTE
    ```
      installed size is  8.4Mb
      sub-directories of 1Mb or more:
        data   3.5Mb
        libs   3.6Mb
    ```

# IHWpaper

Version: 1.7.0

## In both

*   checking tests ...
    ```
     ERROR
    Running the tests in ‘tests/testthat.R’ failed.
    Last 13 lines of output:
      [1] "LSL GBH"
      [1] "TST GBH"
      [1] "SBH"
      [1] "Clfdr"
      [1] "Greedy Indep. Filt."
      [1] "IHW"
      [1] "IHW-Bonferroni E3"
      [1] "Bonferroni"
      [1] "qvalue"
      ══ testthat results  ═══════════════════════════════════════════════════════════
      OK: 1 SKIPPED: 0 FAILED: 1
      1. Error: (unknown) (@test_analyze_datasets.R#4) 
      
      Error: testthat unit tests failed
      Execution halted
    ```

*   checking re-building of vignette outputs ... WARNING
    ```
    Error in re-building vignettes:
      ...
    Quitting from lines 29-65 (BH-explanation.Rmd) 
    Error: processing vignette 'BH-explanation.Rmd' failed with diagnostics:
    Palette not found.
    Execution halted
    ```

*   checking package dependencies ... NOTE
    ```
    Package suggested but not available for checking: ‘airway’
    ```

*   checking installed package size ... NOTE
    ```
      installed size is 24.0Mb
      sub-directories of 1Mb or more:
        doc      13.1Mb
        extdata   9.8Mb
    ```

*   checking R code for possible problems ... NOTE
    ```
    scott_fdrreg: no visible global function definition for ‘FDRreg’
      (/Users/lionel/Desktop/tidyr/revdep/checks.noindex/IHWpaper/new/IHWpaper.Rcheck/00_pkg_src/IHWpaper/R/covariate_methods.R:88)
    scott_fdrreg: no visible global function definition for ‘getFDR’
      (/Users/lionel/Desktop/tidyr/revdep/checks.noindex/IHWpaper/new/IHWpaper.Rcheck/00_pkg_src/IHWpaper/R/covariate_methods.R:97)
    sim_fun_eval: no visible binding for global variable ‘fdr_method’
      (/Users/lionel/Desktop/tidyr/revdep/checks.noindex/IHWpaper/new/IHWpaper.Rcheck/00_pkg_src/IHWpaper/R/benchmarking.R:61-63)
    sim_fun_eval: no visible binding for global variable ‘fdr_pars’
      (/Users/lionel/Desktop/tidyr/revdep/checks.noindex/IHWpaper/new/IHWpaper.Rcheck/00_pkg_src/IHWpaper/R/benchmarking.R:61-63)
    sim_fun_eval: no visible binding for global variable ‘FDP’
      (/Users/lionel/Desktop/tidyr/revdep/checks.noindex/IHWpaper/new/IHWpaper.Rcheck/00_pkg_src/IHWpaper/R/benchmarking.R:61-63)
    sim_fun_eval: no visible binding for global variable ‘rj_ratio’
      (/Users/lionel/Desktop/tidyr/revdep/checks.noindex/IHWpaper/new/IHWpaper.Rcheck/00_pkg_src/IHWpaper/R/benchmarking.R:61-63)
    sim_fun_eval: no visible binding for global variable ‘FPR’
      (/Users/lionel/Desktop/tidyr/revdep/checks.noindex/IHWpaper/new/IHWpaper.Rcheck/00_pkg_src/IHWpaper/R/benchmarking.R:61-63)
    sim_fun_eval: no visible binding for global variable ‘FWER’
      (/Users/lionel/Desktop/tidyr/revdep/checks.noindex/IHWpaper/new/IHWpaper.Rcheck/00_pkg_src/IHWpaper/R/benchmarking.R:61-63)
    Undefined global functions or variables:
      FDP FDRreg FPR FWER fdr_method fdr_pars getFDR rj_ratio
    ```

# INDperform

Version: 0.1.1

## In both

*   checking package dependencies ... ERROR
    ```
    Package required but not available: ‘vegan’
    
    See section ‘The DESCRIPTION file’ in the ‘Writing R Extensions’
    manual.
    ```

# IONiseR

Version: 2.4.0

## In both

*   checking re-building of vignette outputs ... WARNING
    ```
    ...
    
    
    Attaching package: 'GenomicAlignments'
    
    The following object is masked from 'package:dplyr':
    
        last
    
    
    Attaching package: 'ShortRead'
    
    The following object is masked from 'package:dplyr':
    
        id
    
    pandoc-citeproc: when expecting a product (:*:), encountered Object instead
    Error running filter /usr/local/bin/pandoc-citeproc:
    Filter returned error status 1
    Error: processing vignette 'IONiseR.Rmd' failed with diagnostics:
    pandoc document conversion failed with error 83
    Execution halted
    ```

*   checking installed package size ... NOTE
    ```
      installed size is  5.8Mb
      sub-directories of 1Mb or more:
        doc       3.7Mb
        extdata   1.5Mb
    ```

*   checking R code for possible problems ... NOTE
    ```
    ...
      ‘idx’
      (/Users/lionel/Desktop/tidyr/revdep/checks.noindex/IONiseR/new/IONiseR.Rcheck/00_pkg_src/IONiseR/R/Methods-subsetting.R:19-21)
    [,Fast5Summary-ANY-ANY-ANY: no visible binding for global variable
      ‘component’
      (/Users/lionel/Desktop/tidyr/revdep/checks.noindex/IONiseR/new/IONiseR.Rcheck/00_pkg_src/IONiseR/R/Methods-subsetting.R:24-26)
    [,Fast5Summary-ANY-ANY-ANY: no visible binding for global variable
      ‘idx’
      (/Users/lionel/Desktop/tidyr/revdep/checks.noindex/IONiseR/new/IONiseR.Rcheck/00_pkg_src/IONiseR/R/Methods-subsetting.R:24-26)
    show,Fast5Summary: no visible binding for global variable ‘full_2D’
      (/Users/lionel/Desktop/tidyr/revdep/checks.noindex/IONiseR/new/IONiseR.Rcheck/00_pkg_src/IONiseR/R/classes.R:70-71)
    show,Fast5Summary: no visible binding for global variable ‘pass’
      (/Users/lionel/Desktop/tidyr/revdep/checks.noindex/IONiseR/new/IONiseR.Rcheck/00_pkg_src/IONiseR/R/classes.R:75)
    show,Fast5Summary: no visible binding for global variable ‘pass’
      (/Users/lionel/Desktop/tidyr/revdep/checks.noindex/IONiseR/new/IONiseR.Rcheck/00_pkg_src/IONiseR/R/classes.R:77)
    Undefined global functions or variables:
      := AAAAA TTTTT accumulation baseCalledComplement baseCalledTemplate
      bases_called category channel circleFun component duration error freq
      full_2D group hour idx matrixCol matrixRow meanZValue mean_value
      median_signal minute mux name nbases new_reads num_events oddEven
      pass pentamer rbindlist readIDs seq_length start_time time_bin
      time_group x y zvalue
    ```

# ipumsr

Version: 0.3.0

## In both

*   checking dependencies in R code ... NOTE
    ```
    Namespace in Imports field not imported from: ‘R6’
      All declared Imports should be used.
    ```

# isomiRs

Version: 1.8.0

## In both

*   checking package dependencies ... ERROR
    ```
    Package required but not available: ‘targetscan.Hs.eg.db’
    
    Package suggested but not available for checking: ‘org.Mm.eg.db’
    
    See section ‘The DESCRIPTION file’ in the ‘Writing R Extensions’
    manual.
    ```

# jpndistrict

Version: 0.3.2

## In both

*   checking data for non-ASCII characters ... NOTE
    ```
      Note: found 502 marked UTF-8 strings
    ```

# konfound

Version: 0.1.0

## In both

*   checking re-building of vignette outputs ... WARNING
    ```
    Error in re-building vignettes:
      ...
    Quitting from lines 42-43 (Introduction_to_konfound.Rmd) 
    Error: processing vignette 'Introduction_to_konfound.Rmd' failed with diagnostics:
    there is no package called 'devtools'
    Execution halted
    ```

*   checking package dependencies ... NOTE
    ```
    Package suggested but not available for checking: ‘devtools’
    ```

# Lahman

Version: 6.0-0

## In both

*   checking installed package size ... NOTE
    ```
      installed size is  7.6Mb
      sub-directories of 1Mb or more:
        data   7.4Mb
    ```

# linguisticsdown

Version: 1.0.1

## In both

*   checking dependencies in R code ... NOTE
    ```
    Namespaces in Imports field not imported from:
      ‘dplyr’ ‘tidyr’
      All declared Imports should be used.
    ```

# mafs

Version: 0.0.3

## In both

*   checking dependencies in R code ... NOTE
    ```
    Namespaces in Imports field not imported from:
      ‘Rcpp’ ‘cmprsk’ ‘colorspace’ ‘etm’ ‘fracdiff’ ‘gtable’ ‘munsell’
      ‘numDeriv’ ‘plyr’ ‘quadprog’ ‘scales’ ‘timeDate’ ‘tseries’ ‘zoo’
      All declared Imports should be used.
    ```

# malariaAtlas

Version: 0.0.2

## In both

*   checking dependencies in R code ... NOTE
    ```
    Namespace in Imports field not imported from: ‘grid’
      All declared Imports should be used.
    ```

# MANOVA.RM

Version: 0.3.1

## In both

*   checking package dependencies ... NOTE
    ```
    Package suggested but not available for checking: ‘RGtk2’
    ```

*   checking Rd cross-references ... NOTE
    ```
    Package unavailable to check Rd xrefs: ‘nparLD’
    ```

# mason

Version: 0.2.6

## In both

*   checking Rd cross-references ... NOTE
    ```
    Packages unavailable to check Rd xrefs: ‘ggplot2’, ‘pander’, ‘pixiedust’
    ```

# mem

Version: 2.13

## In both

*   checking package dependencies ... ERROR
    ```
    Package required but not available: ‘sm’
    
    See section ‘The DESCRIPTION file’ in the ‘Writing R Extensions’
    manual.
    ```

# memapp

Version: 2.10

## In both

*   checking dependencies in R code ... NOTE
    ```
    Namespaces in Imports field not imported from:
      ‘DT’ ‘RColorBrewer’ ‘RODBC’ ‘dplyr’ ‘foreign’ ‘formattable’ ‘ggplot2’
      ‘haven’ ‘magrittr’ ‘mem’ ‘openxlsx’ ‘plotly’ ‘readxl’ ‘shinyBS’
      ‘shinydashboard’ ‘shinyjs’ ‘shinythemes’ ‘stringi’ ‘stringr’ ‘tidyr’
      All declared Imports should be used.
    ```

# MetaCyto

Version: 1.2.1

## In both

*   checking R code for possible problems ... NOTE
    ```
    ...
    collectData: no visible binding for global variable ‘value’
      (/Users/lionel/Desktop/tidyr/revdep/checks.noindex/MetaCyto/new/MetaCyto.Rcheck/00_pkg_src/MetaCyto/R/collectData.R:27)
    panelSummary: no visible binding for global variable ‘antibodies’
      (/Users/lionel/Desktop/tidyr/revdep/checks.noindex/MetaCyto/new/MetaCyto.Rcheck/00_pkg_src/MetaCyto/R/panelSummary.R:34)
    panelSummary: no visible binding for global variable ‘value’
      (/Users/lionel/Desktop/tidyr/revdep/checks.noindex/MetaCyto/new/MetaCyto.Rcheck/00_pkg_src/MetaCyto/R/panelSummary.R:34)
    plotGA: no visible binding for global variable ‘lower’
      (/Users/lionel/Desktop/tidyr/revdep/checks.noindex/MetaCyto/new/MetaCyto.Rcheck/00_pkg_src/MetaCyto/R/plotGA.R:33-39)
    plotGA: no visible binding for global variable ‘upper’
      (/Users/lionel/Desktop/tidyr/revdep/checks.noindex/MetaCyto/new/MetaCyto.Rcheck/00_pkg_src/MetaCyto/R/plotGA.R:33-39)
    searchCluster : <anonymous>: no visible binding for global variable
      ‘triS’
      (/Users/lionel/Desktop/tidyr/revdep/checks.noindex/MetaCyto/new/MetaCyto.Rcheck/00_pkg_src/MetaCyto/R/searchCluster.R:102)
    searchCluster : <anonymous>: no visible binding for global variable
      ‘triS’
      (/Users/lionel/Desktop/tidyr/revdep/checks.noindex/MetaCyto/new/MetaCyto.Rcheck/00_pkg_src/MetaCyto/R/searchCluster.R:103)
    searchCluster : <anonymous>: no visible binding for global variable
      ‘triS’
      (/Users/lionel/Desktop/tidyr/revdep/checks.noindex/MetaCyto/new/MetaCyto.Rcheck/00_pkg_src/MetaCyto/R/searchCluster.R:104)
    Undefined global functions or variables:
      antibodies lower parameter_name triS upper value
    ```

# MetamapsDB

Version: 0.0.2

## In both

*   checking dependencies in R code ... NOTE
    ```
    Namespaces in Imports field not imported from:
      ‘Matrix’ ‘shiny’
      All declared Imports should be used.
    ```

# microbiome

Version: 1.2.1

## In both

*   checking package dependencies ... ERROR
    ```
    Package required but not available: ‘vegan’
    
    See section ‘The DESCRIPTION file’ in the ‘Writing R Extensions’
    manual.
    ```

# mixOmics

Version: 6.3.2

## In both

*   checking installed package size ... NOTE
    ```
      installed size is  9.7Mb
      sub-directories of 1Mb or more:
        R      5.1Mb
        data   4.0Mb
    ```

# mlbgameday

Version: 0.1.2

## In both

*   R CMD check timed out
    

*   checking dependencies in R code ... NOTE
    ```
    Namespaces in Imports field not imported from:
      ‘doParallel’ ‘iterators’ ‘parallel’
      All declared Imports should be used.
    ```

# modelr

Version: 0.1.2

## In both

*   checking Rd cross-references ... NOTE
    ```
    Packages unavailable to check Rd xrefs: ‘lme4’, ‘rstanarm’
    ```

# monkeylearn

Version: 0.2.0

## In both

*   checking dependencies in R code ... NOTE
    ```
    Namespace in Imports field not imported from: ‘ratelimitr’
      All declared Imports should be used.
    ```

# morse

Version: 3.1.1

## In both

*   checking whether package ‘morse’ can be installed ... ERROR
    ```
    Installation failed.
    See ‘/Users/lionel/Desktop/tidyr/revdep/checks.noindex/morse/new/morse.Rcheck/00install.out’ for details.
    ```

## Installation

### Devel

```
* installing *source* package ‘morse’ ...
** package ‘morse’ successfully unpacked and MD5 sums checked
** R
** data
*** moving datasets to lazyload DB
** inst
** byte-compile and prepare package for lazy loading
Error : .onLoad failed in loadNamespace() for 'rjags', details:
  call: dyn.load(file, DLLpath = DLLpath, ...)
  error: unable to load shared object '/Users/lionel/Desktop/tidyr/revdep/library.noindex/morse/rjags/libs/rjags.so':
  dlopen(/Users/lionel/Desktop/tidyr/revdep/library.noindex/morse/rjags/libs/rjags.so, 10): Library not loaded: /usr/local/lib/libjags.4.dylib
  Referenced from: /Users/lionel/Desktop/tidyr/revdep/library.noindex/morse/rjags/libs/rjags.so
  Reason: image not found
ERROR: lazy loading failed for package ‘morse’
* removing ‘/Users/lionel/Desktop/tidyr/revdep/checks.noindex/morse/new/morse.Rcheck/morse’

```
### CRAN

```
* installing *source* package ‘morse’ ...
** package ‘morse’ successfully unpacked and MD5 sums checked
** R
** data
*** moving datasets to lazyload DB
** inst
** byte-compile and prepare package for lazy loading
Error : .onLoad failed in loadNamespace() for 'rjags', details:
  call: dyn.load(file, DLLpath = DLLpath, ...)
  error: unable to load shared object '/Users/lionel/Desktop/tidyr/revdep/library.noindex/morse/rjags/libs/rjags.so':
  dlopen(/Users/lionel/Desktop/tidyr/revdep/library.noindex/morse/rjags/libs/rjags.so, 10): Library not loaded: /usr/local/lib/libjags.4.dylib
  Referenced from: /Users/lionel/Desktop/tidyr/revdep/library.noindex/morse/rjags/libs/rjags.so
  Reason: image not found
ERROR: lazy loading failed for package ‘morse’
* removing ‘/Users/lionel/Desktop/tidyr/revdep/checks.noindex/morse/old/morse.Rcheck/morse’

```
# mortAAR

Version: 1.0.1

## In both

*   checking re-building of vignette outputs ... WARNING
    ```
    Error in re-building vignettes:
      ...
    Loading required package: bitops
    pandoc-citeproc: when expecting a product (:*:), encountered Object instead
    Error running filter /usr/local/bin/pandoc-citeproc:
    Filter returned error status 1
    Error: processing vignette 'mortAAR_vignette-1.Rmd' failed with diagnostics:
    pandoc document conversion failed with error 83
    Execution halted
    ```

# MortalityLaws

Version: 1.6.0

## In both

*   checking re-building of vignette outputs ... WARNING
    ```
    Error in re-building vignettes:
      ...
    pandoc-citeproc: when expecting a product (:*:), encountered Object instead
    Error running filter /usr/local/bin/pandoc-citeproc:
    Filter returned error status 1
    Error: processing vignette 'Installation.Rmd' failed with diagnostics:
    pandoc document conversion failed with error 83
    Execution halted
    ```

# mosaic

Version: 1.4.0

## In both

*   checking package dependencies ... NOTE
    ```
    Package which this enhances but not available for checking: ‘manipulate’
    ```

*   checking installed package size ... NOTE
    ```
      installed size is  6.6Mb
      sub-directories of 1Mb or more:
        R     4.2Mb
        doc   1.9Mb
    ```

*   checking Rd cross-references ... NOTE
    ```
    Package unavailable to check Rd xrefs: ‘cubature’
    ```

# mosaicData

Version: 0.17.0

## In both

*   checking data for non-ASCII characters ... NOTE
    ```
      Note: found 7 marked UTF-8 strings
    ```

# mosaicModel

Version: 0.3.0

## In both

*   checking dependencies in R code ... NOTE
    ```
    Namespaces in Imports field not imported from:
      ‘MASS’ ‘caret’ ‘ggformula’ ‘knitr’ ‘testthat’ ‘tidyverse’
      All declared Imports should be used.
    ```

# mplot

Version: 1.0.1

## In both

*   checking dependencies in R code ... NOTE
    ```
    Unable to find any JVMs matching version "(null)".
    No Java runtime present, try --request to install.
    ```

# MSstats

Version: 3.12.3

## In both

*   R CMD check timed out
    

*   checking R code for possible problems ... NOTE
    ```
    ...
      (/Users/lionel/Desktop/tidyr/revdep/checks.noindex/MSstats/new/MSstats.Rcheck/00_pkg_src/MSstats/R/plot_quantlim.R:194-197)
    plot_quantlim: no visible binding for global variable ‘ymax’
      (/Users/lionel/Desktop/tidyr/revdep/checks.noindex/MSstats/new/MSstats.Rcheck/00_pkg_src/MSstats/R/plot_quantlim.R:194-197)
    plot_quantlim: no visible binding for global variable ‘x’
      (/Users/lionel/Desktop/tidyr/revdep/checks.noindex/MSstats/new/MSstats.Rcheck/00_pkg_src/MSstats/R/plot_quantlim.R:218-221)
    plot_quantlim: no visible binding for global variable ‘y’
      (/Users/lionel/Desktop/tidyr/revdep/checks.noindex/MSstats/new/MSstats.Rcheck/00_pkg_src/MSstats/R/plot_quantlim.R:218-221)
    plot_quantlim: no visible binding for global variable ‘shape’
      (/Users/lionel/Desktop/tidyr/revdep/checks.noindex/MSstats/new/MSstats.Rcheck/00_pkg_src/MSstats/R/plot_quantlim.R:218-221)
    plot_quantlim: no visible binding for global variable ‘x’
      (/Users/lionel/Desktop/tidyr/revdep/checks.noindex/MSstats/new/MSstats.Rcheck/00_pkg_src/MSstats/R/plot_quantlim.R:223-226)
    plot_quantlim: no visible binding for global variable ‘y’
      (/Users/lionel/Desktop/tidyr/revdep/checks.noindex/MSstats/new/MSstats.Rcheck/00_pkg_src/MSstats/R/plot_quantlim.R:223-226)
    plot_quantlim: no visible binding for global variable ‘shape’
      (/Users/lionel/Desktop/tidyr/revdep/checks.noindex/MSstats/new/MSstats.Rcheck/00_pkg_src/MSstats/R/plot_quantlim.R:223-226)
    Undefined global functions or variables:
      ABUNDANCE FEATURE FRACTION Intensity LABEL Mean Name PeptideSequence
      Protein ProteinName Protein_number RUN Selected_fragments
      Selected_peptides Train_size aggr_Fragment_Annotation aggr_Peak_Area
      analysis ciw datafeature fea label logFC missing.col ncount ount
      residual shape weight x y ymax ymin
    ```

# mudata2

Version: 1.0.3

## In both

*   checking tests ...
    ```
     ERROR
    Running the tests in ‘tests/test-all.R’ failed.
    Last 13 lines of output:
      31: tryCatchList(expr, classes, parentenv, handlers)
      32: tryCatch(withCallingHandlers({    eval(code, test_env)    if (!handled && !is.null(test)) {        skip_empty()    }}, expectation = handle_expectation, skip = handle_skip, warning = handle_warning,     message = handle_message, error = handle_error), error = handle_fatal,     skip = function(e) {    })
      33: test_code(NULL, exprs, env)
      34: source_file(path, new.env(parent = env), chdir = TRUE, wrap = wrap)
      35: force(code)
      36: with_reporter(reporter = reporter, start_end_reporter = start_end_reporter,     {        lister$start_file(basename(path))        source_file(path, new.env(parent = env), chdir = TRUE,             wrap = wrap)        end_context()    })
      37: FUN(X[[i]], ...)
      38: lapply(paths, test_file, env = env, reporter = current_reporter,     start_end_reporter = FALSE, load_helpers = FALSE, wrap = wrap)
      39: force(code)
      40: with_reporter(reporter = current_reporter, results <- lapply(paths,     test_file, env = env, reporter = current_reporter, start_end_reporter = FALSE,     load_helpers = FALSE, wrap = wrap))
      41: test_files(paths, reporter = reporter, env = env, stop_on_failure = stop_on_failure,     stop_on_warning = stop_on_warning, wrap = wrap)
      42: test_dir(path = test_path, reporter = reporter, env = env, filter = filter,     ..., stop_on_failure = stop_on_failure, stop_on_warning = stop_on_warning,     wrap = wrap)
      43: test_package_dir(package = package, test_path = test_path, filter = filter,     reporter = reporter, ..., stop_on_failure = stop_on_failure,     stop_on_warning = stop_on_warning, wrap = wrap)
      44: test_check("mudata2")
      An irrecoverable exception occurred. R is aborting now ...
    ```

# MultiAssayExperiment

Version: 1.6.0

## In both

*   checking dependencies in R code ... NOTE
    ```
    Unexported objects imported by ':::' calls:
      ‘BiocGenerics:::replaceSlots’ ‘S4Vectors:::selectSome’
      See the note in ?`:::` about the use of this operator.
    ```

# multicolor

Version: 0.1.1

## In both

*   checking dependencies in R code ... NOTE
    ```
    Namespace in Imports field not imported from: ‘cowsay’
      All declared Imports should be used.
    ```

# multistateutils

Version: 1.2.0

## In both

*   checking re-building of vignette outputs ... WARNING
    ```
    Error in re-building vignettes:
      ...
    pandoc-citeproc: when expecting a product (:*:), encountered Object instead
    Error running filter /usr/local/bin/pandoc-citeproc:
    Filter returned error status 1
    Error: processing vignette 'Examples.Rmd' failed with diagnostics:
    pandoc document conversion failed with error 83
    Execution halted
    ```

*   checking dependencies in R code ... NOTE
    ```
    Namespaces in Imports field not imported from:
      ‘Rcpp’ ‘survival’
      All declared Imports should be used.
    ```

# naniar

Version: 0.4.0.0

## In both

*   checking tests ...
    ```
     ERROR
    Running the tests in ‘tests/testthat.R’ failed.
    Last 13 lines of output:
      8: withVisible(function_list[[k]](value))
      9: function_list[[k]](value)
      10: dplyr::mutate(., any_missing = label_shadow(., !!!quo_vars, missing = missing, complete = complete))
      11: mutate.tbl_df(., any_missing = label_shadow(., !!!quo_vars, missing = missing, complete = complete))
      12: mutate_impl(.data, dots)
      
      ══ testthat results  ═══════════════════════════════════════════════════════════
      OK: 456 SKIPPED: 23 FAILED: 4
      1. Error: add_label_shadow returns a tibble (@test-add-label-shadow.R#7) 
      2. Error: add_label_shadow adds the right number of columns (@test-add-label-shadow.R#13) 
      3. Error: add_label_shadow adds a column with suffix 'any_missing' (@test-add-label-shadow.R#20) 
      4. Error: (unknown) (@test-add-label-shadow.R#45) 
      
      Error: testthat unit tests failed
      Execution halted
    ```

# ncappc

Version: 0.3.0

## In both

*   checking dependencies in R code ... NOTE
    ```
    Namespace in Imports field not imported from: ‘bookdown’
      All declared Imports should be used.
    ```

# ndexr

Version: 1.2.0

## Newly broken

*   checking examples ... ERROR
    ```
    ...
    The error most likely occurred in:
    
    > ### Name: ndex_get_network
    > ### Title: Get complete network
    > ### Aliases: ndex_get_network
    > 
    > ### ** Examples
    > 
    > ## Establish a server connection
    > ndexcon = ndex_connect()
    > ## Find a network and get its UUID
    > networks = ndex_find_networks(ndexcon,"p53")
    > networkId = networks[1,"externalId"]
    > ## Get the network data 
    > rcx = ndex_get_network(ndexcon, networkId) 
    Error in curl::curl_fetch_memory(url, handle = handle) : 
      transfer closed with outstanding read data remaining
    Error in ndex_helper_httpResponseHandler(response, paste("GET: [", url,  : 
      object 'response' not found
    Calls: ndex_get_network -> ndex_rest_GET -> ndex_helper_httpResponseHandler
    Execution halted
    ```

## In both

*   R CMD check timed out
    

*   checking DESCRIPTION meta-information ... NOTE
    ```
    Deprecated license: BSD
    ```

*   checking dependencies in R code ... NOTE
    ```
    Package in Depends field not imported from: ‘igraph’
      These packages need to be imported from (in the NAMESPACE file)
      for when this namespace is loaded but not attached.
    Unexported object imported by a ':::' call: ‘httr:::default_ua’
      See the note in ?`:::` about the use of this operator.
    ```

*   checking R code for possible problems ... NOTE
    ```
    ...
    rcx_toRCXgraph: no visible global function definition for ‘E’
      (/Users/lionel/Desktop/tidyr/revdep/checks.noindex/ndexr/new/ndexr.Rcheck/00_pkg_src/ndexr/R/ndex_RCXgraph.r:117)
    rcx_toRCXgraph: no visible global function definition for ‘E<-’
      (/Users/lionel/Desktop/tidyr/revdep/checks.noindex/ndexr/new/ndexr.Rcheck/00_pkg_src/ndexr/R/ndex_RCXgraph.r:117)
    rcxgraph_fromRCX: no visible global function definition for ‘V’
      (/Users/lionel/Desktop/tidyr/revdep/checks.noindex/ndexr/new/ndexr.Rcheck/00_pkg_src/ndexr/R/ndex_RCXgraph.r:116)
    rcxgraph_fromRCX: no visible global function definition for ‘V<-’
      (/Users/lionel/Desktop/tidyr/revdep/checks.noindex/ndexr/new/ndexr.Rcheck/00_pkg_src/ndexr/R/ndex_RCXgraph.r:116)
    rcxgraph_fromRCX: no visible global function definition for ‘E’
      (/Users/lionel/Desktop/tidyr/revdep/checks.noindex/ndexr/new/ndexr.Rcheck/00_pkg_src/ndexr/R/ndex_RCXgraph.r:117)
    rcxgraph_fromRCX: no visible global function definition for ‘E<-’
      (/Users/lionel/Desktop/tidyr/revdep/checks.noindex/ndexr/new/ndexr.Rcheck/00_pkg_src/ndexr/R/ndex_RCXgraph.r:117)
    rcxgraph_toRCX: no visible binding for global variable ‘po’
      (/Users/lionel/Desktop/tidyr/revdep/checks.noindex/ndexr/new/ndexr.Rcheck/00_pkg_src/ndexr/R/ndex_RCXgraph.r:268)
    rcxgraph_toRCX: no visible binding for global variable ‘po’
      (/Users/lionel/Desktop/tidyr/revdep/checks.noindex/ndexr/new/ndexr.Rcheck/00_pkg_src/ndexr/R/ndex_RCXgraph.r:294)
    Undefined global functions or variables:
      E E<- V V<- packageVersion po tail
    Consider adding
      importFrom("utils", "packageVersion", "tail")
    to your NAMESPACE file.
    ```

# NetworkChange

Version: 0.4

## In both

*   checking dependencies in R code ... NOTE
    ```
    Namespace in Imports field not imported from: ‘plyr’
      All declared Imports should be used.
    ```

# NetworkExtinction

Version: 0.1.0

## In both

*   checking re-building of vignette outputs ... WARNING
    ```
    ...
    1
    2
    3
    4
    5
    6
    7
    8
    Simulation 100 of 100 ready
    Warning in chisq.test(x = Hypothesis$DF$AccSecondaryExtinction, y = Nullmodel$sims$AccSecondaryExtinction[1:length(Hypothesis$DF$AccSecondaryExtinction)]) :
      Chi-squared approximation may be incorrect
    Joining, by = c("K", "Cumulative", "Scenario", "Exp")
    Joining, by = c("K", "Cumulative", "Scenario", "Exp", "power")
    Joining, by = c("sigma", "isConv", "finTol", "logLik", "AIC", "BIC", "deviance", "df.residual", "model")
    Joining, by = c("sigma", "isConv", "finTol", "logLik", "AIC", "BIC", "deviance", "df.residual", "model")
    pandoc-citeproc: when expecting a product (:*:), encountered Object instead
    Error running filter /usr/local/bin/pandoc-citeproc:
    Filter returned error status 1
    Error: processing vignette 'VignetteNetworkExt.Rmd' failed with diagnostics:
    pandoc document conversion failed with error 83
    Execution halted
    ```

# neuropsychology

Version: 0.5.0

## In both

*   checking dependencies in R code ... NOTE
    ```
    Namespaces in Imports field not imported from:
      ‘htmlTable’ ‘lme4’ ‘stringi’
      All declared Imports should be used.
    ```

# NFP

Version: 0.99.2

## In both

*   checking package dependencies ... NOTE
    ```
    Package suggested but not available for checking: ‘NFPdata’
    ```

*   checking installed package size ... NOTE
    ```
      installed size is  8.7Mb
      sub-directories of 1Mb or more:
        data   8.1Mb
    ```

# nlmixr

Version: 1.0.0-7

## In both

*   checking package dependencies ... NOTE
    ```
    Package suggested but not available for checking: ‘devtools’
    ```

*   checking installed package size ... NOTE
    ```
      installed size is  5.3Mb
      sub-directories of 1Mb or more:
        R      3.0Mb
        libs   1.0Mb
    ```

*   checking dependencies in R code ... NOTE
    ```
    Namespaces in Imports field not imported from:
      ‘PreciseSums’ ‘numDeriv’
      All declared Imports should be used.
    ```

# noaastormevents

Version: 0.1.0

## In both

*   checking package dependencies ... NOTE
    ```
    Package suggested but not available for checking: ‘hurricaneexposuredata’
    ```

*   checking dependencies in R code ... NOTE
    ```
    Namespaces in Imports field not imported from:
      ‘RColorBrewer’ ‘XML’ ‘choroplethr’ ‘choroplethrMaps’ ‘data.table’
      ‘forcats’ ‘hurricaneexposure’ ‘plyr’
      All declared Imports should be used.
    ```

# NOAAWeather

Version: 0.1.0

## Newly broken

*   checking re-building of vignette outputs ... WARNING
    ```
    Error in re-building vignettes:
      ...
    Quitting from lines 61-66 (Report.Rmd) 
    Error: processing vignette 'Report.Rmd' failed with diagnostics:
    transfer closed with outstanding read data remaining
    Execution halted
    ```

## Newly fixed

*   R CMD check timed out
    

## In both

*   checking installed package size ... NOTE
    ```
      installed size is  5.6Mb
      sub-directories of 1Mb or more:
        data   5.1Mb
    ```

# nullabor

Version: 0.3.5

## In both

*   checking dependencies in R code ... NOTE
    ```
    Namespaces in Imports field not imported from:
      ‘forecast’ ‘rlang’ ‘tidyverse’ ‘tsibble’
      All declared Imports should be used.
    ```

# nzelect

Version: 0.4.0

## In both

*   checking installed package size ... NOTE
    ```
      installed size is  5.4Mb
      sub-directories of 1Mb or more:
        data   5.0Mb
    ```

*   checking data for non-ASCII characters ... NOTE
    ```
      Note: found 6409 marked UTF-8 strings
    ```

# openair

Version: 2.5-0

## In both

*   checking installed package size ... NOTE
    ```
      installed size is  5.1Mb
      sub-directories of 1Mb or more:
        R   3.0Mb
    ```

# parsemsf

Version: 0.1.1

## In both

*   checking re-building of vignette outputs ... WARNING
    ```
    Error in re-building vignettes:
      ...
    
    Attaching package: 'dplyr'
    
    The following objects are masked from 'package:stats':
    
        filter, lag
    
    The following objects are masked from 'package:base':
    
        intersect, setdiff, setequal, union
    
    pandoc-citeproc: when expecting a product (:*:), encountered Object instead
    Error running filter /usr/local/bin/pandoc-citeproc:
    Filter returned error status 1
    Error: processing vignette 'introduction.Rmd' failed with diagnostics:
    pandoc document conversion failed with error 83
    Execution halted
    ```

*   checking dependencies in R code ... NOTE
    ```
    Namespace in Imports field not imported from: ‘dbplyr’
      All declared Imports should be used.
    ```

# patentsview

Version: 0.2.1

## Newly broken

*   checking re-building of vignette outputs ... WARNING
    ```
    Error in re-building vignettes:
      ...
    Quitting from lines 42-59 (examples.Rmd) 
    Error: processing vignette 'examples.Rmd' failed with diagnostics:
    parse error: premature EOF
                                           {"patents":[{"patent_number":"7
                         (right here) ------^
    Execution halted
    ```

## Newly fixed

*   R CMD check timed out
    

# PathoStat

Version: 1.6.1

## In both

*   checking package dependencies ... ERROR
    ```
    Packages required but not available: ‘vegan’ ‘devtools’
    
    See section ‘The DESCRIPTION file’ in the ‘Writing R Extensions’
    manual.
    ```

# pcaExplorer

Version: 2.6.0

## In both

*   checking package dependencies ... ERROR
    ```
    Package required but not available: ‘GO.db’
    
    Packages suggested but not available for checking: ‘airway’ ‘org.Hs.eg.db’
    
    See section ‘The DESCRIPTION file’ in the ‘Writing R Extensions’
    manual.
    ```

# pcr

Version: 1.1.2

## In both

*   checking package dependencies ... ERROR
    ```
    Package required but not available: ‘devtools’
    
    See section ‘The DESCRIPTION file’ in the ‘Writing R Extensions’
    manual.
    ```

# performanceEstimation

Version: 1.1.0

## In both

*   checking package dependencies ... NOTE
    ```
    Package suggested but not available for checking: ‘devtools’
    ```

# perturbatr

Version: 1.0.0

## In both

*   checking re-building of vignette outputs ... WARNING
    ```
    Error in re-building vignettes:
      ...
    convert: profile 'icc': 'RGB ': RGB color space not permitted on grayscale PNG `perturbatr_files/figure-html/unnamed-chunk-7-1.png' @ warning/png.c/MagickPNGWarningHandler/1656.
    Fitting hierarchical model
    Only taking largest connected component to ensure ergodicity.
    Diffusion using Markov random walks.
    Correcting for hub degrees.
    normalizing column vectors!
    normalizing column vectors!
    convert: profile 'icc': 'RGB ': RGB color space not permitted on grayscale PNG `perturbatr_files/figure-html/unnamed-chunk-14-1.png' @ warning/png.c/MagickPNGWarningHandler/1656.
    pandoc-citeproc: when expecting a product (:*:), encountered Object instead
    Error running filter /usr/local/bin/pandoc-citeproc:
    Filter returned error status 1
    Error: processing vignette 'perturbatr.Rmd' failed with diagnostics:
    pandoc document conversion failed with error 83
    Execution halted
    ```

# phenopath

Version: 1.4.0

## In both

*   checking re-building of vignette outputs ... WARNING
    ```
    Error in re-building vignettes:
      ...
    convert: profile 'icc': 'RGB ': RGB color space not permitted on grayscale PNG `introduction_to_phenopath_files/figure-html/plot-elbo-1.png' @ warning/png.c/MagickPNGWarningHandler/1656.
    convert: profile 'icc': 'RGB ': RGB color space not permitted on grayscale PNG `introduction_to_phenopath_files/figure-html/plot-results-1.png' @ warning/png.c/MagickPNGWarningHandler/1656.
    convert: profile 'icc': 'RGB ': RGB color space not permitted on grayscale PNG `introduction_to_phenopath_files/figure-html/plot-results-2.png' @ warning/png.c/MagickPNGWarningHandler/1656.
    pandoc-citeproc: when expecting a product (:*:), encountered Object instead
    Error running filter /usr/local/bin/pandoc-citeproc:
    Filter returned error status 1
    Error: processing vignette 'introduction_to_phenopath.Rmd' failed with diagnostics:
    pandoc document conversion failed with error 83
    Execution halted
    ```

# philr

Version: 1.6.0

## In both

*   checking re-building of vignette outputs ... WARNING
    ```
    Error in re-building vignettes:
      ...
    Quitting from lines 27-33 (philr-intro.Rmd) 
    Error: processing vignette 'philr-intro.Rmd' failed with diagnostics:
    package or namespace load failed for 'phyloseq' in loadNamespace(j <- i[[1L]], c(lib.loc, .libPaths()), versionCheck = vI[[j]]):
     there is no package called 'vegan'
    Execution halted
    ```

*   checking R code for possible problems ... NOTE
    ```
    name.balance: no visible global function definition for ‘as’
      (/Users/lionel/Desktop/tidyr/revdep/checks.noindex/philr/new/philr.Rcheck/00_pkg_src/philr/R/name_balances.R:57)
    vote.annotation: no visible global function definition for ‘is’
      (/Users/lionel/Desktop/tidyr/revdep/checks.noindex/philr/new/philr.Rcheck/00_pkg_src/philr/R/name_balances.R:127-131)
    Undefined global functions or variables:
      as is
    Consider adding
      importFrom("methods", "as", "is")
    to your NAMESPACE file (and ensure that your DESCRIPTION Imports
    field contains 'methods').
    ```

*   checking Rd cross-references ... NOTE
    ```
    Package unavailable to check Rd xrefs: ‘compositions’
    ```

# Pi

Version: 1.8.0

## In both

*   checking package dependencies ... ERROR
    ```
    Package required but not available: ‘XGR’
    
    See section ‘The DESCRIPTION file’ in the ‘Writing R Extensions’
    manual.
    ```

# pivot

Version: 18.4.17

## In both

*   checking package dependencies ... NOTE
    ```
    Package which this enhances but not available for checking: ‘odbc’
    ```

*   checking dependencies in R code ... NOTE
    ```
    Namespaces in Imports field not imported from:
      ‘colorspace’ ‘lubridate’
      All declared Imports should be used.
    ```

# pixiedust

Version: 0.8.5

## In both

*   checking Rd cross-references ... NOTE
    ```
    Package unavailable to check Rd xrefs: ‘Hmisc’
    ```

# plotly

Version: 4.8.0

## Newly broken

*   checking tests ...
    ```
     ERROR
    Running the tests in ‘tests/testthat.R’ failed.
    Last 13 lines of output:
      34: tryCatch(withCallingHandlers({    eval(code, test_env)    if (!handled && !is.null(test)) {        skip_empty()    }}, expectation = handle_expectation, skip = handle_skip, warning = handle_warning,     message = handle_message, error = handle_error), error = handle_fatal,     skip = function(e) {    })
      35: test_code(NULL, exprs, env)
      36: source_file(path, new.env(parent = env), chdir = TRUE, wrap = wrap)
      37: force(code)
      38: with_reporter(reporter = reporter, start_end_reporter = start_end_reporter,     {        lister$start_file(basename(path))        source_file(path, new.env(parent = env), chdir = TRUE,             wrap = wrap)        end_context()    })
      39: FUN(X[[i]], ...)
      40: lapply(paths, test_file, env = env, reporter = current_reporter,     start_end_reporter = FALSE, load_helpers = FALSE, wrap = wrap)
      41: force(code)
      42: with_reporter(reporter = current_reporter, results <- lapply(paths,     test_file, env = env, reporter = current_reporter, start_end_reporter = FALSE,     load_helpers = FALSE, wrap = wrap))
      43: test_files(paths, reporter = reporter, env = env, stop_on_failure = stop_on_failure,     stop_on_warning = stop_on_warning, wrap = wrap)
      44: test_dir(path = test_path, reporter = reporter, env = env, filter = filter,     ..., stop_on_failure = stop_on_failure, stop_on_warning = stop_on_warning,     wrap = wrap)
      45: test_package_dir(package = package, test_path = test_path, filter = filter,     reporter = reporter, ..., stop_on_failure = stop_on_failure,     stop_on_warning = stop_on_warning, wrap = wrap)
      46: test_check(...)
      47: test_run("plotly")
      An irrecoverable exception occurred. R is aborting now ...
    ```

## In both

*   checking package dependencies ... NOTE
    ```
    Package suggested but not available for checking: ‘devtools’
    ```

*   checking installed package size ... NOTE
    ```
      installed size is  7.1Mb
      sub-directories of 1Mb or more:
        R             2.3Mb
        htmlwidgets   3.1Mb
    ```

# plyranges

Version: 1.0.3

## In both

*   checking tests ...
    ```
     ERROR
    Running the tests in ‘tests/testthat.R’ failed.
    Last 13 lines of output:
             e$handled <- TRUE
             test_error <<- e
         }, "could not find function \"WIGFile\"", quote(WIGFile(test_wig))) at testthat/test-io-wig.R:24
      2: eval(code, test_env)
      
      ══ testthat results  ═══════════════════════════════════════════════════════════
      OK: 271 SKIPPED: 0 FAILED: 5
      1. Error: read_bed returns correct GRanges (@test-io-bed.R#67) 
      2. Error: read_bed_graph returns correct GRanges (@test-io-bedGraph.R#39) 
      3. Error: reading/ writing bigwig files returns correct GRanges (@test-io-bw.R#19) 
      4. Error: reading GFF files returns correct GRanges (@test-io-gff.R#87) 
      5. Error: reading WIG files (@test-io-wig.R#24) 
      
      Error: testthat unit tests failed
      Execution halted
    ```

*   checking package dependencies ... NOTE
    ```
    Package suggested but not available for checking: ‘BSgenome.Hsapiens.UCSC.hg19’
    ```

# pmc

Version: 1.0.3

## In both

*   R CMD check timed out
    

# pollstR

Version: 2.0.1

## Newly broken

*   checking re-building of vignette outputs ... WARNING
    ```
    Error in re-building vignettes:
      ...
    
    Attaching package: 'dplyr'
    
    The following objects are masked from 'package:stats':
    
        filter, lag
    
    The following objects are masked from 'package:base':
    
        intersect, setdiff, setequal, union
    
    Quitting from lines 30-33 (examples.Rmd) 
    Error: processing vignette 'examples.Rmd' failed with diagnostics:
    Timeout was reached: Operation timed out after 10003 milliseconds with 0 out of 0 bytes received
    Execution halted
    ```

# PopED

Version: 0.4.0

## In both

*   checking dependencies in R code ... NOTE
    ```
    Namespace in Imports field not imported from: ‘tidyr’
      All declared Imports should be used.
    ```

# powerlmm

Version: 0.4.0

## In both

*   checking re-building of vignette outputs ... WARNING
    ```
    Error in re-building vignettes:
      ...
    pandoc-citeproc: when expecting a product (:*:), encountered Object instead
    Error running filter /usr/local/bin/pandoc-citeproc:
    Filter returned error status 1
    Error: processing vignette 'technical.Rmd' failed with diagnostics:
    pandoc document conversion failed with error 83
    Execution halted
    ```

# PPforest

Version: 0.1.1

## In both

*   checking re-building of vignette outputs ... WARNING
    ```
    ...
        nasa
    
    Loading required package: gridExtra
    
    Attaching package: 'gridExtra'
    
    The following object is masked from 'package:dplyr':
    
        combine
    
    Loading required package: PPtreeViz
    Loading required package: partykit
    Loading required package: grid
    Loading required package: libcoin
    Loading required package: mvtnorm
    pandoc-citeproc: when expecting a product (:*:), encountered Object instead
    Error running filter /usr/local/bin/pandoc-citeproc:
    Filter returned error status 1
    Error: processing vignette 'PPforest-vignette.Rmd' failed with diagnostics:
    pandoc document conversion failed with error 83
    Execution halted
    ```

# prisonbrief

Version: 0.1.0

## In both

*   checking data for non-ASCII characters ... NOTE
    ```
      Note: found 2 marked UTF-8 strings
    ```

# proteoQC

Version: 1.16.0

## In both

*   checking re-building of vignette outputs ... WARNING
    ```
    Error in re-building vignettes:
      ...
    Error: processing vignette 'proteoQC.Rmd' failed with diagnostics:
    there is no package called ‘prettydoc’
    Execution halted
    ```

*   checking package dependencies ... NOTE
    ```
    Package suggested but not available for checking: ‘RforProteomics’
    ```

*   checking installed package size ... NOTE
    ```
      installed size is  7.6Mb
      sub-directories of 1Mb or more:
        doc       2.5Mb
        extdata   3.9Mb
    ```

*   checking R code for possible problems ... NOTE
    ```
    ...
    qcHist: no visible binding for global variable ‘techRep’
      (/Users/lionel/Desktop/tidyr/revdep/checks.noindex/proteoQC/new/proteoQC.Rcheck/00_pkg_src/proteoQC/R/visualization.R:406-416)
    qcHist: no visible binding for global variable ‘bioRep’
      (/Users/lionel/Desktop/tidyr/revdep/checks.noindex/proteoQC/new/proteoQC.Rcheck/00_pkg_src/proteoQC/R/visualization.R:406-416)
    qcHist2: no visible binding for global variable ‘error’
      (/Users/lionel/Desktop/tidyr/revdep/checks.noindex/proteoQC/new/proteoQC.Rcheck/00_pkg_src/proteoQC/R/visualization.R:357-365)
    qcHist2: no visible binding for global variable ‘fractile’
      (/Users/lionel/Desktop/tidyr/revdep/checks.noindex/proteoQC/new/proteoQC.Rcheck/00_pkg_src/proteoQC/R/visualization.R:357-365)
    qcHist2: no visible binding for global variable ‘fractile’
      (/Users/lionel/Desktop/tidyr/revdep/checks.noindex/proteoQC/new/proteoQC.Rcheck/00_pkg_src/proteoQC/R/visualization.R:367-369)
    qcHist2: no visible binding for global variable ‘error’
      (/Users/lionel/Desktop/tidyr/revdep/checks.noindex/proteoQC/new/proteoQC.Rcheck/00_pkg_src/proteoQC/R/visualization.R:377-385)
    qcHist2: no visible binding for global variable ‘fractile’
      (/Users/lionel/Desktop/tidyr/revdep/checks.noindex/proteoQC/new/proteoQC.Rcheck/00_pkg_src/proteoQC/R/visualization.R:377-385)
    qcHist2: no visible binding for global variable ‘fractile’
      (/Users/lionel/Desktop/tidyr/revdep/checks.noindex/proteoQC/new/proteoQC.Rcheck/00_pkg_src/proteoQC/R/visualization.R:389-391)
    Undefined global functions or variables:
      ..count.. Intensity MS1QC MS2QC TMT10 TMT6 Tag V1 V2 V3 V4 V5 bioRep
      curenv delta error exprs fractile fraction grid.draw iTRAQ4 iTRAQ8
      label peplength peptide_summary precursorCharge quantify ratio
      readMgfData se techRep val x y
    ```

# proustr

Version: 0.2.1

## In both

*   checking data for non-ASCII characters ... NOTE
    ```
      Note: found 20105 marked UTF-8 strings
    ```

# psychmeta

Version: 2.2.1

## In both

*   checking re-building of vignette outputs ... WARNING
    ```
    Error in re-building vignettes:
      ...
    pandoc-citeproc: when expecting a product (:*:), encountered Object instead
    Error running filter /usr/local/bin/pandoc-citeproc:
    Filter returned error status 1
    Error: processing vignette 'overview.Rmd' failed with diagnostics:
    pandoc document conversion failed with error 83
    Execution halted
    ```

*   checking installed package size ... NOTE
    ```
      installed size is  8.8Mb
      sub-directories of 1Mb or more:
        R   7.1Mb
    ```

# psycho

Version: 0.3.7

## In both

*   checking installed package size ... NOTE
    ```
      installed size is  5.5Mb
      sub-directories of 1Mb or more:
        doc   4.3Mb
    ```

*   checking dependencies in R code ... NOTE
    ```
    Namespace in Imports field not imported from: ‘methods’
      All declared Imports should be used.
    ```

# ptstem

Version: 0.0.3

## In both

*   checking installed package size ... NOTE
    ```
      installed size is  5.3Mb
      sub-directories of 1Mb or more:
        dict   5.1Mb
    ```

# qdap

Version: 2.3.0

## In both

*   checking whether package ‘qdap’ can be installed ... ERROR
    ```
    Installation failed.
    See ‘/Users/lionel/Desktop/tidyr/revdep/checks.noindex/qdap/new/qdap.Rcheck/00install.out’ for details.
    ```

## Installation

### Devel

```
* installing *source* package ‘qdap’ ...
** package ‘qdap’ successfully unpacked and MD5 sums checked
** R
** data
*** moving datasets to lazyload DB
** inst
** byte-compile and prepare package for lazy loading
Unable to find any JVMs matching version "(null)".
No Java runtime present, try --request to install.
Warning in system("/usr/libexec/java_home", intern = TRUE) :
  running command '/usr/libexec/java_home' had status 1
Error : .onLoad failed in loadNamespace() for 'rJava', details:
  call: dyn.load(file, DLLpath = DLLpath, ...)
  error: unable to load shared object '/Users/lionel/Desktop/tidyr/revdep/library.noindex/qdap/rJava/libs/rJava.so':
  dlopen(/Users/lionel/Desktop/tidyr/revdep/library.noindex/qdap/rJava/libs/rJava.so, 6): Library not loaded: /Library/Java/JavaVirtualMachines/jdk-9.jdk/Contents/Home/lib/server/libjvm.dylib
  Referenced from: /Users/lionel/Desktop/tidyr/revdep/library.noindex/qdap/rJava/libs/rJava.so
  Reason: image not found
ERROR: lazy loading failed for package ‘qdap’
* removing ‘/Users/lionel/Desktop/tidyr/revdep/checks.noindex/qdap/new/qdap.Rcheck/qdap’

```
### CRAN

```
* installing *source* package ‘qdap’ ...
** package ‘qdap’ successfully unpacked and MD5 sums checked
** R
** data
*** moving datasets to lazyload DB
** inst
** byte-compile and prepare package for lazy loading
Unable to find any JVMs matching version "(null)".
No Java runtime present, try --request to install.
Warning in system("/usr/libexec/java_home", intern = TRUE) :
  running command '/usr/libexec/java_home' had status 1
Error : .onLoad failed in loadNamespace() for 'rJava', details:
  call: dyn.load(file, DLLpath = DLLpath, ...)
  error: unable to load shared object '/Users/lionel/Desktop/tidyr/revdep/library.noindex/qdap/rJava/libs/rJava.so':
  dlopen(/Users/lionel/Desktop/tidyr/revdep/library.noindex/qdap/rJava/libs/rJava.so, 6): Library not loaded: /Library/Java/JavaVirtualMachines/jdk-9.jdk/Contents/Home/lib/server/libjvm.dylib
  Referenced from: /Users/lionel/Desktop/tidyr/revdep/library.noindex/qdap/rJava/libs/rJava.so
  Reason: image not found
ERROR: lazy loading failed for package ‘qdap’
* removing ‘/Users/lionel/Desktop/tidyr/revdep/checks.noindex/qdap/old/qdap.Rcheck/qdap’

```
# questionr

Version: 0.6.3

## In both

*   checking Rd cross-references ... NOTE
    ```
    Package unavailable to check Rd xrefs: ‘Hmisc’
    ```

*   checking data for non-ASCII characters ... NOTE
    ```
      Note: found 4145 marked UTF-8 strings
    ```

# quokar

Version: 0.1.0

## In both

*   checking whether package ‘quokar’ can be installed ... ERROR
    ```
    Installation failed.
    See ‘/Users/lionel/Desktop/tidyr/revdep/checks.noindex/quokar/new/quokar.Rcheck/00install.out’ for details.
    ```

## Installation

### Devel

```
* installing *source* package ‘quokar’ ...
** package ‘quokar’ successfully unpacked and MD5 sums checked
** libs
gcc-8 -I"/Library/Frameworks/R.framework/Resources/include" -DNDEBUG   -I/usr/local/include   -fPIC  -mtune=core2  -O3 -c init.c -o init.o
gfortran-7   -fPIC  -g -O2  -c rqbr.f -o rqbr.o
make: gfortran-7: No such file or directory
gfortran-7   -fPIC  -g -O2  -c rqfnb.f -o rqfnb.o
make: gfortran-7: No such file or directory
make: *** [rqbr.o] Error 1
make: *** Waiting for unfinished jobs....
make: *** [rqfnb.o] Error 1
ERROR: compilation failed for package ‘quokar’
* removing ‘/Users/lionel/Desktop/tidyr/revdep/checks.noindex/quokar/new/quokar.Rcheck/quokar’

```
### CRAN

```
* installing *source* package ‘quokar’ ...
** package ‘quokar’ successfully unpacked and MD5 sums checked
** libs
gcc-8 -I"/Library/Frameworks/R.framework/Resources/include" -DNDEBUG   -I/usr/local/include   -fPIC  -mtune=core2  -O3 -c init.c -o init.o
gfortran-7   -fPIC  -g -O2  -c rqbr.f -o rqbr.o
make: gfortran-7: No such file or directory
gfortran-7   -fPIC  -g -O2  -c rqfnb.f -o rqfnb.o
make: gfortran-7: No such file or directory
make: *** [rqbr.o] Error 1
make: *** Waiting for unfinished jobs....
make: *** [rqfnb.o] Error 1
ERROR: compilation failed for package ‘quokar’
* removing ‘/Users/lionel/Desktop/tidyr/revdep/checks.noindex/quokar/old/quokar.Rcheck/quokar’

```
# qwraps2

Version: 0.3.0

## In both

*   checking package dependencies ... ERROR
    ```
    Package required but not available: ‘devtools’
    
    See section ‘The DESCRIPTION file’ in the ‘Writing R Extensions’
    manual.
    ```

# radiant.data

Version: 0.9.7

## In both

*   checking dependencies in R code ... NOTE
    ```
    Namespace in Imports field not imported from: ‘shinyFiles’
      All declared Imports should be used.
    ```

# railtrails

Version: 0.1.1

## In both

*   checking data for non-ASCII characters ... NOTE
    ```
      Note: found 1557 marked UTF-8 strings
    ```

# rattle

Version: 5.2.0

## In both

*   checking package dependencies ... NOTE
    ```
    Packages suggested but not available for checking:
      ‘cairoDevice’ ‘gWidgetsRGtk2’ ‘playwith’ ‘rggobi’ ‘RGtk2’
      ‘RGtk2Extras’
    ```

*   checking installed package size ... NOTE
    ```
      installed size is 10.9Mb
      sub-directories of 1Mb or more:
        R      4.0Mb
        data   3.0Mb
        etc    1.9Mb
        po     1.2Mb
    ```

# rclimateca

Version: 1.0.2

## In both

*   checking data for non-ASCII characters ... NOTE
    ```
      Note: found 24 marked UTF-8 strings
    ```

# rcongresso

Version: 0.4.6

## In both

*   checking examples ... ERROR
    ```
    Running examples in ‘rcongresso-Ex.R’ failed
    The error most likely occurred in:
    
    > ### Name: fetch_despesas_deputado
    > ### Title: Fetches expenditures from deputy
    > ### Aliases: fetch_despesas_deputado
    > 
    > ### ** Examples
    > 
    > gastos_abel_mesquita <- fetch_despesas_deputado(id = 178957)
    > gastos_abel_junho2017 <- fetch_despesas_deputado(id = 178957, ano = 2017, mes = 06, itens = -1)
    Error: API did not return json
    Execution halted
    ```

*   R CMD check timed out
    

# rcv

Version: 0.2.1

## In both

*   checking installed package size ... NOTE
    ```
      installed size is  5.2Mb
      sub-directories of 1Mb or more:
        data   5.0Mb
    ```

*   checking data for non-ASCII characters ... NOTE
    ```
      Note: found 6543 marked UTF-8 strings
    ```

# readabs

Version: 0.2.1

## In both

*   checking dependencies in R code ... NOTE
    ```
    Namespaces in Imports field not imported from:
      ‘sjmisc’ ‘stringr’
      All declared Imports should be used.
    ```

# readat

Version: 1.6.0

## In both

*   checking R code for possible problems ... NOTE
    ```
    sfread: no visible binding for global variable ‘header’
      (/Users/lionel/Desktop/tidyr/revdep/checks.noindex/readat/new/readat.Rcheck/00_pkg_src/readat/R/sfread.R:54)
    sfread: no visible binding for global variable ‘nrows’
      (/Users/lionel/Desktop/tidyr/revdep/checks.noindex/readat/new/readat.Rcheck/00_pkg_src/readat/R/sfread.R:54)
    Undefined global functions or variables:
      header nrows
    ```

# redcapAPI

Version: 2.2

## In both

*   checking dependencies in R code ... NOTE
    ```
    Namespaces in Imports field not imported from:
      ‘DBI’ ‘readr’
      All declared Imports should be used.
    ```

# REDCapR

Version: 0.9.8

## In both

*   checking tests ...
    ```
     ERROR
    Running the tests in ‘tests/test-all.R’ failed.
    Last 13 lines of output:
      ══ testthat results  ═══════════════════════════════════════════════════════════
      OK: 91 SKIPPED: 15 FAILED: 11
      1. Error: (unknown) (@test-metadata-read.R#4) 
      2. Error: (unknown) (@test-read-batch-longitudinal.R#4) 
      3. Error: (unknown) (@test-read-batch-simple.R#4) 
      4. Error: One Shot: Bad Uri -Not HTTPS (@test-read-errors.R#8) 
      5. Error: One Shot: Bad Uri -wrong address (@test-read-errors.R#30) 
      6. Error: Batch: Bad Uri -Not HTTPS (@test-read-errors.R#51) 
      7. Error: Batch: Bad Uri -wrong address (@test-read-errors.R#72) 
      8. Error: (unknown) (@test-read-oneshot.R#4) 
      9. Error: (unknown) (@test-read-russian.R#4) 
      1. ...
      
      Error: testthat unit tests failed
      Execution halted
    ```

*   checking package dependencies ... NOTE
    ```
    Package suggested but not available for checking: ‘devtools’
    ```

# rfbCNPJ

Version: 0.1.1

## In both

*   checking data for non-ASCII characters ... NOTE
    ```
      Note: found 27 marked UTF-8 strings
    ```

# rfishbase

Version: 2.1.2

## In both

*   checking package dependencies ... NOTE
    ```
    Package suggested but not available for checking: ‘devtools’
    ```

*   checking data for non-ASCII characters ... NOTE
    ```
      Note: found 44 marked UTF-8 strings
    ```

# rhmmer

Version: 0.1.0

## In both

*   checking dependencies in R code ... NOTE
    ```
    Namespace in Imports field not imported from: ‘dplyr’
      All declared Imports should be used.
    ```

# Rilostat

Version: 0.2.1

## In both

*   checking package dependencies ... NOTE
    ```
    Package suggested but not available for checking: ‘devtools’
    ```

# rmapzen

Version: 0.4.1

## In both

*   checking tests ...
    ```
     ERROR
    Running the tests in ‘tests/testthat.R’ failed.
    Complete output:
      > library(testthat)
      > library(rmapzen)
      > 
      > test_check("rmapzen")
      Assertion failed: (!"should never be reached"), function itemsTree, file ../../../../src/geos-3.6.1/src/index/strtree/AbstractSTRtree.cpp, line 373.
    ```

*   checking data for non-ASCII characters ... NOTE
    ```
      Note: found 31 marked UTF-8 strings
    ```

# RNeXML

Version: 2.1.2

## In both

*   checking re-building of vignette outputs ... WARNING
    ```
    ...
    Retrieving data for taxon 'Trachypithecus_pileatus'
    
    No ENTREZ API key provided
     Get one via use_entrez()
    See https://ncbiinsights.ncbi.nlm.nih.gov/2017/11/02/new-api-keys-for-the-e-utilities/
    
    Retrieving data for taxon 'Trachypithecus_vetulus'
    
    No ENTREZ API key provided
     Get one via use_entrez()
    See https://ncbiinsights.ncbi.nlm.nih.gov/2017/11/02/new-api-keys-for-the-e-utilities/
    
    Retrieving data for taxon 'Varecia_variegata'
    
    Loading required package: maps
    pandoc-citeproc: when expecting a product (:*:), encountered Object instead
    Error running filter /usr/local/bin/pandoc-citeproc:
    Filter returned error status 1
    Error: processing vignette 'simmap.Rmd' failed with diagnostics:
    pandoc document conversion failed with error 83
    Execution halted
    ```

# rODE

Version: 0.99.6

## In both

*   checking dependencies in R code ... NOTE
    ```
    Namespace in Imports field not imported from: ‘data.table’
      All declared Imports should be used.
    ```

# ropenaq

Version: 0.2.6

## In both

*   checking package dependencies ... NOTE
    ```
    Package suggested but not available for checking: ‘devtools’
    ```

# rprev

Version: 1.0.0

## In both

*   checking dependencies in R code ... NOTE
    ```
    Namespaces in Imports field not imported from:
      ‘doParallel’ ‘foreach’
      All declared Imports should be used.
    ```

# RSDA

Version: 2.0.8

## In both

*   checking dependencies in R code ... NOTE
    ```
    Namespace in Imports field not imported from: ‘randomcoloR’
      All declared Imports should be used.
    ```

# rsinaica

Version: 0.6.0

## In both

*   checking data for non-ASCII characters ... NOTE
    ```
      Note: found 467 marked UTF-8 strings
    ```

# rtable

Version: 0.1.5

## In both

*   checking package dependencies ... ERROR
    ```
    Package required but not available: ‘ReporteRs’
    
    See section ‘The DESCRIPTION file’ in the ‘Writing R Extensions’
    manual.
    ```

# RTCGA

Version: 1.10.0

## In both

*   checking examples ... ERROR
    ```
    Running examples in ‘RTCGA-Ex.R’ failed
    The error most likely occurred in:
    
    > ### Name: boxplotTCGA
    > ### Title: Create Boxplots for TCGA Datasets
    > ### Aliases: boxplotTCGA
    > 
    > ### ** Examples
    > 
    > library(RTCGA.rnaseq)
    Error in library(RTCGA.rnaseq) : 
      there is no package called ‘RTCGA.rnaseq’
    Execution halted
    ```

*   checking tests ...
    ```
     ERROR
    Running the tests in ‘tests/testthat.R’ failed.
    Complete output:
      > library(testthat)
      > library(RTCGA)
      Welcome to the RTCGA (version: 1.10.0).
      > library(RTCGA.rnaseq)
      Error in library(RTCGA.rnaseq) : 
        there is no package called 'RTCGA.rnaseq'
      Execution halted
    ```

*   checking package dependencies ... NOTE
    ```
    Packages suggested but not available for checking:
      ‘devtools’ ‘RTCGA.rnaseq’ ‘RTCGA.clinical’ ‘RTCGA.mutations’
      ‘RTCGA.RPPA’ ‘RTCGA.mRNA’ ‘RTCGA.miRNASeq’ ‘RTCGA.methylation’
      ‘RTCGA.CNV’ ‘RTCGA.PANCAN12’
    ```

*   checking R code for possible problems ... NOTE
    ```
    ...
      (/Users/lionel/Desktop/tidyr/revdep/checks.noindex/RTCGA/new/RTCGA.Rcheck/00_pkg_src/RTCGA/R/ggbiplot.R:157-161)
    ggbiplot: no visible binding for global variable ‘xvar’
      (/Users/lionel/Desktop/tidyr/revdep/checks.noindex/RTCGA/new/RTCGA.Rcheck/00_pkg_src/RTCGA/R/ggbiplot.R:157-161)
    ggbiplot: no visible binding for global variable ‘yvar’
      (/Users/lionel/Desktop/tidyr/revdep/checks.noindex/RTCGA/new/RTCGA.Rcheck/00_pkg_src/RTCGA/R/ggbiplot.R:157-161)
    ggbiplot: no visible binding for global variable ‘angle’
      (/Users/lionel/Desktop/tidyr/revdep/checks.noindex/RTCGA/new/RTCGA.Rcheck/00_pkg_src/RTCGA/R/ggbiplot.R:157-161)
    ggbiplot: no visible binding for global variable ‘hjust’
      (/Users/lionel/Desktop/tidyr/revdep/checks.noindex/RTCGA/new/RTCGA.Rcheck/00_pkg_src/RTCGA/R/ggbiplot.R:157-161)
    read.mutations: no visible binding for global variable ‘.’
      (/Users/lionel/Desktop/tidyr/revdep/checks.noindex/RTCGA/new/RTCGA.Rcheck/00_pkg_src/RTCGA/R/readTCGA.R:383)
    read.mutations: no visible binding for global variable ‘.’
      (/Users/lionel/Desktop/tidyr/revdep/checks.noindex/RTCGA/new/RTCGA.Rcheck/00_pkg_src/RTCGA/R/readTCGA.R:386)
    read.rnaseq: no visible binding for global variable ‘.’
      (/Users/lionel/Desktop/tidyr/revdep/checks.noindex/RTCGA/new/RTCGA.Rcheck/00_pkg_src/RTCGA/R/readTCGA.R:372-375)
    survivalTCGA: no visible binding for global variable ‘times’
      (/Users/lionel/Desktop/tidyr/revdep/checks.noindex/RTCGA/new/RTCGA.Rcheck/00_pkg_src/RTCGA/R/survivalTCGA.R:101-137)
    whichDateToUse: no visible binding for global variable ‘.’
      (/Users/lionel/Desktop/tidyr/revdep/checks.noindex/RTCGA/new/RTCGA.Rcheck/00_pkg_src/RTCGA/R/downloadTCGA.R:167-168)
    Undefined global functions or variables:
      . angle hjust muted times varname xvar yvar
    ```

*   checking Rd cross-references ... NOTE
    ```
    Packages unavailable to check Rd xrefs: ‘RTCGA.rnaseq’, ‘RTCGA.clinical’, ‘RTCGA.mutations’, ‘RTCGA.CNV’, ‘RTCGA.RPPA’, ‘RTCGA.mRNA’, ‘RTCGA.miRNASeq’, ‘RTCGA.methylation’, ‘devtools’
    ```

# rtimicropem

Version: 1.3

## In both

*   checking dependencies in R code ... NOTE
    ```
    Namespace in Imports field not imported from: ‘R6’
      All declared Imports should be used.
    ```

# rtrends

Version: 0.1.0

## In both

*   checking dependencies in R code ... NOTE
    ```
    Namespace in Imports field not imported from: ‘dplyr’
      All declared Imports should be used.
    ```

# RtutoR

Version: 1.2

## In both

*   checking package dependencies ... ERROR
    ```
    Package required but not available: ‘devtools’
    
    See section ‘The DESCRIPTION file’ in the ‘Writing R Extensions’
    manual.
    ```

# rubias

Version: 0.1.0

## In both

*   checking dependencies in R code ... NOTE
    ```
    Namespace in Imports field not imported from: ‘ggplot2’
      All declared Imports should be used.
    ```

# RxODE

Version: 0.8.0-8

## In both

*   checking whether package ‘RxODE’ can be installed ... ERROR
    ```
    Installation failed.
    See ‘/Users/lionel/Desktop/tidyr/revdep/checks.noindex/RxODE/new/RxODE.Rcheck/00install.out’ for details.
    ```

*   checking package dependencies ... NOTE
    ```
    Package suggested but not available for checking: ‘devtools’
    ```

## Installation

### Devel

```
* installing *source* package ‘RxODE’ ...
** package ‘RxODE’ successfully unpacked and MD5 sums checked
checking for gcc... gcc-8
checking whether the C compiler works... yes
checking for C compiler default output file name... a.out
checking for suffix of executables... 
checking whether we are cross compiling... no
checking for suffix of object files... o
checking whether we are using the GNU C compiler... yes
checking whether gcc-8 accepts -g... yes
checking for gcc-8 option to accept ISO C89... none needed
checking for gcc-8 option to support OpenMP... -fopenmp
checking whether OpenMP will work in a package... yes
configure: creating ./config.status
config.status: creating src/Makevars
--------[begin src/Makevars]--------
# -*- mode: makefile-gmake -*-
CXX_STD     = CXX11

################################################################################
## Package library flags.
PKG_LIBS    = $(LAPACK_LIBS) $(BLAS_LIBS) $(FLIBS) -fopenmp
## add -lprofiler for access to gperftools;  You also have to have -g
## https://stackoverflow.com/questions/13224322/profiling-rcpp-code-on-os-x
## -Wl,--no-as-needed -lprofiler -Wl,--as-needed
## Clang UBSAN requires -lubsan
# PKG_LIBS    = $(LAPACK_LIBS) $(BLAS_LIBS) $(FLIBS) -fopenmp -lubsan

################################################################################
## Compiling flags

## fsanitize=address = ASAN debugging with gcc
# PKG_FFLAGS  = -g -ggdb -O0 -fno-inline-functions -fsanitize=address,undefined,bounds-strict -fno-omit-frame-pointer -Wall -Wextra $(FPICFLAGS) 
# PKG_FCFLAGS = -g -ggdb -O0 -fno-inline-functions -fsanitize=address,undefined,bounds-strict -fno-omit-frame-pointer -Wall -Wextra $(FPICFLAGS)
# PKG_CFLAGS  = -g -ggdb -O0 -fno-inline-functions -fsanitize=address,undefined,bounds-strict -fno-omit-frame-pointer -Wall -Wextra -fopenmp
# PKG_CPPFLAGS = -g -ggdb -O0 -fno-inline-functions -fsanitize=address,undefined,bounds-strict -fno-omit-frame-pointer -Wall -Wextra -fopenmp

# Clang UBSAN debugging
# PKG_FFLAGS  = -g -fsanitize=address,undefined -fno-sanitize=float-divide-by-zero -fno-omit-frame-pointer $(FPICFLAGS) 
# PKG_FCFLAGS = -g -fsanitize=address,undefined -fno-sanitize=float-divide-by-zero -fno-omit-frame-pointer -frtti $(FPICFLAGS)
# PKG_CFLAGS  = -g -fsanitize=address,undefined -fno-sanitize=float-divide-by-zero -fno-omit-frame-pointer -frtti -fopenmp
# PKG_CPPFLAGS = -g -fsanitize=address,undefined -fno-sanitize=float-divide-by-zero -fno-omit-frame-pointer -frtti -fopenmp

## Standard debug for gdb and valgrind
# PKG_FFLAGS  = -g -ggdb -O0 -Wall -Wextra $(FPICFLAGS) 
# PKG_FCFLAGS = -g -ggdb -O0 -Wall -Wextra $(FPICFLAGS)
# PKG_CFLAGS  = -g -ggdb -O0 -Wall -Wextra -fopenmp
# PKG_CPPFLAGS = -g -ggdb -O0 -Wall -Wextra -fopenmp

# Release options
PKG_FFLAGS  = $(FPICFLAGS) 
PKG_FCFLAGS = $(FPICFLAGS)
PKG_CFLAGS  =  -fopenmp
PKG_CPPFLAGS = -fopenmp

SOURCES_C = call_dvode.c dop853.c tran.c omegaChol.c init.c par_solve.c cfode.c common.c corfailure.c correction.c daxpy.c ddot.c dgefa.c dgesl.c dscal.c fnorm.c idamax.c intdy.c lsoda.c methodswitch.c orderswitch.c prja.c scaleh.c solsy.c stoda.c vmnorm.c strdup_printf.c rprintf.c box.c lbfgsR.c lincmt.c
SOURCES_CPP = RcppExports.cpp WinDrive.cpp rxInv.cpp rxData.cpp eventTable.cpp inner.cpp
SOURCES_FORTAN = dlsoda.f opkda1_abbr.f opkda2.f

OBJECTS = $(SOURCES_C:.c=.o) $(SOURCES_FORTAN:.f=.o) $(SOURCES_CPP:.cpp=.o)


--------[end src/Makevars]--------
** libs
gcc-8 -I"/Library/Frameworks/R.framework/Resources/include" -DNDEBUG -fopenmp -I"/Users/lionel/Desktop/tidyr/revdep/library.noindex/RxODE/dparser/include" -I"/Users/lionel/Desktop/tidyr/revdep/library.noindex/tidyr/new/Rcpp/include" -I"/Users/lionel/Desktop/tidyr/revdep/library.noindex/RxODE/RcppArmadillo/include" -I"/Users/lionel/Desktop/tidyr/revdep/library.noindex/RxODE/PreciseSums/include" -I/usr/local/include  -fopenmp -fPIC  -mtune=core2  -O3 -c call_dvode.c -o call_dvode.o
gcc-8 -I"/Library/Frameworks/R.framework/Resources/include" -DNDEBUG -fopenmp -I"/Users/lionel/Desktop/tidyr/revdep/library.noindex/RxODE/dparser/include" -I"/Users/lionel/Desktop/tidyr/revdep/library.noindex/tidyr/new/Rcpp/include" -I"/Users/lionel/Desktop/tidyr/revdep/library.noindex/RxODE/RcppArmadillo/include" -I"/Users/lionel/Desktop/tidyr/revdep/library.noindex/RxODE/PreciseSums/include" -I/usr/local/include  -fopenmp -fPIC  -mtune=core2  -O3 -c dop853.c -o dop853.o
gcc-8 -I"/Library/Frameworks/R.framework/Resources/include" -DNDEBUG -fopenmp -I"/Users/lionel/Desktop/tidyr/revdep/library.noindex/RxODE/dparser/include" -I"/Users/lionel/Desktop/tidyr/revdep/library.noindex/tidyr/new/Rcpp/include" -I"/Users/lionel/Desktop/tidyr/revdep/library.noindex/RxODE/RcppArmadillo/include" -I"/Users/lionel/Desktop/tidyr/revdep/library.noindex/RxODE/PreciseSums/include" -I/usr/local/include  -fopenmp -fPIC  -mtune=core2  -O3 -c tran.c -o tran.o
gcc-8 -I"/Library/Frameworks/R.framework/Resources/include" -DNDEBUG -fopenmp -I"/Users/lionel/Desktop/tidyr/revdep/library.noindex/RxODE/dparser/include" -I"/Users/lionel/Desktop/tidyr/revdep/library.noindex/tidyr/new/Rcpp/include" -I"/Users/lionel/Desktop/tidyr/revdep/library.noindex/RxODE/RcppArmadillo/include" -I"/Users/lionel/Desktop/tidyr/revdep/library.noindex/RxODE/PreciseSums/include" -I/usr/local/include  -fopenmp -fPIC  -mtune=core2  -O3 -c omegaChol.c -o omegaChol.o
gcc-8 -I"/Library/Frameworks/R.framework/Resources/include" -DNDEBUG -fopenmp -I"/Users/lionel/Desktop/tidyr/revdep/library.noindex/RxODE/dparser/include" -I"/Users/lionel/Desktop/tidyr/revdep/library.noindex/tidyr/new/Rcpp/include" -I"/Users/lionel/Desktop/tidyr/revdep/library.noindex/RxODE/RcppArmadillo/include" -I"/Users/lionel/Desktop/tidyr/revdep/library.noindex/RxODE/PreciseSums/include" -I/usr/local/include  -fopenmp -fPIC  -mtune=core2  -O3 -c init.c -o init.o
gcc-8 -I"/Library/Frameworks/R.framework/Resources/include" -DNDEBUG -fopenmp -I"/Users/lionel/Desktop/tidyr/revdep/library.noindex/RxODE/dparser/include" -I"/Users/lionel/Desktop/tidyr/revdep/library.noindex/tidyr/new/Rcpp/include" -I"/Users/lionel/Desktop/tidyr/revdep/library.noindex/RxODE/RcppArmadillo/include" -I"/Users/lionel/Desktop/tidyr/revdep/library.noindex/RxODE/PreciseSums/include" -I/usr/local/include  -fopenmp -fPIC  -mtune=core2  -O3 -c par_solve.c -o par_solve.o
gcc-8 -I"/Library/Frameworks/R.framework/Resources/include" -DNDEBUG -fopenmp -I"/Users/lionel/Desktop/tidyr/revdep/library.noindex/RxODE/dparser/include" -I"/Users/lionel/Desktop/tidyr/revdep/library.noindex/tidyr/new/Rcpp/include" -I"/Users/lionel/Desktop/tidyr/revdep/library.noindex/RxODE/RcppArmadillo/include" -I"/Users/lionel/Desktop/tidyr/revdep/library.noindex/RxODE/PreciseSums/include" -I/usr/local/include  -fopenmp -fPIC  -mtune=core2  -O3 -c cfode.c -o cfode.o
gcc-8 -I"/Library/Frameworks/R.framework/Resources/include" -DNDEBUG -fopenmp -I"/Users/lionel/Desktop/tidyr/revdep/library.noindex/RxODE/dparser/include" -I"/Users/lionel/Desktop/tidyr/revdep/library.noindex/tidyr/new/Rcpp/include" -I"/Users/lionel/Desktop/tidyr/revdep/library.noindex/RxODE/RcppArmadillo/include" -I"/Users/lionel/Desktop/tidyr/revdep/library.noindex/RxODE/PreciseSums/include" -I/usr/local/include  -fopenmp -fPIC  -mtune=core2  -O3 -c common.c -o common.o
gcc-8 -I"/Library/Frameworks/R.framework/Resources/include" -DNDEBUG -fopenmp -I"/Users/lionel/Desktop/tidyr/revdep/library.noindex/RxODE/dparser/include" -I"/Users/lionel/Desktop/tidyr/revdep/library.noindex/tidyr/new/Rcpp/include" -I"/Users/lionel/Desktop/tidyr/revdep/library.noindex/RxODE/RcppArmadillo/include" -I"/Users/lionel/Desktop/tidyr/revdep/library.noindex/RxODE/PreciseSums/include" -I/usr/local/include  -fopenmp -fPIC  -mtune=core2  -O3 -c corfailure.c -o corfailure.o
gcc-8 -I"/Library/Frameworks/R.framework/Resources/include" -DNDEBUG -fopenmp -I"/Users/lionel/Desktop/tidyr/revdep/library.noindex/RxODE/dparser/include" -I"/Users/lionel/Desktop/tidyr/revdep/library.noindex/tidyr/new/Rcpp/include" -I"/Users/lionel/Desktop/tidyr/revdep/library.noindex/RxODE/RcppArmadillo/include" -I"/Users/lionel/Desktop/tidyr/revdep/library.noindex/RxODE/PreciseSums/include" -I/usr/local/include  -fopenmp -fPIC  -mtune=core2  -O3 -c correction.c -o correction.o
gcc-8 -I"/Library/Frameworks/R.framework/Resources/include" -DNDEBUG -fopenmp -I"/Users/lionel/Desktop/tidyr/revdep/library.noindex/RxODE/dparser/include" -I"/Users/lionel/Desktop/tidyr/revdep/library.noindex/tidyr/new/Rcpp/include" -I"/Users/lionel/Desktop/tidyr/revdep/library.noindex/RxODE/RcppArmadillo/include" -I"/Users/lionel/Desktop/tidyr/revdep/library.noindex/RxODE/PreciseSums/include" -I/usr/local/include  -fopenmp -fPIC  -mtune=core2  -O3 -c daxpy.c -o daxpy.o
gcc-8 -I"/Library/Frameworks/R.framework/Resources/include" -DNDEBUG -fopenmp -I"/Users/lionel/Desktop/tidyr/revdep/library.noindex/RxODE/dparser/include" -I"/Users/lionel/Desktop/tidyr/revdep/library.noindex/tidyr/new/Rcpp/include" -I"/Users/lionel/Desktop/tidyr/revdep/library.noindex/RxODE/RcppArmadillo/include" -I"/Users/lionel/Desktop/tidyr/revdep/library.noindex/RxODE/PreciseSums/include" -I/usr/local/include  -fopenmp -fPIC  -mtune=core2  -O3 -c ddot.c -o ddot.o
gcc-8 -I"/Library/Frameworks/R.framework/Resources/include" -DNDEBUG -fopenmp -I"/Users/lionel/Desktop/tidyr/revdep/library.noindex/RxODE/dparser/include" -I"/Users/lionel/Desktop/tidyr/revdep/library.noindex/tidyr/new/Rcpp/include" -I"/Users/lionel/Desktop/tidyr/revdep/library.noindex/RxODE/RcppArmadillo/include" -I"/Users/lionel/Desktop/tidyr/revdep/library.noindex/RxODE/PreciseSums/include" -I/usr/local/include  -fopenmp -fPIC  -mtune=core2  -O3 -c dgefa.c -o dgefa.o
gcc-8 -I"/Library/Frameworks/R.framework/Resources/include" -DNDEBUG -fopenmp -I"/Users/lionel/Desktop/tidyr/revdep/library.noindex/RxODE/dparser/include" -I"/Users/lionel/Desktop/tidyr/revdep/library.noindex/tidyr/new/Rcpp/include" -I"/Users/lionel/Desktop/tidyr/revdep/library.noindex/RxODE/RcppArmadillo/include" -I"/Users/lionel/Desktop/tidyr/revdep/library.noindex/RxODE/PreciseSums/include" -I/usr/local/include  -fopenmp -fPIC  -mtune=core2  -O3 -c dgesl.c -o dgesl.o
gcc-8 -I"/Library/Frameworks/R.framework/Resources/include" -DNDEBUG -fopenmp -I"/Users/lionel/Desktop/tidyr/revdep/library.noindex/RxODE/dparser/include" -I"/Users/lionel/Desktop/tidyr/revdep/library.noindex/tidyr/new/Rcpp/include" -I"/Users/lionel/Desktop/tidyr/revdep/library.noindex/RxODE/RcppArmadillo/include" -I"/Users/lionel/Desktop/tidyr/revdep/library.noindex/RxODE/PreciseSums/include" -I/usr/local/include  -fopenmp -fPIC  -mtune=core2  -O3 -c dscal.c -o dscal.o
gcc-8 -I"/Library/Frameworks/R.framework/Resources/include" -DNDEBUG -fopenmp -I"/Users/lionel/Desktop/tidyr/revdep/library.noindex/RxODE/dparser/include" -I"/Users/lionel/Desktop/tidyr/revdep/library.noindex/tidyr/new/Rcpp/include" -I"/Users/lionel/Desktop/tidyr/revdep/library.noindex/RxODE/RcppArmadillo/include" -I"/Users/lionel/Desktop/tidyr/revdep/library.noindex/RxODE/PreciseSums/include" -I/usr/local/include  -fopenmp -fPIC  -mtune=core2  -O3 -c fnorm.c -o fnorm.o
gcc-8 -I"/Library/Frameworks/R.framework/Resources/include" -DNDEBUG -fopenmp -I"/Users/lionel/Desktop/tidyr/revdep/library.noindex/RxODE/dparser/include" -I"/Users/lionel/Desktop/tidyr/revdep/library.noindex/tidyr/new/Rcpp/include" -I"/Users/lionel/Desktop/tidyr/revdep/library.noindex/RxODE/RcppArmadillo/include" -I"/Users/lionel/Desktop/tidyr/revdep/library.noindex/RxODE/PreciseSums/include" -I/usr/local/include  -fopenmp -fPIC  -mtune=core2  -O3 -c idamax.c -o idamax.o
gcc-8 -I"/Library/Frameworks/R.framework/Resources/include" -DNDEBUG -fopenmp -I"/Users/lionel/Desktop/tidyr/revdep/library.noindex/RxODE/dparser/include" -I"/Users/lionel/Desktop/tidyr/revdep/library.noindex/tidyr/new/Rcpp/include" -I"/Users/lionel/Desktop/tidyr/revdep/library.noindex/RxODE/RcppArmadillo/include" -I"/Users/lionel/Desktop/tidyr/revdep/library.noindex/RxODE/PreciseSums/include" -I/usr/local/include  -fopenmp -fPIC  -mtune=core2  -O3 -c intdy.c -o intdy.o
gcc-8 -I"/Library/Frameworks/R.framework/Resources/include" -DNDEBUG -fopenmp -I"/Users/lionel/Desktop/tidyr/revdep/library.noindex/RxODE/dparser/include" -I"/Users/lionel/Desktop/tidyr/revdep/library.noindex/tidyr/new/Rcpp/include" -I"/Users/lionel/Desktop/tidyr/revdep/library.noindex/RxODE/RcppArmadillo/include" -I"/Users/lionel/Desktop/tidyr/revdep/library.noindex/RxODE/PreciseSums/include" -I/usr/local/include  -fopenmp -fPIC  -mtune=core2  -O3 -c lsoda.c -o lsoda.o
gcc-8 -I"/Library/Frameworks/R.framework/Resources/include" -DNDEBUG -fopenmp -I"/Users/lionel/Desktop/tidyr/revdep/library.noindex/RxODE/dparser/include" -I"/Users/lionel/Desktop/tidyr/revdep/library.noindex/tidyr/new/Rcpp/include" -I"/Users/lionel/Desktop/tidyr/revdep/library.noindex/RxODE/RcppArmadillo/include" -I"/Users/lionel/Desktop/tidyr/revdep/library.noindex/RxODE/PreciseSums/include" -I/usr/local/include  -fopenmp -fPIC  -mtune=core2  -O3 -c methodswitch.c -o methodswitch.o
gcc-8 -I"/Library/Frameworks/R.framework/Resources/include" -DNDEBUG -fopenmp -I"/Users/lionel/Desktop/tidyr/revdep/library.noindex/RxODE/dparser/include" -I"/Users/lionel/Desktop/tidyr/revdep/library.noindex/tidyr/new/Rcpp/include" -I"/Users/lionel/Desktop/tidyr/revdep/library.noindex/RxODE/RcppArmadillo/include" -I"/Users/lionel/Desktop/tidyr/revdep/library.noindex/RxODE/PreciseSums/include" -I/usr/local/include  -fopenmp -fPIC  -mtune=core2  -O3 -c orderswitch.c -o orderswitch.o
gcc-8 -I"/Library/Frameworks/R.framework/Resources/include" -DNDEBUG -fopenmp -I"/Users/lionel/Desktop/tidyr/revdep/library.noindex/RxODE/dparser/include" -I"/Users/lionel/Desktop/tidyr/revdep/library.noindex/tidyr/new/Rcpp/include" -I"/Users/lionel/Desktop/tidyr/revdep/library.noindex/RxODE/RcppArmadillo/include" -I"/Users/lionel/Desktop/tidyr/revdep/library.noindex/RxODE/PreciseSums/include" -I/usr/local/include  -fopenmp -fPIC  -mtune=core2  -O3 -c prja.c -o prja.o
gcc-8 -I"/Library/Frameworks/R.framework/Resources/include" -DNDEBUG -fopenmp -I"/Users/lionel/Desktop/tidyr/revdep/library.noindex/RxODE/dparser/include" -I"/Users/lionel/Desktop/tidyr/revdep/library.noindex/tidyr/new/Rcpp/include" -I"/Users/lionel/Desktop/tidyr/revdep/library.noindex/RxODE/RcppArmadillo/include" -I"/Users/lionel/Desktop/tidyr/revdep/library.noindex/RxODE/PreciseSums/include" -I/usr/local/include  -fopenmp -fPIC  -mtune=core2  -O3 -c scaleh.c -o scaleh.o
gcc-8 -I"/Library/Frameworks/R.framework/Resources/include" -DNDEBUG -fopenmp -I"/Users/lionel/Desktop/tidyr/revdep/library.noindex/RxODE/dparser/include" -I"/Users/lionel/Desktop/tidyr/revdep/library.noindex/tidyr/new/Rcpp/include" -I"/Users/lionel/Desktop/tidyr/revdep/library.noindex/RxODE/RcppArmadillo/include" -I"/Users/lionel/Desktop/tidyr/revdep/library.noindex/RxODE/PreciseSums/include" -I/usr/local/include  -fopenmp -fPIC  -mtune=core2  -O3 -c solsy.c -o solsy.o
gcc-8 -I"/Library/Frameworks/R.framework/Resources/include" -DNDEBUG -fopenmp -I"/Users/lionel/Desktop/tidyr/revdep/library.noindex/RxODE/dparser/include" -I"/Users/lionel/Desktop/tidyr/revdep/library.noindex/tidyr/new/Rcpp/include" -I"/Users/lionel/Desktop/tidyr/revdep/library.noindex/RxODE/RcppArmadillo/include" -I"/Users/lionel/Desktop/tidyr/revdep/library.noindex/RxODE/PreciseSums/include" -I/usr/local/include  -fopenmp -fPIC  -mtune=core2  -O3 -c stoda.c -o stoda.o
gcc-8 -I"/Library/Frameworks/R.framework/Resources/include" -DNDEBUG -fopenmp -I"/Users/lionel/Desktop/tidyr/revdep/library.noindex/RxODE/dparser/include" -I"/Users/lionel/Desktop/tidyr/revdep/library.noindex/tidyr/new/Rcpp/include" -I"/Users/lionel/Desktop/tidyr/revdep/library.noindex/RxODE/RcppArmadillo/include" -I"/Users/lionel/Desktop/tidyr/revdep/library.noindex/RxODE/PreciseSums/include" -I/usr/local/include  -fopenmp -fPIC  -mtune=core2  -O3 -c vmnorm.c -o vmnorm.o
gcc-8 -I"/Library/Frameworks/R.framework/Resources/include" -DNDEBUG -fopenmp -I"/Users/lionel/Desktop/tidyr/revdep/library.noindex/RxODE/dparser/include" -I"/Users/lionel/Desktop/tidyr/revdep/library.noindex/tidyr/new/Rcpp/include" -I"/Users/lionel/Desktop/tidyr/revdep/library.noindex/RxODE/RcppArmadillo/include" -I"/Users/lionel/Desktop/tidyr/revdep/library.noindex/RxODE/PreciseSums/include" -I/usr/local/include  -fopenmp -fPIC  -mtune=core2  -O3 -c strdup_printf.c -o strdup_printf.o
gcc-8 -I"/Library/Frameworks/R.framework/Resources/include" -DNDEBUG -fopenmp -I"/Users/lionel/Desktop/tidyr/revdep/library.noindex/RxODE/dparser/include" -I"/Users/lionel/Desktop/tidyr/revdep/library.noindex/tidyr/new/Rcpp/include" -I"/Users/lionel/Desktop/tidyr/revdep/library.noindex/RxODE/RcppArmadillo/include" -I"/Users/lionel/Desktop/tidyr/revdep/library.noindex/RxODE/PreciseSums/include" -I/usr/local/include  -fopenmp -fPIC  -mtune=core2  -O3 -c rprintf.c -o rprintf.o
gcc-8 -I"/Library/Frameworks/R.framework/Resources/include" -DNDEBUG -fopenmp -I"/Users/lionel/Desktop/tidyr/revdep/library.noindex/RxODE/dparser/include" -I"/Users/lionel/Desktop/tidyr/revdep/library.noindex/tidyr/new/Rcpp/include" -I"/Users/lionel/Desktop/tidyr/revdep/library.noindex/RxODE/RcppArmadillo/include" -I"/Users/lionel/Desktop/tidyr/revdep/library.noindex/RxODE/PreciseSums/include" -I/usr/local/include  -fopenmp -fPIC  -mtune=core2  -O3 -c box.c -o box.o
gcc-8 -I"/Library/Frameworks/R.framework/Resources/include" -DNDEBUG -fopenmp -I"/Users/lionel/Desktop/tidyr/revdep/library.noindex/RxODE/dparser/include" -I"/Users/lionel/Desktop/tidyr/revdep/library.noindex/tidyr/new/Rcpp/include" -I"/Users/lionel/Desktop/tidyr/revdep/library.noindex/RxODE/RcppArmadillo/include" -I"/Users/lionel/Desktop/tidyr/revdep/library.noindex/RxODE/PreciseSums/include" -I/usr/local/include  -fopenmp -fPIC  -mtune=core2  -O3 -c lbfgsR.c -o lbfgsR.o
gcc-8 -I"/Library/Frameworks/R.framework/Resources/include" -DNDEBUG -fopenmp -I"/Users/lionel/Desktop/tidyr/revdep/library.noindex/RxODE/dparser/include" -I"/Users/lionel/Desktop/tidyr/revdep/library.noindex/tidyr/new/Rcpp/include" -I"/Users/lionel/Desktop/tidyr/revdep/library.noindex/RxODE/RcppArmadillo/include" -I"/Users/lionel/Desktop/tidyr/revdep/library.noindex/RxODE/PreciseSums/include" -I/usr/local/include  -fopenmp -fPIC  -mtune=core2  -O3 -c lincmt.c -o lincmt.o
gfortran-7  -fPIC  -fPIC  -g -O2  -c dlsoda.f -o dlsoda.o
make: gfortran-7: No such file or directory
make: *** [dlsoda.o] Error 1
make: *** Waiting for unfinished jobs....
ERROR: compilation failed for package ‘RxODE’
* removing ‘/Users/lionel/Desktop/tidyr/revdep/checks.noindex/RxODE/new/RxODE.Rcheck/RxODE’

```
### CRAN

```
* installing *source* package ‘RxODE’ ...
** package ‘RxODE’ successfully unpacked and MD5 sums checked
checking for gcc... gcc-8
checking whether the C compiler works... yes
checking for C compiler default output file name... a.out
checking for suffix of executables... 
checking whether we are cross compiling... no
checking for suffix of object files... o
checking whether we are using the GNU C compiler... yes
checking whether gcc-8 accepts -g... yes
checking for gcc-8 option to accept ISO C89... none needed
checking for gcc-8 option to support OpenMP... -fopenmp
checking whether OpenMP will work in a package... yes
configure: creating ./config.status
config.status: creating src/Makevars
--------[begin src/Makevars]--------
# -*- mode: makefile-gmake -*-
CXX_STD     = CXX11

################################################################################
## Package library flags.
PKG_LIBS    = $(LAPACK_LIBS) $(BLAS_LIBS) $(FLIBS) -fopenmp
## add -lprofiler for access to gperftools;  You also have to have -g
## https://stackoverflow.com/questions/13224322/profiling-rcpp-code-on-os-x
## -Wl,--no-as-needed -lprofiler -Wl,--as-needed
## Clang UBSAN requires -lubsan
# PKG_LIBS    = $(LAPACK_LIBS) $(BLAS_LIBS) $(FLIBS) -fopenmp -lubsan

################################################################################
## Compiling flags

## fsanitize=address = ASAN debugging with gcc
# PKG_FFLAGS  = -g -ggdb -O0 -fno-inline-functions -fsanitize=address,undefined,bounds-strict -fno-omit-frame-pointer -Wall -Wextra $(FPICFLAGS) 
# PKG_FCFLAGS = -g -ggdb -O0 -fno-inline-functions -fsanitize=address,undefined,bounds-strict -fno-omit-frame-pointer -Wall -Wextra $(FPICFLAGS)
# PKG_CFLAGS  = -g -ggdb -O0 -fno-inline-functions -fsanitize=address,undefined,bounds-strict -fno-omit-frame-pointer -Wall -Wextra -fopenmp
# PKG_CPPFLAGS = -g -ggdb -O0 -fno-inline-functions -fsanitize=address,undefined,bounds-strict -fno-omit-frame-pointer -Wall -Wextra -fopenmp

# Clang UBSAN debugging
# PKG_FFLAGS  = -g -fsanitize=address,undefined -fno-sanitize=float-divide-by-zero -fno-omit-frame-pointer $(FPICFLAGS) 
# PKG_FCFLAGS = -g -fsanitize=address,undefined -fno-sanitize=float-divide-by-zero -fno-omit-frame-pointer -frtti $(FPICFLAGS)
# PKG_CFLAGS  = -g -fsanitize=address,undefined -fno-sanitize=float-divide-by-zero -fno-omit-frame-pointer -frtti -fopenmp
# PKG_CPPFLAGS = -g -fsanitize=address,undefined -fno-sanitize=float-divide-by-zero -fno-omit-frame-pointer -frtti -fopenmp

## Standard debug for gdb and valgrind
# PKG_FFLAGS  = -g -ggdb -O0 -Wall -Wextra $(FPICFLAGS) 
# PKG_FCFLAGS = -g -ggdb -O0 -Wall -Wextra $(FPICFLAGS)
# PKG_CFLAGS  = -g -ggdb -O0 -Wall -Wextra -fopenmp
# PKG_CPPFLAGS = -g -ggdb -O0 -Wall -Wextra -fopenmp

# Release options
PKG_FFLAGS  = $(FPICFLAGS) 
PKG_FCFLAGS = $(FPICFLAGS)
PKG_CFLAGS  =  -fopenmp
PKG_CPPFLAGS = -fopenmp

SOURCES_C = call_dvode.c dop853.c tran.c omegaChol.c init.c par_solve.c cfode.c common.c corfailure.c correction.c daxpy.c ddot.c dgefa.c dgesl.c dscal.c fnorm.c idamax.c intdy.c lsoda.c methodswitch.c orderswitch.c prja.c scaleh.c solsy.c stoda.c vmnorm.c strdup_printf.c rprintf.c box.c lbfgsR.c lincmt.c
SOURCES_CPP = RcppExports.cpp WinDrive.cpp rxInv.cpp rxData.cpp eventTable.cpp inner.cpp
SOURCES_FORTAN = dlsoda.f opkda1_abbr.f opkda2.f

OBJECTS = $(SOURCES_C:.c=.o) $(SOURCES_FORTAN:.f=.o) $(SOURCES_CPP:.cpp=.o)


--------[end src/Makevars]--------
** libs
gcc-8 -I"/Library/Frameworks/R.framework/Resources/include" -DNDEBUG -fopenmp -I"/Users/lionel/Desktop/tidyr/revdep/library.noindex/RxODE/dparser/include" -I"/Users/lionel/Desktop/tidyr/revdep/library.noindex/tidyr/old/Rcpp/include" -I"/Users/lionel/Desktop/tidyr/revdep/library.noindex/RxODE/RcppArmadillo/include" -I"/Users/lionel/Desktop/tidyr/revdep/library.noindex/RxODE/PreciseSums/include" -I/usr/local/include  -fopenmp -fPIC  -mtune=core2  -O3 -c call_dvode.c -o call_dvode.o
gcc-8 -I"/Library/Frameworks/R.framework/Resources/include" -DNDEBUG -fopenmp -I"/Users/lionel/Desktop/tidyr/revdep/library.noindex/RxODE/dparser/include" -I"/Users/lionel/Desktop/tidyr/revdep/library.noindex/tidyr/old/Rcpp/include" -I"/Users/lionel/Desktop/tidyr/revdep/library.noindex/RxODE/RcppArmadillo/include" -I"/Users/lionel/Desktop/tidyr/revdep/library.noindex/RxODE/PreciseSums/include" -I/usr/local/include  -fopenmp -fPIC  -mtune=core2  -O3 -c dop853.c -o dop853.o
gcc-8 -I"/Library/Frameworks/R.framework/Resources/include" -DNDEBUG -fopenmp -I"/Users/lionel/Desktop/tidyr/revdep/library.noindex/RxODE/dparser/include" -I"/Users/lionel/Desktop/tidyr/revdep/library.noindex/tidyr/old/Rcpp/include" -I"/Users/lionel/Desktop/tidyr/revdep/library.noindex/RxODE/RcppArmadillo/include" -I"/Users/lionel/Desktop/tidyr/revdep/library.noindex/RxODE/PreciseSums/include" -I/usr/local/include  -fopenmp -fPIC  -mtune=core2  -O3 -c tran.c -o tran.o
gcc-8 -I"/Library/Frameworks/R.framework/Resources/include" -DNDEBUG -fopenmp -I"/Users/lionel/Desktop/tidyr/revdep/library.noindex/RxODE/dparser/include" -I"/Users/lionel/Desktop/tidyr/revdep/library.noindex/tidyr/old/Rcpp/include" -I"/Users/lionel/Desktop/tidyr/revdep/library.noindex/RxODE/RcppArmadillo/include" -I"/Users/lionel/Desktop/tidyr/revdep/library.noindex/RxODE/PreciseSums/include" -I/usr/local/include  -fopenmp -fPIC  -mtune=core2  -O3 -c omegaChol.c -o omegaChol.o
gcc-8 -I"/Library/Frameworks/R.framework/Resources/include" -DNDEBUG -fopenmp -I"/Users/lionel/Desktop/tidyr/revdep/library.noindex/RxODE/dparser/include" -I"/Users/lionel/Desktop/tidyr/revdep/library.noindex/tidyr/old/Rcpp/include" -I"/Users/lionel/Desktop/tidyr/revdep/library.noindex/RxODE/RcppArmadillo/include" -I"/Users/lionel/Desktop/tidyr/revdep/library.noindex/RxODE/PreciseSums/include" -I/usr/local/include  -fopenmp -fPIC  -mtune=core2  -O3 -c init.c -o init.o
gcc-8 -I"/Library/Frameworks/R.framework/Resources/include" -DNDEBUG -fopenmp -I"/Users/lionel/Desktop/tidyr/revdep/library.noindex/RxODE/dparser/include" -I"/Users/lionel/Desktop/tidyr/revdep/library.noindex/tidyr/old/Rcpp/include" -I"/Users/lionel/Desktop/tidyr/revdep/library.noindex/RxODE/RcppArmadillo/include" -I"/Users/lionel/Desktop/tidyr/revdep/library.noindex/RxODE/PreciseSums/include" -I/usr/local/include  -fopenmp -fPIC  -mtune=core2  -O3 -c par_solve.c -o par_solve.o
gcc-8 -I"/Library/Frameworks/R.framework/Resources/include" -DNDEBUG -fopenmp -I"/Users/lionel/Desktop/tidyr/revdep/library.noindex/RxODE/dparser/include" -I"/Users/lionel/Desktop/tidyr/revdep/library.noindex/tidyr/old/Rcpp/include" -I"/Users/lionel/Desktop/tidyr/revdep/library.noindex/RxODE/RcppArmadillo/include" -I"/Users/lionel/Desktop/tidyr/revdep/library.noindex/RxODE/PreciseSums/include" -I/usr/local/include  -fopenmp -fPIC  -mtune=core2  -O3 -c cfode.c -o cfode.o
gcc-8 -I"/Library/Frameworks/R.framework/Resources/include" -DNDEBUG -fopenmp -I"/Users/lionel/Desktop/tidyr/revdep/library.noindex/RxODE/dparser/include" -I"/Users/lionel/Desktop/tidyr/revdep/library.noindex/tidyr/old/Rcpp/include" -I"/Users/lionel/Desktop/tidyr/revdep/library.noindex/RxODE/RcppArmadillo/include" -I"/Users/lionel/Desktop/tidyr/revdep/library.noindex/RxODE/PreciseSums/include" -I/usr/local/include  -fopenmp -fPIC  -mtune=core2  -O3 -c common.c -o common.o
gcc-8 -I"/Library/Frameworks/R.framework/Resources/include" -DNDEBUG -fopenmp -I"/Users/lionel/Desktop/tidyr/revdep/library.noindex/RxODE/dparser/include" -I"/Users/lionel/Desktop/tidyr/revdep/library.noindex/tidyr/old/Rcpp/include" -I"/Users/lionel/Desktop/tidyr/revdep/library.noindex/RxODE/RcppArmadillo/include" -I"/Users/lionel/Desktop/tidyr/revdep/library.noindex/RxODE/PreciseSums/include" -I/usr/local/include  -fopenmp -fPIC  -mtune=core2  -O3 -c corfailure.c -o corfailure.o
gcc-8 -I"/Library/Frameworks/R.framework/Resources/include" -DNDEBUG -fopenmp -I"/Users/lionel/Desktop/tidyr/revdep/library.noindex/RxODE/dparser/include" -I"/Users/lionel/Desktop/tidyr/revdep/library.noindex/tidyr/old/Rcpp/include" -I"/Users/lionel/Desktop/tidyr/revdep/library.noindex/RxODE/RcppArmadillo/include" -I"/Users/lionel/Desktop/tidyr/revdep/library.noindex/RxODE/PreciseSums/include" -I/usr/local/include  -fopenmp -fPIC  -mtune=core2  -O3 -c correction.c -o correction.o
gcc-8 -I"/Library/Frameworks/R.framework/Resources/include" -DNDEBUG -fopenmp -I"/Users/lionel/Desktop/tidyr/revdep/library.noindex/RxODE/dparser/include" -I"/Users/lionel/Desktop/tidyr/revdep/library.noindex/tidyr/old/Rcpp/include" -I"/Users/lionel/Desktop/tidyr/revdep/library.noindex/RxODE/RcppArmadillo/include" -I"/Users/lionel/Desktop/tidyr/revdep/library.noindex/RxODE/PreciseSums/include" -I/usr/local/include  -fopenmp -fPIC  -mtune=core2  -O3 -c daxpy.c -o daxpy.o
gcc-8 -I"/Library/Frameworks/R.framework/Resources/include" -DNDEBUG -fopenmp -I"/Users/lionel/Desktop/tidyr/revdep/library.noindex/RxODE/dparser/include" -I"/Users/lionel/Desktop/tidyr/revdep/library.noindex/tidyr/old/Rcpp/include" -I"/Users/lionel/Desktop/tidyr/revdep/library.noindex/RxODE/RcppArmadillo/include" -I"/Users/lionel/Desktop/tidyr/revdep/library.noindex/RxODE/PreciseSums/include" -I/usr/local/include  -fopenmp -fPIC  -mtune=core2  -O3 -c ddot.c -o ddot.o
gcc-8 -I"/Library/Frameworks/R.framework/Resources/include" -DNDEBUG -fopenmp -I"/Users/lionel/Desktop/tidyr/revdep/library.noindex/RxODE/dparser/include" -I"/Users/lionel/Desktop/tidyr/revdep/library.noindex/tidyr/old/Rcpp/include" -I"/Users/lionel/Desktop/tidyr/revdep/library.noindex/RxODE/RcppArmadillo/include" -I"/Users/lionel/Desktop/tidyr/revdep/library.noindex/RxODE/PreciseSums/include" -I/usr/local/include  -fopenmp -fPIC  -mtune=core2  -O3 -c dgefa.c -o dgefa.o
gcc-8 -I"/Library/Frameworks/R.framework/Resources/include" -DNDEBUG -fopenmp -I"/Users/lionel/Desktop/tidyr/revdep/library.noindex/RxODE/dparser/include" -I"/Users/lionel/Desktop/tidyr/revdep/library.noindex/tidyr/old/Rcpp/include" -I"/Users/lionel/Desktop/tidyr/revdep/library.noindex/RxODE/RcppArmadillo/include" -I"/Users/lionel/Desktop/tidyr/revdep/library.noindex/RxODE/PreciseSums/include" -I/usr/local/include  -fopenmp -fPIC  -mtune=core2  -O3 -c dgesl.c -o dgesl.o
gcc-8 -I"/Library/Frameworks/R.framework/Resources/include" -DNDEBUG -fopenmp -I"/Users/lionel/Desktop/tidyr/revdep/library.noindex/RxODE/dparser/include" -I"/Users/lionel/Desktop/tidyr/revdep/library.noindex/tidyr/old/Rcpp/include" -I"/Users/lionel/Desktop/tidyr/revdep/library.noindex/RxODE/RcppArmadillo/include" -I"/Users/lionel/Desktop/tidyr/revdep/library.noindex/RxODE/PreciseSums/include" -I/usr/local/include  -fopenmp -fPIC  -mtune=core2  -O3 -c dscal.c -o dscal.o
gcc-8 -I"/Library/Frameworks/R.framework/Resources/include" -DNDEBUG -fopenmp -I"/Users/lionel/Desktop/tidyr/revdep/library.noindex/RxODE/dparser/include" -I"/Users/lionel/Desktop/tidyr/revdep/library.noindex/tidyr/old/Rcpp/include" -I"/Users/lionel/Desktop/tidyr/revdep/library.noindex/RxODE/RcppArmadillo/include" -I"/Users/lionel/Desktop/tidyr/revdep/library.noindex/RxODE/PreciseSums/include" -I/usr/local/include  -fopenmp -fPIC  -mtune=core2  -O3 -c fnorm.c -o fnorm.o
gcc-8 -I"/Library/Frameworks/R.framework/Resources/include" -DNDEBUG -fopenmp -I"/Users/lionel/Desktop/tidyr/revdep/library.noindex/RxODE/dparser/include" -I"/Users/lionel/Desktop/tidyr/revdep/library.noindex/tidyr/old/Rcpp/include" -I"/Users/lionel/Desktop/tidyr/revdep/library.noindex/RxODE/RcppArmadillo/include" -I"/Users/lionel/Desktop/tidyr/revdep/library.noindex/RxODE/PreciseSums/include" -I/usr/local/include  -fopenmp -fPIC  -mtune=core2  -O3 -c idamax.c -o idamax.o
gcc-8 -I"/Library/Frameworks/R.framework/Resources/include" -DNDEBUG -fopenmp -I"/Users/lionel/Desktop/tidyr/revdep/library.noindex/RxODE/dparser/include" -I"/Users/lionel/Desktop/tidyr/revdep/library.noindex/tidyr/old/Rcpp/include" -I"/Users/lionel/Desktop/tidyr/revdep/library.noindex/RxODE/RcppArmadillo/include" -I"/Users/lionel/Desktop/tidyr/revdep/library.noindex/RxODE/PreciseSums/include" -I/usr/local/include  -fopenmp -fPIC  -mtune=core2  -O3 -c intdy.c -o intdy.o
gcc-8 -I"/Library/Frameworks/R.framework/Resources/include" -DNDEBUG -fopenmp -I"/Users/lionel/Desktop/tidyr/revdep/library.noindex/RxODE/dparser/include" -I"/Users/lionel/Desktop/tidyr/revdep/library.noindex/tidyr/old/Rcpp/include" -I"/Users/lionel/Desktop/tidyr/revdep/library.noindex/RxODE/RcppArmadillo/include" -I"/Users/lionel/Desktop/tidyr/revdep/library.noindex/RxODE/PreciseSums/include" -I/usr/local/include  -fopenmp -fPIC  -mtune=core2  -O3 -c lsoda.c -o lsoda.o
gcc-8 -I"/Library/Frameworks/R.framework/Resources/include" -DNDEBUG -fopenmp -I"/Users/lionel/Desktop/tidyr/revdep/library.noindex/RxODE/dparser/include" -I"/Users/lionel/Desktop/tidyr/revdep/library.noindex/tidyr/old/Rcpp/include" -I"/Users/lionel/Desktop/tidyr/revdep/library.noindex/RxODE/RcppArmadillo/include" -I"/Users/lionel/Desktop/tidyr/revdep/library.noindex/RxODE/PreciseSums/include" -I/usr/local/include  -fopenmp -fPIC  -mtune=core2  -O3 -c methodswitch.c -o methodswitch.o
gcc-8 -I"/Library/Frameworks/R.framework/Resources/include" -DNDEBUG -fopenmp -I"/Users/lionel/Desktop/tidyr/revdep/library.noindex/RxODE/dparser/include" -I"/Users/lionel/Desktop/tidyr/revdep/library.noindex/tidyr/old/Rcpp/include" -I"/Users/lionel/Desktop/tidyr/revdep/library.noindex/RxODE/RcppArmadillo/include" -I"/Users/lionel/Desktop/tidyr/revdep/library.noindex/RxODE/PreciseSums/include" -I/usr/local/include  -fopenmp -fPIC  -mtune=core2  -O3 -c orderswitch.c -o orderswitch.o
gcc-8 -I"/Library/Frameworks/R.framework/Resources/include" -DNDEBUG -fopenmp -I"/Users/lionel/Desktop/tidyr/revdep/library.noindex/RxODE/dparser/include" -I"/Users/lionel/Desktop/tidyr/revdep/library.noindex/tidyr/old/Rcpp/include" -I"/Users/lionel/Desktop/tidyr/revdep/library.noindex/RxODE/RcppArmadillo/include" -I"/Users/lionel/Desktop/tidyr/revdep/library.noindex/RxODE/PreciseSums/include" -I/usr/local/include  -fopenmp -fPIC  -mtune=core2  -O3 -c prja.c -o prja.o
gcc-8 -I"/Library/Frameworks/R.framework/Resources/include" -DNDEBUG -fopenmp -I"/Users/lionel/Desktop/tidyr/revdep/library.noindex/RxODE/dparser/include" -I"/Users/lionel/Desktop/tidyr/revdep/library.noindex/tidyr/old/Rcpp/include" -I"/Users/lionel/Desktop/tidyr/revdep/library.noindex/RxODE/RcppArmadillo/include" -I"/Users/lionel/Desktop/tidyr/revdep/library.noindex/RxODE/PreciseSums/include" -I/usr/local/include  -fopenmp -fPIC  -mtune=core2  -O3 -c scaleh.c -o scaleh.o
gcc-8 -I"/Library/Frameworks/R.framework/Resources/include" -DNDEBUG -fopenmp -I"/Users/lionel/Desktop/tidyr/revdep/library.noindex/RxODE/dparser/include" -I"/Users/lionel/Desktop/tidyr/revdep/library.noindex/tidyr/old/Rcpp/include" -I"/Users/lionel/Desktop/tidyr/revdep/library.noindex/RxODE/RcppArmadillo/include" -I"/Users/lionel/Desktop/tidyr/revdep/library.noindex/RxODE/PreciseSums/include" -I/usr/local/include  -fopenmp -fPIC  -mtune=core2  -O3 -c solsy.c -o solsy.o
gcc-8 -I"/Library/Frameworks/R.framework/Resources/include" -DNDEBUG -fopenmp -I"/Users/lionel/Desktop/tidyr/revdep/library.noindex/RxODE/dparser/include" -I"/Users/lionel/Desktop/tidyr/revdep/library.noindex/tidyr/old/Rcpp/include" -I"/Users/lionel/Desktop/tidyr/revdep/library.noindex/RxODE/RcppArmadillo/include" -I"/Users/lionel/Desktop/tidyr/revdep/library.noindex/RxODE/PreciseSums/include" -I/usr/local/include  -fopenmp -fPIC  -mtune=core2  -O3 -c stoda.c -o stoda.o
gcc-8 -I"/Library/Frameworks/R.framework/Resources/include" -DNDEBUG -fopenmp -I"/Users/lionel/Desktop/tidyr/revdep/library.noindex/RxODE/dparser/include" -I"/Users/lionel/Desktop/tidyr/revdep/library.noindex/tidyr/old/Rcpp/include" -I"/Users/lionel/Desktop/tidyr/revdep/library.noindex/RxODE/RcppArmadillo/include" -I"/Users/lionel/Desktop/tidyr/revdep/library.noindex/RxODE/PreciseSums/include" -I/usr/local/include  -fopenmp -fPIC  -mtune=core2  -O3 -c vmnorm.c -o vmnorm.o
gcc-8 -I"/Library/Frameworks/R.framework/Resources/include" -DNDEBUG -fopenmp -I"/Users/lionel/Desktop/tidyr/revdep/library.noindex/RxODE/dparser/include" -I"/Users/lionel/Desktop/tidyr/revdep/library.noindex/tidyr/old/Rcpp/include" -I"/Users/lionel/Desktop/tidyr/revdep/library.noindex/RxODE/RcppArmadillo/include" -I"/Users/lionel/Desktop/tidyr/revdep/library.noindex/RxODE/PreciseSums/include" -I/usr/local/include  -fopenmp -fPIC  -mtune=core2  -O3 -c strdup_printf.c -o strdup_printf.o
gcc-8 -I"/Library/Frameworks/R.framework/Resources/include" -DNDEBUG -fopenmp -I"/Users/lionel/Desktop/tidyr/revdep/library.noindex/RxODE/dparser/include" -I"/Users/lionel/Desktop/tidyr/revdep/library.noindex/tidyr/old/Rcpp/include" -I"/Users/lionel/Desktop/tidyr/revdep/library.noindex/RxODE/RcppArmadillo/include" -I"/Users/lionel/Desktop/tidyr/revdep/library.noindex/RxODE/PreciseSums/include" -I/usr/local/include  -fopenmp -fPIC  -mtune=core2  -O3 -c rprintf.c -o rprintf.o
gcc-8 -I"/Library/Frameworks/R.framework/Resources/include" -DNDEBUG -fopenmp -I"/Users/lionel/Desktop/tidyr/revdep/library.noindex/RxODE/dparser/include" -I"/Users/lionel/Desktop/tidyr/revdep/library.noindex/tidyr/old/Rcpp/include" -I"/Users/lionel/Desktop/tidyr/revdep/library.noindex/RxODE/RcppArmadillo/include" -I"/Users/lionel/Desktop/tidyr/revdep/library.noindex/RxODE/PreciseSums/include" -I/usr/local/include  -fopenmp -fPIC  -mtune=core2  -O3 -c box.c -o box.o
gcc-8 -I"/Library/Frameworks/R.framework/Resources/include" -DNDEBUG -fopenmp -I"/Users/lionel/Desktop/tidyr/revdep/library.noindex/RxODE/dparser/include" -I"/Users/lionel/Desktop/tidyr/revdep/library.noindex/tidyr/old/Rcpp/include" -I"/Users/lionel/Desktop/tidyr/revdep/library.noindex/RxODE/RcppArmadillo/include" -I"/Users/lionel/Desktop/tidyr/revdep/library.noindex/RxODE/PreciseSums/include" -I/usr/local/include  -fopenmp -fPIC  -mtune=core2  -O3 -c lbfgsR.c -o lbfgsR.o
gcc-8 -I"/Library/Frameworks/R.framework/Resources/include" -DNDEBUG -fopenmp -I"/Users/lionel/Desktop/tidyr/revdep/library.noindex/RxODE/dparser/include" -I"/Users/lionel/Desktop/tidyr/revdep/library.noindex/tidyr/old/Rcpp/include" -I"/Users/lionel/Desktop/tidyr/revdep/library.noindex/RxODE/RcppArmadillo/include" -I"/Users/lionel/Desktop/tidyr/revdep/library.noindex/RxODE/PreciseSums/include" -I/usr/local/include  -fopenmp -fPIC  -mtune=core2  -O3 -c lincmt.c -o lincmt.o
gfortran-7  -fPIC  -fPIC  -g -O2  -c dlsoda.f -o dlsoda.o
make: gfortran-7: No such file or directory
make: *** [dlsoda.o] Error 1
make: *** Waiting for unfinished jobs....
ERROR: compilation failed for package ‘RxODE’
* removing ‘/Users/lionel/Desktop/tidyr/revdep/checks.noindex/RxODE/old/RxODE.Rcheck/RxODE’

```
# SanzCircos

Version: 0.1.0

## In both

*   checking dependencies in R code ... NOTE
    ```
    Namespaces in Imports field not imported from:
      ‘purrr’ ‘tidyr’
      All declared Imports should be used.
    ```

# scanstatistics

Version: 1.0.1

## In both

*   checking re-building of vignette outputs ... WARNING
    ```
    Error in re-building vignettes:
      ...
    pandoc-citeproc: when expecting a product (:*:), encountered Object instead
    Error running filter /usr/local/bin/pandoc-citeproc:
    Filter returned error status 1
    Error: processing vignette 'introduction.Rmd' failed with diagnostics:
    pandoc document conversion failed with error 83
    Execution halted
    ```

# SCORPIUS

Version: 1.0.2

## In both

*   checking whether package ‘SCORPIUS’ can be installed ... ERROR
    ```
    Installation failed.
    See ‘/Users/lionel/Desktop/tidyr/revdep/checks.noindex/SCORPIUS/new/SCORPIUS.Rcheck/00install.out’ for details.
    ```

## Installation

### Devel

```
* installing *source* package ‘SCORPIUS’ ...
** package ‘SCORPIUS’ successfully unpacked and MD5 sums checked
** R
** data
*** moving datasets to lazyload DB
** inst
** byte-compile and prepare package for lazy loading
Error in loadNamespace(j <- i[[1L]], c(lib.loc, .libPaths()), versionCheck = vI[[j]]) : 
  there is no package called ‘devtools’
ERROR: lazy loading failed for package ‘SCORPIUS’
* removing ‘/Users/lionel/Desktop/tidyr/revdep/checks.noindex/SCORPIUS/new/SCORPIUS.Rcheck/SCORPIUS’

```
### CRAN

```
* installing *source* package ‘SCORPIUS’ ...
** package ‘SCORPIUS’ successfully unpacked and MD5 sums checked
** R
** data
*** moving datasets to lazyload DB
** inst
** byte-compile and prepare package for lazy loading
Error in loadNamespace(j <- i[[1L]], c(lib.loc, .libPaths()), versionCheck = vI[[j]]) : 
  there is no package called ‘devtools’
ERROR: lazy loading failed for package ‘SCORPIUS’
* removing ‘/Users/lionel/Desktop/tidyr/revdep/checks.noindex/SCORPIUS/old/SCORPIUS.Rcheck/SCORPIUS’

```
# sdStaf

Version: 1.0.0

## In both

*   checking dependencies in R code ... NOTE
    ```
    Namespaces in Imports field not imported from:
      ‘rgdal’ ‘rgeos’ ‘tidyr’
      All declared Imports should be used.
    ```

# sejmRP

Version: 1.3.4

## In both

*   checking dependencies in R code ... NOTE
    ```
    Namespaces in Imports field not imported from:
      ‘cluster’ ‘factoextra’ ‘tidyr’
      All declared Imports should be used.
    ```

# seqCAT

Version: 1.2.1

## In both

*   checking re-building of vignette outputs ... WARNING
    ```
    ...
    Reading VCF file ...
    Creating SNV profile ...
    Created and stored SNV profile for "HKE3" in [hke3_profile.txt].
    Reading profile for HKE3 in file hke3_profile.txt ...
    Comparing HCT116 and HKE3 ...
    Comparing HCT116 and HCT116 [1 / 6]
    Comparing HCT116 and HKE3 [2 / 6]
    Comparing HCT116 and RKO [3 / 6]
    Comparing HKE3 and HKE3 [4 / 6]
    Comparing HKE3 and RKO [5 / 6]
    Comparing RKO and RKO [6 / 6]
    Comparing COSMIC.HCT116 and COSMIC.HCT116 ...
    Comparing COSMIC.HCT116 and HCT116 [1 / 3]
    Comparing COSMIC.HCT116 and HKE3 [2 / 3]
    Comparing COSMIC.HCT116 and RKO [3 / 3]
    pandoc-citeproc: when expecting a product (:*:), encountered Object instead
    Error running filter /usr/local/bin/pandoc-citeproc:
    Filter returned error status 1
    Error: processing vignette 'seqCAT.Rmd' failed with diagnostics:
    pandoc document conversion failed with error 83
    Execution halted
    ```

# Seurat

Version: 2.3.4

## In both

*   checking tests ...
    ```
     ERROR
    Running the tests in ‘tests/testthat.R’ failed.
    Last 13 lines of output:
      30: tryCatchList(expr, classes, parentenv, handlers)
      31: tryCatch(withCallingHandlers({    eval(code, test_env)    if (!handled && !is.null(test)) {        skip_empty()    }}, expectation = handle_expectation, skip = handle_skip, warning = handle_warning,     message = handle_message, error = handle_error), error = handle_fatal,     skip = function(e) {    })
      32: test_code(NULL, exprs, env)
      33: source_file(path, new.env(parent = env), chdir = TRUE, wrap = wrap)
      34: force(code)
      35: with_reporter(reporter = reporter, start_end_reporter = start_end_reporter,     {        lister$start_file(basename(path))        source_file(path, new.env(parent = env), chdir = TRUE,             wrap = wrap)        end_context()    })
      36: FUN(X[[i]], ...)
      37: lapply(paths, test_file, env = env, reporter = current_reporter,     start_end_reporter = FALSE, load_helpers = FALSE, wrap = wrap)
      38: force(code)
      39: with_reporter(reporter = current_reporter, results <- lapply(paths,     test_file, env = env, reporter = current_reporter, start_end_reporter = FALSE,     load_helpers = FALSE, wrap = wrap))
      40: test_files(paths, reporter = reporter, env = env, stop_on_failure = stop_on_failure,     stop_on_warning = stop_on_warning, wrap = wrap)
      41: test_dir(path = test_path, reporter = reporter, env = env, filter = filter,     ..., stop_on_failure = stop_on_failure, stop_on_warning = stop_on_warning,     wrap = wrap)
      42: test_package_dir(package = package, test_path = test_path, filter = filter,     reporter = reporter, ..., stop_on_failure = stop_on_failure,     stop_on_warning = stop_on_warning, wrap = wrap)
      43: test_check("Seurat")
      An irrecoverable exception occurred. R is aborting now ...
    ```

*   checking package dependencies ... NOTE
    ```
    Package suggested but not available for checking: ‘loomR’
    ```

# sf

Version: 0.7-1

## In both

*   checking tests ...
    ```
    ...
    < POINT (0 0)
    ---
    > POINT (0 -7.081155e-10)
     ERROR
    Running the tests in ‘tests/gdal_geom.R’ failed.
    Last 13 lines of output:
      address 0x80, cause 'memory not mapped'
      
      Traceback:
       1: CPL_gdal_segmentize(x, dfMaxLength)
       2: st_sfc(CPL_gdal_segmentize(x, dfMaxLength), crs = st_crs(x))
       3: st_segmentize.sfc(st_geometry(x), dfMaxLength, ...)
       4: st_segmentize(st_geometry(x), dfMaxLength, ...)
       5: st_segmentize.sf(nc_tr, -0.1)
       6: st_segmentize(nc_tr, -0.1)
       7: doTryCatch(return(expr), name, parentenv, handler)
       8: tryCatchOne(expr, names, parentenv, handlers[[1L]])
       9: tryCatchList(expr, classes, parentenv, handlers)
      10: tryCatch(expr, error = function(e) {    call <- conditionCall(e)    if (!is.null(call)) {        if (identical(call[[1L]], quote(doTryCatch)))             call <- sys.call(-4L)        dcall <- deparse(call)[1L]        prefix <- paste("Error in", dcall, ": ")        LONG <- 75L        sm <- strsplit(conditionMessage(e), "\n")[[1L]]        w <- 14L + nchar(dcall, type = "w") + nchar(sm[1L], type = "w")        if (is.na(w))             w <- 14L + nchar(dcall, type = "b") + nchar(sm[1L],                 type = "b")        if (w > LONG)             prefix <- paste0(prefix, "\n  ")    }    else prefix <- "Error : "    msg <- paste0(prefix, conditionMessage(e), "\n")    .Internal(seterrmessage(msg[1L]))    if (!silent && isTRUE(getOption("show.error.messages"))) {        cat(msg, file = outFile)        .Internal(printDeferredWarnings())    }    invisible(structure(msg, class = "try-error", condition = e))})
      11: try(x <- st_segmentize(nc_tr, -0.1))
      An irrecoverable exception occurred. R is aborting now ...
    ```

*   checking package dependencies ... NOTE
    ```
    Package suggested but not available for checking: ‘stars’
    ```

*   checking installed package size ... NOTE
    ```
      installed size is 18.9Mb
      sub-directories of 1Mb or more:
        R        2.1Mb
        doc     11.8Mb
        sqlite   1.5Mb
    ```

# SIBER

Version: 2.1.3

## In both

*   checking examples ... ERROR
    ```
    ...
    > ### ** Examples
    > 
    > x <- stats::rnorm(50)
    > y <- stats::rnorm(50)
    > parms <- list()
    > parms$n.iter <- 2 * 10^3
    > parms$n.burnin <- 500
    > parms$n.thin <- 2     
    > parms$n.chains <- 2    
    > priors <- list()
    > priors$R <- 1 * diag(2)
    > priors$k <- 2
    > priors$tau.mu <- 1.0E-3
    > fitEllipse(x, y, parms, priors)
    Error: .onLoad failed in loadNamespace() for 'rjags', details:
      call: dyn.load(file, DLLpath = DLLpath, ...)
      error: unable to load shared object '/Users/lionel/Desktop/tidyr/revdep/library.noindex/SIBER/rjags/libs/rjags.so':
      dlopen(/Users/lionel/Desktop/tidyr/revdep/library.noindex/SIBER/rjags/libs/rjags.so, 10): Library not loaded: /usr/local/lib/libjags.4.dylib
      Referenced from: /Users/lionel/Desktop/tidyr/revdep/library.noindex/SIBER/rjags/libs/rjags.so
      Reason: image not found
    Execution halted
    ```

*   checking re-building of vignette outputs ... WARNING
    ```
    Error in re-building vignettes:
      ...
    Warning in engine$weave(file, quiet = quiet, encoding = enc) :
      The vignette engine knitr::rmarkdown is not available, because the rmarkdown package is not installed. Please install it.
    Quitting from lines 74-93 (Centroid-Vectors.Rmd) 
    Error: processing vignette 'Centroid-Vectors.Rmd' failed with diagnostics:
    .onLoad failed in loadNamespace() for 'rjags', details:
      call: dyn.load(file, DLLpath = DLLpath, ...)
      error: unable to load shared object '/Users/lionel/Desktop/tidyr/revdep/library.noindex/SIBER/rjags/libs/rjags.so':
      dlopen(/Users/lionel/Desktop/tidyr/revdep/library.noindex/SIBER/rjags/libs/rjags.so, 10): Library not loaded: /usr/local/lib/libjags.4.dylib
      Referenced from: /Users/lionel/Desktop/tidyr/revdep/library.noindex/SIBER/rjags/libs/rjags.so
      Reason: image not found
    Execution halted
    ```

*   checking dependencies in R code ... NOTE
    ```
    Namespaces in Imports field not imported from:
      ‘dplyr’ ‘ggplot2’ ‘viridis’
      All declared Imports should be used.
    ```

# sidrar

Version: 0.2.4

## In both

*   checking dependencies in R code ... NOTE
    ```
    Namespace in Imports field not imported from: ‘dplyr’
      All declared Imports should be used.
    ```

# simmer

Version: 4.0.1

## In both

*   checking tests ...
    ```
     ERROR
    Running the tests in ‘tests/testthat.R’ failed.
    Last 13 lines of output:
      41: tryCatchList(expr, classes, parentenv, handlers)
      42: tryCatch(withCallingHandlers({    eval(code, test_env)    if (!handled && !is.null(test)) {        skip_empty()    }}, expectation = handle_expectation, skip = handle_skip, warning = handle_warning,     message = handle_message, error = handle_error), error = handle_fatal,     skip = function(e) {    })
      43: test_code(NULL, exprs, env)
      44: source_file(path, new.env(parent = env), chdir = TRUE, wrap = wrap)
      45: force(code)
      46: with_reporter(reporter = reporter, start_end_reporter = start_end_reporter,     {        lister$start_file(basename(path))        source_file(path, new.env(parent = env), chdir = TRUE,             wrap = wrap)        end_context()    })
      47: FUN(X[[i]], ...)
      48: lapply(paths, test_file, env = env, reporter = current_reporter,     start_end_reporter = FALSE, load_helpers = FALSE, wrap = wrap)
      49: force(code)
      50: with_reporter(reporter = current_reporter, results <- lapply(paths,     test_file, env = env, reporter = current_reporter, start_end_reporter = FALSE,     load_helpers = FALSE, wrap = wrap))
      51: test_files(paths, reporter = reporter, env = env, stop_on_failure = stop_on_failure,     stop_on_warning = stop_on_warning, wrap = wrap)
      52: test_dir(path = test_path, reporter = reporter, env = env, filter = filter,     ..., stop_on_failure = stop_on_failure, stop_on_warning = stop_on_warning,     wrap = wrap)
      53: test_package_dir(package = package, test_path = test_path, filter = filter,     reporter = reporter, ..., stop_on_failure = stop_on_failure,     stop_on_warning = stop_on_warning, wrap = wrap)
      54: test_check("simmer")
      An irrecoverable exception occurred. R is aborting now ...
    ```

# simTool

Version: 1.1.0

## Newly broken

*   checking tests ...
    ```
     ERROR
    Running the tests in ‘tests/testthat.R’ failed.
    Last 13 lines of output:
      ── 2. Error: (unknown) (@test_eval_tibbles.R#68)  ──────────────────────────────
      cannot open the connection
      1: parallel::makeCluster(rep("localhost", 2), type = "PSOCK") at testthat/test_eval_tibbles.R:68
      2: makePSOCKcluster(names = spec, ...)
      3: newPSOCKnode(names[[i]], options = options, rank = i)
      4: socketConnection("localhost", port = port, server = TRUE, blocking = TRUE, open = "a+b", 
             timeout = timeout)
      
      ══ testthat results  ═══════════════════════════════════════════════════════════
      OK: 30 SKIPPED: 0 FAILED: 2
      1. Error: (unknown) (@test_evalGrids.R#3) 
      2. Error: (unknown) (@test_eval_tibbles.R#68) 
      
      Error: testthat unit tests failed
      Execution halted
    ```

# SingleCaseES

Version: 0.4.0

## In both

*   checking re-building of vignette outputs ... WARNING
    ```
    Error in re-building vignettes:
      ...
    pandoc-citeproc: when expecting a product (:*:), encountered Object instead
    Error running filter /usr/local/bin/pandoc-citeproc:
    Filter returned error status 1
    Error: processing vignette 'Effect-size-definitions.Rmd' failed with diagnostics:
    pandoc document conversion failed with error 83
    Execution halted
    ```

# singscore

Version: 1.0.0

## In both

*   checking examples ... ERROR
    ```
    Running examples in ‘singscore-Ex.R’ failed
    The error most likely occurred in:
    
    > ### Name: projectScoreLandscape
    > ### Title: Project data on the landscape plot obtained from
    > ###   'plotScoreLandscape()'
    > ### Aliases: projectScoreLandscape
    > 
    > ### ** Examples
    > 
    > ranked <- rankGenes(toy_expr_se)
    > scoredf1 <- simpleScore(ranked, upSet = toy_gs_up, downSet = toy_gs_dn)
    > scoredf2 <- simpleScore(ranked, upSet = toy_gs_up)
    > psl <- plotScoreLandscape(scoredf1, scoredf2)
    > projectScoreLandscape(psl,scoredf1, scoredf2)
    Warning: Ignoring unknown aesthetics: text
    Error in FUN(X[[i]], ...) : object 'Signature 1' not found
    Calls: <Anonymous> ... ggplot_build.ggplot -> by_layer -> f -> <Anonymous> -> f -> lapply -> FUN
    Execution halted
    ```

*   checking re-building of vignette outputs ... WARNING
    ```
    ...
    
    Loading required package: XML
    
    Attaching package: 'XML'
    
    The following object is masked from 'package:tools':
    
        toHTML
    
    Loading required package: graph
    
    Attaching package: 'graph'
    
    The following object is masked from 'package:XML':
    
        addNode
    
    Quitting from lines 174-182 (singscore.Rmd) 
    Error: processing vignette 'singscore.Rmd' failed with diagnostics:
    object 'tcga-EPI' not found
    Execution halted
    ```

# sjstats

Version: 0.17.1

## In both

*   checking Rd cross-references ... NOTE
    ```
    Package unavailable to check Rd xrefs: ‘arm’
    ```

# sparklyr

Version: 0.9.2

## In both

*   checking installed package size ... NOTE
    ```
      installed size is  7.1Mb
      sub-directories of 1Mb or more:
        R      4.1Mb
        java   1.9Mb
    ```

# staRdom

Version: 1.0.8

## In both

*   checking re-building of vignette outputs ... WARNING
    ```
    Error in re-building vignettes:
      ...
    Writing 18 Bibtex entries ... OK
    Results written to file 'references.bib'
    pandoc-citeproc: when expecting a product (:*:), encountered Object instead
    Error running filter /usr/local/bin/pandoc-citeproc:
    Filter returned error status 1
    Error: processing vignette 'Basic_analysis_of_DOM_samples.Rmd' failed with diagnostics:
    pandoc document conversion failed with error 83
    Execution halted
    ```

*   checking dependencies in R code ... NOTE
    ```
    Namespaces in Imports field not imported from:
      ‘readr’ ‘tools’
      All declared Imports should be used.
    ```

# starmie

Version: 0.1.2

## In both

*   checking installed package size ... NOTE
    ```
      installed size is  7.2Mb
      sub-directories of 1Mb or more:
        doc       1.1Mb
        extdata   4.9Mb
    ```

*   checking dependencies in R code ... NOTE
    ```
    Namespace in Imports field not imported from: ‘MCMCpack’
      All declared Imports should be used.
    ```

# statsDK

Version: 0.1.1

## In both

*   checking dependencies in R code ... NOTE
    ```
    Namespaces in Imports field not imported from:
      ‘dplyr’ ‘ggplot2’ ‘stringr’
      All declared Imports should be used.
    ```

# stormwindmodel

Version: 0.1.1

## In both

*   checking re-building of vignette outputs ... WARNING
    ```
    ...
        filter, lag
    
    The following objects are masked from 'package:base':
    
        intersect, setdiff, setequal, union
    
    
    Attaching package: 'gridExtra'
    
    The following object is masked from 'package:dplyr':
    
        combine
    
    Linking to GEOS 3.6.3, GDAL 2.3.1, PROJ 5.1.0
    Warning: Removed 1 rows containing missing values (geom_path).
    pandoc-citeproc: when expecting a product (:*:), encountered Object instead
    Error running filter /usr/local/bin/pandoc-citeproc:
    Filter returned error status 1
    Error: processing vignette 'Details.Rmd' failed with diagnostics:
    pandoc document conversion failed with error 83
    Execution halted
    ```

# STRMPS

Version: 0.5.8

## In both

*   checking package dependencies ... NOTE
    ```
    Package suggested but not available for checking: ‘STRaitRazoR’
    ```

# subSeq

Version: 1.10.0

## In both

*   checking R code for possible problems ... NOTE
    ```
    ...
      (/Users/lionel/Desktop/tidyr/revdep/checks.noindex/subSeq/new/subSeq.Rcheck/00_pkg_src/subSeq/R/summary.subsamples.R:127-129)
    summary.subsamples: no visible binding for global variable ‘percent’
      (/Users/lionel/Desktop/tidyr/revdep/checks.noindex/subSeq/new/subSeq.Rcheck/00_pkg_src/subSeq/R/summary.subsamples.R:127-129)
    summary.subsamples: no visible binding for global variable ‘proportion’
      (/Users/lionel/Desktop/tidyr/revdep/checks.noindex/subSeq/new/subSeq.Rcheck/00_pkg_src/subSeq/R/summary.subsamples.R:127-129)
    summary.subsamples: no visible binding for global variable ‘method’
      (/Users/lionel/Desktop/tidyr/revdep/checks.noindex/subSeq/new/subSeq.Rcheck/00_pkg_src/subSeq/R/summary.subsamples.R:127-129)
    voomLimma: no visible global function definition for ‘model.matrix’
      (/Users/lionel/Desktop/tidyr/revdep/checks.noindex/subSeq/new/subSeq.Rcheck/00_pkg_src/subSeq/R/handlers.R:41)
    Undefined global functions or variables:
      . ID average.depth average.value coefficient cor count cov depth
      estFDP method metric model.matrix o.coefficient o.lfdr o.padj
      p.adjust padj percent plot proportion pvalue rFDP rbinom replication
      selectMethod significant valid value var
    Consider adding
      importFrom("graphics", "plot")
      importFrom("methods", "selectMethod")
      importFrom("stats", "cor", "cov", "model.matrix", "p.adjust", "rbinom",
                 "var")
    to your NAMESPACE file (and ensure that your DESCRIPTION Imports
    field contains 'methods').
    ```

# sugrrants

Version: 0.1.6

## In both

*   checking re-building of vignette outputs ... WARNING
    ```
    ...
    Error in re-building vignettes:
      ...
    
    Attaching package: 'dplyr'
    
    The following objects are masked from 'package:stats':
    
        filter, lag
    
    The following objects are masked from 'package:base':
    
        intersect, setdiff, setequal, union
    
    Loading required package: viridisLite
    Loading required package: ggplot2
    pandoc-citeproc: when expecting a product (:*:), encountered Object instead
    Error running filter /usr/local/bin/pandoc-citeproc:
    Filter returned error status 1
    Error: processing vignette 'frame-calendar.Rmd' failed with diagnostics:
    pandoc document conversion failed with error 83
    Execution halted
    ```

# SummarizedBenchmark

Version: 1.0.4

## In both

*   checking re-building of vignette outputs ... WARNING
    ```
    ...
    ==================================================
    downloaded 1.6 MB
    
    trying URL 'https://www.ebi.ac.uk/arrayexpress/files/E-MTAB-4119/E-MTAB-4119.processed.2.zip'
    Content type 'application/zip' length 541401 bytes (528 KB)
    ==================================================
    downloaded 528 KB
    
    
    Attaching package: 'rnaseqcomp'
    
    The following object is masked from 'package:SummarizedBenchmark':
    
        plotROC
    
    pandoc-citeproc: when expecting a product (:*:), encountered Object instead
    Error running filter /usr/local/bin/pandoc-citeproc:
    Filter returned error status 1
    Error: processing vignette 'QuantificationBenchmark.Rmd' failed with diagnostics:
    pandoc document conversion failed with error 83
    Execution halted
    ```

*   checking package dependencies ... NOTE
    ```
    Package suggested but not available for checking: ‘scRNAseq’
    
    Depends: includes the non-default packages:
      ‘tidyr’ ‘SummarizedExperiment’ ‘S4Vectors’ ‘BiocGenerics’
      ‘UpSetR’ ‘rlang’ ‘stringr’ ‘BiocParallel’ ‘ggplot2’ ‘mclust’
      ‘dplyr’
    Adding so many packages to the search path is excessive and
    importing selectively is preferable.
    ```

*   checking installed package size ... NOTE
    ```
      installed size is 12.8Mb
      sub-directories of 1Mb or more:
        data   9.0Mb
        doc    3.3Mb
    ```

*   checking dependencies in R code ... NOTE
    ```
    Unexported object imported by a ':::' call: ‘BiocGenerics:::replaceSlots’
      See the note in ?`:::` about the use of this operator.
    ```

*   checking R code for possible problems ... NOTE
    ```
    .list2mat : <anonymous>: no visible binding for global variable
      ‘.method’
      (/Users/lionel/Desktop/tidyr/revdep/checks.noindex/SummarizedBenchmark/new/SummarizedBenchmark.Rcheck/00_pkg_src/SummarizedBenchmark/R/buildBench.R:275)
    .list2mat : <anonymous>: no visible binding for global variable ‘.val’
      (/Users/lionel/Desktop/tidyr/revdep/checks.noindex/SummarizedBenchmark/new/SummarizedBenchmark.Rcheck/00_pkg_src/SummarizedBenchmark/R/buildBench.R:275)
    .list2mat : <anonymous>: no visible binding for global variable ‘.id’
      (/Users/lionel/Desktop/tidyr/revdep/checks.noindex/SummarizedBenchmark/new/SummarizedBenchmark.Rcheck/00_pkg_src/SummarizedBenchmark/R/buildBench.R:276-277)
    plotROC: no visible binding for global variable ‘FDR’
      (/Users/lionel/Desktop/tidyr/revdep/checks.noindex/SummarizedBenchmark/new/SummarizedBenchmark.Rcheck/00_pkg_src/SummarizedBenchmark/R/PlottingFunctions.R:81-82)
    plotROC: no visible binding for global variable ‘TPR’
      (/Users/lionel/Desktop/tidyr/revdep/checks.noindex/SummarizedBenchmark/new/SummarizedBenchmark.Rcheck/00_pkg_src/SummarizedBenchmark/R/PlottingFunctions.R:81-82)
    plotROC: no visible binding for global variable ‘method’
      (/Users/lionel/Desktop/tidyr/revdep/checks.noindex/SummarizedBenchmark/new/SummarizedBenchmark.Rcheck/00_pkg_src/SummarizedBenchmark/R/PlottingFunctions.R:81-82)
    Undefined global functions or variables:
      .id .method .val FDR TPR method
    ```

# sunburstR

Version: 2.1.0

## In both

*   checking package dependencies ... NOTE
    ```
    Package which this enhances but not available for checking: ‘treemap’
    ```

# survminer

Version: 0.4.3

## In both

*   checking installed package size ... NOTE
    ```
      installed size is  6.4Mb
      sub-directories of 1Mb or more:
        R     1.0Mb
        doc   5.1Mb
    ```

# survtmle

Version: 1.1.0

## In both

*   checking re-building of vignette outputs ... WARNING
    ```
    Error in re-building vignettes:
      ...
    pandoc-citeproc: when expecting a product (:*:), encountered Object instead
    Error running filter /usr/local/bin/pandoc-citeproc:
    Filter returned error status 1
    Error: processing vignette 'survtmle_intro.Rmd' failed with diagnostics:
    pandoc document conversion failed with error 83
    Execution halted
    ```

# sweep

Version: 0.2.1.1

## In both

*   checking package dependencies ... ERROR
    ```
    Package required but not available: ‘devtools’
    
    See section ‘The DESCRIPTION file’ in the ‘Writing R Extensions’
    manual.
    ```

# switchde

Version: 1.6.0

## In both

*   checking for hidden files and directories ... NOTE
    ```
    Found the following hidden files and directories:
      .travis.yml
    These were most likely included in error. See section ‘Package
    structure’ in the ‘Writing R Extensions’ manual.
    ```

# SWMPrExtension

Version: 0.3.16

## In both

*   checking installed package size ... NOTE
    ```
      installed size is  5.2Mb
      sub-directories of 1Mb or more:
        data   4.0Mb
    ```

*   checking dependencies in R code ... NOTE
    ```
    Namespace in Imports field not imported from: ‘rgeos’
      All declared Imports should be used.
    ```

# syuzhet

Version: 1.0.4

## In both

*   checking package dependencies ... NOTE
    ```
    Package suggested but not available for checking: ‘devtools’
    ```

*   checking installed package size ... NOTE
    ```
      installed size is  5.8Mb
      sub-directories of 1Mb or more:
        R         2.1Mb
        extdata   3.1Mb
    ```

# taxa

Version: 0.3.1

## In both

*   checking installed package size ... NOTE
    ```
      installed size is  5.3Mb
      sub-directories of 1Mb or more:
        R      2.0Mb
        data   1.1Mb
        doc    1.7Mb
    ```

*   checking dependencies in R code ... NOTE
    ```
    Namespaces in Imports field not imported from:
      ‘knitr’ ‘lazyeval’ ‘rlang’ ‘tidyr’
      All declared Imports should be used.
    ```

# teachingApps

Version: 1.0.4

## In both

*   checking package dependencies ... ERROR
    ```
    Package required but not available: ‘devtools’
    
    See section ‘The DESCRIPTION file’ in the ‘Writing R Extensions’
    manual.
    ```

# temperatureresponse

Version: 0.1

## In both

*   checking dependencies in R code ... NOTE
    ```
    Namespaces in Imports field not imported from:
      ‘nlme’ ‘tidyr’
      All declared Imports should be used.
    ```

# textreuse

Version: 0.1.4

## In both

*   checking Rd cross-references ... NOTE
    ```
    Package unavailable to check Rd xrefs: ‘tm’
    ```

# TFEA.ChIP

Version: 1.0.0

## In both

*   checking package dependencies ... ERROR
    ```
    Packages required but not available:
      ‘TxDb.Hsapiens.UCSC.hg19.knownGene’ ‘org.Hs.eg.db’
    
    See section ‘The DESCRIPTION file’ in the ‘Writing R Extensions’
    manual.
    ```

# theseus

Version: 0.1.0

## In both

*   checking package dependencies ... ERROR
    ```
    Package required but not available: ‘vegan’
    
    See section ‘The DESCRIPTION file’ in the ‘Writing R Extensions’
    manual.
    ```

# thinkr

Version: 0.13

## In both

*   checking package dependencies ... ERROR
    ```
    Package required but not available: ‘devtools’
    
    See section ‘The DESCRIPTION file’ in the ‘Writing R Extensions’
    manual.
    ```

# tidybayes

Version: 1.0.3

## In both

*   checking tests ...
    ```
     ERROR
    Running the tests in ‘tests/testthat.R’ failed.
    Last 13 lines of output:
             modules = modules, factories = factories, jags = jags, call.setup = TRUE, method = method, 
             mutate = mutate)
      10: setup.jags(model = outmodel, monitor = outmonitor, data = outdata, n.chains = n.chains, 
             inits = outinits, modules = modules, factories = factories, response = response, 
             fitted = fitted, residual = residual, jags = jags, method = method, mutate = mutate)
      11: loadandcheckrjags()
      12: stop("Loading the rjags package failed (diagnostics are given above this error message)", 
             call. = FALSE)
      
      ══ testthat results  ═══════════════════════════════════════════════════════════
      OK: 268 SKIPPED: 2 FAILED: 1
      1. Error: tidy_draws works with runjags (@test.tidy_draws.R#87) 
      
      Error: testthat unit tests failed
      Execution halted
    ```

# tidygraph

Version: 1.1.0

## In both

*   checking tests ...
    ```
     ERROR
    Running the tests in ‘tests/testthat.R’ failed.
    Last 13 lines of output:
      14: mutate_as_tbl(.data, !!!dot) at /Users/lionel/Desktop/tidyr/revdep/checks.noindex/tidygraph/new/tidygraph.Rcheck/00_pkg_src/tidygraph/R/mutate.R:7
      15: mutate(d_tmp, ...) at /Users/lionel/Desktop/tidyr/revdep/checks.noindex/tidygraph/new/tidygraph.Rcheck/00_pkg_src/tidygraph/R/mutate.R:43
      16: mutate.tbl_df(d_tmp, ...)
      17: mutate_impl(.data, dots)
      18: group_optimal()
      19: membership(cluster_optimal(graph = .G(), weights = weights)) at /Users/lionel/Desktop/tidyr/revdep/checks.noindex/tidygraph/new/tidygraph.Rcheck/00_pkg_src/tidygraph/R/group.R:124
      20: cluster_optimal(graph = .G(), weights = weights) at /Users/lionel/Desktop/tidyr/revdep/checks.noindex/tidygraph/new/tidygraph.Rcheck/00_pkg_src/tidygraph/R/group.R:124
      
      ══ testthat results  ═══════════════════════════════════════════════════════════
      OK: 268 SKIPPED: 0 FAILED: 2
      1. Error: grouping returns integer vector (@test-group.R#14) 
      2. Error: grouping returns integer of correct length (@test-group.R#31) 
      
      Error: testthat unit tests failed
      Execution halted
    ```

# tidyhydat

Version: 0.3.5

## In both

*   checking tests ...
    ```
     ERROR
    Running the tests in ‘tests/testthat.R’ failed.
    Last 13 lines of output:
      8: realtime_stations()
      9: httr::GET(realtime_link, httr::user_agent("https://github.com/ropensci/tidyhydat")) at /Users/lionel/Desktop/tidyr/revdep/checks.noindex/tidyhydat/new/tidyhydat.Rcheck/00_pkg_src/tidyhydat/R/realtime.R:115
      10: request_perform(req, hu$handle$handle)
      11: request_fetch(req$output, req$url, handle)
      12: request_fetch.write_memory(req$output, req$url, handle)
      13: curl::curl_fetch_memory(url, handle = handle)
      
      ══ testthat results  ═══════════════════════════════════════════════════════════
      OK: 197 SKIPPED: 17 FAILED: 3
      1. Error: realtime_network_meta returns a data frame (@test_realtime_network.R#4) 
      2. Error: search_stn_number returns a dataframe (@test_search.R#4) 
      3. Error: search_stn_name returns a dataframe (@test_search.R#9) 
      
      Error: testthat unit tests failed
      Execution halted
    ```

# tidyLPA

Version: 0.2.2

## In both

*   checking package dependencies ... NOTE
    ```
    Package suggested but not available for checking: ‘devtools’
    ```

# tidyquant

Version: 0.5.5

## In both

*   checking installed package size ... NOTE
    ```
      installed size is  5.4Mb
      sub-directories of 1Mb or more:
        doc   4.1Mb
    ```

*   checking dependencies in R code ... NOTE
    ```
    Unable to find any JVMs matching version "(null)".
    No Java runtime present, try --request to install.
    ```

# tidytext

Version: 0.2.0

## In both

*   checking dependencies in R code ... NOTE
    ```
    Unable to find any JVMs matching version "(null)".
    No Java runtime present, try --request to install.
    ```

# tidytransit

Version: 0.3.4

## In both

*   checking installed package size ... NOTE
    ```
      installed size is  5.4Mb
      sub-directories of 1Mb or more:
        extdata   4.4Mb
    ```

*   checking dependencies in R code ... NOTE
    ```
    Namespaces in Imports field not imported from:
      ‘here’ ‘htmltools’ ‘scales’ ‘stringr’
      All declared Imports should be used.
    ```

*   checking data for non-ASCII characters ... NOTE
    ```
      Note: found 41 marked UTF-8 strings
    ```

# tidyverse

Version: 1.2.1

## In both

*   checking dependencies in R code ... NOTE
    ```
    Namespaces in Imports field not imported from:
      ‘dbplyr’ ‘reprex’ ‘rlang’
      All declared Imports should be used.
    ```

# tidyxl

Version: 1.0.3

## In both

*   checking tests ...
    ```
     ERROR
    Running the tests in ‘tests/testthat.R’ failed.
    Last 13 lines of output:
      31: tryCatchList(expr, classes, parentenv, handlers)
      32: tryCatch(withCallingHandlers({    eval(code, test_env)    if (!handled && !is.null(test)) {        skip_empty()    }}, expectation = handle_expectation, skip = handle_skip, warning = handle_warning,     message = handle_message, error = handle_error), error = handle_fatal,     skip = function(e) {    })
      33: test_code(NULL, exprs, env)
      34: source_file(path, new.env(parent = env), chdir = TRUE, wrap = wrap)
      35: force(code)
      36: with_reporter(reporter = reporter, start_end_reporter = start_end_reporter,     {        lister$start_file(basename(path))        source_file(path, new.env(parent = env), chdir = TRUE,             wrap = wrap)        end_context()    })
      37: FUN(X[[i]], ...)
      38: lapply(paths, test_file, env = env, reporter = current_reporter,     start_end_reporter = FALSE, load_helpers = FALSE, wrap = wrap)
      39: force(code)
      40: with_reporter(reporter = current_reporter, results <- lapply(paths,     test_file, env = env, reporter = current_reporter, start_end_reporter = FALSE,     load_helpers = FALSE, wrap = wrap))
      41: test_files(paths, reporter = reporter, env = env, stop_on_failure = stop_on_failure,     stop_on_warning = stop_on_warning, wrap = wrap)
      42: test_dir(path = test_path, reporter = reporter, env = env, filter = filter,     ..., stop_on_failure = stop_on_failure, stop_on_warning = stop_on_warning,     wrap = wrap)
      43: test_package_dir(package = package, test_path = test_path, filter = filter,     reporter = reporter, ..., stop_on_failure = stop_on_failure,     stop_on_warning = stop_on_warning, wrap = wrap)
      44: test_check("tidyxl")
      An irrecoverable exception occurred. R is aborting now ...
    ```

# tilegramsR

Version: 0.2.0

## In both

*   checking dependencies in R code ... NOTE
    ```
    Namespace in Imports field not imported from: ‘sp’
      All declared Imports should be used.
    ```

*   checking data for non-ASCII characters ... NOTE
    ```
      Note: found 341 marked UTF-8 strings
    ```

# timetk

Version: 0.1.1.1

## In both

*   checking package dependencies ... ERROR
    ```
    Package required but not available: ‘devtools’
    
    See section ‘The DESCRIPTION file’ in the ‘Writing R Extensions’
    manual.
    ```

# TissueEnrich

Version: 1.0.7

## In both

*   checking re-building of vignette outputs ... WARNING
    ```
    ...
    
    Loading required package: graph
    
    Attaching package: 'graph'
    
    The following object is masked from 'package:XML':
    
        addNode
    
    Read 97 items
    No background list provided. Using all the
                    genes as background.
    Read 97 items
    No background list provided. Using all the
                    genes as background.
    pandoc-citeproc: when expecting a product (:*:), encountered Object instead
    Error running filter /usr/local/bin/pandoc-citeproc:
    Filter returned error status 1
    Error: processing vignette 'TissueEnrich.Rmd' failed with diagnostics:
    pandoc document conversion failed with error 83
    Execution halted
    ```

# tmap

Version: 2.1-1

## In both

*   checking installed package size ... NOTE
    ```
      installed size is  6.8Mb
      sub-directories of 1Mb or more:
        R      3.0Mb
        data   1.4Mb
        doc    2.1Mb
    ```

# toxplot

Version: 0.1.1

## In both

*   checking package dependencies ... NOTE
    ```
    Package suggested but not available for checking: ‘devtools’
    ```

*   checking dependencies in R code ... NOTE
    ```
    Namespace in Imports field not imported from: ‘tidyr’
      All declared Imports should be used.
    ```

# TPP

Version: 3.8.5

## In both

*   R CMD check timed out
    

*   checking installed package size ... NOTE
    ```
      installed size is 15.1Mb
      sub-directories of 1Mb or more:
        R              2.0Mb
        data           1.9Mb
        example_data   8.0Mb
        test_data      1.9Mb
    ```

*   checking dependencies in R code ... NOTE
    ```
    Namespace in Imports field not imported from: ‘broom’
      All declared Imports should be used.
    Unexported objects imported by ':::' calls:
      ‘doParallel:::.options’ ‘mefa:::rep.data.frame’
      See the note in ?`:::` about the use of this operator.
    ```

*   checking R code for possible problems ... NOTE
    ```
    File ‘TPP/R/TPP.R’:
      .onLoad calls:
        packageStartupMessage(msgText, "\n")
    
    See section ‘Good practice’ in '?.onAttach'.
    
    plot_fSta_distribution: no visible binding for global variable
      ‘..density..’
      (/Users/lionel/Desktop/tidyr/revdep/checks.noindex/TPP/new/TPP.Rcheck/00_pkg_src/TPP/R/plot_fSta_distribution.R:19-28)
    plot_pVal_distribution: no visible binding for global variable
      ‘..density..’
      (/Users/lionel/Desktop/tidyr/revdep/checks.noindex/TPP/new/TPP.Rcheck/00_pkg_src/TPP/R/plot_pVal_distribution.R:22-31)
    Undefined global functions or variables:
      ..density..
    ```

# translateSPSS2R

Version: 1.0.0

## In both

*   checking R code for possible problems ... NOTE
    ```
    ...
    xpssTtest: no visible global function definition for ‘t.test’
      (/Users/lionel/Desktop/tidyr/revdep/checks.noindex/translateSPSS2R/new/translateSPSS2R.Rcheck/00_pkg_src/translateSPSS2R/R/xpssTtest.R:617)
    xpssTtest: no visible global function definition for ‘na.omit’
      (/Users/lionel/Desktop/tidyr/revdep/checks.noindex/translateSPSS2R/new/translateSPSS2R.Rcheck/00_pkg_src/translateSPSS2R/R/xpssTtest.R:627)
    xpssTtest: no visible global function definition for ‘sd’
      (/Users/lionel/Desktop/tidyr/revdep/checks.noindex/translateSPSS2R/new/translateSPSS2R.Rcheck/00_pkg_src/translateSPSS2R/R/xpssTtest.R:628)
    xpssTtest: no visible global function definition for ‘na.omit’
      (/Users/lionel/Desktop/tidyr/revdep/checks.noindex/translateSPSS2R/new/translateSPSS2R.Rcheck/00_pkg_src/translateSPSS2R/R/xpssTtest.R:628)
    xpssTtest: no visible global function definition for ‘cor.test’
      (/Users/lionel/Desktop/tidyr/revdep/checks.noindex/translateSPSS2R/new/translateSPSS2R.Rcheck/00_pkg_src/translateSPSS2R/R/xpssTtest.R:631)
    Undefined global functions or variables:
      anova as.formula complete.cases cor.test density frequency
      globalVariables head lines lm median na.omit quantile sd summary.lm
      t.test tail title var
    Consider adding
      importFrom("graphics", "lines", "title")
      importFrom("stats", "anova", "as.formula", "complete.cases",
                 "cor.test", "density", "frequency", "lm", "median",
                 "na.omit", "quantile", "sd", "summary.lm", "t.test", "var")
      importFrom("utils", "globalVariables", "head", "tail")
    to your NAMESPACE file.
    ```

# treeio

Version: 1.4.3

## In both

*   checking re-building of vignette outputs ... WARNING
    ```
    Error in re-building vignettes:
      ...
    pandoc-citeproc: when expecting a product (:*:), encountered Object instead
    Error running filter /usr/local/bin/pandoc-citeproc:
    Filter returned error status 1
    Error: processing vignette 'Exporter.Rmd' failed with diagnostics:
    pandoc document conversion failed with error 83
    Execution halted
    ```

# trialr

Version: 0.0.4

## In both

*   checking re-building of vignette outputs ... WARNING
    ```
    Error in re-building vignettes:
      ...
    Loading required package: Rcpp
    pandoc-citeproc: when expecting a product (:*:), encountered Object instead
    Error running filter /usr/local/bin/pandoc-citeproc:
    Filter returned error status 1
    Error: processing vignette 'BEBOP.Rmd' failed with diagnostics:
    pandoc document conversion failed with error 83
    Execution halted
    ```

*   checking installed package size ... NOTE
    ```
      installed size is  8.3Mb
      sub-directories of 1Mb or more:
        libs   6.4Mb
    ```

# tsibble

Version: 0.5.3

## In both

*   checking re-building of vignette outputs ... WARNING
    ```
    ...
    The following object is masked from 'package:stats':
    
        filter
    
    
    Attaching package: 'lubridate'
    
    The following objects are masked from 'package:tsibble':
    
        interval, new_interval
    
    The following object is masked from 'package:base':
    
        date
    
    pandoc-citeproc: when expecting a product (:*:), encountered Object instead
    Error running filter /usr/local/bin/pandoc-citeproc:
    Filter returned error status 1
    Error: processing vignette 'intro-tsibble.Rmd' failed with diagnostics:
    pandoc document conversion failed with error 83
    Execution halted
    ```

# ukbtools

Version: 0.11.0

## In both

*   checking dependencies in R code ... NOTE
    ```
    Namespace in Imports field not imported from: ‘plyr’
      All declared Imports should be used.
    ```

*   checking data for non-ASCII characters ... NOTE
    ```
      Note: found 5 marked UTF-8 strings
    ```

# understandBPMN

Version: 1.1.0

## In both

*   checking package dependencies ... ERROR
    ```
    Package required but not available: ‘devtools’
    
    See section ‘The DESCRIPTION file’ in the ‘Writing R Extensions’
    manual.
    ```

# unvotes

Version: 0.2.0

## In both

*   checking package dependencies ... NOTE
    ```
    Package suggested but not available for checking: ‘devtools’
    ```

*   checking data for non-ASCII characters ... NOTE
    ```
      Note: found 4494 marked UTF-8 strings
    ```

# valr

Version: 0.4.1

## In both

*   checking tests ...
    ```
     ERROR
    Running the tests in ‘tests/testthat.R’ failed.
    Last 13 lines of output:
      31: tryCatchList(expr, classes, parentenv, handlers)
      32: tryCatch(withCallingHandlers({    eval(code, test_env)    if (!handled && !is.null(test)) {        skip_empty()    }}, expectation = handle_expectation, skip = handle_skip, warning = handle_warning,     message = handle_message, error = handle_error), error = handle_fatal,     skip = function(e) {    })
      33: test_code(NULL, exprs, env)
      34: source_file(path, new.env(parent = env), chdir = TRUE, wrap = wrap)
      35: force(code)
      36: with_reporter(reporter = reporter, start_end_reporter = start_end_reporter,     {        lister$start_file(basename(path))        source_file(path, new.env(parent = env), chdir = TRUE,             wrap = wrap)        end_context()    })
      37: FUN(X[[i]], ...)
      38: lapply(paths, test_file, env = env, reporter = current_reporter,     start_end_reporter = FALSE, load_helpers = FALSE, wrap = wrap)
      39: force(code)
      40: with_reporter(reporter = current_reporter, results <- lapply(paths,     test_file, env = env, reporter = current_reporter, start_end_reporter = FALSE,     load_helpers = FALSE, wrap = wrap))
      41: test_files(paths, reporter = reporter, env = env, stop_on_failure = stop_on_failure,     stop_on_warning = stop_on_warning, wrap = wrap)
      42: test_dir(path = test_path, reporter = reporter, env = env, filter = filter,     ..., stop_on_failure = stop_on_failure, stop_on_warning = stop_on_warning,     wrap = wrap)
      43: test_package_dir(package = package, test_path = test_path, filter = filter,     reporter = reporter, ..., stop_on_failure = stop_on_failure,     stop_on_warning = stop_on_warning, wrap = wrap)
      44: test_check("valr")
      An irrecoverable exception occurred. R is aborting now ...
    ```

*   checking package dependencies ... NOTE
    ```
    Package suggested but not available for checking: ‘devtools’
    ```

# vcfR

Version: 1.8.0

## In both

*   checking package dependencies ... ERROR
    ```
    Package required but not available: ‘vegan’
    
    See section ‘The DESCRIPTION file’ in the ‘Writing R Extensions’
    manual.
    ```

# vidger

Version: 1.0.0

## In both

*   checking installed package size ... NOTE
    ```
      installed size is  6.2Mb
      sub-directories of 1Mb or more:
        data   4.0Mb
        doc    1.7Mb
    ```

# visdat

Version: 0.5.1

## In both

*   checking dependencies in R code ... NOTE
    ```
    Namespaces in Imports field not imported from:
      ‘plotly’ ‘rlang’
      All declared Imports should be used.
    ```

# vqtl

Version: 2.0.4

## In both

*   checking dependencies in R code ... NOTE
    ```
    Namespaces in Imports field not imported from:
      ‘iterators’ ‘knitr’ ‘purrr’ ‘testthat’
      All declared Imports should be used.
    ```

# VWPre

Version: 1.1.0

## In both

*   checking installed package size ... NOTE
    ```
      installed size is  5.0Mb
      sub-directories of 1Mb or more:
        data   3.1Mb
        doc    1.3Mb
    ```

# wand

Version: 0.2.0

## In both

*   checking whether package ‘wand’ can be installed ... ERROR
    ```
    Installation failed.
    See ‘/Users/lionel/Desktop/tidyr/revdep/checks.noindex/wand/new/wand.Rcheck/00install.out’ for details.
    ```

## Installation

### Devel

```
* installing *source* package ‘wand’ ...
** package ‘wand’ successfully unpacked and MD5 sums checked
Checking to see if libmagic is available...
** libs
g++-8 -I"/Library/Frameworks/R.framework/Resources/include" -DNDEBUG -L/usr/local/include -L/opt/local/include -I"/Users/lionel/Desktop/tidyr/revdep/library.noindex/tidyr/new/Rcpp/include" -I/usr/local/include   -fPIC  -mtune=core2 -O3 -c RcppExports.cpp -o RcppExports.o
g++-8 -I"/Library/Frameworks/R.framework/Resources/include" -DNDEBUG -L/usr/local/include -L/opt/local/include -I"/Users/lionel/Desktop/tidyr/revdep/library.noindex/tidyr/new/Rcpp/include" -I/usr/local/include   -fPIC  -mtune=core2 -O3 -c wand.cpp -o wand.o
g++-8 -dynamiclib -Wl,-headerpad_max_install_names -undefined dynamic_lookup -single_module -multiply_defined suppress -L/Library/Frameworks/R.framework/Resources/lib -L/usr/local/lib -o wand.so RcppExports.o wand.o -L/usr/local/lib -L/opt/local/lib -L/usr/lib -lmagic -F/Library/Frameworks/R.framework/.. -framework R -Wl,-framework -Wl,CoreFoundation
ld: library not found for -lmagic
collect2: error: ld returned 1 exit status
make: *** [wand.so] Error 1
ERROR: compilation failed for package ‘wand’
* removing ‘/Users/lionel/Desktop/tidyr/revdep/checks.noindex/wand/new/wand.Rcheck/wand’

```
### CRAN

```
* installing *source* package ‘wand’ ...
** package ‘wand’ successfully unpacked and MD5 sums checked
Checking to see if libmagic is available...
** libs
g++-8 -I"/Library/Frameworks/R.framework/Resources/include" -DNDEBUG -L/usr/local/include -L/opt/local/include -I"/Users/lionel/Desktop/tidyr/revdep/library.noindex/tidyr/old/Rcpp/include" -I/usr/local/include   -fPIC  -mtune=core2 -O3 -c RcppExports.cpp -o RcppExports.o
g++-8 -I"/Library/Frameworks/R.framework/Resources/include" -DNDEBUG -L/usr/local/include -L/opt/local/include -I"/Users/lionel/Desktop/tidyr/revdep/library.noindex/tidyr/old/Rcpp/include" -I/usr/local/include   -fPIC  -mtune=core2 -O3 -c wand.cpp -o wand.o
g++-8 -dynamiclib -Wl,-headerpad_max_install_names -undefined dynamic_lookup -single_module -multiply_defined suppress -L/Library/Frameworks/R.framework/Resources/lib -L/usr/local/lib -o wand.so RcppExports.o wand.o -L/usr/local/lib -L/opt/local/lib -L/usr/lib -lmagic -F/Library/Frameworks/R.framework/.. -framework R -Wl,-framework -Wl,CoreFoundation
ld: library not found for -lmagic
collect2: error: ld returned 1 exit status
make: *** [wand.so] Error 1
ERROR: compilation failed for package ‘wand’
* removing ‘/Users/lionel/Desktop/tidyr/revdep/checks.noindex/wand/old/wand.Rcheck/wand’

```
# wbstats

Version: 0.2

## In both

*   R CMD check timed out
    

*   checking data for non-ASCII characters ... NOTE
    ```
      Note: found 1528 marked UTF-8 strings
    ```

# weathercan

Version: 0.2.8

## In both

*   checking tests ...
    ```
     ERROR
    Running the tests in ‘tests/testthat.R’ failed.
    Last 13 lines of output:
      ══ testthat results  ═══════════════════════════════════════════════════════════
      OK: 244 SKIPPED: 4 FAILED: 41
      1. Error: weather_html/raw (hour) download a data frame (@test_04_weather_raw.R#6) 
      2. Error: weather_html/raw (day) download a data frame (@test_04_weather_raw.R#23) 
      3. Error: weather_html/raw (month) download a data frame (@test_04_weather_raw.R#39) 
      4. Error: weather (hour) returns a data frame (@test_06_weather_dl.R#6) 
      5. Error: weather (hour) formats timezone display (@test_06_weather_dl.R#34) 
      6. Error: weather (hour) formats timezone to UTC with multiple zones (@test_06_weather_dl.R#44) 
      7. Error: weather (hour) gets all (@test_06_weather_dl.R#61) 
      8. Error: weather (hour) trims NAs (@test_06_weather_dl.R#73) 
      9. Error: weather (hour) multiple stations (@test_06_weather_dl.R#80) 
      1. ...
      
      Error: testthat unit tests failed
      Execution halted
    ```

*   checking re-building of vignette outputs ... WARNING
    ```
    Error in re-building vignettes:
      ...
    
    Attaching package: 'dplyr'
    
    The following objects are masked from 'package:stats':
    
        filter, lag
    
    The following objects are masked from 'package:base':
    
        intersect, setdiff, setequal, union
    
    Quitting from lines 27-32 (flags.Rmd) 
    Error: processing vignette 'flags.Rmd' failed with diagnostics:
    Evaluation error: Could not resolve host: climate.weather.gc.ca.
    Execution halted
    ```

*   checking package dependencies ... NOTE
    ```
    Package suggested but not available for checking: ‘devtools’
    ```

*   checking dependencies in R code ... NOTE
    ```
    Namespace in Imports field not imported from: ‘xml2’
      All declared Imports should be used.
    ```

*   checking data for non-ASCII characters ... NOTE
    ```
      Note: found 25 marked UTF-8 strings
    ```

# wordbankr

Version: 0.3.0

## In both

*   R CMD check timed out
    

*   checking dependencies in R code ... NOTE
    ```
    Namespace in Imports field not imported from: ‘dbplyr’
      All declared Imports should be used.
    ```

# wrswoR

Version: 1.1

## In both

*   checking tests ...
    ```
     ERROR
    Running the tests in ‘tests/testthat.R’ failed.
    Last 13 lines of output:
      30: tryCatchList(expr, classes, parentenv, handlers)
      31: tryCatch(withCallingHandlers({    eval(code, test_env)    if (!handled && !is.null(test)) {        skip_empty()    }}, expectation = handle_expectation, skip = handle_skip, warning = handle_warning,     message = handle_message, error = handle_error), error = handle_fatal,     skip = function(e) {    })
      32: test_code(NULL, exprs, env)
      33: source_file(path, new.env(parent = env), chdir = TRUE, wrap = wrap)
      34: force(code)
      35: with_reporter(reporter = reporter, start_end_reporter = start_end_reporter,     {        lister$start_file(basename(path))        source_file(path, new.env(parent = env), chdir = TRUE,             wrap = wrap)        end_context()    })
      36: FUN(X[[i]], ...)
      37: lapply(paths, test_file, env = env, reporter = current_reporter,     start_end_reporter = FALSE, load_helpers = FALSE, wrap = wrap)
      38: force(code)
      39: with_reporter(reporter = current_reporter, results <- lapply(paths,     test_file, env = env, reporter = current_reporter, start_end_reporter = FALSE,     load_helpers = FALSE, wrap = wrap))
      40: test_files(paths, reporter = reporter, env = env, stop_on_failure = stop_on_failure,     stop_on_warning = stop_on_warning, wrap = wrap)
      41: test_dir(path = test_path, reporter = reporter, env = env, filter = filter,     ..., stop_on_failure = stop_on_failure, stop_on_warning = stop_on_warning,     wrap = wrap)
      42: test_package_dir(package = package, test_path = test_path, filter = filter,     reporter = reporter, ..., stop_on_failure = stop_on_failure,     stop_on_warning = stop_on_warning, wrap = wrap)
      43: test_check("wrswoR")
      An irrecoverable exception occurred. R is aborting now ...
    ```

# XGR

Version: 1.1.4

## In both

*   checking installed package size ... NOTE
    ```
      installed size is  6.8Mb
      sub-directories of 1Mb or more:
        R      4.0Mb
        data   1.1Mb
    ```

# zFactor

Version: 0.1.7

## In both

*   checking re-building of vignette outputs ... WARNING
    ```
    Error in re-building vignettes:
      ...
    
    Attaching package: 'dplyr'
    
    The following objects are masked from 'package:stats':
    
        filter, lag
    
    The following objects are masked from 'package:base':
    
        intersect, setdiff, setequal, union
    
    pandoc-citeproc: when expecting a product (:*:), encountered Object instead
    Error running filter /usr/local/bin/pandoc-citeproc:
    Filter returned error status 1
    Error: processing vignette 'Ann10.Rmd' failed with diagnostics:
    pandoc document conversion failed with error 83
    Execution halted
    ```

*   checking dependencies in R code ... NOTE
    ```
    Namespace in Imports field not imported from: ‘rootSolve’
      All declared Imports should be used.
    ```

# zFPKM

Version: 1.2.0

## In both

*   checking re-building of vignette outputs ... WARNING
    ```
    ...
    The following object is masked from 'package:S4Vectors':
    
        expand
    
    trying URL 'ftp://ftp.ncbi.nlm.nih.gov/geo/series/GSE94nnn/GSE94802/suppl/GSE94802_Minkina_etal_normalized_FPKM.csv.gz'
    Content type 'unknown' length 800733 bytes (781 KB)
    ==================================================
    trying URL 'ftp://ftp.ncbi.nlm.nih.gov/geo/series/GSE94nnn/GSE94802/suppl/GSE94802_Minkina_etal_raw_counts.csv.gz'
    Content type 'unknown' length 574041 bytes (560 KB)
    ==================================================
    
    Attaching package: 'limma'
    
    The following object is masked from 'package:BiocGenerics':
    
        plotMA
    
    Quitting from lines 108-122 (zFPKM.Rmd) 
    Error: processing vignette 'zFPKM.Rmd' failed with diagnostics:
    statmod package required but is not installed
    Execution halted
    ```

*   checking R code for possible problems ... NOTE
    ```
    ...
    PlotGaussianFitDF: no visible binding for global variable ‘density’
      (/Users/lionel/Desktop/tidyr/revdep/checks.noindex/zFPKM/new/zFPKM.Rcheck/00_pkg_src/zFPKM/R/zfpkm.R:223)
    PlotGaussianFitDF: no visible binding for global variable ‘log2fpkm’
      (/Users/lionel/Desktop/tidyr/revdep/checks.noindex/zFPKM/new/zFPKM.Rcheck/00_pkg_src/zFPKM/R/zfpkm.R:223)
    PlotGaussianFitDF: no visible binding for global variable ‘sample_name’
      (/Users/lionel/Desktop/tidyr/revdep/checks.noindex/zFPKM/new/zFPKM.Rcheck/00_pkg_src/zFPKM/R/zfpkm.R:223)
    PlotGaussianFitDF: no visible binding for global variable ‘log2fpkm’
      (/Users/lionel/Desktop/tidyr/revdep/checks.noindex/zFPKM/new/zFPKM.Rcheck/00_pkg_src/zFPKM/R/zfpkm.R:227-233)
    PlotGaussianFitDF: no visible binding for global variable ‘density’
      (/Users/lionel/Desktop/tidyr/revdep/checks.noindex/zFPKM/new/zFPKM.Rcheck/00_pkg_src/zFPKM/R/zfpkm.R:227-233)
    zFPKMCalc: no visible global function definition for ‘density’
      (/Users/lionel/Desktop/tidyr/revdep/checks.noindex/zFPKM/new/zFPKM.Rcheck/00_pkg_src/zFPKM/R/zfpkm.R:162)
    zFPKMTransform: no visible global function definition for ‘is’
      (/Users/lionel/Desktop/tidyr/revdep/checks.noindex/zFPKM/new/zFPKM.Rcheck/00_pkg_src/zFPKM/R/zfpkm.R:125-127)
    Undefined global functions or variables:
      density dnorm is log2fpkm sample_name
    Consider adding
      importFrom("methods", "is")
      importFrom("stats", "density", "dnorm")
    to your NAMESPACE file (and ensure that your DESCRIPTION Imports
    field contains 'methods').
    ```


# Set commit-env
## project level
> 'sh tools/set-commitenv-project'
## global level
> 'sh tools/set-commitenv-global'

# shell
# set-commitenv-project:
> `npm run setpath && npm run setmodule'

# set-commitenv-global:
> `npm run setglobalpath && npm run setglobalmodule'

# gtest-and-coverage: 
> `Compile and the directory where the reports are stored'

# sdaa-src: 
> `source code of sdaa'

# tools: 
> `script that compiles and generates a report'

## make-script
- make_gtest.sh: compile googltest
- make_sdaa.sh: compile sdaa code
- make_unittest.sh: compile unittest code
- make_release.sh: release

## check-script
- run_unittest.sh: run unittest and gengerate report
- clang_format.sh: format src-code and redeuce mistakes of coding-style 
- cpplint_check.sh: execute cmd of cpplint and generate report
- cppncss_check.sh: execute cmd of cppncss and generate report
- gcovr_check.sh execute cmd of gcovr and generate report
- pylint_check.sh: execute cmd of pylint and generate report

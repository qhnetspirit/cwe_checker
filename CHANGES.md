0.2-dev (2019-XX-XX)
=====

-   Refactoring: Unification of cwe_checker function interface
-   Refactoring: Created utils module for JSON functionality
-   Added check for CWE 248: Uncaught Exception (PR #5)
-   Added automated test suite (run with make test) (PR #7)
-   Improved cross compiling for acceptance test cases by using dockcross (PR #8)
-   Added BAP recipe for standard cwe_checker run (PR #9)
-   Improved check for CWE-476 (NULL Pointer Dereference) using data flow analysis (PR #11)
-   Added cwe_checker_emulation plugin based on BAP's Primus to detect CWE-125, CWE-415, and CWE-416 (PR #15)
-   Switched C build system from make to scons (PR #16)
-   Added type inference pass (PR #14)
-   Added unit tests to test suite (PR #14)

0.1 (2018-10-08)
=====

Initial release of cwe_checker.

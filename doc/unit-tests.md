Compiling/running unit tests
------------------------------------

Unit tests will be automatically compiled if dependencies were met in configure
and tests weren't explicitly disabled.

After configuring, they can be run with 'make check'.

To run the pengd tests manually, launch src/test/test_peng .

To add more pengd tests, add `BOOST_AUTO_TEST_CASE` functions to the existing
.cpp files in the test/ directory or add new .cpp files that
implement new BOOST_AUTO_TEST_SUITE sections.

To run the peng-qt tests manually, launch src/qt/test/peng-qt_test

To add more peng-qt tests, add them to the `src/qt/test/` directory and
the `src/qt/test/test_main.cpp` file.

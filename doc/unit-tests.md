Compiling/running unit tests
------------------------------------

Unit tests will be automatically compiled if dependencies were met in configure
and tests weren't explicitly disabled.

After configuring, they can be run with 'make check'.

To run the goldbeard tests manually, launch src/test/test_goldbear .

To add more goldbeard tests, add `BOOST_AUTO_TEST_CASE` functions to the existing
.cpp files in the test/ directory or add new .cpp files that
implement new BOOST_AUTO_TEST_SUITE sections.

To run the goldbear-qt tests manually, launch src/qt/test/goldbear-qt_test

To add more goldbear-qt tests, add them to the `src/qt/test/` directory and
the `src/qt/test/test_main.cpp` file.

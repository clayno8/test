# Test framework

In Medley, load both files. The second one depends on the first.

    (LOAD 'TEST-FRAMEWORK-TRY)
    (LOAD 'TEST-EXAMPLES)

The package has to be UNIT-TEST before the run.

    (IN-PACKAGE "UNIT-TEST")
    (RUN-ALL-TESTS)

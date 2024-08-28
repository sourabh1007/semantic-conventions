<!--- Hugo front matter used to generate the website version of this page:
--->

<!-- NOTE: THIS FILE IS AUTOGENERATED. DO NOT EDIT BY HAND. -->
<!-- see templates/registry/markdown/attribute_namespace.md.j2 -->

# Test

## Test Attributes

This group describes attributes specific to [software tests](https://en.wikipedia.org/wiki/Software_testing).

| Attribute                 | Type   | Description                                                                                          | Examples                                                                                 | Stability                                                        |
| ------------------------- | ------ | ---------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------- | ---------------------------------------------------------------- |
| `test.case.name`          | string | The fully qualified human readable name of the [test case](https://en.wikipedia.org/wiki/Test_case). | `org.example.TestCase1.test1`; `example/tests/TestCase1.test1`; `ExampleTestCase1_test1` | ![Experimental](https://img.shields.io/badge/-experimental-blue) |
| `test.case.result.status` | string | The status of the actual test case result from test execution.                                       | `pass`; `fail`                                                                           | ![Experimental](https://img.shields.io/badge/-experimental-blue) |
| `test.suite.name`         | string | The human readable name of a [test suite](https://en.wikipedia.org/wiki/Test_suite).                 | `TestSuite1`                                                                             | ![Experimental](https://img.shields.io/badge/-experimental-blue) |
| `test.suite.run.status`   | string | The status of the test suite run.                                                                    | `success`; `failure`; `skipped`; `aborted`; `timed_out`; `in_progress`                   | ![Experimental](https://img.shields.io/badge/-experimental-blue) |

`test.case.result.status` has the following list of well-known values. If one of them applies, then the respective value MUST be used; otherwise, a custom value MAY be used.

| Value  | Description | Stability                                                        |
| ------ | ----------- | ---------------------------------------------------------------- |
| `fail` | fail        | ![Experimental](https://img.shields.io/badge/-experimental-blue) |
| `pass` | pass        | ![Experimental](https://img.shields.io/badge/-experimental-blue) |

`test.suite.run.status` has the following list of well-known values. If one of them applies, then the respective value MUST be used; otherwise, a custom value MAY be used.

| Value         | Description | Stability                                                        |
| ------------- | ----------- | ---------------------------------------------------------------- |
| `aborted`     | aborted     | ![Experimental](https://img.shields.io/badge/-experimental-blue) |
| `failure`     | failure     | ![Experimental](https://img.shields.io/badge/-experimental-blue) |
| `in_progress` | in_progress | ![Experimental](https://img.shields.io/badge/-experimental-blue) |
| `skipped`     | skipped     | ![Experimental](https://img.shields.io/badge/-experimental-blue) |
| `success`     | success     | ![Experimental](https://img.shields.io/badge/-experimental-blue) |
| `timed_out`   | timed_out   | ![Experimental](https://img.shields.io/badge/-experimental-blue) |
# Guidance on how to contribute

> By submitting a pull request or filing a bug, issue, or feature request,
> you are agreeing to comply with this waiver of copyright interest.
> Details can be found in our [LICENSE](LICENSE).


There are two primary ways to help:
 - Using the issue tracker, and
 - Changing the code-base.


## Using the issue tracker

Use the issue tracker to suggest feature requests, report bugs, and ask questions.
This is also a great way to connect with the developers of the project as well
as others who are interested in this solution.

Use the issue tracker to find ways to contribute. Find a bug or a feature, mention in
the issue that you will take on that effort, then follow the _Changing the code-base_
guidance below.


## Changing the code-base

Generally speaking, you should fork this repository, make changes in your
own fork, and then submit a pull request. All new code should have associated
unit tests that validate implemented features and the presence or lack of defects.
Additionally, the code should follow any stylistic and architectural guidelines
prescribed by the project. In the absence of such guidelines, mimic the styles
and patterns in the existing code-base.

### Contribution guidelines
 - Your code should follow PEP 8 -- Style Guide for Python Code
 - Your changes should be covered by unit-tests
 - If you add a unit-test within the `test_compare_flat.py`, make sure to add the equivalent test to the `test_partial_compare_flat.py` (and vice versa).
 - If you add a unit-test within the `test_compare_deep.py`, make sure to add the equivalent test to the `test_partial_compare_deep.py` (and vice versa).

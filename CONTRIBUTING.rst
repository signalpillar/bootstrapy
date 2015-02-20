Contributing to the project
---------------------------

``<project-name>`` uses <issue-tracking-system-name> to keep track of bugs, feature requests, and associated patches.
For reviews we use <review-system-name>.


Setup development environment
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

Several lines about project setup process.


Making Changes
~~~~~~~~~~~~~~

-  Update a topic branch from where you want to base your work.
-  This is usually the ``develop`` branch.
-  Please avoid working directly on a topic branch.
-  Make commits of logical units (if needed rebase your feature branch before submitting it).
-  Check for unnecessary whitespace with ``git diff --check`` before committing.
-  Make sure your commit messages are in the proper format.
-  If your commit fixes an open issue, reference it in the commit message.
-  Make sure your code conforms to PEP8.
-  Make sure you have added the necessary tests for your changes.
-  Run all the tests to assure nothing else was accidentally broken.
-  Don't forget to add yourself to AUTHORS.

These guidelines also apply when helping with documentation (actually, for typos and minor additions).


Code Review
~~~~~~~~~~~

Several lines about code review process

Testing
~~~~~~~

Every non-trivial change to the code base should be accompanied by a relevant addition to or
modification of the test suite. If you don't believe this is necessary, please add an explanation
in the ticket why no such changes are either needed or possible.

All changes must also pass the full test suite (including your test additions/changes) on your
local machine before you open a pull request.

To run all test-suites::

    <command-line>


* As a runner we use <tests-runner>.
* As a framework we use <framework-name>.
* As a mocking library - <mocking library if there is one>.

Style Guide
~~~~~~~~~~~

``<project-name>`` aims to follow PEP8 including 4 space indents and 100 character line limits.


To check style with flake8::

    <command-line>

**Documentation** in the project is written in reStructured markup language and docstrings
using the sphinx_ syntax.

.. _sphinx: https://pythonhosted.org/an_example_pypi_project/sphinx.html

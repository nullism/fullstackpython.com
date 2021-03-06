title: Unit Testing
category: page
slug: unit-testing
sort-order: 0802
meta: Unit testing exercises one function isolated from a program. Learn more about unit testing on Full Stack Python.


# Unit testing
Unit testing is a method of determining the correctness of a single function 
isolated from a larger codebase. The idea is that if all the atomic units
of an application work as intended in isolation, then integrating them 
together as intended is much easier.


## Why is unit testing important?
Unit testing is just one form of [testing](/testing.html) that works in
combination with other testing approaches to wring out the bugs from a
piece of software being developed. When several functions and classes are
put together it's often difficult to determine the source of a problem if
several bugs are occurring at the same time. Unit testing helps eliminate
as many of the individual bugs as possible so when the application comes
together as a whole the separate parts work as correct as possible. Then
when issues arise they can often be tracked down as unintended consequences
of the disparate pieces not fitting together properly.


## Unit testing tools
There are many tools for creating tests in Python. Some of these tools, such
as pytest, replace the built-in unittest framework. Other tools, such as
nose, are extensions that ease test case creation. Note that many of these
tools are also used for [integration testing](/integration-testing.html)
by writing the test cases to exercise multiple parts of code at once.

* [unittest](https://docs.python.org/3/library/unittest.html)
  is the built-in standard library tool for testing Python code.

* [pytest](http://pytest.org/latest/) is a complete testing tool that
  emphasizes backwards-compatibility and minimizing boilerplate code.

* [nose](https://nose.readthedocs.org/en/latest/) is an extension to
  unittest that makes it easier to create and execute test cases.

* [testify](https://github.com/Yelp/Testify/) was a testing framework
  meant to replace the common unittest+nose combination. However, the team
  behind testify is transitioning to pytest so it's recommended you do
  not use testify for new projects.


### Unit testing resources
* [The Minimum Viable Test Suite](https://realpython.com/blog/python/the-minimum-viable-test-suite/)
  shows how to set unit tests and integration tests for a Flask example
  application.

* [Dive into Python 3's chapter on unit testing](http://www.diveintopython3.net/unit-testing.html)
  has a complete example with code and a detailed explanation for creating
  unit testing with the 
  [unittest](https://docs.python.org/3/library/unittest.html) module.

* [Understanding unit testing](https://jeffknupp.com/blog/2013/12/09/improve-your-python-understanding-unit-testing/)
  explains why testing is important and shows how to do it effectively in
  your applications.

* [Unit testing with Python](http://www.drdobbs.com/testing/unit-testing-with-python/240165163)
  provides a high-level overview of testing and has diagrams to demonstrate
  what's going on in the testing cycle.

* The Python wiki has a page with a list of 
  [Python testing tools and extensions](https://wiki.python.org/moin/PythonTestingToolsTaxonomy).

* [Working Effectively with Unit Tests](http://blog.fogcreek.com/working-effectively-with-unit-tests-interview-with-jay-fields/)
  is an interview with the author of a book by the title where he shares
  some of the insight he's learned on the topic.

* [Generate your tests](http://blog.kevinastone.com/generate-your-tests.html)
  shows how to write a test generator that works with the `unittest` 
  framework.



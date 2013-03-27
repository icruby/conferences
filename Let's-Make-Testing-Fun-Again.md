From [[WindyCityRails 2012]]

**Presenter:** [[Noel Rappin]]

## Abstract

> “Programmers Love Writing Tests” is the subtitle of one of Kent Beck’s first articles about Test-Driven Development. I don’t think I’m alone in being drawn to TDD at first because it was fun. The quick and consistent feedback and the ability to turn complicated problems into a series of smaller problems to be solved made TDD development seem more like a game than work.
> 
> Eventually TDD became less fun. Slow tests made running test suites a cruel joke. Test code gets bulky, and is hard to refactor because, of course, tests don’t have their own tests.
> 
> Let’s fix that. We’ll show some notorious testing joy-killers, like slow tests, hard to read tests, tests that paper over bad designs rather than driving new ones. And we’ll squash them, and regain testing delight.

## Summary

* Testing best practices

## Memorable Quotes

* "Correctness is a side effect" - Kent Beck

## Notes

From @benjaminoakes:

* Kent Beck: "Programmers Love Writing Tests"
* Noel liked doing JUnit, etc
* We get satisfaction from solving problems well, but do we love writing tests?
    * Do we just love saying we wrote tests?

What makes testing nice:

* Feedback:  learn something about your code
* Communication (longer term)

Good Rspec Habits:

* Name by behavior
* Take small steps
* Test one thing at a time; good when your business logic changes
* Don't make too many objects (e.g. make 100 to make sure #101 acts differently)
   * Slow
   * Find ways to make just enough objects
* Remove noise
   * Complicated setup?  Maybe your code is too complicated to begin with
* Don't use Cucumber for unit tests
* Make single assertions... when it makes sense

### External Links

* [Slides](https://speakerdeck.com/u/noelrap/p/lets-make-testing-fun-again)
* [Video](http://vimeo.com/49525644)
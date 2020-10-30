# ECE444-flaskr-tdd2
Replay of tutorial from https://github.com/mjhea0/flaskr-tdd

## Pros and Cons of TDD

### Pros of test driven development

* It will force your code to be modular since you are writing small tests at time. This helps the developer better
understand and internalize the key principles of modular design

  * As a result, TDD forces a good architecture
  
* Documentations are always up-to-date since the tests in TDD are running all time
* The code becomes easier to maintain and refactor.
* It helps prevent defects early on and warns developers in the early stages of development if there are inherent design flaws
in the architecture or project structure
* Unit tests are valuable as a safety net when new features are added or bugs are getting fixed.

### Cons of test driven development

* The tests may be hard to write, especially those that evaluate integration between multiple features (i.e. integration tests) of an app.
* It slows down development initially. The implementation code may not be ready for some time due to the time
spent writing and running the tests first. A trade-off is that in the long run development speeds up.
* Housekeeping must be performed continually. Booking more and more tests makes the build longer and longer. This necessitates
developers to refine those tests (e.g. by removing redundant ones) so they can run more quickly.

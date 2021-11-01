# ECE444-F2021-Lab6

Pros:
- The most obvious benefit of TDD is high test coverage which gives developers confidence that their features function accordingly. This also gives you confidence when fixing bugs or refactoring code that it will not jeopardize the whole application because the tests/test suites should be very detailed and test the features thoroughly. In other words, TDD helps prevent defects from arising. 
- Because code written is driven by tests, it becomes a microfeature design where code is written in a modular design. This makes checking code and interpreting code to be easy.
- The code is also easier to maintain because different parts of the application have clear interfaces and are separate from one another. This means that you can adjust code in one microfeature without affecting the others and the tests corresponding with each microfeature will only affect that microfeature. 
- It helps clarify the requirements for the application being developed because you have to figure out what the expected output is. 
- Gives confidence for coworkers to interpret and alter each other's code because everyone is following TDD. So it gives developers more confidence when you want to refactor or edit code. 

Cons:
- Focusing on TDD will inherently increase the amount of time needed to complete a feature because not only do you need to develop the feature itself, but also write thorough tests to test the feature. 
- Tests also need to be maintained due to many reasons such as business logic changes, bugs that arise, and etc, which means that the tests need to be rewritten or reconfigured. And this introduces even more problems when old tests need to be changed and new employees may not be familiar with the tests. 
- Can become too focused on writing tests that the tests become too complex, which introduces problems when having to maintain the test. Sometimes, moderate efforts in writing tests is enough to secure confidence for the feature being developed and so more time can be allocated in writing code. 
- Switching to TDD may be extremely difficult to apply to legacy code because the code written before was not following the same framework. This means writing tests and covering all the functionalities may require a lot of effort and time. 

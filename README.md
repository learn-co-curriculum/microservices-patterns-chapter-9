# Thoughts/Questions:
What is the difference between a stub and a mock? Book as this to say:
- The terms stubs and mocks are often used interchangeably, although they have slightly different behavior. A stub is a test double that returns values to the SUT. A mock is a test double that a test uses to verify that the SUT correctly invokes a dependency. Also, a mock is often a stub.
- How do we use mocks and stubs in Ironboard? Is there a pattern that we adhere to? Whats the difference between our approach and a library like mockito or the other mock frameworks mentioned? What are the advantages of such a framework?

## Consumer-driven Contract Testing

- API interactions have a consumer, and a producer
- The team that develops the consumer writes contract tests in the producer’s test suite.
- Contract tests run alongside other tests in test suite.
- [This library](https://github.com/pact-foundation/pact-ruby) looks like a good place to start understanding these kinds of tests using Ruby code.

<p class='util--hide'>View <a href='https://learn.co/lessons/microservices-patterns-chapter-9'>Microservices Patterns Chapter 9</a> on Learn.co and start learning to code for free.</p>

# Writing Unit Tests

## Learning Objectives

- Define unit testing as the process of testing the smallest possible 'unit' of a programme.
- Understand each of the "3 As" of a unit test.
- Write some simple unit tests.

## Starter (10 minutes)

### Why Write tests?

Unit tests provide us with the reassurance that our code actually does what we think it's supposed to do, and also guard against future errors.

### Example



### Demonstration

```ruby
class FileSystem
  attr_reader :storage

  def initialize
    @storage = []
  end

  def store(file)
    storage.push(file)
  end
end
```

Discuss the above code snippet with devs, establishing what is happening on a line by line basis.

Introduce the 'arrage, act, assert' format for constructing a unit test. Collaborate with the devs to put together a unit test for the `store` method.

## Main (40 minutes)

Devs should complete the exercises in README.md

## Plenary (10 minutes)

Choose two students' examples to share, and critique them.

Touch on TDD - we would usually write our tests prior to our code so we have to engage in a process of imagining the code we would like to have.

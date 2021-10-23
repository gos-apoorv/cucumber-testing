# Cucumber Testing
 This repo deomonstrates following:
 - Init Cucumber `make init`
 - Write your Scenario using the Gherkin syntax
 - Write your step definition in Ruby
 - Run Cucumber `make exec`

# Behaviour-Driven Development (BDD)
  This demonstrates the usage of [BDD](https://en.wikipedia.org/wiki/Behavior-driven_development) workflow to develop a code and evaluate it using multiple scenario

# Requirement
  This repo needs following:
  - [Ruby](https://www.ruby-lang.org/en/)
  - [Bundler](https://bundler.io/)

# Ubiquitous Language
 When using cucumber for BDD, we use [Ubiquitous Language](https://martinfowler.com/bliki/UbiquitousLanguage.html) to make it more easy to understand and maintain

# Specification
Create a file named rule.feature in the features directory with:

features/rule.feature

    Feature: Rule

        Scenario: A passing scenario
            Given this will pass
            When I do an action
            Then some results should be there

        Scenario: A failing scenario
            Given this will fail
            When I do an action
            Then some results should be there

# Reference
 - [cucumber-10-minute-tutorial](https://cucumber.io/docs/guides/10-minute-tutorial/)

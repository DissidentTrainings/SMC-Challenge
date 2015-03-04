# Jump and Run BDD Challenge

This is a exercise to learn how to specify requirements with Gherkin in a way that suits development with BDD. 

Assignment: 

Create well written Scenarios that describe the features in the computer Game "Secret Maryo Chronicles". 
See: http://www.secretmaryo.org/


## Agenda

* Introduction of the workshop assgiment and the contents. Brainstorm
* Introduction Feature Injection
* Sort the brainstorm results into the feature injection layers. 
* Intro to Gherkin and SWIFT
* Write Gherkin Style Features/Scenarios
* Debrefing

Please describe the game using the Gherkin Syntax

## Examples 


Featrue : Collect Stars


Scenario: Count collected Stars
```
Given a one player game
When Maryo collects a star
Then the count of stars should be increased 1
```

Scenario: Bonus Live for 100 stars
```
Given a one player game
And Maryo has 99 Stars
When Maryo collects a star
Then the count of lives should be increased by 1 
```













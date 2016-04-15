# Fitbug Test Automation Test

Thank you for applying for a role at Fitbug, the following assessment consists of three parts:

* [A technical exercise](#technical-exercise) 
* [Technical questions](#technical-questions)
* [Submitting answers to us](#submitting-answers)

## Technical Exercise

The following website [Kiqplan app](http://test.my.kiqplan.com/fitbugdemo/game/fitbug-step-challenge/app) demonstrates the Fitbug step challenge. The application builds on top of the [Kiqplan API](http://test.kiqplan.com/api/v2/) which is [documented here](http://test.kiqplan.com/documentation/v2/). 

You will be provided a login for the 'Kiqplan app' that will also allow you to authenticate with the API. 

1. Write a suite of functional tests in Cucumber syntax to cover some functionality of the site above, you must include the following two scenarios.

```
Feature: Use the app to compete in a challenge
   So that I can compete in a step challenge
   As a company employee
   I want to be part of a Team

   Scenario:
      Given I am a Team member
      When I select my Team in the Leaderboard 
      Then I will see my 'Total steps'
	  
   Scenario:
      Given I am a Team member
      When I view my Team in the Leaderboard 
      Then I will see a combined 'Average team steps' count	  
```

The 'game' name that should be used within API requests is 'fitbugdemo'
 
1. Implement your suite of tests to run in an automated fashion

### Suggested timescale
Feel free to spend as much or as little time as you like (although a guideline would be  2-3 hours), please ensure you meet the following requirements:
* Complete both the technical exercise and technical questions
* Provide instructions on how to run your tests for the technical exercise, clarity and accuracy of these instructions is important, please create a README file containing the instructions

### Choice of tools

You can solve the technical test using any tools of choice, we use tools such as:
* Visual Studio 
* SpecFlow
* Coded UI
* Selenium WebDriver
* Protractor

## Technical Questions
Please provide all technical questions in a markdown file

1. How long did you spend on the technical test, if you would tackle it differently in hindsight, what would you have done?
1. What would be your tools of choice for implementing a test automation framework?
1. What areas particularly interest you in the world of test automation?

## Submitting Answers
Please submit the full assessment as one zip file, this should be named **{firstname-secondname-role-applied-for}.zip** and should be added to the shared DropBox folder you are provided when requested to complete the test.



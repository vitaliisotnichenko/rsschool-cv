# Vitalii Sotnichenko

### e-mail: vitalii.sotnichenko@gmail.com

### skype: vsot_89

## My goals:

### I'm looking for the company where I have a chance to get comprehensive development in terms of Fronted development,

### achiving my wishes and roadmap. I prefer company with no bureacracy and flexible approach to work

## Summary

- more than 5 years experience in IT as QA Engineer
- hands-on experience with UI, backend testing activities
- set up the automation on the project from scratch
- have experience with containerization tools, various test frameworks, CI/CD tools
- collaboration with cross national teams

## Skills

1. JS, Python programming languages - basic level
2. Git, Bitbucket, JIRA, Confluence, TestRail
3. REST API, Swagger, cURL
4. CI (Jenkins, Bamboo)
5. Testing frameworks (CodeceptJS, RobotFramework)
6. Allure, Selenoid, Moon, docker
7. Linux, MySQL

## Code Examples - CodeceptJS

> Feature("Add tasks")

> Before((I) => {
> I.amOnPage('/')
> })

> Data(function\*() {
> yield { text: 'undefined'};
> yield { text: 'undef'};
> yield { text: 'null'};
> yield { text: 'true'};
> yield { text: 'False'};
> }).Scenario('Add tasks with different data', (I, current) => {
> I.fillField('#new-todo', current.text)
> I.pressKey('Enter')
> I.see(current.text)
> })

## Experience

- QA Automation Engineer - IntellectEU
  Since April 2019

- Senior QA - Ciklum
  August 2018 - April 2019

- QA Engineer - SPD-Ukraine
  August 2016 - August 2018

- Own automation framework based on Python - https://github.com/vitaliisotnichenko/python_automation

## Education

- Master's degree in System Programming
- Master's degree in HR
- ISTQB - Foundation and Adavnced (Test Analyst)
- QA Automation JS course (Otus)

# Testing GraphQL Calls in Cypress - Example

This project contains an example of how to test when a call has (or has not) been made in Cypress.

The backend contains a simple Express server serving GraphQL (simple todos)

The frontend contains a simple website which consumes and displays the result of the graphQL call (the todos)

The most important file is `frontend/cypress/e2e/example.cy.js`, which contains the relevant tests

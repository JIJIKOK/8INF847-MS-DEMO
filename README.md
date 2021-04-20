[![Board Status](https://dev.azure.com/benm0131/f4b956b1-8f22-4bd9-aaec-d4ce1107cea0/c6b60dd7-06ef-49bb-b6ce-c82ea4a45f46/_apis/work/boardbadge/abc561fe-2881-479a-ab97-707aba4ee935)](https://dev.azure.com/benm0131/f4b956b1-8f22-4bd9-aaec-d4ce1107cea0/_boards/board/t/c6b60dd7-06ef-49bb-b6ce-c82ea4a45f46/Microsoft.RequirementCategory)
# Calculator.js: a node.js Demonstration Project

An example node.js project, including tests with mocha, that behaves like
a pocket calculator.

The project contains a simple node.js application that exposes REST APIs
to perform arithmetic on integers, and provides a test suite with mocha
and chai. `mocha-junit-reporters` package is included to provide XML
output that can be presented in a continuous integration tool like
[Azure DevOps](https://azure.com/devops).

To build,:

1. Runs `npm install` to install dependencies.
2. Runs `npm test` to run Mocha and execute the unit tests.

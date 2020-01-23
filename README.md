# Template-Engine-2

You will build a software engineering team generator command line application. The application will prompt the user for information about the team manager and then information about the team members. The user can input any number of team members, and they may be a mix of engineers and interns. This assignment must also pass all unit tests. When the user has completed building the team, the application will create an HTML file that displays a nicely formatted team roster based on the information provided by the user. 


How do you deliver this? Here are some guidelines:


  Use the Inquirer npm package to prompt the user for their email, id, and specific information based on their role with the company.     For instance, an intern may provide their school, whereas an engineer may provide their GitHub username.


  Your app will run as a Node CLI to gather information about each employee.
  
The dependencies are, jest for running the provided tests, and inquirer for collecting input from the user.
There are also unit tests to help you build the classes necessary.
It is recommended that you follow this workflow:

Run tests
Create or update classes to pass a single test case
Repeat

🎗 Remember, you can run the tests at any time with npm run test
It is recommended that you start with a directory structure that looks like this:
lib/           // classes and helper code
output/        // rendered output
templates/     // HTML template(s)
test/          // jest tests
  Employee.test.js
  Engineer.test.js
  Intern.test.js
  Manager.test.js
app.js         // Runs the application

Hints


Create multiple HTML templates for each type of user. For example, you could use the following templates:


main.html


engineer.html


intern.html


manager.html




You will want to make your methods as pure as possible. This means try to make your methods simple so that they are easier to test.


The different employee types should all inherit some methods and properties from a base class of Employee.


In your HTML template files, you may want to add a placeholder character that helps your program identify where the dynamic markup begins and ends.



Minimum Requirements


Functional application.


GitHub repository with a unique name and a README describing the project.


User can use the CLI to generate an HTML page that displays information about their team.


All tests must pass.

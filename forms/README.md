## Getting Started

- Install the version of Node JS for your OS https://nodejs.org/en/download
- From a terminal run the following commands to check if the installation was successful:
  - `$ node -v`
  - `$ npm -v`
  - Set PATH environment variable to path/to/bin/node and path/to/bin/npm if the above commands failed to return the version number.
- In the terminal install dependencies using the command:
    `$ npm install`
- In the terminal run the local server using the command:
  - `node form-server.js`
- Open "form.html" in a browser. Enter username and password and click "Submit".

## Questions for you to answer
1. What is the purpose of the _action_ attribute in the _form_ tag?
  To specify the location where the form data should be sent when the form is submitted.
2. What is the purpose of the _method_ attribute in the _form_ tag?
  To define how the form data should be sent to the server.
3. What is the purpose of the _name_ attribute in the _input_ tag?
  To associate a name with the input element so that we can identify and handle different form elements when processing the form data.
4. What is the purpose of the _type_ attrbute in the _input_ tag?
  To define what kind of data the user can input or what kind of functionality the input element provides.
5. What is the purpose of the _label_ tag?
  To provide a textual description oor label for an input element.
6. What is the purpose of the _required_ attribute?
  To specify that a user must fill in a particular form field before submitting the form.

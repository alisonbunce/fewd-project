# fewd-project
code for fewd final project

Final Project FEWD
__________________

BUSINESS OBJECTIVE
__________________

For my final FEWD project I took an active business problem and created an MVP solution using HTML and JS.

The business problem: Business users in Upper level management don't understand the value in the application S4.

Context: There are 4 different departments thats service data needs to internal employees (in some capacity)

The project: Create a marketing campaign help users understand the value to eventually evangelize S4

Project proposal: Create a flyer that featured quotes of the value of s4

My solution: Create a user prompted search tool that allowed the user to discover and understand the value of s4 on their on, based on their needs. And then be able to track/assess future user needs.
__________________

CODE
__________________
Line 1, we have a document and doc is a html doc and the js is listening to html

Line 2= we are grabing the element by the Id of search form because we are grabbing the entire search form

Line 3= adding event listener to listen for the submit action, it takes in a callback function which is the on submit function. We want to trigger this function after submit has been actioned. If you click a submit, this has to happen. Until submit has been clicked, it’s idling. 

Line 4= natural state of form is to refersh when you click something but we don’t want it do refresh. We want it to display something so we use prevent default function.

Line 5= creating variable called inputval that is grabbing the element by the id of search term and that value is going to get us that value.

Line 7= if the input value == “”
Line 8= we are setting the inter html value of the element by the id of sr-results to be ‘yes’

Line 8- you can use 
Implementing the same function in line 8 throughout the rest of the if/else statement

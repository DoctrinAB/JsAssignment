# Anamnes - [Medical history](https://en.wikipedia.org/wiki/Medical_history)

First and foremost, thank you for taking your time to be part of our goal, to impact 1 000 000 000 (One billion) people. Everything we do is focused on this goal and to reach it we need people like __you__!

The medical team at [doctrin](http://doctrin.se/en/) are always looking for new ways to improve healthcare. Through years of practicing medicine they have become experts of listening and talking to patients. In this process they also learnt to ask the right questions about a patients condition and medical history.

The medical team hires __you__ as they heard that __you__ are a motivated and excellent problemsolver, they need you to build functioning prototype of their system.


## Requirements

Before each patient appointment they want the patient to fill in a questionnaire. The questionnaire will help the doctors before and during the appointment to give the best possible treatment. The questionnaire should be built using web-technologies and be functioning on standard mobile devices.


### Functional requirements

* Create a landing page where the user inputs their (Swedish) social-security number and presses a button to confirm.

* The user should be presented with a questionnaire, the questions are given to you by the Medical team (See end of this text document).

* The questions should be presented one at the time, , a new question is presented after a question has been answered.

* When the last question is answered a thank you page is shown.

* The questions have different inpyt types (checkboxes, radio buttons, freetext etc)

* The questions and answers should be persisted in a database.

* Create an endpoint where you can fetch a report in JSON format by passing in the patients SSN. The report should be queryable even if the patient hasn't answered all questions.

### Technical requirements
*  HTML/JS/CSS
*  CSS and styling
*  React/Redux or other JS framework
*  Node.js
*  MongoDB or other DB of choice

### Setup requirements

* npm install
* npm run start (tests if any ;) , lint, and server)

### Questions for fever
 
1.	What was the last measured temperature. (dropdown)
	1.	35 to 42 degrees.
	1.	Don't know.

2. How long have you had a fever? (dropdown)
	1. 0 to 14 days

3. Do you have any of the following. (radiobuttons, must activly select no)

	1. Problem breathing
	2. Stiff neck
	3. Chest pain
	4. abdominal pain

4. Do you have any of the following? (checkboxes)

	1. Soar throat
	2. Cough
	3. Muscle pain
	4. Vomiting
	5. cough

5. Have you recently traveled abroad? (radiobuttons)
	1. Yes
	2. No

6. Shown if answered yes to question 5.
	1. Where did you travel (freetext)

7. END - Thank you

# **Sprint 2 User Stories**

> The checked use stories are the accepted user stories

- [x] As an user, I want to create a multiple choice question to add variety and complexity to the tests and the type of questions in the system.
    * User Acceptance Test: Given that I am an a signed in user, when I create a new mcq question, the question will be stored in the system.
    * Task: Add create 'mcq' button to drop down menu
    * Task: Create page for multiple choice question 
- [x] As an user, I want to create an essay question to add variety and complexity to the tests and the type of questions in the system.
    * User Acceptance Test: Given that I am an a signed in user, when I create a new essay question, the question will be stored in the system. 
    * Task: Add create 'essay question' link to drop down menu
    * Task: Create page for essay question  
- [x] As an user, I want to create a text entry question to add variety and complexity to the tests and the type of questions in the system.
    * User Acceptance Test: Given that I am an a signed in user, when I create a new text-entry question, the question will be stored in the system. 
    * Task: Add create 'text entry question' link to drop down menu
    * Task: Create page for a text entry question  
- [x] As an user, I want to import questions from documents into the question management system to avoid having to recreate questions that already exist.
    * User Acceptance Test: Given that I am an a signed in user, when I import my question from the document, the question will be stored in the 
      system. 
    * Task: Create QTI files
    * Task: Create page for import questions
- [x] As an user, I want to login to the system to get access to question bank system
    * User Acceptance Test: Given that I enter a valid credentials, when I log in, the system will give me access
    * Task: Create a valid log-in user  
- [ ] As an user, I want to peer review questions (like/dislike) on the system to ensure that the questions on the system are of high quality/standard.
    * User Acceptance Test: Given that I am an a signed in user, when I review a question, the review will be saved in the system. 
    * Task: Create page for peer review

- [ ] As an authorised person (staff member), I want to track my activity (sessions) on the system to monitor my interaction with the system.

# **Technical Requirements Sprint 2**

* Log-in to system
  * Only a valid user that has access the system can access the system with their valid log-in credentials
   
* Create new question of different types
  * Going from the Hub/menu, to create question page, user will be able to add a new question from a drop-down menu of choice (Multiple-choice question, text-entry,       essay)

* Import question into the question bank
  * Going from the Hub/menu, user will be able to import a question into the question bank using CSV’s, QTI’s, Word Document, etc.

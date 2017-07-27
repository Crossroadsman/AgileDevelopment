Acceptance Criteria
===================

What are Acceptance Criteria?
-----------------------------

- Statements of requirements;
- From the point of view of the user;
- That determine when a story is done and working as expected.

Acceptance criteria are emerging and evolving and assumed to be flexible enough to change until the team works on the associated story.


Benefits of Acceptance Criteria
-------------------------------

- Triggers the thought process for the team to think through how a feature will work from the end-user perspective;
- Helps the team to write accurate test cases without ambiguity;
- Eliminates unnecessary scope that adds no value to the story.


Example of a User Story With Acceptance Criteria
------------------------------------------------

### Story ###
AS A bank customer 
I WANT an email sent to my registered email address when my account goes into overdraft 
SO THAT I know to fund my account.

### Acceptance Criteria ###

Input                 | Process                   | Output
----------------------|---------------------------|-------------------------------------------------------------------------------
valid email address   | email validation          | message sent to email address
invalid email address | email validation          | flag profile as incomplete, kickoff snail mail message
valid email address   | overdraft warning message | message content matches specs provided by customer relations
valid email address   | overdraft warning message | message contains clickable link that allows user to navigate to online banking

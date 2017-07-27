Definitions
===========

Acceptance Criteria
-------------------

A list of verifiable and testable conditions describing the inputs/processes/outcomes that constitute a completed functional story.


Card
----

Usually refers to the "AS A/I WANT/SO THAT" part of the *story*.


Confirmations
-------------

Synonym for *acceptance criteria*.


Conversation
------------

The discussion among developers and stakeholders, prompted by the *story*, that more fully describes the user needs, actions, and value 
that the *story* represents. Used to generate ideas for producing the *confirmations* / *acceptance criteria*


Customer Proxy
--------------

When the customer is unavailable, the proxy helps to ensure the team works on stories that deliver the highest value.

The proxy needs to understand business requirements and their relative priority.


Epic
----

A large *story* that can be broken down into multiple smaller *stories*. Alternatively, it could be described as a large activity that has 
user value.

Similar to a *theme* in that it is made up of multiple *stories* but differs in that these comprise a complete workflow for a user. Also 
unlike a *theme*, the business value is only realised when all the underlying *stories* are completed.

Example:
```
AS A salesperson, I WANT to set my password, SO THAT I can remember my login
```

This can be broken down into, e.g., the following stories:

```
1. AS AN admin, I WANT to send an email to a new salesperson, containing a tokenized link, SO THAT they can temporarily access the system 
to set a password.
2. AS A salesperson, I WANT to edit my profile SO THAT I can set my password.
3. AS AN admin, I WANT to ensure that all passwords meet corporate strength requirements, SO THAT I can provide a system hardened against
attacks.
```

Notice that the above *stories* depend on eachother for any business value to be realized.


Product Owner
-------------

Formally represents the interests of all stakeholders.

Defines the features of the product and prioritizes the backlog according to the value each *story* delivers.

Also, typically responsible for the profitability of the product and accepting or rejecting work results.


Story
-----

A *story* is a self-contained unit of work agreed upon by the developers and the stakeholders. Sometimes also called a *task*. 
Typically takes the form "AS A <user-type>, I WANT to <action/goal description> SO THAT <description of value to user>."


Task
----

Sometimes used to mean a sub-unit of work below a *story*. Other times treated as synonymous with *story* (in which case *sub-task* is 
used to describe a unit of work within a *story*).


Theme
-----

A group of related *stories*.
Often the themed *stories* all contribute to a common goal or are related in some obvious way, such as focusing on a single customer.


User
----

A type of person using the system. Defining a particular user will involve answering questions such as:

- what do they do day to day?
- what is their level of comfort with technology?
- what goals are they trying to accomplish?
- what are the daily pains they deal with?

A defined user might look something like:

**Online Holiday Shopper**
```
Rarely shops online except during the holiday season. Average comfort with computers and the internet, but throws hands up at technical 
jargon and JavaScript error messages.
Wants to shop online to avoid lines and traffic of bricks and mortar stores around the holidays.
Top ecommerce pains: having to call customer service to get order status, slow shipping, opaque order processing, having to double ship 
(get items delivered to credit card billing address then posts item on to gift recipient).
```

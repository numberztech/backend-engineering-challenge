# numberz Backend Engineering Challenge

Greetings, tinkerer!

Thank you for your interest in joining numberz! We believe our assessment process should evaluate the skills you would use on a regular day at work. For that reason, we've included this challenge as part of the process.

We appreciate that this may involve a considerable investment of your time & effort, but we’re hopeful it will ultimately be worthwhile for both you and us.

Thanks again, and all the best!
The numberz team


## Overview

The challenge involves a design phase and a coding phase.

In the design phase, you're required to come up with the high level design of a system which accomplishes the requirements that are enumerated in the next section. The high level design is a technical document that includes anything that helps effectively describe the system being worked on. This includes but isn't limited to architectural diagrams, database schema definitions, sequence diagrams, etc.

Once ready with the design submission, please drop us an email on tech-jobs@numberz.in along with the design document. We will then evaluate the submission and schedule a conversation to review the design.

After the design review, we'll kick off the coding phase which will require you to code an implementation of a small subset of what you laid out in the design.

## Requirements

The system to be designed is a product that will be used by multiple businesses, to accomplish the following requirements:
1. Store the business's invoice data (including details such as amount, customer info, due date, payment status, etc.)
2. Allow the business to manually send reminder emails for these invoices to their customers.
3. Send out automated reminders to the business's customers, for their open invoices, as per configurable rules.

Some more information:
1. Reminder rules are typically of the format: "Send (email/sms) reminder (before/after/on) due date by X days"
2. The content of the reminders should be configurable.
3. The business should be able to know which are the upcoming reminders for a customer/invoice.

Possible future enhancements to keep in mind when coming up with the design: 
1. Create reminder rules scoped at the customer level, i.e. a rule can also be created that applies only to a specific customer and not others
2. Disable/enable reminders to for specific customers/invoices
3. It's possible that on a single day multiple reminders for different invoices may need to be sent to the same customer. In such cases, the multiple reminders need to be consolidated into a single reminder.

The future enhancements are not in scope for the high level design but it would be good if the design can be created keeping that sort of extensibility in mind.

## Evaluation Criteria

Design phase:
* Architectural decisions taken and the considerations/assumptions behind them.
* Best practices followed for robustness, modularity and evolvability.

Coding phase:
* Code hygiene factors such as readability, reusability, testability, etc.
* Proficiency in our backend tech stack (Node.js, Golang) will be viewed positively.

# pgp-renewal-reminder

Little webapp to send reminders when your pgp key is going to expire.

## Workflow
* Input keyid or email
* email sent to address with verification code
* send reminders every x days
* each email has an unbubscribe link

## Services
* [Mailgun](mailgun.com) is free until lots of email.
* Write in golang, because learning
* sqlite db

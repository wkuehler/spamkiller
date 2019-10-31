# Spam Killer

Leads are created from a web-to-lead form.

In our first flow, we check to see if
-the lead contain any suspicious words (a list is maintained in the Spam Words object)
-is using a known spam email address (a list is maintained in the Spam Emails object)

If it is, we set the lead status to spam


In our second flow, on a nightly basis (scheduled flow), we delete all leads flagged as spam
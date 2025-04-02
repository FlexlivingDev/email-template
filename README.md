# WTTJ EMAIL TEMPLATES

## Introduction
Our templates are made using [MJML](https://mjml.io/)

We only store .MJML, you can create HTML using the [online editor](https://mjml.io/try-it-live) or by [installing MJML on your computer](https://documentation.mjml.io/#installation).

**I chose not to use a header / footer / css common to all templates by using mj-include.**
With includes, updates are instantaneous if you change the reference template.
But mails change without being requested and without any guarantee that they'll be put into production.
By doing this, the template is updated deliberately and with a goal of putting it into production.

We also provide a test_data.json that you can paste directly in sendgrid test data.

## Template
[**A blank template is provided to kicktart your new email**](/Blank/)


## List of templates in this repository :
- [**Email proposing an extension of stay**](/Prolongation/)

## Model for use in readme :
- Name : **template name**
- What : explanation
- Object : mail subject
- Used by : automations or applications that send the email
- Status : status of the mail
- Sendgrid Template ID : template ID in Sendgrid
- Sendgrid link : link of the last template version
- Version : version of the template
- Date : last modification date

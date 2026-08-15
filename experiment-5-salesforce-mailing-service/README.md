# Experiment 5 – Salesforce Apex Mailing Service

## Aim

To implement a mailing service using the Apex programming language of Salesforce.

## Procedure

1. Open the Salesforce Developer Console.
2. Create a new Apex class named `EmailManager`.
3. Replace the default class body with the mailing-service implementation.
4. Save the class.
5. Open **Debug → Open Execute Anonymous Window**.
6. Create an `EmailManager` object and call the `sendMail()` method with the recipient address, subject, and body.
7. Execute the code and verify the result.

## Apex Program

The `EmailManager` class creates a `Messaging.SingleEmailMessage`, sets the recipient, subject and body, sends the email, and checks the returned result.

## Execute Anonymous

```apex
EmailManager em = new EmailManager();
em.sendMail('your-email-address', 'Email Subject', 'Email Body');
```

Replace `your-email-address` with the required email address before execution.

## Result

The Apex mailing service is implemented using Salesforce and can be tested from the Developer Console.

## Output

The execution log can be checked after running the Apex code. A successful execution displays:

```text
Email sent successfully
```

## Screenshots

```text
screenshots/
├── apex-email-manager.png
└── execute-anonymous.png
```

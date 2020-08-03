# Information Security

Back to [https://tasksift.com](https://tasksift.com) ↗︎

### How is my data protected from another customer’s data?

Each of our Services has a single database for all of that Service users' data. We use software best practices to guarantee that only people who you designate as viewers of your data can access it. In other words, we segment our customer data via software. We do our best and are very confident we’re doing a good job at it, but, like every other web app that hosts their customers data on the same database, cannot guarantee that a sophisticated hacker cannot access other people's data.

### How are you protecting my data from hacker attacks?

Security is one of the main reasons we chose [Heroku](https://www.heroku.com/) \(a wholly-owned subsidiary of [Salesforce](https://developer.salesforce.com/platform/heroku)\) as the infrastructure provider for our TaskSift Services.

To see all the steps Heroku takes to protect the data saved on its services, take a look at their extensive [security page](https://www.heroku.com/policy/security). It’s what makes us sleep well at night.

We also have our own practices in place, which follow the industry’s best practices. We only give access to our servers to senior TaskSift security experts, we keep our servers always up to date with security fixes, have one-click ways to take down servers should they become infected/compromised and to create and deploy new clean ones, we have an automated suite of tests against cyber attacks, we use 2-factor authentication whenever possible, and more.

Our Services have never been compromised so far.

Should our systems get compromised we’ll shut down the service until we can fix the vulnerability. We will also hire outside experts to help us and verify that we’re safe to resume service.

### What should I do if I find a security vulnerability in a TaskSift service?

Please visit our [responsible disclosure](responsible-disclosure.md) page.


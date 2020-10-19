# Domain Model
![Domain Model](https://github.com/nmalitz/finWELL-Apps/blob/master/Auxiliary%20Files/DomainModel_Pic.png)
- User: User is the base class for every user’s account, it contains their name, username, and password.

- Dependents: A user’s spouse or other individual for which the user is able to claim a tax exemption. Dependents have a direct effect on the limits of Allocation categories.

- Employee: An employee is a user that is linked to a company, the company can utilize admins to moderate employees in various ways.

- Admin: An admin is a user that is linked to a company, the role of an admin is to supervise the employees within its company.

- Company: A collection of employees and admins, their information can be utilized by admins.

- Bank Account: A user’s account at a financial institution, i.e. bank. A user’s transaction history will be directly input into by their bank account.

- Debit Card: A card issued by a user’s bank, which is used to make transactions with their account. Transactions are made based on the balance of the account instead of on credit.

- Credit Card: A card used to make transactions based on the credit of the account holder. Credit cards, when used correctly build a user’s credit, but are destructive when used frivolously.

- Transaction History: The transactions of a designated period of time. While transactions histories are thought of as chronological, other possible ways to sort a transaction history include by transaction amount and by the effect a transaction has on the user’s taxable income.

- Transaction: An instance of buying or selling a good or service. Keeping track of transactions on a granular level is achieved when they are applied to a fitting allocation category of a user’s budget.

- Receipt: A document summarizing a transaction. Useful data recorded by receipts include an itemized list of items bought by price, the tax information for a transaction, date, et cetera.

- Budget: A way to keep track of a user’s income as well as their expenses for a set amount of time.

- Allocation Category: A category of expenses, the collection of which makes up the expenses portion of a budget.

- Savings Goal: The focus of a user’s ambition to keep their budget continuously over a consecutive number of months, or even years as the case may be. Savings Goals are an important factor in maintaining a user’s interest in a potential app focused on the budgeting process as well.

- Income Source: The source of a user’s financial earnings. For user’s who are employees of a company, that company serves as that user’s source of income.

- Balance: The amount of money left to spend in an allocation category. Being able to reference these amounts will inform the user as to their current financial position.

- Debt Category: Stores any pre existing debt input by the user and can track any new debt that may be accumulated, it can also be subtracted over time by having it in a allocated category.

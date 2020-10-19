# Use Cases
## Actors
- Users
  - Users are everyone who uses the app. From employees of an admin user, to everyday users not related to any company.
- User’s Bank Account(s)
    - A user’s bank account may be linked to the users account for a better knowledge of how much money they have available to them.
- User’s Credit Card Account(s)
    - A user's credit card information may be linked to a users account for better information on what their transaction history is, when they have their credit card bill due, and what their credit score is.
- Admin - Business owners/Management
    - An admin is a business owner or someone who has a group of users beneath and tied to them. Admins are able to monitor how certain users use the app, and help provide them with money.
- System Server
    - The system server will send and pull information from and to the database.
- Database System 
    - The database will hold all of the users accounts information, budgets, goals, achievements, etc. Everything should be encrypted and admins will have specific access to parts of it if they have employees in their domain.
# Use Cases
- UC1 - Create an account:
    - An account provides the users with the ability to save their (budgetary) data for later use. This ability is paramount to the app’s functionality as a financial tool.
    - Actors include users
    1.  Open the app
    2.  Click the “create account” option
    3.  Input basic information such as name, username, age, and password
    4.  Input financial information such as level of income, expenses, and current assets
    5.  Give the user an option to provide more details such as dependents, debts, bank account(s) , and credit card account(s)
    6.  Confirm account settings
    7.  The user-account is information is sent to the system server 
    8.  The system server sends the information to the database where it is saved.
    - This ties in with BR1
- UC2 - Edit an account:
    - Account information may become outdated and need changed in order for a user to feel their information is both secure, and up to date.
    - Actors include users and admins
    1.  Open the app
    2.  Open a profile tab
    3.  Open a settings menu for the profile.
    4.  Be given the option to change notifications, phone number, email,  linked accounts, privacy information, the ability to delete your account etc.
    5.  Confirm and save new account settings 
    6.  This information is sent to the System Server where it then update the database
    - This ties in with BR1
- UC3 - Create a budget
    - Supplying the end-user with a customized budget is the raison d’etre of this project. All other functionality is centered on being able to achieve this. By providing a budget for the user to follow, the user is able to save for goals and to meet their other financial responsibilities.
    - Actors include all users
    1. Open the app
    2. Open the profile tab
    3. Select option to create a budget
    4. Adjust three options of a percentage from remaining income after expenses : entertainment, personal goals, and savings
    5. Budget is created and displayed for user
    - This meets BR1
- UC4 - Save your created budget
    - For users to be able to refer to the budget they created, and thereby maximize the utility they receive from it, they will need to be able to save said budget and be able to reference what they saved when they select it from a previous-budget-user-menu.
    - Actors include all users
    1. After creating a budget, users can click on the “Save Budget” button.
    2. This budget is then sent to the system server
    3. The server then sends this information to the database where it is kept.
    4. Users can select their previously saved budget, which contacts the System server
    5. The system server then pulls from the database the previously saved budget
    - This meets BR1
- UC5 - Visualize spending habits
    - Users must also be able look over their past purchases and spending habits to make sure they are keeping in line with their created budget. This feature enables the user to see how much money they have spent in a budgetary category and to also see how much more money they have left to spend in said category.
    - Actors include all users
    1. Users can click on a tab that opens their profile.
    2. Users can select an option to view financial history.
    3. The app will showcase different graphs (selected by user) that show overall spending habits.
    - This ties in with BR1
- UC6 - Look at spending history
    - The ability of the end-user to look up their spending history will provide the ability to verify transactions and to analyze their spending habits.
    - Actors include all users
    1. Users click on a tab that opens their financial history
    2. If available the system Server will pull information from the users bank accounts/Credit card accounts and compile them into a list that is then sent to the user
    3. On the financial history section they can look at all their previous purchases by different formats such as by time, category, price, and more.
    4. If it is not pulled from the users bank account/credit card accounts it will have been all manually added by the user and pulled from the database.
    - This meets BR1
- UC7 - Save receipt data to assist in the tracking of spending habits
    - To assist the users in being accountable for their purchases, this feature will allow customers to more efficiently log their spending habits. Instead of having to manually enter the details of the purchase, this feature will allow them to scan their receipt to have the details of the purchase automatically logged and saved to their spending history.
    - Actors include all users.
    1. Users open a financial history section
    2. Users can manually input new transactions into the section.
    3. Alternatively whenever a transaction takes place on the users credit card/debit card the transaction is added to the financial history.
    - This meets BR1
- UC8 - Notify users that they have over-spent in an allocation category
    - This will help the user keep track of their actual spending, which will help them to better adhere to their budget on a category level.
    - Actors include all users.
    1. User inputs a transaction in an allocation category that exceeds the maximum amount allotted for the time period
    2. Alternatively the system server will pull information from the credit card company/bank that a transaction has occurred and it will add the transaction history
    3. The app will send the user a notification telling them of the overspending in X category.
    - This meets BR1
- UC9 - Provide users with financial wellness content.
    - Users lacking experience adhering to a budget will benefit from content focused on creating/maintaining good financial habits. This content, which may be provided by MoneyTree or others, will increase the customer’s exposure to them as a brand and foster a sense of brand-loyalty.
    - Actors include all users.
    1. After the user has created an account an option is available to them asking if they want to receive financial help sources
    2. If they accept this option they will be directed to financial sources based on their spending habits
    3. For example, if the user is in credit card debt, a article notification will appear informing the downsides of credit card debt
    4. Another example if the user has a bad credit score a article notification will appear informing the user how to build a better credit score
    5. Another example is if the user can not stick with their budget created an article will appear on how to be more self disciplined with their money
    6. These sources can link to Accutech or 3rd party sources
    - This meets BR1 and BR2.
- UC10 - Specify a savings goal.
    - Specifying a savings goal is a major reason to use the app. You are saving money so that you may invest it towards something later in your life. Such as your retirement or a car.
    - Actors include all users.
    1. User opens Financial Goal sections
    2. Users can create a “save money for ___” goal
    3. From there users can specify what the saving money is for.
    4. They then select how much % or $ amount they want to invest in their saving goal. Per X amount of time.
    5. The user may also specify when the goal must be met.
    6. The budget will adjust itself automatically to meet the users new savings need.
    - This meets BR1
- UC11 - A user will be able to view the progress they have made toward their savings goal.
    - This is an important factor in a user’s savings goals ability to function as motivation to adhere to a budget. The customer will see how close or far away they are monetarily from their goal, and this will motivate them to make decisions more prone to adhering to their budget.
    - Actors include all users.
    1. Once a saving goal has been created, users will be able to look at their saving goals
    2. Opening savings goal will show all saving goals and how far they are from being completed. And how much money has been put towards each category
    - This meets BR1
- UC12 - Set bill/payment reminders.
    - In order to help the client implement their budget throughout the month,, they will be given the ability to set reminders for payments. This, in conjunction with the ability to track actual spending, will provide the user with a more complete understanding of finances throughout the budgetary cycle, i.e. month.
    - Actors include all users.
    1. he user can open a bills tab
    2. From there the user can specify what bills they have and if they are recurring or not. (such as housing bill)
    3. The user can then save the bills information, that is then sent to the system server and saved on the database.
    4. Alternatively if the user has a credit card linked to their account, that information may be automatically added for when their credit card bill is due and how much they will owe.
    - This meets BR1
- UC13 - Set custom spending limit for Budgetary Category
    - The ability to set the spending limit of a budgetary category is the chief way a user will customize their budget. A budget, which is strictly composed of such categories, is customizable only to the extent that they are able to be set by the user. Once achieved, this will enhance re-use appeal.
    - Actors are users.
    1. A budget is first created automatically
    2. After it has been created users can fine tune each category to better fit their needs.
    3. Limits will be placed in each category so the user can't spend more money than they make per X amount of time
    4. The users changes will be saved and updated on the database.
    - This meets BR1
- UC14 - Show users the amount they have left to spend in a budgetary category. 
    - Knowing how much they have left to spend will assist users in making more informed decisions about which transactions to make or not make throughout the month.
    - Actors include all users
    1. Users open their budget
    2. This information is pulled from the transaction history the user has input either manually or has been pulled from the users account aggregation 
    3. On the budget section it shows users how much they have spent in each category and how much left they can spend in each category while maintaining their goal.
    - This meets BR1
- UC 15 - The user will specify a warning threshold defined by the amount of money left to spend in a budgetary category.
    - This threshold will help the user stay informed about their adherence, or lack thereof, to keeping a budget by triggering a warning at a certain threshold, which may be described by the user. If the user does not specify, the system will create a threshold for them. The user may change the threshold or turn off the warnings whenever they choose.
    - Actors include all users
    1. After creating the budget the user then can opt in to receive notifications for if their budget limits is approaching its maximum
    2. If a user is within 10% of their budget category limit they will be notified they are approaching the limit.
    - This meets BR1
- UC16 - Alter/delete any financial goals
    - It is likely that throughout the course of saving money user’s goals will change; users should be able to change their goals on the app in accordance with changes in their own goals.
    - Actors include all users
    1. User clicks on the financial goals tab
    2. User then presses on the settings option
    3. User will select to either edit or delete the goal
        - If the user decides to edit, they may change the type of financial goal and then modify the budgetary categories
        - If the user decides to delete, an “Are you sure?” Dialogue box appears
        - If they select yes, the financial goal will be deleted and cleared from the database
        - If they select no, they are returned to the settings screen
    4. This information is saved on the database
    - This meets BR1
- UC17 - If a user has not used the app within a customizable amount of time, then they will receive a notification.
    - This is important because if users are not using the app, they are likely not following their desired budget.
    - Actors include all users
    1. While the user is creating an account they are given an option to receive notifications 
    2. If the user accepts phone notifications they are automatically set to receive a notification if they do not open the app within 7 days of their last opening.
    3. If the users want they can adjust this setting to be weekly, or monthly, or opt out completely
    4. The notification will simply inform the user they have not accessed their budget in X amount of time and may struggle to stick to their goals if they don't pay attention to their spending habits
    - This meets BR1
- UC18 - Users should be able to reward themselves for sticking to their financial goal
    - The user should be rewarded for staying in line with a set financial goal. At the end of a set period (month), if the user stayed on track for a financial goal they should be able to choose from a set of options how they want to reward themselves. (Such as a gift card, charity, or no reward). This would make the user feel good that they are meeting their goals.
    - Actors include all users
    1. At the end of the month, if a user has maintained all of their budgetary categories, a menu should appear on the user's home screen\
    2. This menu will allow the user to select an option as to accept to reward themselves or not
    3. The options should be a small reward ($5 gift card), donating the money to a charity, or adding the money back into their savings
    - This meets BR1
- UC19 - Add payment methods (Such as credit card/debit card) to track spending
    - This will be useful to the user because it can help them know how much money they are putting on credit cards, or how much they have left in their accounts
    - Actors include all users
    1. After creating an account users can add payment methods to their account
    2. When adding receipts, or financial spending they can select which mode of payment they used
    3. Side Note: If this is to become account aggregation we will need to have direct access with several banks such as Chase or MasterCard.
    - This meets BR1
- UC20 - Edit/delete/add expenses, income, dependencies, and current assets
    - This will help users maintain and change their budgets in relation to their current financial status. If something changes to their current income, they can still plan ahead and adjust any financial goals they have set in place.
    - Actors include all users
    1. When viewing budgets, users can select a button to edit said budget.
    2. Users will be prompted to re-enter income/expenses/other info that will change the budget.
    3. The app will automatically adjust the budget according to this new information.
    4. The new information will update the current budget and be saved on the database
    - This meets BR1
- UC21 - Visualize Planned (future) savings
    - This can greatly motivate users because they can visualize how much money they will have saved, or earned over the course of time. It may also help them to understand how long it may take to have money saved up for something they may want to buy, such as a car.
    - Actors include all users
    1. The user opens their budget.
    2. From their the user can open a “Future Finances tab”
    3. From here the user can specify how far into the future they want to see their assets/debts if they stick with their budget. (such as 3 months or 3 years).
    4. When this is chosen the System Server contacts the database and calculates how much money they will have saved if the user has kept their financial goals
    5. The system server then sends this information to the user for their benefit.
    - This meets BR1
- UC22 - Match with a MoneyTree adviser if the consumer wants help
    - This would greatly help users who have issues with either the app or struggle with meeting their financial goals. By providing the user with a real person from Moneytree it also makes MoneyTree a more known and trusted company.
    - Actors include both users and Admins
    1. Users/admins open a “contact us” page
    2. On that page it provides users with a link to Moneytree, and some of its employees specialized in helping users navigate the app and their goals
    - This meets BR2
- UC23 - The user should be able to link their bank account/credit cards on their user-account.
    - This would make the functionality of the app much easier on the user, as much of the input would be done automatically instead of manually. It would also enable them to see a much more clear picture into their finances in a single place rather than have all that information spread across multiple platforms.
    - Actors include all users 
    1. When creating an account the user can provide their bank/credit card information
    2. They may also provide that information at any later time in their account settings
    3. Once that information is provided it is sent to the system server before being saved in the database. (All of this information is encrypted for the sake of security)
    - This meets BR1
- UC24 - Admin users can create their employee’s users-accounts
    - This is important for large business who want their employees to use the app. By taking the responsibility away from the user it makes it easier for employees to use the app.
    - Actors include Admins
    1. Admins use a web application that allows them to create/edit accounts that fall into their companies jurisdiction.
    - This meets BR3
- UC25 - Admins can see how their employees are using the app
    - This is important for Admins as it ensures their employees are actually using the app, and they can see HOW they are using the app. (As well as what they use and don't use within the app)
    - Actors include all admins
    1. From a web application admins can look at a database that holds all of their employees (encrypted) data 
    2. Admins can specify what categories they wish to see and visual how their employees use the app
    - This meets BR3
- UC26 - Have company admins put money into the system for its employees' benefit.
    - To further incentivize the use of the app by employees in a corporation, managers should be able to add money to a pool to be allocated towards prizes and incentives for employees who follow their budgets. This will increase accountability in their budget, which serves to further MoneyTree’s goal of employee participation. At the end of a set period (month), users who maintained their budget categories would be able to choose a small prize from the pool or have it directly entered into their savings.
    - Actors include admins
    1. Admins use their web application and open a “Employee Incentive Program” section
    2. From there Admins can invest money into the app of their choosing
    3. After specifying how much money they wish to invest, they can select how much employees are able to receive for reaching their goals (such as 5$, 10$ etc)
    4. They are also able to specify if they can receive rewards multiple times or only one
    5. From there the money is saved into an account, and it is later given to users who complete their goals under their employees. The money will be sent into the users aggregated accounts
    - This meets BR3
- UC27- Users can earn badges for completing savings goals
    - By giving users little badges for achieving their financial goals it can give users something to look at as proof of their actions. This would help foster a more enjoyable experience when saving money
    - Actors include all users
    1. Users can earn badges in multiple ways. For example the user creates a financial goal and follows it for 1 month.
    2. That information is sent to the System server that adds that accomplishment to the database.
    3. The database stores what badges the users have achieved and how many time they have achieved it
    - This meets BR1
- UC28 - Users should be able to implement religious themes within their app experience if that is their preference.
    - Since MoneyTree is a faith-based company, part of its goal is to promote its philanthropic and religious values. As a method of promoting this, users should have the option to toggle on or off a faith-based encouragement mode.
    - Actors include users
    1. Users select the options menu from the home screen of the application
    2. Users will then toggle the faith-based encouragement button on or off
    - This meets BR1

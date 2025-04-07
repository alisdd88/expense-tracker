# expense-tracker

✅ Authentication Routes (/api/v1/auth)
Handles user login, registration, and profile.

Method	Endpoint	Description
POST	/register	Register new user
POST	/login	Login + get token
GET	/profile	Get user info
💸 Transaction Routes (/api/v1/transactions)
Create, view, update, delete and filter transactions.

Method	Endpoint	Description
POST	/add	Add new transaction
GET	/user/:userId	Get all user's transactions
GET	/user/:userId/stats	Get stats (monthly, by category)
PUT	/:id	Update a transaction
DELETE	/:id	Delete a transaction
💰 Budget Routes (/api/v1/budgets)
Manage user budgets per category/month.

Method	Endpoint	Description
POST	/add	Add a new budget
GET	/user/:userId	Get user's budgets
PUT	/:id	Update budget
DELETE	/:id	Delete budget
🛡️ Admin Routes (/api/v1/admin)
For admin dashboard (user management).

Method	Endpoint	Description
GET	/users	List all users
DELETE	/users/:id	Delete user

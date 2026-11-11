# Daily Budget Splitter

Offline budget app: split a total over days, track plans, and find a realistic budget from your spending.

- `budget-splitter.html`: the app (SQLite via sql.js is embedded, works offline)
- `budget.sqlite`: empty starter database; keep it in the same folder as the HTML and open it from the app's Data tab

Older database files upgrade automatically when opened.

## Layout

- Bottom navigation: Home, Planner, Tracker
- Home: demo account (not real money) with balance, add/withdraw, activity and a summary
- Planner and Tracker each have a New and a My list (plans or trackings)
- Turn on "Link to my account" when creating a plan or tracking (or later on its page) and what you log is taken out of the account balance

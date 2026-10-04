# Grocery Expense Tracker public legal pages

These static pages are designed for a separate, public GitHub Pages repository.
They do not contain app source, secrets, receipts, analytics or JavaScript.

- `privacy.html`: use its public URL in Play Console's Privacy policy field.
- `delete-account.html`: use its public URL in Data safety's account-deletion field.
- `how-it-works.html`: user guide for saving/reviewing receipts, main currencies,
  foreign-currency conversion, date filters, reports and Excel exports.
- `index.html`: entry page linking to the guide and both legal pages.

The app's version 3 privacy agreement links to the public privacy policy and
describes temporary cloud storage for queued analysis and direct Frankfurter
exchange-rate requests. Version 1.4 requires acceptance of this updated agreement.
Currency preferences and selected rates remain in the account's private archive
on the phone; there is no hosted currency-profile database or archive sync.
Unknown currency uses the main currency provisionally and is flagged for review;
a known foreign receipt without a rate is excluded from converted totals.

Public URLs:

- https://shumaly.github.io/grocery-expense-tracker-legal/
- https://shumaly.github.io/grocery-expense-tracker-legal/how-it-works.html
- https://shumaly.github.io/grocery-expense-tracker-legal/privacy.html
- https://shumaly.github.io/grocery-expense-tracker-legal/delete-account.html

Review this policy whenever the app, cloud service, AI provider, retention or
support contact changes. In particular, the current server-side quota record
has no automatic expiry and is not deleted by the current in-app account-delete
action; the published text states that limitation rather than promising more.

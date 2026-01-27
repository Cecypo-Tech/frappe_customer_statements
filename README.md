# Customer Statements

Our first open source app for Frappe's ERPNext!

# UPDATES - Jan 2026
- Fixed issue with some not being able to generate PDF's (caused by a customized field that we use ourselves)

# Better **Statements**
- Prettier & more compact for both; **GENERAL LEDGER** & **ACCOUNTS RECEIVABLE**
- `Show Remarks` shows/hides the whole column for better spacing
- Better formatting for `terms & conditions`
- Includes `Future Payments` in a compact list
- Includes custom fields for Kenyan based TIMS (e-invoicing) integrations, but should not effect you, should you not use such

# Screenshots
## What does this app effect?
![Effect](https://i.imgur.com/b1YIDEy.png)
## General Ledger
![Statement of Account](https://i.imgur.com/MakMjKv.png)*(updated Jan 2026)*
## Accounts Receivable
![Accounts Receivable](https://i.imgur.com/GVnVwH8.png)*(updated Jan 2026)*
## Sample with letterhead set (for multi-company setups)
![Letterhead](https://i.imgur.com/ZB5rrWE.png)
## Installation

```bash
$ bench get-app https://github.com/Cecypo-Tech/frappe_customer_statements.git
$ bench --site <site_name> install-app customer_statements
```

#### Other
If you are interested in our TIMS Integration (Kenya), see our (paid) direct integration tool here: https://docs.cecypo.tech/s/kb/doc/erpnext-O7U5xeE9DN

#### License

agpl-3.0
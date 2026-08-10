
1. Cloud Platform
2. Organization can store business data
3. Build applications around that data
4. Automate processes
5. Give employees/customers interfaces to interact with it.

                 SALESFORCE
                     │
       ┌─────────────┼─────────────┐
       ↓             ↓             ↓
     DATA         BUSINESS       USER
                  LOGIC          INTERFACE
       │             │             │
    Objects         Flow          Apps
    Records         Apex          Forms
    Fields          Rules         Dashboards



Salesforce itself uses the table analogy when explaining its data model.
For example:

```
Account
────────────────────
Id
Name
Phone
Industry
Address
```

That's an **Account object**.

Then individual rows are:

```
Account
────────────────────────────
Id       Name
001      Microsoft
002      BMW
003      Sathyabama
```

Those individual rows are called:

> **Records**

And the columns are:

> **Fields**

So:

|Normal database|Salesforce|
|---|---|
|Database|Org|
|Table|Object|
|Row|Record|
|Column|Field|
|SQL|SOQL|
|INSERT/UPDATE/DELETE|DML|
|Application|Salesforce App|
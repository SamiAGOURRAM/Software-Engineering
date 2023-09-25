# Execrcices

## Exercice 1:

### Functional Requirements:

1. The ATMs must allow Mary Geoise customers to check balances.
2. The ATMs must allow Mary Geoise customers to withdraw funds.
3. The ATMs must allow Mary Geoise customers to pay cash and cheques in.
4. The ATMs must allow Mary Geoise customers to print a mini statement of their last 5 transactions.
5. Customers of other banks will be able to check balances.
6. Customers of other banks will be able to withdraw funds.
7. Users will be limited to making 3 withdrawals in a 24-hour period up to a maximum of 2000MAD total.
8. At the end of each business day, a report will be produced of all successful and unsuccessful transactions.

### Non-Functional Requirements:

1. The ATMs must be available 23 hours a day, 7 days a week. Any downtime must be between 2 am and 4 am.
   - This is a non-functional requirement related to system availability and uptime.

2. The display screen and buttons must comply with Disability Access legislation.
   - This is a non-functional requirement related to compliance with accessibility standards and regulations.

3. Users will be identified by the card number used and this will be authenticated by entering a PIN.
    - this a non-functional requirement related to security.

4. Three incorrect PIN entries will cause the card to be retained.

## Exercice 2:


### Functional Requirements:

1. All new customers need to be added to the system easily.
3. Office staff can do 1. & 2. and so can customers themselves, via the website.
4. The system should generate (but not send) invoices automatically as orders are received.
5. Office staff (only) must be able to revise the details of an order, and a new invoice should be generated as a result.( the exclusive part is a non-functional requirement related to security )
6. Weekly reports of unpaid invoices will be needed by the Managing Director.
7. Office staff must be able to print invoices or email them to customers.
8. The Production Manager would like to be able to view all customer orders so that she can plan production.
9. It should be possible to vary the payment terms on the invoices.
10. It all needs to interface with the payroll system (MD’s requirement).

### Non-Functional Requirements:

1. (The system must record customer orders (not payments yet) up to about 50 per day). These need to be retained for five years.
   - Category: Data Retention
2. Weekly reports of unpaid invoices will be needed by the Managing Director.
   - Category: Reporting


Ambiguities in the Requirements:
- The requirement "All new customers need to be added to the system easily" is somewhat ambiguous. It doesn't specify what "easily" means or the exact process.
- The statement "The system should generate (but not send) invoices automatically as orders are received" could be clarified regarding the criteria for generating invoices and what happens after they are generated but not sent.

Solution Language:
- The requirement "The system must record customer orders (not payments yet) up to about 50 per day" contains a degree of ambiguity with "about 50 per day." It would be better to specify an exact number for clarity.

Now, let's use the MoSCoW prioritization technique to prioritize these requirements:

- Must Have:
   1. All new customers need to be added to the system easily.
   3. Office staff can do 1. & 2. and so can customers themselves, via the website.
   5. Office staff (only) must be able to revise the details of an order, and a new invoice should be


## Exercice 3:


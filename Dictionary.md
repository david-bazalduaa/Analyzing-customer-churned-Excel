# Metadata
---

## 🧍 Customer Status

| Column            | Description                                                                 |
|-------------------|-----------------------------------------------------------------------------|
| `Customer ID`     | Unique identifier for each customer.                                        |
| `Churn Label`     | Indicates if the customer churned (`Yes` or `No`).                          |
| `Churn Category`  | Groups churn reasons into broader categories.                              |
| `Churn Reason`    | Specific reason the customer ended the contract.                            |

---

## 👤 Demographics

| Column     | Description                                                                 |
|------------|-----------------------------------------------------------------------------|
| `Age`      | Age of the customer.                                                        |
| `Under 30` | Indicates if the customer is under 30 (`Yes` or `No`).                      |
| `Senior`   | Indicates if the customer is above 65 (`Yes` or `No`).                      |
| `Gender`   | Gender of the customer: `Male`, `Female`, or `Prefer not to say`.           |

---

## 🤝 Contract Information

| Column                    | Description                                                                 |
|---------------------------|-----------------------------------------------------------------------------|
| `Group`                   | Indicates if the customer is in a group contract (`Yes` or `No`).           |
| `Number of customers in a group` | Number of customers in that group.                                    |
| `Phone Number`            | Customer’s phone number.                                                    |
| `State`                   | State code where the customer resides.                                     |
| `Payment Method`          | `Credit Card`, `Direct Debit`, or `Paper Check`.                           |
| `Contract Type`           | `Month to Month`, `One Year`, or `Two Year`.                                |

---

## 📞 Subscription Types & Charges

| Column                    | Description                                                                 |
|---------------------------|-----------------------------------------------------------------------------|
| `Account Length`          | Number of months the customer has been with Databel.                        |
| `Local Calls`             | Number of local (within the US) calls made.                                 |
| `Local Mins`              | Total minutes of local calls.                                               |
| `Intl Calls`              | Number of international calls made.                                        |
| `Intl Mins`               | Total minutes of international calls.                                       |
| `Intl Active`             | Indicates if the customer called internationally (`Yes` or `No`).          |
| `Intl Plan`               | Indicates if the customer has a premium international calling plan.        |
| `Extra International Charges` | Charges for international calls without a plan.                          |
| `Customer Service Calls`  | Number of calls made to customer service.                                   |
| `Avg Monthly GB Download` | Average monthly download volume in GB.                                     |
| `Unlimited Data Plan`     | Indicates if the customer has unlimited data (`Yes` or `No`).               |
| `Extra Data Charges`      | Charges for additional data for customers without unlimited data.           |
| `Device Protection & Online Backup` | Indicates if the customer pays for these services (`Yes` or `No`). |
| `Monthly Charges`         | Average of all monthly charges.                                             |
| `Total Charges`           | Total sum of all monthly charges.                                           |

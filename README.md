### SQL Fraud Detection Batch Rules

<br>

#### Big Sellers Risk Profiles:
- **BOF**: Break Out Fraud (biggest risk, high cashout, fast action, with intention)  
- **FOS**: Fade Out Seller (churn users that stop selling and generate a long tail cashout without intention)  
- **BES**: Bad Experience Seller (big sellers that have problems with shipments and claims, no cashout risk, but bad experience for buyers)

<br>

| Rules above             | Assigned Profile |
|:------------------------|:-----------------|
| Bad shipments BES (BSB) | BES              |
| Electronics peak        | BOF              |
| High claim alert        | FOS              |
| Induced BOF by fakes    | BOF              |
| Micro BOF               | BOF              |
| Money advance peak      | BOF              |

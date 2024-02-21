# Nordic Banking System

We are creating a new internal system for a bank, to be used solely by the banks employees across different departments.
The system i supposed to support all the primary parts of the bank and including costumer accounts and loans, arbitrage and provide overviews of the bank's finances. The system will have restrictions dependent on which department the user is associated with, and should include logging to make sure transactions are tracked. The system must take into account that it is a legal requirement in Denmark to report gains/losses, interest attributions and more, to the government tax department. 

As a start we have decided to focus on the functionality of the advisors.

### Primary Actors.
- Advisors
- Financial employees
- HR
- Director

### Advisors

- Issuing / handling of loans
- Administer transactions
- Handling of stocks
- Sales and administring of insurances 
  
#### Use Cases for rådgiver
- Deposits (Personal accounts + customers, affiliated accounts, money deposits and withdrawals, interest, automatic payment services)
- Loans (Creation of loans, handling and change of loan conditions)
- Stocks (Customer stocks, Acquiring + sales of stocks, handling of stock depots)
- Insurance (Cooperation with insurance companies or sales of the banks own insurances, risk, customer payment of bills + payment of insurance benefits)
  

### Financial employees

- Overview of the banks finances
- Budget creation for the banks different departments.
- Setting and tracking the banks financial goals. 

  
### HR
- Administration of the banks employees.
- Hiring of employees.
- Handling salaries across every department of the bank. 


### Director

- Should be able to access relevant information from the different departments, but not access to peoples accounts and such.
# C5 : Core Banking Systems

# 1. Overview of Banking Services

## 1.1 Introduction

Factors that helped banks reach high levels of service delivery :

- IT
- Government Reforms
- Government focus for financial inclusion of all Indians
- Growth of Internet

## 1.2 Overview of Banking Services

Key features of banking business :

- Custody of large volumes of monetary items whose physical security should be ensured.
- Dealing in large volume of transactions
- Operating through geographically dispersed branches
- Increased possibility of Fraud

Major Products and Services :

- Acceptance  of Deposits
- Granting of Advances
- Remittances ( Transfer of funds from one place to another )
    - RTGS ( Real Time Gross Settlement )
    - NEFT ( National Electronic Funds Transfer )
    - IMPS ( Immediate Payment Service )
- Collections
- Clearing
- Letters of Credit and Guarantees
- Credit Cards
- Debit Cards
- Other Banking Services
    - Retail Banking
    - High Net Worth Individuals
    - Risk Management
    - Specialized Services

## 1.3 Overview of Core Banking Systems ( CBS )

Refers to a common IT solution wherein a central shared database supports the entire banking application.

Characteristics :

- Common Database in a Central Server → Consolidated view of operations
- Branches function as delivery channels
- Components designed to meet the demands of banking industry
- Benefits to customer of the Bank and not the Branch
- Modular Structure
- Integration of third-party applications

Key Modules 

- Back End Applications
    - Back Office
    - Data Warehouse
    - Credit card system
    - ATM Switch
- Central Server
- Front End Applications
    - Mobile Banking
    - Internet Banking
    - Phone Banking
    - Branch Banking

## 1.4 Core Features of CBS

- Basic Banking Services
- On-line real time delivery
- transactions posted immediately
- databases updated simultaneously
- centralized operations
- remote interaction with customers
- anytime anywhere access to customers and vendors
- automatic processing of standing instructions

# 2. Components and Architecture of CBS

## 2.1 Technology Components of CBS

CBS deployed by banks include Data Centre (DC) and the disaster recovery centre

Key technology components of CBS are :

- Database environment
- Application environment
- web environment
- security solution
- connectivity to corporate network and the internet
- Data center and disaster recovery center
- Online transaction monitoring for fraud risk management

Some key aspects built into CBS architecture are :

- Information flow
- Customer centric
- Regulatory compliance
- Resource optimisation

## 2.2 CBS IT Environment

Includes :

- Application Server
- Database server
- ATM Channel Server
- Internet Banking Channel Server
- Web Server
- Proxy Server
- Anti virus software server

## 2.3 Functional Architecture of CBS

CBS is modular in nature and is generally implemented for all functions or for core functions as decided by the bank.

## 2.4 Internet Banking Process

Deemed irrelevant 

## 2.5 e-Commerce Transaction processing

Deemed irrelevant 

## 2.6 Case Study

Deemed irrelevant 

## 2.7 Implementation of CBS

- Planning
- Approval
- Selection
- Design & Develop / Procure
- Testing
- Implementation
- Maintenance
- Support
- Updation
- Audit

# 3 CBS Risks, Security Policy and Controls

## 3.1 Risk Associated with CBS

1. Operational Risk
    - Components include processing risk, information security risk, legal risk, compliance risk and people risk
2. Credit Risk
3. Market Risk 
4. Strategic Risk ( Business Risk )
5. Compliance Risk
6. IT Risk
    - Ownership of data/process
    - Authorization process
    - Authentication process
    - Maintaining response time
    - Access Controls etc.

## 3.2 Security Policy

Information Security ( ISO 27001:2013 ) : confidentiality, integrity and availability of information. Comprised of the following sub processes :

- Information Security policies, procedures and practices
- User Security Administration
- Application Security
- DB Security
- OS Security
- Network Security
- Physical Security

[[Risk & Control w.r.t Information Security]]

## 3.3 Internal Control Systems in Banks

Objective : Ensure orderly and efficient conduct of business, adherence to management policies, safeguarding assets through prevention and detection of fraud and error, ensuring accuracy and completeness of the accounting record and timely preparation of the reliable financial information.

1. Internal control in banks : examples 
    - Work of one staff member checked by another
    - System of job rotation
    - fixed financial / administrative powers for each person and properly communicated
    - books balanced periodically
    - fraud prone items and securities are in custody of at least 2 officials
2. IT Controls in Banks 
    - Record of log-in and log-out
    - transactions in dormant account halted and processed only with supervisory password
    - System checks : Amount withdrawn is within drawing power
    - access to system only in stipulated time and specific days
    - user timeout is prescribed
3. Application Software

    4 Gateways :- Configuration, Maters, Transactions and Reports

[[Risk & Control w.r.t Application Controls ]]

4. CBS: Core banking process - relevant risks and control

[[Risk & Control w.r.t CASA Process ]]

[[Risk & Control w.r.t Credit Card Process ]]

[[Risk & Control w.r.t Mortgage Process ]]

## 4 Reporting Systems and MIS, Data Analytics and Business Intelligence

Risk Prediction for Basel III based on AI

Basel III - comprehensive set of reform measures developed by Basel Committee on Banking supervision , to strengthen the regulation, supervision and risk management of the banking sector.

- Improve banking sectors ability to absorb shocks arising from financial and economic stress.
- determining capital adequacy based on risk assessment.

Data from the CBS is transferred to a data warehouse which stores data in multi dimensional cubes. 

Data in the warehouse is never purged.

# 5 Applicable Regulatory and compliance requirements

## 5.1 Impact of technology on Banking

- In CBS Environment, technology encompasses all the four critical components which are business process, policies and procedures, regulatory requirements and organizational structure.
- These are embedded inside and are facilitated through technology

## 5.2 Money Laundering

- Process by which the proceeds of a crime and the true ownership of those proceeds are concealed or made opaque so that proceeds appear to come from a legitimate source.
- Objective - Conceal the existence, illegal source or illegal application of income to make it appear legitimate.

Stages of Money Laundering 

1. Placement 
2. Layering
3. Integration 

Anti-Money Laundering using Technology 

- Special fraud detection and risk management software to prevent and detect fraud and integrate this as part of their internal process.

Financing of Terrorism

- Unlike conventional money laundering, the money frequently starts out clean i.e. as a charitable donation before moving to terrorist accounts. Highly time sensitive requiring immediate response

## 5.3 Cyber Crimes

- Crime that involves use of a computer or a network.
- Definition - " Offences that are committed against individuals or group of individuals with a criminal motive to intentionally harm the reputation of the victim or cause physical or mental harm, or loss, to the victim directly or indirectly, using modern telecommunication networks such a Internet and mobile phones"
- UN Classification
    - Committing of a fraud by manipulation of input output or throughput of a computer based system
    - Computer forgery which involves changing images or data stored in computers
    - Deliberate damage caused to computer data or programs
    - Unauthorized access to computers
    - Unauthorized reproduction of computer programs or software piracy
    - Cyber-warfare

## 5.4 Banking Regulation Acts

1. Negotiable Instruments Act 1881
2. RBI Regulations
3. Prevention of Money Laundering Act
4. Information Technology Act
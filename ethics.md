# 4.4 Ethical and Social Issues

## 4.4 Ethical and Social Issues overview
The information environment at Truelec generates material privacy and security requirements due to the existence of numerous systems that gather and utilize operationally sensitive and personal information. Customer identity records and transaction records can be stored in the booking application, employee records can be stored in HR and payroll systems, invoices and payment-related data can be stored in finance systems, and physical security technologies (CCTV, RFID access control, and IoT sensors) will create continuous logs, the analysis of which may tell about habits over time. There are also ethical risks in the form of external cyber attack and excessive collection, ambiguous limit of purpose, limited transparency, and unsuitable internal access. Privacy-by-design and governance controls, therefore, should be used to balance technical protection to make sure that data is accessed in the ways that are proportionate, legally and in the manner that would not be considered as breaching the trust of stakeholders.

## 4.4.1 Data collected by system
- **Booking application:** Customer identifiers (e.g., name, contact details) and booking history (services, dates, outcomes).
- **HR/payroll:** Employee identifiers, employment records, payroll information, and related HR administration data.
- **Finance/accounting:** Invoices, transaction records, and payment references needed for accounting and audit.
- **CCTV/RFID:** Video footage and access logs (badge IDs, timestamps, entry/exit events).
- **IoT sensors:** Telemetry (equipment status, environmental readings) and, depending on placement, presence- or location-adjacent information.

## 4.4.2 Key concerns across the data lifecycle
- **Collection:** Apply data minimisation and clear notice. To ensure CCTV and access logging, transparency is paramount due to the impact of monitoring on autonomy and trust in the workplace, and its possible need to be formally notified based on jurisdiction.
- **Storage:** Enforce retention limits, encrypt sensitive stores, and restrict access to authorised roles. Over retention is a contributor to breach impact and may be in excess of expectations due to necessity.
- **Use and sharing:** Installing role-based admissions and formal management to third-party contractors. Documents on purpose limitation and approvals should be used to prevent secondary use (function creep).
- **Monitoring:** Establish limits on employee surveillance (what/why/who/who will see it; and retention), and convey policies to create the legitimate expectations.

## 4.4.3 Relevant regulations and implications
The Privacy Act 1988 (Cth) and the Australian Privacy Principles (APPs) at the national level present the rights of collection, use/disclosure and a secure handling of personal information. Under the Notifiable Data Breaches (NDB) scheme, individuals and the OAIC should be notified about a breach that is likely to cause serious harm. In case the monitoring of the employees is in scope, a good example of a state definition is New South Wales Workplace Surveillance Act 2005, which puts forth conditions, including making prior notification of some types of monitoring in the workplace.

## 4.4.4 Impact analysis if a breach occurs
- **Customers:** Misuse or fraud risk of identity, loss of trust, and loss of desire to pay to the business.
- **Employees:** Privacy harm and distress; exposure of access patterns may raise safety concerns.
- **Truelec:** Exposure to regulations, recovery and response costs, operational downtime and reputational loss that could impact tenders and client relations.
- **Clients:** Commercial and contractual damages in case of the project documentation or site information disclosure.

## 4.4.5 Mitigation and ethical handling practices
Truelec should apply minimisation and retention schedules aligned to stated purpose, Enforce least privilege and periodic access reviews, encrypt sensitive data at rest and maintain secure, tested backups, publish clear CCTV/RFID policies (purpose, access restrictions, retention, escalation), and maintain an incident response plan with defined decision points for NDB notification readiness. The practices minimize the risk of unauthorised access, as well as the magnitude of harms in case of breach.

## References
- OAIC. Australian Privacy Principles. https://www.oaic.gov.au/privacy/australian-privacy-principles
- OAIC. About the Notifiable Data Breaches scheme. https://www.oaic.gov.au/privacy/notifiable-data-breaches/about-the-notifiable-data-breaches-scheme
- Australian Government. Privacy (Privacy Act 1988 overview). https://www.ag.gov.au/rights-and-protections/privacy
- NSW Legislation. Workplace Surveillance Act 2005 (NSW). https://legislation.nsw.gov.au/view/whole/html/inforce/current/act-2005-047

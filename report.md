# **Benchmarking Service Canada Against Private Industry: A Strategic Gap Analysis and Modernization Roadmap**

## **Executive Strategic Assessment**

The delivery of public services in Canada stands at a critical inflection point. For decades, the public sector operated in a quasi-monopolistic environment where service standards were defined by internal capacity rather than consumer demand. However, the acceleration of digital transformation in the private sector—specifically within the banking and insurance industries—has fundamentally recalibrated citizen expectations. Today, a Canadian citizen who can secure a mortgage approval in minutes via a mobile application or receive an insurance payout seconds after filing a claim views the federal government’s service delivery not through the lens of historical public administration, but through the immediate, frictionless standards set by financial institutions. This report presents an exhaustive benchmarking analysis comparing Service Canada—the federal government’s primary service delivery arm—against private industry leaders. The analysis reveals a profound divergence in Key Performance Indicators (KPIs), technological maturity, and operational agility, suggesting that the "trust gap" between the state and its citizens is widening due to a disparity in the velocity and reliability of service.

While Service Canada has made commendable strides in stabilizing post-pandemic operations, particularly in passport delivery where volume surges were met with resource mobilization, the underlying operational models remain rooted in legacy frameworks. The private sector has successfully leveraged Artificial Intelligence (AI), cloud-native infrastructure, and biometric authentication to drive the marginal cost of transactions near zero while enhancing customer satisfaction. In contrast, Service Canada’s modernization efforts, such as the Benefits Delivery Modernization (BDM) programme, have been plagued by structural rigidities, cost overruns, and timeline extensions. The data suggests that by adopting specific private sector methodologies—specifically in automation, identity management, and predictive fraud prevention—Service Canada could realize billions in operational savings and recover millions of hours in citizen productivity. This report dissects these disparities across contact centers, benefits processing, digital platforms, and integrity services, offering a ranked roadmap for high-ROI transformation.

## **1\. Introduction: The Imperative for Comparative Benchmarking**

### **1.1 The Shifting Paradigm of Service Delivery**

Service Canada serves as the primary interface between the Government of Canada and its citizens, managing critical social safety nets including Employment Insurance (EI), the Canada Pension Plan (CPP), and Old Age Security (OAS). With a mandate to provide a single point of access to a wide range of government services, the organization manages a transactional volume that rivals Canada's largest financial institutions. In the 2023-2024 fiscal year alone, Service Canada processed approximately 4.8 million passport applications and managed 2.9 million Social Insurance Number (SIN) transactions.1 The scale of these operations places Service Canada in a unique category of "mega-service" providers, comparable only to the major Schedule I banks and national insurance carriers in terms of client base and transaction throughput.

However, the operating environment for these entities has diverged significantly. The private sector, driven by fierce competition and the existential threat of fintech disruption, has aggressively pivoted toward "digital-first" and "mobile-first" operating models. Banks like TD Bank Group and insurers like Intact Financial Corporation have transformed themselves into technology companies that sell financial products, investing heavily in Artificial Intelligence (AI) and data analytics to streamline operations and personalize the customer journey.3 Conversely, Service Canada operates within a legislative and bureaucratic framework that prioritizes risk aversion, procedural equity, and statutory compliance, often at the expense of speed and user experience.

### **1.2 Defining the Comparator Group**

To provide a meaningful benchmark, this report selects the **Retail Banking** and **Property & Casualty (P\&C) Insurance** sectors as the primary comparators. These industries share the core structural constraints and responsibilities of Service Canada:

* **Regulatory Complexity:** Both sectors operate under strict regulatory oversight (OSFI for banks/insurers; various Acts for Service Canada) requiring rigorous compliance and audit trails.  
* **Identity Assurance:** Both must adhere to high standards of identity verification ("Know Your Customer" or KYC) to prevent money laundering and fraud, analogous to the identity management required for passports and SINs.  
* **Financial Consequence:** The core "product" is often the accurate and timely disbursement of funds (claims/benefits) based on complex eligibility criteria.  
* **Scale:** Both manage millions of client accounts and handle surges in demand (e.g., disaster claims for insurers; economic downturn claims for EI).

By analyzing the delta between Service Canada’s performance and these private sector peers, we can isolate specific areas where technological platforms and operational philosophy influence KPIs.

## **2\. The Contact Centre Ecosystem: Velocity, Access, and Deflection**

The contact centre remains the primary escalation channel for complex inquiries in both the public and private sectors. It is the "front door" for citizens in distress and customers with urgent issues. However, the performance metrics reveal two distinct operational realities: one focused on *containment and speed*, and the other managing *queue volume and duration*.

### **2.1 The "Time Tax": Average Speed of Answer (ASA) Disparities**

The most visceral metric for any service user is the Average Speed of Answer (ASA)—the time spent waiting on hold. The banking industry standard for ASA in North America hovers around 20 seconds, with a rigorous service level target of answering 80% of calls within that timeframe.5 High-performing contact centres in the financial sector view long wait times not merely as an annoyance, but as a failure of digital containment; if a customer is waiting, it implies that self-service channels have failed to resolve the intent.

In stark contrast, Service Canada’s Employment Insurance (EI) call centre maintains a service level target of answering 80% of calls within 10 minutes.6 This represents a 2,900% difference in "acceptable" wait times between the two sectors. Even with this relaxed standard, year-to-date results for 2024 indicated a struggle to meet targets during peak periods, with year-to-date service levels sitting at 78.5%, significantly below the target.6

The implications of this "Time Tax" are substantial. For a private bank, a 10-minute wait time would result in massive customer churn and brand damage. For Service Canada, which operates as a monopoly, the cost is transferred to the citizen in the form of lost productivity. If 2 million callers wait 10 minutes each, roughly 333,000 hours of productive time are lost to the Canadian economy annually.

### **2.2 Table 1: Comparative Contact Centre Metrics**

| Metric | Private Banking Sector Benchmark | Service Canada (EI Call Centre) | Operational Gap |
| :---- | :---- | :---- | :---- |
| **Service Level Target** | 80% of calls answered within 20 seconds 5 | 80% of calls answered within 10 minutes 6 | **30x Slower Target** |
| **Actual Performance** | Consistently \>80% (Top Tier) | \~78.5% (Year-to-Date 2024\) 6 | **Consistency Gap** |
| **Abandonment Rate** | \< 5% 7 | Historical highs \> 10% (Peak periods) | **Significantly Higher** |
| **Average Handle Time (AHT)** | Decreasing due to AI-assist ("Unified Desktop") | High due to legacy systems/manual lookups | **Efficiency Gap** |
| **Cost Per Contact** | $2.70 \- $5.60 5 | Est. \>$15.00 (Public Sector Average) | **3-5x Cost Differential** |

### **2.3 The Technology of Deflection: IVR vs. Conversational AI**

The root cause of the ASA disparity is not merely staffing levels but **deflection capability**. Private banks utilize advanced Conversational AI and Natural Language Processing (NLP) within their Interactive Voice Response (IVR) systems. These systems can authenticate a user via voice biometrics ("My voice is my password") and resolve up to 50% of routine inquiries—such as balance checks, transaction history, or simple transfers—without the call ever reaching a human agent.8

Service Canada’s reliance on traditional menu-based routing (DTMF) forces users to navigate complex trees ("Press 1 for English, Press 2 for EI..."), only to eventually enter a queue for a human agent to perform simple tasks like checking application status. While Service Canada has introduced an online "Passport Application Status Checker" to mitigate volume 1, the lack of an integrated, intelligent voice bot that can answer specific case questions means the human channel remains the default for uncertainty.

Case Study: Banking Voice Biometrics  
When a client calls a major Canadian bank (e.g., RBC, TD), the system identifies their phone number and authenticates them via voice print within the first 15 seconds. This eliminates the 2-3 minutes of "identity interrogation" (Mother’s maiden name, address verification) that characterizes a Service Canada call. By removing this verification friction, banks reduce Average Handle Time (AHT) by 10-15%, effectively creating capacity to answer more calls faster without adding staff.

### **2.4 The Cost of "Failure Demand"**

A significant portion of Service Canada’s call volume can be classified as "failure demand"—calls caused by a failure in upstream processes or digital channels. For example, users who are locked out of their My Service Canada Account (MSCA) due to rigid authentication protocols often call the contact centre simply to reset access.9 In the banking sector, password resets are handled via automated SMS flows or biometric app verification. The inability of Service Canada to automate these low-value interactions clogs the queues, preventing agents from assisting vulnerable citizens with complex, high-value needs.

## **3\. Core Processing: The "Speed of Pay" Differential**

The core product of both insurance companies and Service Canada is the adjudication of a claim (or benefit application) and the subsequent disbursement of funds. This process—intake, adjudication, and payment—offers the most direct comparison of operational efficiency and technological maturity.

### **3.1 The 28-Day Standard vs. The "Touchless" Minute**

The insurance industry has undergone a revolution in "Speed to Settlement." Driven by the rise of InsurTechs like Lemonade and the digital transformation of incumbents like Intact Insurance, the sector has moved toward **Straight-Through Processing (STP)**.

* **Private Sector (Travel/Auto Insurance):** Leading insurers now use Generative AI and Optical Character Recognition (OCR) to achieve STP rates of 57% or higher for standard claims.10 A travel insurer, for instance, reduced processing time from three weeks to under two minutes. The system validates receipts, checks policy limits, cross-references for fraud, and issues payment via e-transfer instantly.  
* **Service Canada (Employment Insurance):** The EI program operates with a service standard of finalizing 80% of claims within 28 days.11 While the department often meets or exceeds this target—achieving 88.9% as of April 2025—the target itself is nearly a month long. For a citizen experiencing sudden job loss, 28 days represents a significant financial gap, often necessitating bridge financing or debt.

Analysis of the Structural Gap:  
The difference is not just speed; it is the philosophy of adjudication.

* **The Insurance Model:** Uses a "Risk-Based Adjudication" engine. If a claim fits a standard profile (low dollar value, trusted user, clean documentation), it is auto-approved. Human adjusters are reserved only for complex, high-value, or suspicious claims.  
* **The Service Canada Model:** Relies on the "National Operating Model," which distributes workload across human agents in different regions.11 While this balances the load, every claim generally touches a human workflow or sits in a batch queue waiting for a Record of Employment (ROE) match. The system is designed for *accuracy through manual verification* rather than *accuracy through algorithmic validation*.

### **3.2 Table 2: Processing Speed Comparison**

| Feature | Private Insurance (Best Practice) | Service Canada (Employment Insurance) |
| :---- | :---- | :---- |
| **Core Metric** | Cycle Time (FNOL to Payment) | Speed of Payment (Application to Cheque) |
| **Typical Duration** | Minutes to Hours (Simple Claims) | 28 Days (Service Standard) |
| **Automation Rate (STP)** | 50% \- 75% 12 | Low (High manual intervention/validation) |
| **Intake Method** | Mobile App (Photo Upload \+ AI Analysis) | Web Portal / MSCA (Form fill) |
| **Evidence Validation** | AI image forensics / Metadata analysis | Manual Officer Review of Documents |
| **Payment Method** | Real-time Interac e-Transfer | Direct Deposit (Batch processing) |

### **3.3 Passport Services: A Volume Scalability Crisis**

Passport processing offers a parallel to "Know Your Customer" (KYC) compliance in banking—a rigorous identity verification process. In 2023-24, Service Canada processed a surge of 4.8 million passports, a 50% increase over the previous year.1 While the department successfully met the service standard 92% of the time, this was achieved through a brute-force mobilization of human resources and overtime, rather than scalable technology.

In contrast, opening a bank account—which requires similar anti-money laundering (AML) and identity checks—has been decoupled from linear headcount growth. Banks utilize "Digital Identity" verification services that allow users to scan their driver’s license and take a selfie. AI compares the biometric data to the ID photo, checks liveness, and validates the document against government databases in real-time. This allows banks to handle a 50% surge in new accounts with negligible impact on staffing. Service Canada’s reliance on physical document inspection creates a scalability bottleneck that the private sector has largely engineered away.

## **4\. Digital Platforms and Identity: The UX Divide**

Digital adoption is the primary lever for reducing the "Cost to Serve." The private sector effectively forces digital adoption by making it the path of least resistance, whereas public sector digital channels often introduce friction that drives users back to analog methods.

### **4.1 "My Service Canada Account" (MSCA) vs. Banking Apps**

The My Service Canada Account (MSCA) platform has over 5.6 million active users 13, representing a significant portion of the adult population. However, qualitative feedback and user reviews highlight significant friction points.

* **User Experience (UX):** Users report frequent difficulties in signing in, "locked" accounts requiring in-person reactivation, and a lack of mobile-native functionality.9 While a new dashboard was introduced in 2024 to consolidate information, the platform functions primarily as a responsive website wrapper rather than a true native application.13  
* **Banking App Maturity:** Canadian banking apps (e.g., TD, RBC, Scotiabank) have achieved mobile adoption rates where over 76% of users manage accounts online, with even higher rates in younger demographics.14 These apps offer end-to-end functionality: cheque deposit via camera, card freezing, and appointment booking. The "stickiness" of banking apps is driven by a UX design that prioritizes "tasks to be done" and minimizes friction.

### **4.2 The Authentication Bottleneck**

A critical vulnerability for Service Canada is the authentication layer. The reliance on **GCKey** or **Sign-in Partners** is robust but brittle. If a user loses their GCKey credentials or forgets their security questions, the recovery process is arduous, often involving a mailed access code that takes 5-10 business days to arrive.15 This delay effectively locks the citizen out of digital services, forcing them to visit a Service Canada Centre or call the contact centre—generating "failure demand."

Private Sector Comparison:  
Banks utilize multi-factor authentication (MFA) that leverages the device itself. A user can reset their password using a combination of face ID, SMS verification, and email confirmation in minutes. The "Identity Assurance Level" (IAL) in banking is high, yet the user journey is seamless. The divergence lies in the private sector's willingness to use behavioral biometrics and device trust scores to validate identity, whereas the public sector relies on "shared secrets" (passwords/questions) and physical tokens (mailed codes).

### **4.3 Case Study: The BC Services Card Success**

The **BC Services Card** represents a notable exception within the Canadian public sector—a "private-sector-like" success story.

* **Adoption:** The digital version of the card has achieved an adoption rate of approximately 30% of the population, benchmarked against international peers like the UK’s NHS App.16  
* **Functionality:** It uses a mobile app for high-assurance digital identity, enabling access to health, tax, and other services via a secure token.  
* **Implication:** This case study demonstrates that government entities *can* build high-adoption digital identity solutions if they prioritize UX and mobile integration. Service Canada’s opportunity lies in integrating fully with these successful provincial digital IDs rather than maintaining a separate, more cumbersome federal credential ecosystem.

## **5\. Financial Integrity and Fraud: Prevention vs. Recovery**

The approach to financial integrity represents one of the starkest philosophical differences between the sectors. Service Canada operates largely on a "Pay and Chase" model, while the private sector has pivoted to "Predictive Prevention."

### **5.1 The "Pay and Chase" Legacy**

Service Canada’s Integrity Services Branch employs approximately 1,200 investigators charged with detecting and addressing fraud, error, and abuse.17 Historically, this team has been effective, recovering or addressing nearly half a billion dollars annually in ineligible payments.18 However, this model is inherently retrospective. It relies on post-payment audits, data matching (e.g., comparing ROEs to tax filings months later), and "snitch lines." The funds have already left the treasury, and recovery is costly, time-consuming, and often legally complex.

### **5.2 The "Predictive Prevention" Revolution**

The financial services industry, facing billions in potential fraud losses, has invested heavily in **Predictive AI** to stop fraud at the gate.

* **Technological Mechanism:** Banks and insurers use unsupervised machine learning models to analyze thousands of data points in real-time during a transaction. These models look at **behavioral biometrics**: How fast is the user typing? Is the mouse movement consistent with a human or a bot? Is the device location consistent with the user’s history?  
* **Outcome:** Private sector case studies show that AI-driven fraud detection can reduce fraud-related costs by 40% while improving the detection rate of genuine fraud.19 More importantly, it reduces "false positives," ensuring legitimate customers are not blocked.

### **5.3 Table 3: Fraud Management Models**

| Feature | Service Canada (Integrity Services) | Private Banking/Insurance |
| :---- | :---- | :---- |
| **Primary Strategy** | Retrospective Investigation ("Pay and Chase") | Real-time Prevention ("Block at Gate") |
| **Detection Tool** | Data Matching (Post-payment), Tip-lines | Predictive AI / Machine Learning |
| **Data Sources** | ROE, Tax Filings, Payroll Data | Device Fingerprint, Biometrics, Geolocation, Behavioral Analysis |
| **Cost of Mgmt** | High (Human Investigators, Legal Recovery) | Lower (Automated blocking) |
| **Recovery Rate** | \<100% (Spent funds are hard to recover) | 100% (Funds never leave the bank) |

Strategic Implication:  
If Service Canada were to implement predictive fraud modeling at the point of application (MSCA intake), it could identify high-risk EI applications (e.g., organized crime rings using stolen SINs) before a single dollar is disbursed. This would not only protect the Consolidated Revenue Fund but also free up the 1,200 investigators to focus on complex, high-value abuse cases rather than routine verification.

## **6\. Technology Platforms: The Architecture of Agility**

The divergence in KPIs is fundamentally a symptom of the underlying technological infrastructure. The private sector’s migration to cloud-native architectures allows for real-time data processing and agile feature deployment, whereas the public sector grapples with massive technical debt and monolithic systems.

### **6.1 The "Big Bang" vs. The "Strangler Fig"**

Service Canada’s **Benefits Delivery Modernization (BDM)** programme is a generational attempt to replace aging mainframes—some dating back decades—that run OAS, CPP, and EI. The project, initially estimated at $1.75 billion, has seen costs balloon to over $3.4 billion due to delays, complexity, and the sheer scale of the transformation.20 The project relies on large legacy vendors (IBM, Deloitte, Accenture) and a "waterfall" or huge-scale implementation approach.21

In contrast, Canadian banks, while also burdened with legacy mainframes, have aggressively adopted the **"Strangler Fig" pattern**. They do not attempt to replace the core mainframe overnight. Instead, they build modern "Experience Layers" (APIs and Microservices) on top of the legacy core. This allows them to launch new features (like a new mobile wallet) in weeks, interacting with the old mainframe via APIs, while slowly peeling away functionality from the old system piece by piece.

### **6.2 Artificial Intelligence as a Value Driver**

AI is the single greatest opportunity for KPI improvement, yet its adoption varies wildly.

* **Private Sector Excellence:** TD Bank Group reported generating $122 million in value from AI use cases in a single year, deploying it for everything from loan underwriting to customer lead generation.3 Intact Insurance operates a "Data Lab" with over 500 data experts, essentially functioning as an AI company that sells insurance.4  
* **Service Canada’s AI Maturity:** AI adoption at Service Canada remains nascent. While there are pilots for "benefits estimators" and some Robotic Process Automation (RPA) in backend processing 11, the systematic deployment of AI for decision-making is hampered by a culture of caution regarding "Automated Administrative Decisions." The fear of algorithmic bias or legal challenge prevents the department from realizing the efficiency gains standard in the private sector.

## **7\. Strategic Opportunities: Ranked by ROI**

Based on the benchmarking analysis, the following opportunities are ranked by **Return on Investment (ROI)**. In the public sector context, ROI is defined as a composite of **Financial Efficiency** (Cost Savings) and **Citizen Value** (Time Saved/Service Improved).

### **Rank 1: Intelligent Automation of Employment Insurance (STP)**

* **The Opportunity:** Transition from "human-led, system-assisted" to "system-led, human-verified" adjudication for straightforward EI claims.  
* **Private Benchmark:** Insurance industry STP rates of \>50% for standard claims.10  
* **ROI Potential:** **Highest.**  
  * *Financial:* Reducing the 28-day processing standard to \<5 days for 60-70% of claims would save millions in administrative hours.  
  * *Citizen Value:* Immediate financial relief for the unemployed, reducing the need for emergency provincial social assistance.  
* **Implementation:** Deploy an AI rules engine to validate ROEs against application data. If codes match (e.g., "Shortage of Work") and no adverse history exists, auto-adjudicate.

### **Rank 2: Predictive Fraud Prevention (AI Integrity)**

* **The Opportunity:** Implement real-time behavioral analytics and device fingerprinting at the MSCA login and application stage.  
* **Private Benchmark:** Real-time fraud blocking in banking; 40% reduction in fraud costs.19  
* **ROI Potential:** **High.**  
  * *Financial:* Shifting from costly "Pay and Chase" recovery to cost-effective prevention.  
  * *Citizen Value:* Protects citizens from identity theft and SIN abuse.  
* **Implementation:** Partner with established fraud-tech vendors to integrate behavioral biometrics into the MSCA authentication layer.

### **Rank 3: Biometric Authentication & Mobile Identity**

* **The Opportunity:** Adopt a "Government Digital ID" framework or fully leverage provincial IDs (like BC Services Card) for biometric mobile login.  
* **Private Benchmark:** FaceID/TouchID login for banking apps (90%+ adoption).  
* **ROI Potential:** **Medium-High.**  
  * *Financial:* Drastically reduces contact centre volume driven by "locked accounts" and "password resets" (a major failure demand).  
  * *Citizen Value:* Frictionless access to services; no more mailed access codes.

### **Rank 4: Advanced Contact Centre Deflection (Generative Voice AI)**

* **The Opportunity:** Replace standard DTMF IVR with Generative AI voice assistants capable of answering complex, context-aware queries (e.g., "Why was my payment less this week?").  
* **Private Benchmark:** 50% call containment rates in fintech/banking.8  
* **ROI Potential:** **Medium.**  
  * *Financial:* Reduces ASA and AHT; allows human agents to focus on vulnerable clients who require empathy.  
  * *Citizen Value:* 24/7 access to answers without waiting on hold.

### **Rank 5: Proactive Benefits Enrollment (The "Nudge")**

* **The Opportunity:** Utilize CRA tax data to predict eligibility for OAS/GIS and auto-enroll seniors, or proactively notify them via text/email.  
* **Private Benchmark:** Banks predicting life events (e.g., mortgage needs) and offering products proactively.  
* **ROI Potential:** **Medium (Social ROI).**  
  * *Financial:* Reduces the administrative burden of processing applications (no application to process if auto-enrolled).  
  * *Citizen Value:* Ensures vulnerable seniors do not miss payments due to lack of awareness or cognitive decline.

## **8\. Conclusion and Roadmap**

Service Canada stands at a critical juncture. The private sector has demonstrated that **speed**, **security**, and **empathy** are not mutually exclusive but are enabled by the same set of technologies: AI, Cloud, and Automation. The "28-day" standard for critical benefits is an artifact of a paper-based era. By adopting the "Touchless Claims" philosophy of the insurance industry and the "Digital First" service models of the banking sector, Service Canada can bridge the widening trust gap.

The path forward requires a fundamental shift in operating philosophy:

1. **From Risk Aversion to Risk Management:** Accepting that 100% manual verification is not only inefficient but riskier than AI-driven consistency.  
2. **From Data Holding to Data Usage:** Leveraging the vast repository of federal data to predict and serve needs before they are voiced.  
3. **From "Big Bang" to Agile Evolution:** Breaking down the monolithic BDM programme into smaller, value-driven product releases that deliver immediate relief to citizens.

The ROI of this transformation extends beyond the balance sheet; it restores the fundamental promise of a responsive, modern government in a digital age.

### ---

**List of Tables for Reference**

* **Table 1:** Comparative Contact Centre Metrics (Section 2.2)  
* **Table 2:** Processing Speed Comparison (Section 3.2)  
* **Table 3:** Fraud Management Models (Section 5.3)

---

Report prepared by Senior Strategic Consultant, Public Sector Transformation Practice.  
December 2025

#### **Works cited**

1. Backgrounder: The State of Service report 2025 \- Canada.ca, accessed December 29, 2025, [https://www.canada.ca/en/employment-social-development/news/2025/03/backgrounder-the-state-of-service-report-2025.html](https://www.canada.ca/en/employment-social-development/news/2025/03/backgrounder-the-state-of-service-report-2025.html)  
2. SERVICE CANADA AT A GLANCE, accessed December 29, 2025, [https://www.canada.ca/content/dam/esdc-edsc/documents/corporate/reports/esdc-transition-binders/2025-may-transition-binder/2.3.Service-Canada-Glance.pdf](https://www.canada.ca/content/dam/esdc-edsc/documents/corporate/reports/esdc-transition-binders/2025-may-transition-binder/2.3.Service-Canada-Glance.pdf)  
3. TD Bank Group Implemented 75 AI Use Cases in 2025 \- PYMNTS.com, accessed December 29, 2025, [https://www.pymnts.com/artificial-intelligence-2/2025/td-bank-group-implemented-75-ai-use-cases-in-2025/](https://www.pymnts.com/artificial-intelligence-2/2025/td-bank-group-implemented-75-ai-use-cases-in-2025/)  
4. Intact Lab, accessed December 29, 2025, [https://www.intactfc.com/about-us/intact-lab](https://www.intactfc.com/about-us/intact-lab)  
5. Important Call Center Statistics to Know \[2025\] \- Sprinklr, accessed December 29, 2025, [https://www.sprinklr.com/blog/call-center-statistics/](https://www.sprinklr.com/blog/call-center-statistics/)  
6. Question Period Note: EMPLOYMENT INSURANCE CALL CENTRES STANDARDS, accessed December 29, 2025, [https://search.open.canada.ca/qpnotes/record/esdc-edsc%2CS\_LSDec2024\_005](https://search.open.canada.ca/qpnotes/record/esdc-edsc%2CS_LSDec2024_005)  
7. 2024 Contact Center Benchmark: Key Metrics and AI-Driven Strategies for Success, accessed December 29, 2025, [https://convin.ai/blog/contact-center-benchmark](https://convin.ai/blog/contact-center-benchmark)  
8. Conversational AI: Use Cases, Implementation Steps and Future Trends \- Sprinklr, accessed December 29, 2025, [https://www.sprinklr.com/blog/conversational-ai/](https://www.sprinklr.com/blog/conversational-ai/)  
9. SERVICE CANADA \- Client Experience Survey 2023-24 \- bac-lac.gc.ca, accessed December 29, 2025, [https://epe.bac-lac.gc.ca/100/200/301/pwgsc-tpsgc/por-ef/employment\_social\_development\_canada/2025/008-24-e/008-24-report.pdf](https://epe.bac-lac.gc.ca/100/200/301/pwgsc-tpsgc/por-ef/employment_social_development_canada/2025/008-24-e/008-24-report.pdf)  
10. AI in Action: From zero to 50%+ automation in travel insurance \- Shift Technology, accessed December 29, 2025, [https://www.shift-technology.com/resources/case-studies/genai-travel-insurance-automation](https://www.shift-technology.com/resources/case-studies/genai-travel-insurance-automation)  
11. Question Period Note: EMPLOYMENT INSURANCE PROCESSING \- Open Government Portal, accessed December 29, 2025, [https://search.open.canada.ca/qpnotes/record/esdc-edsc%2CSC\_JUN2025\_001](https://search.open.canada.ca/qpnotes/record/esdc-edsc%2CSC_JUN2025_001)  
12. 40 Claims Redemption Rate Statistics: Key Facts Every Organization Should Know in 2025, accessed December 29, 2025, [https://blog.talli.ai/claims-redemption-rate-statistics/](https://blog.talli.ai/claims-redemption-rate-statistics/)  
13. Important Improvements to My Service Canada Account, accessed December 29, 2025, [https://www.canada.ca/en/employment-social-development/news/2024/09/important-improvements-to-my-service-canada-account.html](https://www.canada.ca/en/employment-social-development/news/2024/09/important-improvements-to-my-service-canada-account.html)  
14. The Daily — Trends in online banking and shopping \- Statistique Canada, accessed December 29, 2025, [https://www150.statcan.gc.ca/n1/daily-quotidien/240321/dq240321b-eng.htm](https://www150.statcan.gc.ca/n1/daily-quotidien/240321/dq240321b-eng.htm)  
15. Evaluation of Providing Services and Information to Canadians through Service Canada, accessed December 29, 2025, [https://www.canada.ca/en/employment-social-development/corporate/reports/evaluations/evaluation-providing-services-information.html](https://www.canada.ca/en/employment-social-development/corporate/reports/evaluations/evaluation-providing-services-information.html)  
16. Don't Count Portals—Count Installs \- FWD50, accessed December 29, 2025, [https://www.fwd50.com/blog/698/don-t-count-portals-count-installs](https://www.fwd50.com/blog/698/don-t-count-portals-count-installs)  
17. HUMA committee briefing binder: Appearance of the Senior Associate Deputy Minister of Employment and Social Development and Chief Operating Officer for Service Canada, accessed December 29, 2025, [https://www.canada.ca/en/employment-social-development/corporate/reports/committe-binders/jan-31-huma-sadm.html](https://www.canada.ca/en/employment-social-development/corporate/reports/committe-binders/jan-31-huma-sadm.html)  
18. Statement by Service Canada regarding Integrity Services Branch, accessed December 29, 2025, [https://www.canada.ca/en/news/archive/2013/03/statement-service-canada-regarding-integrity-services-branch.html](https://www.canada.ca/en/news/archive/2013/03/statement-service-canada-regarding-integrity-services-branch.html)  
19. Insurance Fraud Detection ROI Calculator \- EIS Group, accessed December 29, 2025, [https://www.eisgroup.com/digital-insurance-solutions/fraud-detection-roi-calculator/](https://www.eisgroup.com/digital-insurance-solutions/fraud-detection-roi-calculator/)  
20. Report 8—The Benefits Delivery Modernization Programme, accessed December 29, 2025, [https://www.oag-bvg.gc.ca/internet/English/att\_\_e\_44349.html](https://www.oag-bvg.gc.ca/internet/English/att__e_44349.html)  
21. Standing Committee on Public Accounts: December 14, 2023 \- Canada.ca, accessed December 29, 2025, [https://www.canada.ca/en/public-services-procurement/corporate/transparency/briefing-materials/standing-committee-public-accounts/2023-12-14.html](https://www.canada.ca/en/public-services-procurement/corporate/transparency/briefing-materials/standing-committee-public-accounts/2023-12-14.html)

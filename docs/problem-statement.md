# Part A: Problem Formulation

## A1. Problem Statement
Malaysian drivers, motorcyclists, and vehicle owners using the MyJPJ mobile application often struggle to find direct answers about traffic rules, vehicle ownership changes, and driving license renewal requirements. Currently, users have to navigate through plain FAQ pages and separate official portals that explain complex procedural rules manually. As a result, this leads to confusion among motorists, leading them to abandon self-service transactions, risking missing critical renewal deadlines or overloading JPJ physical counters and MyGCC call centers with routine inquiries. For example, official JPJ MyJPJ FAQs and summons payment guidelines require drivers to coordinate multiple separate rules regarding active blacklists, non-compoundable offenses and notice codes before completing basic online transactions.

## A2. Users, Stakeholders and Scope

* **Primary Users:** Malaysian motorists and vehicle owners using the MyJPJ mobile application to check driving license renewal eligibility, demerit points, vehicle transfer steps, and summons settlement rules.
* **Secondary Users:** JPJ customer service who receives user inquiries about unusual cases.
* **Stakeholders:** Jabatan Pengangkutan Jalan (JPJ), Ministry of Transport Malaysia (MOT), and the Malaysia Government Call Centre (MyGCC).

### In Scope
* Conversational question answering in English and Bahasa Melayu strictly grounded in official JPJ FAQs, licensing guidelines and summons regulations.
* Source attribution showing the specific Official JPJ FAQ Section or Circular Title used to generate each answer.
* Smooth handover to a live JPJ support officer when a query is not covered by the indexed knowledge base.

### Out of Scope
* Redesign of the overall MyJPJ mobile interface, navigation menus or visual theme.
* Enabling offline caching of digital driving license (e-LMM) or digital road tax (e-LKM).
* Processing of direct FPX, credit card or e-wallet payment transactions for traffic summons.

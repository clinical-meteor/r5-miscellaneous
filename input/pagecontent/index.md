# R5 Patient Introduction

Welcome!  You have navigated to the Patient Introduction for the Fast Healthcare Interoperability Resources (FHIR) standard.  If you've recently been told about something called 'fire' related to your Personal Health Records, you're in the right place.  The following document will give a brief overview of how you, as a patient, can access your own personal health records under various government laws.  

Fast Healthcare Interoperability Resources (FHIR) is a data specification for sharing healthcare data.  Unlike prior standards that were based on FAX machines or PDF documents, the FHIR format is based on modern web standards.  Fundamentally, its "healthcare" and the "internet".  For this to work, healthcare systems and technology vendors have had to come together and agree on how they're going to send and share data with each other.  We call this an application programming interface (API); and the protocol we use is the HyperText Transfer Protocol (HTTP).  The FHIR specification, then, is an API specification of how to send healthcare data via hypertext (HTTP) on the web.

Many healthcare systems and technology vendors are already supporting the FHIR data standard, including the electronic medical record systems of the largest hospitals in the US, as well as major tech vendors such as Apple and Microsoft.

### How does FHIR help me as a patient?
Taking ownership of one's healthrecords can be a lifechanging and empowering decision.  Rather than guessing about your health, one can participate in the process of measuring and understanding your health.  You may find FHIR useful when:

- Aggregating your health records from different health clinics 
- Researching and understanding your own health 
- Researching and understanding a diagnosis your healthcare provider made
- Making sure the records your physician or nurse have about you is correct
- Collaborating with your care plan or treatment plan
- Sharing data you've collected with your care team
- Sharing your records with friends, family, and caregivers
- Sharing your records during a specialist consultation
- Planing surgical procedures 
- Downloading your billing records from your payors
- Moving from one city to another

### How do I use FHIR?  How do I access my FHIR records?   

You may, in fact, already be using FHIR without knowing it.  FHIR is frequently used when hospital systems transfer records between one setting to another.  This may include the patient portal that you use to access your records; a health information exchange that you've signed up for; or a personal health record application on your smartphone, such as Apple Health or Android Common Health..  

Oftentimes, there is interoperability going on, but it works somewhat behind the scenes.  A savvy patient, however, can access the FHIR endpoints directly.  To do so, the patient needs a FHIR application (either an app on a phone or online); the user credentials supplied by your healthcare organizations; and possibly a registration process to register the app with the healthcare system.  

 
### Where can I find FHIR applications?
Some health organizations have lists of FHIR applications on their website.  Here are some examples:

[My Health Applications](https://myhealthapplication.com/health-apps/gallery)  
[SMART App Gallery](https://apps.smarthealthit.org/apps/featured)  



### Why do I need copies of my Health Records?  

Patient surveys show that a major reason patients tend to be interested in having copies of their own healthrecords is to check for accuracy and errors.  When a medical record has an error, it can result in safety issues with dire consequences.  Amongst the most common errors are left/right errors and having contents in the record from another patient.  Getting copies of your records can help assure that your records are accurate.

Patients often request copies of their own records when they want to take a more active ownership of their own health.  This often happens after a health incident where a person re-evaluates their habits and seek to implement new careplans and new routines. And can be as simple as tracking personal fitness goals or as complex as doing a complete quantified self workup and measure metabolic biomarkers on a monthly or quarterly basis.  

### Getting a copy of your records  
Health records are available from many organizations, although they all tend to be password and account protected according to various privacy laws.  Which is precisely why they tend to be restricted and patient access is even an issue of concern.  

Typically, one will first want to check with one's local hospital or clinic or laboratory, to see if they have a patient portal.  If so, sign up and look there for downloadable data.  Typically, these documents will be provided in PDF format.  

Second, consumer Health Information Exchanges such as provide users with browsable directories of participating providers they can download their data from.  



### Laws - United States

Numerous laws cover patient privacy, patient data ownership, and patient right to access their own data.  Relevant laws and legal precendent include:  

- [Health Insurance Portability and Accountability Act](https://www.hipaaguide.net/hipaa-updates/) (United States)
- [Medicare Access and CHIP Reauthorization ](https://www.cms.gov/Medicare/Quality-Initiatives-Patient-Assessment-Instruments/Value-Based-Programs/MACRA-MIPS-and-APMs/MACRA-MIPS-and-APMs) (United States) 
- [21st Century Cures Act (United States)](https://www.healthit.gov/curesrule/)  
- [21st Century Cures Act (Information Blocking Rule](https://www.healthit.gov/topic/information-blocking) 
- [Coronavirus Aid, Relief, and Economic Security Act)](https://www.congress.gov/bill/116th-congress/house-bill/748)] (United States)
- [General Data Protection Regulation](https://en.wikipedia.org/wiki/General_Data_Protection_Regulation) (Europe)
- [Personal Information Privacy Law](https://www2.deloitte.com/cn/en/pages/risk/articles/personal-information-protection-law.html) (China)
- [Privacy Act](https://www.oaic.gov.au/privacy/the-privacy-act) (Australia)

Note that, in the United States, the 21st Century Cures Act is of particular importance to patients; and the rule includes provisions requiring that patients can electronically access all of their electronic health information (EHI), structured and/or unstructured, at no cost, and with the application of their choice.  Patients have the recourse to [report information blocking](https://inquiry.healthit.gov/support/plugins/servlet/desk/portal/6) by healthcare systems and other vendors.


### What Data is Included?

FHIR provides out-of-the-box data schemas and implementation guidance for many common data types that are found in healthcare... allergies, immunizations, medications, patient demographics, clinical observations, vital signs, procedures, and much more!

- US Common Data for Interoperability (USCDI)  
USCDI is a set of basic data that the US Government expects applications and technology vendors to support in order to obtain certification as an interoperability compliant product or service.  


- Argonaut
The Argonaut project (a pun on the JSON format, refering to Jason and the Argonauts from Homer's Odyssey) is one of the oldest FHIR projects, and comprises a set of core data resources that EHR vendors have agreed to use to communicate clinical findings.  

- International Patient Summary  
International Patient Summary is an European Union led project, focusing on patient summaries as they are exchanged between different countries in the EU.  Particular attention is given to different languages and terminologies, and necessary documentation for crossing borders (such as vaccines).

- Vaccine Card  
Public health data such as vaccine passports and vaccination status.

- Continuity of Care Documents (CCD)
Continuity of Care documents are the clinical documents that hospitals and clinics provide to you when you leave an over night stay at a hospital.  They include progress notes, treatment summary, diagnosis, and similar documents.  They may also include ambulance and transportation instructions.


### Patient Implementators 
Patients that wish to build tools and utilities using their own health records will have additional interests and needs. Such patients may find the activities in the HL7 Implementation Division to be of interest.  Patients with software development experience will want to refer to the [Developer introduction](http://hl7.org/fhir/overview-dev.html) and the [Implementation Support Module](https://hl7.org/FHIR/implsupport-module.html).

- [SMART on FHIR App Examples](https://github.com/smart-on-fhir/smart-examples)  
- [Creating Your First SMART on FHIR Application](https://techcommunity.microsoft.com/t5/healthcare-and-life-sciences/creating-your-first-smart-on-fhir-application/ba-p/2802999)  
- [Smart on FHIR Tutorial](https://github.com/cerner/smart-on-fhir-tutorial)  
- [Clinical safety checklist](https://www.hl7.org/fhir/safety.html)   
- [Synthea](https://synthetichealth.github.io/synthea/) 


### References    

[FHIR Fact Sheets](https://www.healthit.gov/topic/standards-technology/standards/fhir-fact-sheets)  
[What is FHIR?](https://www.healthit.gov/sites/default/files/2019-08/ONCFHIRFSWhatIsFHIR.pdf)  
 

 
 
 
 

 

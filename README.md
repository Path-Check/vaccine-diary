# ![logo](https://github.com/mikhaildmitrienko/VaccineDiary/blob/main/trusted_pandemic.png)

This repository is a compilation of Trusted Pandemic Technologies' efforts to design digital solutions that engage citizens in four core areas — Logistics, Health Outcomes, User-centric impact, and Communication.

Our mission is to help public health professionals to instantly overcome challenging barriers they encounter as they engage citizens as an active participants in digital solutions for fighting COVID-19 and future pandemics.

Today, the program is focused on creating a citizen-centric solutions for the digital management of COVID-19 vaccine distribution, testing, and health verification. Previously the program worked with public health officials as they designed and deployed exposure notification and digital contact tracing solutions. Subsequent initiatives under consideration include surveillance, monitoring, and predictive modeling to better prepare us, as a society, for future pandemics.

The founding belief of the Trusted Pandemic Technologies is that when it comes to engaging citizens in a quest for the common good, especially public health, trust at all levels and among all participants is mandatory for success. So, the program builds on privacy-preserving systems for smartphone data, analytics, and machine learning.

* [VaccineDiary Mobile App](#mobile-app)
* [VaccineDiary Demo Video](https://youtu.be/njUGAN98PSk)
* [Vaccination Record Card Proposals](#vaccination-record-card-proposals)
* [App Sketches](#app-sketches)
* [Conceptual Dashboard for Health Agencies](#conceptual-dashboard-for-health-agencies)
* [Vaccine Workflows](#vaccine-workflows)
* [News and Analysis](#news-and-analysis)
* [FAQ](#faq)
* [Team](#Team)
* [Papers](#papers)
* [Apps and Prototypes](#apps-and-prototypes)
* [Team Background](#team-background)

### VaccineDiary Mobile App
[<img src="https://github.com/Path-Check/vaccine-diary/blob/main/Resources/download_google_play.png" alt="Download on Play Store" width="200"/>](https://play.google.com/store/apps/details?id=org.pathcheck.boost)
[<img src="https://github.com/Path-Check/vaccine-diary/blob/main/Resources/download_app_store.png" alt="Download on App Store" width="200"/>](https://comingsoon.com)

[VaccineDiary Demo Video](https://youtu.be/njUGAN98PSk)

<img src="https://github.com/Path-Check/vaccine-diary/blob/main/Resources/vaccinediary.gif" alt="App_gif" width="300"/>

![App_screens](https://github.com/Path-Check/vaccine-diary/blob/main/Resources/Vaccine_App_Screens.png)
![App_screens1](https://github.com/Path-Check/vaccine-diary/blob/main/Resources/app_1.png)
![App_screens2](https://github.com/Path-Check/vaccine-diary/blob/main/Resources/app_2.png)
![App_screens3](https://github.com/Path-Check/vaccine-diary/blob/main/Resources/app_3.png)
![App_screens4](https://github.com/Path-Check/vaccine-diary/blob/main/Resources/app_4.png)
![App_screens5](https://github.com/Path-Check/vaccine-diary/blob/main/Resources/app_5.png)
![App_screens6](https://github.com/Path-Check/vaccine-diary/blob/main/Resources/app_6.png)
![App_screens7](https://github.com/Path-Check/vaccine-diary/blob/main/Resources/app_7.png)

### Vaccination Record Card Proposals

![Record Card](https://github.com/Path-Check/vaccine-diary/blob/main/Resources/P_V_Card_1.png)
![Record Card](https://github.com/Path-Check/vaccine-diary/blob/main/Resources/P_V_Card_2.png)

### App Sketches

A privacy-protecting, user-centric app to enhance vaccination coordination and data-aggregation. 

![Sketches](https://github.com/Path-Check/vaccine-diary/blob/main/Resources/sketches.png)
![Sketches](https://github.com/Path-Check/vaccine-diary/blob/main/Resources/sketch2.png)

### Conceptual Dashboard for Health Agencies
![Dashboard](https://github.com/mikhaildmitrienko/VaccineDiary/blob/main/Dashboard.png)

### Vaccine Workflows
![Workflows](https://github.com/mikhaildmitrienko/VaccineDiary/blob/main/Vaccine_workflows.png)
![Workflows](https://github.com/Path-Check/vaccine-diary/blob/main/Resources/vaccine_workflow.png)

## News and Analysis

[Privacy, equity, and efficiency in vaccine distribution - Boston Globe](https://github.com/Path-Check/vaccine-diary/blob/main/Resources/Privacy%2C%20equity%2C%20and%20efficiency%20in%20vaccine%20distribution%20-%20The%20Boston%20Globe.pdf)

## FAQ

### Is the VaccineDiary app a replacement for existing CDC or State systems? 
No. Systems such as VAMS/VAERS/V-Safe/IIS/IZ. are important in wide ranging COVID-19 vaccination efforts. Our proposed app would provide an alternative method for vaccination that is privacy-sparing, efficient, and equitable while serving as a supplemental source of vaccine monitoring information.  

### How will this interface with VAMS/VAERS/V-Safe/ IIS/IZ? What changes are required?
Vaccine diary, second-dose and health status alert, and informational features of our proposed app would be independent of the existing systems. The input of vaccination information upon administration of a vaccine and side effect/efficacy reports are two areas with potential for integration with government systems. 
To verify and record the vaccine administration, vaccination clinics or governments would need to provide signed QR codes that can be printed / copied by pharmacies or by users. This QR code would have information regarding the lot, manufacturer, and dosing of a vaccine which can then be verified by others with the appropriate digital key. 

For interoperability of symptom/side effect reports, state or federal systems will need to allow the pseudorandom identifier associated with a user to be used for data identification purposes rather than PII such as name, address, etc. This is already part of the PPRL (privacy preserving record linkage) protocol for VAMS and IIS.

### If you don't have PII, how can doctor or PH get in touch with the user?
Doctors and public health officials can contact users regarding pertinent information about their specific vaccine lot and other important details via app-mediated push notifications and contextual alerts. This is similar to ‘recalls’ in auto-parts, food safety, toys, etc. 

### What difference will it make? Wouldn’t everyone be vaccinated anyway?
The emphasis is on privacy, equity and efficiency. Significant chunks of the population still exhibit vaccine hesitancy and many may be unwilling to receive a COVID-19 vaccine. This app aims to remove potential barriers to vaccination by protecting data privacy, creating a convenient, streamlined user experience, and providing multiple vaccine-related functionalities in one platform. We also believe that decentralized data can be used for a broad range of public health research. 

### Is this app primarily a vaccine passport or verifiable credentials? 
This app does support vaccine verification while also including modules surrounding eligibility confirmation, dose scheduling and reminders, health assessments and symptom reporting, and providing users with push-notifications and contextual alerts. 

### How will you reach marginalized and low-resource communities?
We have also proposed state-produced physical vaccine cards that can be used for many of the functions of our app solution. This enables a privacy-focused solution for vaccination. Please see a thorough explanation in section 6. 

### Why should user trust such apps?
The app is developed using open-source code and open standards. Similar to the  exposure notification apps, the app does not request any PII. 

### Why do centralized systems including VAMS and VAERS require so much PII and HPI?
PII including name, date of birth, and contact information is primarily used for user identification, contact, and record-keeping. 
Health information is stored to determine eligibility for vaccination based upon exclusion criteria and to track the interactions between various medical conditions and vaccination. 
Other personal information might be used for aggregate analysis and statistical purposes regarding equitable distribution among diverse populations. 
Our app-based approach addresses each of these functions without the use of PII. 

Identification of an individual for record-keeping is performed using a pseudorandom identification number rather than name or date of birth. Previous health information can be inputted into the app for exclusion determination where it is not stored. As soon as the app determines eligibility for vaccination information shared in these questions will be deleted. Symptom and adverse event reporting can be performed either anonymously or with personal information that might lend insight into vaccine and medical condition interactions. All demographic information can be anonymized and aggregated for reporting. 

### What if the user does not have a smartphone? 
We expect users seeking a privacy oriented approach to vaccination to use a physical card containing a digitally-signed QR code from the government. 

### What is PathCheck and what role can it play?
PathCheck is a nonprofit organization originating in Dr. Ramesh Raskar’s lab at MIT. PathChck is  the world’s largest open source, open standards nonprofit organization for COVID-19 and innovates  across a broad array of problems stemming from the pandemic. PathCheck was the first organization to launch an EN app for contact tracing in COVID-19, successfully partnering with 6 US states and territories. 

### What is MIT SafePaths? What is its role?
MIT SafePaths is a set of standards protocols and algorithms and open-source tools. The project on vaccination protocols is led by Ramesh Raskar at Trusted Pandemic Tech and MIT Media Lab, Sanjay Sarma at MIT Auto-ID Lab and Anna Lysyanskaya at Brown University. 

## Team

Ramesh Raskar - Associate Professor, MIT Media Lab

Sanjay Sarma - Vice President for Open Learning, MIT

Anna Lysyanskaya - Professor, Brown University

Vitor Pampalona - CEO EyeNetra INC

Joseph Bae - Stony Brook Medicine

Abhishek Singh - MIT Media Lab

Rohan Iyer - PathCheck

Krishnendu Dasgupta - PathCheck

Rohan Sukumaran - PathCheck

Priyanshi Katiyar - PathCheck

Sheshank Shankar - PathCheck

Jatin Malhotra - Lead, App Partnership Jio

Maurizio Arseni - Content Manager, ITG

Ashley Mehra - PathCheck

Sethuraman - PathCheck

Darshan Gandhi - PathCheck

Mikhail Dmitrienko - PathCheck

Nathan Yap - PathCheck

Saurish Srivastava - PathCheck



## Papers

[Vaccines for All: Challenges and Potential Solutions for Equitable COVID-19 Vaccine Distribution](https://github.com/mikhaildmitrienko/VaccineDiary/blob/main/Papers/PositionPaper_VaccinesForAllConferenceAtMITDec11th.pdf)

[Verifiable Proof of Health using Public Key Cryptography](https://github.com/mikhaildmitrienko/VaccineDiary/blob/main/Papers/public_key_crypto.pdf)

[Safepaths: Vaccine Diary Protocol and Decentralized Vaccine Coordination System using a Privacy Preserving User Centric Experience](https://github.com/)

## Apps and Prototypes

[ProtoPie](https://github.com/mikhaildmitrienko/VaccineDiary/blob/main/Prototypes.md): interactive prototype of the Vaccine Diary app

By Rohan Iyer

## Team Background

- [Exposure Notification App, now in 6 US states and territories by PathCheck Foundation](https://www.pathcheck.org/en/covid-19-exposure-notification-app)

- [First contact tracing app in the US](https://covidawaremn.com/)

- [First to propose decentralized algorithm for privacy preserving automation of contact tracing on mobile phone](https://arxiv.org/abs/2003.08567)

- [First white paper on unintended consequences of digital solutions for contact tracing](https://arxiv.org/abs/2003.08567)

- [First contact tracing team invited to testify for US Congressional Hearing on Contact Tracing and Exposure Notification](https://www.media.mit.edu/events/ramesh-raskar-testifies/)

- [PathCheck Foundation: World's largest non-profit opensource project for Covid19 software, 501(c)(3) spin-off from MIT](https://pathcheck.org)

- Host of convening events for COVID-19 digital solutions (https://pandemic.mit.edu) and (https://responsibledata.ai/events/trust)

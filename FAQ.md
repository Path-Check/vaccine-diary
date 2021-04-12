# FAQ

### Is the Vaccine  app a replacement for existing CDC or state systems? 
No. Systems such as VAMS/VAERS/V-Safe/IIS/IZ. are important in wide ranging COVID-19 vaccination efforts. Our proposed app would provide an alternative method for vaccination that is privacy-sparing, efficient, and equitable while serving as a supplemental source of vaccine monitoring information.  

### How will this interface with VAMS/VAERS/V-Safe/ IIS/IZ? What changes are required?
Vaccine diary, second-dose and health status alert, and informational features of our proposed app would be independent of existing systems. The input of vaccination information upon administration of a vaccine and side effect/efficacy reports are two areas with potential for integration with government systems. 
To verify and record vaccine administration, vaccination clinics or governments would need to provide signed QR codes that can be printed / copied by pharmacies or by users. This QR code would have information regarding the lot, manufacturer, and dosing of a vaccine which can then be verified by others with the appropriate digital key. 

For interoperability of symptom/side effect reports, state or federal systems will need to allow the pseudorandom identifier associated with a user to be used for data identification purposes rather than PII such as name, address, etc. This is already part of the PPRL (privacy preserving record linkage) protocol for VAMS and IIS.

### If you don't have PII, how can doctor or PH get in touch with the user?
Doctors and public health officials can contact users regarding pertinent information about their specific vaccine lot and other important details via app-mediated push notifications and contextual alerts. This is similar to ‘recalls’ in auto-parts, food safety, toys, etc. 

### What difference will it make? Wouldn’t everyone be vaccinated anyway?
The emphasis is on privacy, equity and efficiency. Significant chunks of the population still exhibit vaccine hesitancy and many may be unwilling to receive a COVID-19 vaccine. This app aims to potential barriers to vaccination by protecting data privacy, creating a convenient, streamlined user experience, and providing multiple vaccine-related functionalities in one platform. We also believe decentralized data can be used for a broad range of public health research. 

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
PathCheck is a nonprofit organization originating in Dr. Ramesh Raskar’s lab at MIT. PathCheck is  the world’s largest open source, open standards nonprofit organization for COVID-19 and innovates  across a broad array of problems stemming from the pandemic. PathCheck was the first organization to launch an EN app for contact tracing in COVID-19, successfully partnering with 6 US states and territories. 

### What is MIT SafePaths? What is its role?
MIT SafePaths is a set of standards protocols and algorithms and open-source tools. The project on vaccination protocols is led by Ramesh Raskar at Trusted Pandemic Tech and MIT Media Lab, Sanjay Sarma at MIT Auto-ID Lab and Anna Lysyanskaya at Brown University. 

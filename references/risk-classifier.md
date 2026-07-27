# Risk Classifier Template

Use this template to classify an AI system under the EU AI Act.

## Step 1: System Description

- **System name:**
- **Provider (who builds/brands it):**
- **Deployer (who uses it):**
- **Target market:** EU / EEA / affects EU residents
- **Use case description:**

## Step 2: Prohibited Check (Article 5)

Does the system do ANY of the following?

- [ ] Social scoring by governments
- [ ] Real-time remote biometric identification in public spaces
- [ ] Manipulation of vulnerable groups (age, disability, social situation)
- [ ] Emotion recognition in workplaces or schools
- [ ] Untargeted scraping of facial images
- [ ] Predictive policing based solely on profiling
- [ ] Exploitation of vulnerabilities

If YES to any: **STOP. Prohibited. Advise immediate cessation.**

If NO to all: Continue to Step 3.

## Step 3: High-Risk Check (Annex III)

Is the AI system used in any of these areas?

### A. Biometrics
- [ ] Remote biometric identification
- [ ] Biometric categoration (race, political opinion, trade union membership, religious beliefs, sex life, sexual orientation)
- [ ] Emotion recognition (outside workplace/school)

### B. Critical Infrastructure
- [ ] Management of critical digital infrastructure
- [ ] Energy supply management
- [ ] Water supply management
- [ ] Transport management

### C. Education
- [ ] Grading or assessment of students
- [ ] Admission decisions (university, school)
- [ ] Vocational training assignment

### D. Employment
- [ ] CV screening or resume filtering
- [ ] Job candidate ranking or selection
- [ ] Worker task allocation
- [ ] Performance monitoring or evaluation
- [ ] Termination decisions

### E. Essential Services
- [ ] Credit scoring or creditworthiness assessment
- [ ] Insurance risk assessment or pricing
- [ ] Emergency services dispatch
- [ ] Access to social benefits

### F. Law Enforcement
- [ ] Evidence analysis
- [ ] Risk assessment for criminal activity
- [ ] Profiling in criminal investigations

### G. Migration
- [ ] Visa or asylum application processing
- [ ] Border control
- [ ] Document verification

### H. Justice
- [ ] Assisting judicial decision-making
- [ ] Applying the law to facts

### I. Democracy
- [ ] Influencing election outcomes
- [ ] Generating political content at scale

If YES to any: **High-Risk.** Map obligations by role.

If NO to all: Continue to Step 4.

## Step 4: Annex I Check (Regulated Products)

Is the AI system embedded in any of these products?

- [ ] Medical devices (EU 2017/745)
- [ ] Machinery (EU 2023/1230)
- [ ] Toys (EU 2009/48/EC)
- [ ] Vehicles (EU 2018/858)
- [ ] Aircraft (EU 2018/1139)
- [ ] Lifts (EU 2014/33/EU)
- [ ] Equipment for explosive atmospheres (EU 2014/34/EU)
- [ ] Radio equipment (EU 2014/53/EU)
- [ ] Civilian firearms (EU 2017/853)
- [ ] Recreational craft (EU 2013/53/EU)
- [ ] Cableway installations (EU 2016/424)
- [ ] Pressure equipment (EU 2014/68/EU)

If YES: **High-Risk.** Deadline may differ (August 2028 for Annex I systems).

## Step 5: Limited Risk Check

Does the system:

- [ ] Interact directly with natural persons (chatbots, virtual assistants)?
- [ ] Generate text, images, audio, or video content?
- [ ] Perform emotion recognition?
- [ ] Perform biometric categoration?
- [ ] Produce deepfakes?

If YES: **Limited Risk.** Article 50 transparency obligations apply from August 2026.

## Step 6: Minimal Risk

If none of the above apply: **Minimal Risk.** Only AI literacy obligations under Article 4.

## Classification Result

- **Risk tier:**
- **Basis:**
- **Key deadline:**
- **Next step:**

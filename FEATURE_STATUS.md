# Feature status — Hospital, diagnostics & emergency care

| Capability | Status |
| --- | --- |
| Native sidebar and canonical feature registry | Built; 408 pages |
| Shared records, validation, relationships, persistence | Implemented in shared runtime |
| Clickable table rows with centered details popup | Implemented; Edit, Delete, Cancel, keyboard access and mobile layout |
| Domain field forms and source traceability | Imported from static source definitions; historical routes are labeled in mapping |
| CSV exports, attachments, audit and report totals | Implemented |
| At least 15 fictional rows per editable feature | Seeded by startup; measured in reports/seed-verification.json |
| AI question-and-answer workspace | Replaces AI feature tables; questions, context fields, formatted answers, follow-ups and saved history; live provider configuration required |
| Source calculation adapters | Available for explicitly registered calculation variants only |
| Source business-rule and state-machine parity | Incomplete beyond registered adapters and native records; verify each source journey |
| Original account/business data migration | Not performed; source data preserved |
| Provider integrations and external delivery | Not connected; request preparation only |
| Hosted authentication, independent-review roles and tenant isolation | Not migrated; local single-user boundary |

A successful build or populated table is not evidence of full source workflow parity. The source-to-feature map records every extracted definition and route, with explicit exclusions and migration warnings. Test/build reports distinguish checked behavior from remaining work.

| Canonical feature | Native mode | Source entries | Calculators | Status |
| --- | --- | ---: | ---: | --- |
| Clients & customers | records | 0 | 0 | Native records/view |
| Work items & projects | records | 2 | 0 | Native records/view |
| Contacts & parties | records | 0 | 0 | Native records/view |
| Tasks | records | 0 | 0 | Native records/view |
| Calendar | records | 1 | 0 | Native records/view |
| Deadlines & reminders | records | 0 | 0 | Native records/view |
| Notes | records | 0 | 0 | AI question-and-answer workspace; records available as context |
| Documents | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Templates | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Invoices & billing | records | 4 | 0 | Native records/view |
| Time tracking | records | 0 | 0 | Native records/view |
| Messages & communications | records | 3 | 0 | Native records/view |
| Reports & analytics | report | 7 | 0 | Native records/view |
| Activity & audit trail | audit | 2 | 0 | Native records/view |
| Provider connections | integration | 1 | 0 | Provider request records only |
| Patient Outcome | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Cardiac Outcome | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Staffing Optimization | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Community Paramedicine | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Training Simulator | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Units | records | 1 | 0 | Native records/view |
| Calls | records | 1 | 0 | Native records/view |
| Crew | records | 1 | 0 | Native records/view |
| Schedules | records | 2 | 0 | Native records/view |
| Pcr | records | 1 | 0 | Native records/view |
| Hospitals | records | 1 | 0 | Native records/view |
| Stroke bypass readiness | records | 1 | 0 | Native records/view |
| Equipment | records | 3 | 0 | Native records/view |
| Medications | records | 3 | 0 | Native records/view |
| Maintenance | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Certifications | records | 1 | 0 | Native records/view |
| Incidents | records | 1 | 0 | Native records/view |
| Metrics | records | 1 | 0 | Native records/view |
| Protocols | records | 1 | 0 | Native records/view |
| Comm logs | records | 1 | 0 | Native records/view |
| Exposure | records | 1 | 0 | Native records/view |
| Qa reviews | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Mutual aid | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Triage | records | 2 | 0 | AI question-and-answer workspace; records available as context |
| Unit selection | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Pcr draft | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Protocol | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Demand forecast | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Fatigue analysis | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Hospital divert | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Drug interaction | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Mutual aid optimizer | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Caller script | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Qi dashboard | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Post call debrief | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Incident prediction | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Crew schedule | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Mci plan | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| History | records | 4 | 0 | AI question-and-answer workspace; records available as context |
| Backlog | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Nurses | records | 1 | 0 | Native records/view |
| Patients | records | 6 | 0 | Native records/view |
| Visits | records | 1 | 0 | Native records/view |
| Medical Orders | records | 1 | 0 | Native records/view |
| Routes | records | 1 | 0 | Native records/view |
| Visit Notes | records | 2 | 0 | Native records/view |
| Route Optimizer | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Order Processor | records | 1 | 0 | Native records/view |
| Smart Scheduler | records | 1 | 0 | Native records/view |
| Risk Assessment | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| AI Assistant | records | 2 | 0 | AI question-and-answer workspace; records available as context |
| AI Logs | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Traffic Adjust | records | 2 | 0 | Native records/view |
| Acuity Alerts | records | 1 | 0 | Native records/view |
| Med Interactions | records | 2 | 0 | Native records/view |
| Skill Matching | records | 2 | 0 | Native records/view |
| Outcome Predict | records | 2 | 0 | AI question-and-answer workspace; records available as context |
| Family Portal | records | 1 | 0 | Native records/view |
| Shift Swaps | records | 2 | 0 | Native records/view |
| Pre-Auth | records | 2 | 0 | Native records/view |
| No-Show Predict | records | 2 | 0 | AI question-and-answer workspace; records available as context |
| Acuity check | records | 1 | 0 | Native records/view |
| Family summary | records | 1 | 0 | Native records/view |
| Check conflict | records | 1 | 0 | Native records/view |
| Drugs | records | 1 | 0 | Native records/view |
| Interactions | records | 1 | 0 | Native records/view |
| Adverse reactions | records | 1 | 0 | Native records/view |
| Dosage | records | 1 | 0 | Native records/view |
| Renal dose review | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Alternatives | records | 1 | 0 | Native records/view |
| Allergies | records | 2 | 0 | Native records/view |
| Contraindications | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Food interactions | records | 1 | 0 | Native records/view |
| Pregnancy | records | 1 | 0 | Native records/view |
| Pediatric | records | 1 | 0 | Native records/view |
| Geriatric | records | 1 | 0 | Native records/view |
| Pharmacogenomics | records | 1 | 0 | Native records/view |
| Guidelines | records | 1 | 0 | Native records/view |
| Multi check | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Geriatric risk | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Audit summary | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Clinical trials | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Bed Management | records | 2 | 0 | Native records/view |
| Patient Tracking | records | 1 | 0 | Native records/view |
| Staff Scheduling | records | 1 | 0 | Native records/view |
| Departments | records | 1 | 0 | Native records/view |
| Resources | records | 1 | 0 | Native records/view |
| Operating Rooms | records | 1 | 0 | Native records/view |
| Supply Chain | records | 1 | 0 | Native records/view |
| Emergency Capacity | records | 1 | 0 | Native records/view |
| Isolation Bed Match | records | 1 | 0 | Native records/view |
| AI Insights | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Advanced AI | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| agentic hospital command center visualiz | records | 1 | 0 | Native records/view |
| predictive surge management forecasting | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| length of stay prediction at admission | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| staff allocation optimizer predicting ac | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| readmission prevention ai with enhanced | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| equipment utilization optimizer for vent | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| readmission risk prediction | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| icu step down recommendation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| automated census balancing agent acro | records | 1 | 0 | Native records/view |
| providerclinician scheduling beyond s | records | 1 | 0 | Native records/view |
| billingcoding integration | integration | 1 | 0 | Provider request records only |
| patientfamily communication portal | records | 1 | 0 | Native records/view |
| clinical decision support drug intera | records | 1 | 0 | Native records/view |
| webhook surface | integration | 1 | 0 | Provider request records only |
| real time websocket bed board | records | 1 | 0 | Native records/view |
| Slides | records | 2 | 0 | Native records/view |
| AI Analysis | records | 2 | 0 | AI question-and-answer workspace; records available as context |
| Cancer Detection | records | 1 | 0 | Native records/view |
| Cell Classification | records | 1 | 0 | Native records/view |
| Tissue Segmentation | records | 1 | 0 | Native records/view |
| Quality Control | records | 1 | 0 | Native records/view |
| Annotations | records | 2 | 0 | Native records/view |
| ai pathology assistant | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| second opinion consensus | records | 1 | 0 | Native records/view |
| educational mode | records | 1 | 0 | Native records/view |
| registry integration | integration | 1 | 0 | Provider request records only |
| quality assurance loop | records | 1 | 0 | Native records/view |
| quality assess | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| multi | records | 3 | 0 | Native records/view |
| auto report generate | records | 1 | 0 | Native records/view |
| dedicated routes directory all routes inline in | records | 1 | 0 | Native records/view |
| dicom server integration medical image standard | integration | 1 | 0 | Provider request records only |
| lis lab information system integration | integration | 1 | 0 | Provider request records only |
| whole slide image wsi viewer only stored images | records | 1 | 0 | Native records/view |
| webhooks for lab result delivery | integration | 1 | 0 | Provider request records only |
| notifications layer grep returned 0 notificatio | records | 1 | 0 | Native records/view |
| limited rbac basic auth only | records | 1 | 0 | Native records/view |
| Encounters | records | 1 | 0 | Native records/view |
| Problem List | records | 1 | 0 | Native records/view |
| Clinical Orders | records | 1 | 0 | Native records/view |
| Referrals | records | 1 | 0 | Native records/view |
| Clinical Notes | records | 1 | 0 | Native records/view |
| FHIR Resources | records | 1 | 0 | Native records/view |
| Prescriptions (eRx) | records | 1 | 0 | Native records/view |
| Imaging Studies | records | 1 | 0 | Native records/view |
| Vital Signs Monitor | records | 1 | 0 | Native records/view |
| Symptom Analysis | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Priority Queue | records | 1 | 0 | Native records/view |
| Live ER Board | records | 1 | 0 | Native records/view |
| Doctor Assignment | records | 1 | 0 | Native records/view |
| Treatment Plans | records | 1 | 0 | Native records/view |
| Wait Time Estimation | records | 1 | 0 | Native records/view |
| Medical History | records | 1 | 0 | Native records/view |
| Lab Orders | records | 3 | 0 | Native records/view |
| Discharge Planning | records | 1 | 0 | Native records/view |
| Emergency Alerts | records | 3 | 0 | Native records/view |
| Patient Flow Analytics | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| ESI Calculator | records | 1 | 0 | Native records/view |
| Stroke Door-to-Needle | records | 1 | 0 | Native records/view |
| Resource Predictor | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Medication Safety | records | 1 | 0 | Native records/view |
| AI Predictive | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Agentic ER flow optimization | records | 1 | 0 | Native records/view |
| Multi-modal symptom assessment | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Prediction + action bundling | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Sepsis early warning | records | 1 | 0 | Native records/view |
| Discharge risk stratification | records | 1 | 0 | Native records/view |
| Patients without `/patient | records | 1 | 0 | Native records/view |
| Resources without `/staffing | records | 1 | 0 | Native records/view |
| Discharge without `/readmission | records | 1 | 0 | Native records/view |
| Backend collapses everything into crud.js | records | 1 | 0 | Native records/view |
| No production | records | 1 | 0 | Native records/view |
| No real | records | 1 | 0 | Native records/view |
| No ambulance/EMS integration (arrival notifications, field triage data) | integration | 1 | 0 | Provider request records only |
| No webhooks for critical alerts to pagers/phones | integration | 1 | 0 | Provider request records only |
| No notifications layer dedicated to clinical alerts | records | 1 | 0 | Native records/view |
| No file upload for imaging/lab attachments visible | records | 1 | 0 | Native records/view |
| Patient History Summarize | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Staffing Optimize | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Readmission Risk | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Disease Outbreaks | records | 3 | 0 | Native records/view |
| Vaccination Campaigns | records | 3 | 0 | AI question-and-answer workspace; records available as context |
| Regional Risk Assessment | records | 2 | 0 | AI question-and-answer workspace; records available as context |
| Resource Allocation | records | 2 | 0 | Native records/view |
| Epidemiological Data | records | 2 | 0 | Native records/view |
| Vaccine Inventory | records | 2 | 0 | Native records/view |
| Healthcare Facilities | records | 2 | 0 | Native records/view |
| Disease Prediction | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Risk Factor Analysis | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Drug Interactions | records | 1 | 0 | Native records/view |
| Differential Diagnosis | records | 2 | 0 | Native records/view |
| Population Analytics | records | 2 | 0 | AI question-and-answer workspace; records available as context |
| Patient History | records | 1 | 0 | Native records/view |
| Analysis | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Comorbidity analyze | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Seasonality predict | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| agentic disease surveillance | records | 1 | 0 | Native records/view |
| individual risk dashboard | records | 1 | 0 | Native records/view |
| treatment efficacy tracking | records | 1 | 0 | Native records/view |
| outbreak simulation | records | 1 | 0 | Native records/view |
| travel health risk | records | 1 | 0 | Native records/view |
| patients without comorbidity | records | 1 | 0 | Native records/view |
| trends without seasonality | records | 1 | 0 | Native records/view |
| backend collapses to crud js | records | 1 | 0 | Native records/view |
| public health database integration cdc who | integration | 1 | 0 | Provider request records only |
| case management workflows | records | 1 | 0 | Native records/view |
| contact tracing | records | 2 | 0 | Native records/view |
| limited population health analytics | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| ehr integration | integration | 1 | 0 | Provider request records only |
| notifications module grep 0 | records | 1 | 0 | Native records/view |
| webhooks for outbreak alerts | integration | 1 | 0 | Provider request records only |
| integration with clinical systems | integration | 1 | 0 | Provider request records only |
| Syndromic Surveillance | records | 3 | 0 | Native records/view |
| Water Quality | records | 1 | 0 | Native records/view |
| Air Quality | records | 1 | 0 | Native records/view |
| Hospital Capacity | records | 1 | 0 | Native records/view |
| Mortality Statistics | records | 1 | 0 | Native records/view |
| Disease Reports | records | 1 | 0 | Native records/view |
| Antimicrobial Resistance | records | 1 | 0 | Native records/view |
| Vector-Borne Diseases | records | 1 | 0 | Native records/view |
| Health Equity | records | 1 | 0 | Native records/view |
| Cross-Border Alerts | records | 2 | 0 | Native records/view |
| Assess Importation Risk | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Recommend POE Screening | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Classify Threat Level | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Generate Alert Bulletin | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Recommend Bilateral Actions | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Predict Local Transmission Risk | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Assess Traveler Advisory Need | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Summarize Corridor Epidemiology | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Recommend Vector Control | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Classify Cooperation Readiness | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Predict Spread Timeline | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Generate Joint Investigation Plan | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Assess Economic Impact | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Recommend Communication Strategy | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Classify Outbreak Origin | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Summarize Regional Risk | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Genomic Sequencing | records | 2 | 0 | Native records/view |
| Classify Variant Risk | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Predict Immune Escape | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Summarize Lineage Spread | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Detect Novel Mutations | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Recommend Sequencing Priority | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Compare Variants | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Predict Transmission Advantage | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Generate Phylogenetic Narrative | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Score Sequence Quality | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Assess Vaccine Mismatch | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Predict Clinical Severity | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Summarize Regional Diversity | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Detect Recombination Event | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Recommend Surveillance Targets | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Generate Variant Report | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Assess GISAID Submission Readiness | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Outbreak Cluster Detection | records | 2 | 0 | Native records/view |
| Assess Cluster Significance | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Identify Source Hypothesis | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Recommend Investigation Steps | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Prioritize Clusters | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Predict Cluster Growth | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Generate Cluster Narrative | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Assess Control Measure Effectiveness | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Detect Secondary Clusters | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Classify Exposure Type | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Recommend Contact Tracing Scope | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Summarize Cluster Epidemiology | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Predict Final Cluster Size | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Assess Reporting Completeness | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Generate WHO Report | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Compare Historical Clusters | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Score Environmental Risk | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| R0 / Rt Estimation | records | 1 | 0 | Native records/view |
| Interpret R Value | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Predict Epidemic Trajectory | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Recommend Intervention Intensity | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Assess Estimation Uncertainty | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Compare R Across Regions | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Detect R Changepoint | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Predict Herd Immunity Threshold | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Generate R Narrative | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Recommend Data Window | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Assess Reporting Delay Impact | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Classify Transmission Phase | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Predict Peak Timing | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Assess Intervention Effect | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Summarize Transmission Dynamics | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Recommend Monitoring Frequency | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Generate Policy Brief | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Detect Syndrome Anomaly | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Classify Symptom Cluster | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Predict Disease from Syndrome | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Recommend Investigation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Score Signal Strength | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Generate Alert Narrative | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Summarize ED Visits | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Validate Chief Complaint Coding | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Refine Syndrome Definition | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Detect Facility Bias | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Classify Age Group Pattern | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Predict Seasonal Shift | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Recommend Data Source Addition | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Generate Weekly Report | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Score Data Timeliness | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Summarize Spatial Pattern | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Wastewater Signals | records | 2 | 0 | Native records/view |
| Detect Signal Anomaly | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Classify Pathogen Pattern | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Predict Clinical Cases (Lag) | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Recommend Sampling Frequency | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Score Signal Quality | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Generate Trend Narrative | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Summarize Treatment Plant | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Validate Normalization | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Suggest PMMoV Correction | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Detect Sample Degradation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Classify Shedding Rate | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Predict Outbreak Pressure | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Recommend Confirmatory Testing | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Generate Public Bulletin | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Score Catchment Coverage | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Multi-Pathogen Trend Summary | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| WHO IHR Reporting | records | 2 | 0 | Native records/view |
| Assess PHEIC Criteria | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Generate IHR Notification | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Score Notification Completeness | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Assess International Spread Risk | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Recommend Annex2 Actions | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Classify Event Severity | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Generate Communication Draft | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Assess Country IHR Capacity | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Predict Escalation Likelihood | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Recommend Verification Steps | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Summarize Event Timeline | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Assess Control Measure Adequacy | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Generate Situation Report | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Recommend Cross-Border Actions | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Classify Reporter Credibility | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Summarize IHR Compliance | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| nowcast case trajectory | records | 1 | 0 | Native records/view |
| variant tracking forecasting | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| equityaware resource allocation | records | 1 | 0 | Native records/view |
| social determinants rag | records | 1 | 0 | Native records/view |
| multilanguage health messaging | records | 1 | 0 | Native records/view |
| zoonotic spillover risk model | records | 1 | 0 | Native records/view |
| outbreakprediction spatialtemporal modeli | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| equitygapanalysis disparities by demograp | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| interventionrecommendation evidencebased | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| caseclustering anomaly detection | records | 1 | 0 | Native records/view |
| vaccinationcoverageforecast | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| resourceallocation ai | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| realtime outbreak mapdashboard route | records | 1 | 0 | Native records/view |
| case linelist deduplication workflow | records | 1 | 0 | Native records/view |
| syndromic surveillance ingestion ed otc p | records | 1 | 0 | Native records/view |
| cdcstate healthdepartment api integration | integration | 1 | 0 | Provider request records only |
| contact tracing workflow beyond data stor | records | 1 | 0 | Native records/view |
| notificationssms push for alerts | records | 1 | 0 | Native records/view |
| reportingexport csvpdf | records | 1 | 0 | Native records/view |
| rbac for clinical vs admin roles | records | 1 | 0 | Native records/view |
| Alert subscriptions | records | 1 | 0 | Native records/view |
| Case clustering | records | 1 | 0 | Native records/view |
| Outbreak intervention | records | 1 | 0 | Native records/view |
| R0 estimation | records | 1 | 0 | Native records/view |
| Radiology report generator work | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Smart Scheduling | records | 1 | 0 | Native records/view |
| Clinical Workflows | records | 1 | 0 | Native records/view |
| Revenue Cycle Management | records | 7 | 0 | Native records/view |
| AI Clinical Assistant | records | 5 | 0 | AI question-and-answer workspace; records available as context |
| Quality & MIPS Tracking | records | 5 | 0 | Native records/view |
| Patient Engagement | records | 2 | 0 | Native records/view |
| SOAP Notes | records | 1 | 0 | Native records/view |
| E-Prescriptions | records | 1 | 0 | Native records/view |
| Imaging Orders | records | 1 | 0 | Native records/view |
| Schedule | records | 1 | 0 | Native records/view |
| Appointments | records | 2 | 0 | Native records/view |
| Waitlist | records | 1 | 0 | Native records/view |
| Clinical | records | 2 | 0 | Native records/view |
| Overview | records | 1 | 0 | Native records/view |
| Claims | records | 1 | 0 | Native records/view |
| Payments | records | 2 | 0 | Native records/view |
| Superbills | records | 1 | 0 | Native records/view |
| Aging Report | records | 1 | 0 | Native records/view |
| Denials | records | 1 | 0 | Native records/view |
| Eligibility | records | 1 | 0 | Native records/view |
| Insurance | records | 2 | 0 | Native records/view |
| Verification | records | 1 | 0 | Native records/view |
| Allergy Review | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Fax | records | 1 | 0 | Native records/view |
| Quality & MIPS | records | 1 | 0 | Native records/view |
| AI Features | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Medical Scribe | records | 1 | 0 | Native records/view |
| Settings | records | 2 | 0 | Native records/view |
| Providers | records | 1 | 0 | Native records/view |
| Locations | records | 1 | 0 | Native records/view |
| Services | records | 1 | 0 | Native records/view |
| Fee Schedules | records | 1 | 0 | Native records/view |
| Security | records | 1 | 0 | Native records/view |
| HIPAA | records | 1 | 0 | Native records/view |
| Dashboard | records | 1 | 0 | Native records/view |
| Medical Records | records | 1 | 0 | Native records/view |

Row popup verification passed: dashboard and feature rows, keyboard/focus, editing and persistence, delete confirmation/cancellation, centered mobile layout and full-record navigation. See `reports/row-popup-verification.json`.

## Verified local build

Build, API, browser and actual `start.sh` checks passed. All 408 feature pages were visited in the browser; 406 editable tables contain at least 15 fictional rows each. CRUD persistence and mobile layout were checked. Evidence is in `reports/verification.json`, `reports/browser-verification.json` and `reports/startup-verification.json`.

These checks cover the native local workspace. Full source-specific business rules, authentication and live provider operations remain incomplete as described above. Test servers were stopped after verification.

## AI workspace verification

All 192 AI feature routes were checked in the browser and show questions and formatted answers instead of the original record table. Existing records are retained as optional context. Questions, follow-ups, saved history across restart, Markdown tables, safe rendering, downloads, provider-failure recovery and mobile layout passed with a mocked provider. See `reports/ai-workspace-verification.json`.

Live answers require `OPENROUTER_API_KEY` and `OPENROUTER_MODEL` in this app's `.env` and an app restart. No live provider call was made during verification. Conversational answers do not execute unmigrated specialist engines, read record attachments automatically or perform external actions.


## AI word limits

Questions support up to 5,000 words with a live counter and server validation. AI responses and record drafts have a 16,000-token output budget and a default 180-second timeout to support answers up to 5,000 words; actual length depends on the request and model. Answers show their word count, and long questions can be expanded. Browser checks passed for 5,000-word questions and answers, saved history, full downloads, mobile layout and rejection of 5,001-word questions. See `reports/word-limit-verification.json` (mock-provider boundary checks).

## Merged AI assistants

192 original AI entries are now grouped into **7 assistants** in the sidebar. Choose up to 8 related capabilities and add up to 10 questions for one provider request and one saved response. Shared context is sent once; repeated questions are removed after trimming and whitespace/case normalization. The total question limit is 5,000 words and the combined answer target is up to 5,000 words.

Original feature URLs still open the appropriate assistant with that capability selected. Existing records and answers stay in place; the assistant history includes answers saved under its member features. Non-AI record tables retain their popup actions. This merges the assistant workflow and navigation; it does not implement previously missing external integrations or specialist engines. See `reports/assistant-merge-map.json` and `reports/assistant-merge-verification.json`.

## Floating Ask AI assistant

Implemented across this workspace. The bottom-right **Ask AI** button opens a persistent chat panel on every page. Use **Ask AI about item** in a row popup or record view, or **Use current item** inside the panel, to supply the selected record.

- Questions about the page, any explicitly chosen app record, and general topics.
- Formatted answers, comparison tables, follow-ups, copy and Markdown download.
- Conversation and question drafts stay intact during in-app navigation. Saved answers persist in SQLite; the last conversation restores in the same browser tab after reload. The latest 50 saved answers are listed; restoring one displays up to 20 turns. Up to four preceding turns are sent as AI context.
- Up to 5,000 input words and a response budget of up to 5,000 words. Output length remains dependent on the provider and the question.
- Page title and description are supplied automatically; record fields and notes are sent only for a selected item. Attachments and unselected records are not included. **New chat** starts without earlier conversation context.
- Existing AI provider configuration, timeout, rate limit and safe response renderer are reused. The assistant answers and drafts; it does not execute record changes or external actions.

Validation: shared backend tests, all 64 app builds/API checks, and all 64 browser checks passed with an injected test provider. Browser checks cover item context, navigation, saved history/reload, follow-ups, new-chat isolation, error recovery, word limits, keyboard controls, mobile bounds, safe Markdown rendering and attachment refresh. See [verification](reports/floating-ai-verification.json).

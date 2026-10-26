\# Anti-Amyloid Therapy (AAT) Candidacy \& Risk Assessment Tool



A rapid, client-side pre-referral screening checklist and EHR documentation generator for clinicians evaluating patients with early-stage Alzheimer's disease for monoclonal anti-amyloid therapies (e.g. lecanemab, donanemab).



\*\*\[Launch the Live Tool](https://github.com/carlerickson-md/antiamyloid_therapy_screener)\*\*



\---



\## Overview



Anti-amyloid monoclonal antibodies require systematic screening for clinical safety, baseline biomarker confirmation, and Amyloid-Related Imaging Abnormalities (ARIA) risk stratification. 



This tool provides a lightweight, single-page interface to:

\- Check baseline diagnostic validity (pTau-217 and eGFR).

\- Screen out absolute and relative contraindications.

\- Track confirmatory workup status (Amyloid-PET, MRI microhemorrhages, ApoE genotyping).

\- Generate plain-text output formatted for EHR progress notes (Epic) and patient-friendly After Visit Summaries (AVS).



\## Key Features



\- \*\*Self-Contained \& Offline-Ready:\*\* Pure vanilla HTML5, CSS3, and JavaScript. No external libraries, build tools, or CDNs required.

\- \*\*Zero Protected Health Information (PHI):\*\* No identifying patient data is collected. Operates 100% in the user's local browser memory. No data is stored, cached, or transmitted to any server.

\- \*\*Tri-State Determination Engine:\*\* Dynamically categorizes candidates into \*Potential Candidate\*, \*Pending/Ordered\*, or \*Contraindicated\*.

\- \*\*Quick-Fill Shortcuts:\*\* Section headers feature rapid-fill buttons for pre-screened patients.



\## Clinical Architecture \& Development Methodology



\- \*\*Clinical Design:\*\* Conceived, clinically mapped, and maintained by Carl Erickson, MD.

\- \*\*Engineering Process:\*\* Developed using a physician-in-the-loop, AI-assisted context engineering workflow. Clinical thresholds, safety exclusions, and decision rules were physician-specified and iteratively validated against published guidelines.

\- \*\*Primary References:\*\*

&#x20; - Cummings J, et al. \*Donanemab: Appropriate Use Recommendations\*. J Prev Alzheimers Dis. 2025; 12(1):100094.

&#x20; - Cummings J, et al. \*Lecanemab: Appropriate Use Recommendations\*. J Prev Alzheimers Dis. 2023; 10(3):362-377.

&#x20; - Phase 3 Clarity AD and TRAILBLAZER-ALZ 2 safety monitoring data (ARIA incidence, ApoE ε4 carrier stratification, and microhemorrhage criteria).



\---



\*Disclaimer: This tool is intended for licensed healthcare providers (MD/DO, PA, NP) as an informal clinical decision aid and documentation assistant. It does not substitute for independent clinical judgment, formal specialty cognitive neurology consultation, or manufacturer prescribing information.\*


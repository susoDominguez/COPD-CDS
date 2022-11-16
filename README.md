# COPD-CDS system

A remote, non-proprietary, FHIR- and CDS-Hooks-compliant clinical decision support system that uses evidence-based recommendations from [GOLD COPD 2017](https://goldcopd.org/wp-content/uploads/2017/02/wms-GOLD-2017-FINAL.pdf) to manage COPD symptoms and treatments. In particular, the system provides a personalised assessment of the COPD severity of the patient to then review the current COPD treatment by suggesting one or more patient-specific care plan proposals to treat COPD when CKD or CVD are present.

The system is built on top of *MAGE-DSS*, a **Microservice Architecture for Guideline Embedding in Decision Support Systems**, using the *Transition-based Medical Representation* (TMR) modelling language to represent, and reason about, GOLD COPD 2017.



# COPD-CDS system

#### Deployed at

<img src="Kings_College_London-logo.png" width="150">


<img src="Imperial-College-London-logo.jpeg" width="150">

#### Integrated with

<img src="heliant_logo.jpeg" width="150">

A remote, non-proprietary, FHIR- and CDS-Hooks-compliant clinical decision support system that uses evidence-based recommendations from [GOLD COPD 2017](https://goldcopd.org/wp-content/uploads/2017/02/wms-GOLD-2017-FINAL.pdf) to manage COPD symptoms and treatments. In particular, the system provides a personalised assessment of the COPD severity of the patient to then review the current COPD treatment by suggesting one or more patient-specific care plan proposals to treat COPD when CKD or CVD are present.

The system is built on top of *MAGE-DSS*, a **Microservice Architecture for Guideline Embedding in Decision Support Systems**, using the *Transition-based Medical Representation* (TMR) modelling language to represent, and reason about, GOLD COPD 2017.

For installation of all the services that compose the COPD-CDS system, and execution using the use cases from the ROAD2H proof-of-concept evaluation, read the [technical specification document](COPD-CDS_system_installation.docx).



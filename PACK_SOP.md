# **PACK: Preservation & Access Compliance Kit**

**Standard Operating Procedures (v2025.1)**

## **Scope & Disclaimer**

This protocol suite addresses technical workflows for data continuity, redundancy, and attribution. It is designed to satisfy specific sub-sections of federal data mandates (NOT-OD-21-013). **It is not a comprehensive legal compliance program.** Adherence to these protocols does not substitute for Institutional Review Board (IRB) approval, HIPAA compliance, or Export Control regulations.

## **Regulatory Alignment**

These protocols align laboratory workflows with [**NIH Policy NOT-OD-21-013**](https://grants.nih.gov/grants/guide/notice-files/NOT-OD-21-013.html) (Data Management and Sharing) and the [**OSTP "Nelson Memo"**](https://www.google.com/search?q=https://www.whitehouse.gov/wp-content/uploads/2022/08/08-2022-OSTP-Public-Access-Memo.pdf), ensuring the persistence, findability, and attribution of research outputs.

## **1\. Preservation (Version Control)**

**Policy Basis:** NIH NOT-OD-21-013 requires "preservation of scientific data" regardless of personnel changes.

* **Redundant Forking:** To mitigate "Bus Factor" risks, all researchers must maintain a personal Fork of active repositories. This ensures a distributed backup exists if the primary lab repo faces administrative lockout or corruption.  
* **Frequency:** Code pushes should occur daily to ensure continuity.

## **2\. Access (Persistent Identifiers)**

**Policy Basis:** [**NIH NOT-OD-21-016**](https://grants.nih.gov/grants/guide/notice-files/NOT-OD-21-016.html) prioritizes repositories that "Assign Unique Persistent Identifiers (PIDs)."

* **Zenodo Integration:** Major releases must be archived via [**Zenodo**](https://zenodo.org) to generate a **DOI (Digital Object Identifier)**.  
* **Compliance:** This satisfies the "Findability" requirement of FAIR data principles and provides an immutable record for grant reporting.

## **3\. Metadata (Attribution & Reuse)**

**Policy Basis:** Clear metadata is required for "Data Reuse" (Element 3 of DMS Plans).

* **CRediT Tracking:** Projects must initiate with an Authorship MOU based on the [**Contributor Roles Taxonomy (CRediT)**](https://credit.niso.org).  
* **Audit Trail:** Researchers should submit brief email recaps following supervisory meetings to create a searchable log of experimental pivots and decisions.

## **4\. Integrity (Preregistration)**

**Policy Basis:** Enhances rigor per NIH "Enhancing Reproducibility" ([**NOT-OD-15-103**](https://grants.nih.gov/grants/guide/notice-files/NOT-OD-15-103.html)).

* Confirmatory studies must be preregistered on the [**Open Science Framework (OSF)**](https://osf.io). This establishes a public, immutable timestamp of intellectual property and study design.

## **5\. Continuity (Departure Protocol)**

**Policy Basis:** Ensures data remains accessible "at the end of the performance period."

* Researchers must certify their Personal Forks are synced with the Lab Remote prior to departure.  
* Researchers should retain local copies of correspondence and data dictionaries to assist with future post-publication inquiries or audits.
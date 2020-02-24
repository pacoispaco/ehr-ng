# About EHR-ng

EHR-ng is a new approach to EHR-systems.

There is no code yet. Just ideas!

# Current problems of EHR-systems

In no particluar order of seriousness:

* Monolithic systems.
* Data hoarding systems. No simple export or import of data.
* Bad or poor API:s. Poor support for systems integration.
* Expensive licenses. Customers pay for both licenses and development.
* Huge and complex standards that are difficult and seldome fully implemented.
* Tight integration of health care process data and features with EHR data and features.
* No clear separation of communication between health care professionals and EHR data. Communication often stored in EHR.
* Based on the assumption that the healthcare provider "owns" the EHR, not the patient.
* No modern UX and usability design.

# Some principles for a new EHR system

**The core principles**:

* The patient owns the EHR-data.
* EHR-data is the most valuable asset of the system.
* Separate the EHR-data from health care process data, and communication between health care professionals.
* EHR-data should be seen as a time log of events; a journal.
* Conserve integrety and traceability of changes to EHR-data.

_Note_: By health care process data is meant, among other things, information on health care units and organisation, status of patient treatment in health care flow, bookings, invoices etc.

**Technical principles**:

* Data-centric design.
* Distributed by design.
* No technical or data dependencies between different peoples EHR-data.
* Separate persistance and integrity of EHR-data from presentation of and features on EHR-data.
* Standards used must be open, free, simple and have open-source reference implementations.
* It should be easy for third party providers to develop and provide tools and servcies for manipulating EHR-data.

# Some technologies that are relevant

* Blockchain.
* C API for accessing EHR-data.
* Command line tools for accessing and manipulating EHR-data.
* Mobile app
* Webb app
* Microservices for core data sets

# EHR-data: some core data sets

_Note_: All data should be seen as being entered on a time line; a journal!

* Personal core characteristics; birth date, weight, length, sex, blood type, etc.
* Personal characteristics; allergies, etc.
* Personal comments on health.
* Measurement based data and calculated characteristics; age, BMI, blood pressure, etc.
* Medication data.
* Vaccination data.
* Lab-based data and calculated characteristics; blood samples, renal clearance, etc.
* Image based data; radiography, magnetic resonance imaging, ultrasound, photoacoustic imaging, magnetic particle imaging, etc.
* Diagnostics by medical professionals.
* Comments by medicial professionals.
* Recommended treatment and instructions by medical professionals.

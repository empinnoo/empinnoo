The overall goal of this project is to simulate a Health Information Exchange (HIE) and hospital production environment. It teaches how information can be shared between different hospitals using the HIE. 


This project is broken up into five different main parts:

1. Virtual Machine Configuration - The purpose of this part is to setup five different virtual machines (VMs) on Michigan Tech's CoC Virtual Cluster software. Four VMs are to mimic the production environment of hospitals, while the other VM is to mimic a Health Information Exchange (HIE) system. To ensure I had setup the VM's and their compatibility with HAPI-FHIR and OpenEMR, I successfully pinged the four hospitals from the HIE.

2. Installation, Configuration, and Security of OpenEMR - The purpose of this part is to learn about the installation and configuration of an electronic health record (EHR) which had to take place in each of the four hospital's VMs. This involved using commands in the terminal to install and configure security options for the software.

3. Generation of Synthea Patient and Syndromic Surveillance Data for Hospital EHRs to Simulate Disease Outbreak - The purpose for this part is essentially in the name. I had to learn the process of generating patient data using Synthea software to simulate a disease outbreak for the four hospitals. This involved using terminal commands to both setup Synthea and use the software to generate patient data that was stored in .json files.

4. Installation and Configuration of Hapi-FHIR Server - For this part, the main goal was to learn about the installation and configuration of a Hapi-FHIR server. Using the HIE VM, I used commands in the terminal to install and run the Hapi-FHIR software. Confirmation of successful running was seen by opening it up in the local web browser.

5. Interoperability, FHIR Data Exchange with HAPI-FHIR - The purpose of this part is to learn how Hapi-FHIR's framework can accept HL7 FHIR (Fast Healthcare Interoperability Resources) message systems for critical public health surveillance. This involved working with Postman to create new FHIR instances and creating both GET and POST requests to send and receive information about the generated patient data.

Challenges:
There were a few challenges that I encountered throughout the process of this project:
  - Learning the different terminal commands to accomplish the necessary tasks.
  - The repeatability of steps throughout multiple VMs.
  - Encountered errors when trying to use GET requests using Postman.

Outcome:
Successfully setup five VMs. Four VMs representing hospitals where I installed, configured, and secured the OpenEMR software and generated synthetic patient data using Synthea. One VM represent the HIE where the Hapi-FHIR Server was installed, configured, and ran. I used the Postman software to utilize GET and POST requests to grab synthetic patient data information from the four hospital's VMs.

Project Files:
The five other files in this project are the results to each part of this project and are named in accordance with each part.

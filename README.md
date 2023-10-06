# Create Invoice («FI-Buchung anlegen»)

## Goal of this repository

The primary purpose of an FI-CA (Financial Accounting – Contract Accounting) repository as an API within SAP is to enhance the interaction with contract accounting functionalities. This repository allows for the integration and automation of processes, such as billing and payments, making these features accessible to various systems through standardization.

The repository ensures secure and compliant interactions, which are essential for meeting regulatory requirements. Moreover, it bolsters efficiency when executing complex financial transactions and offers scalability for managing contract accounting tasks. In essence, the FI-CA repository simplifies and optimizes financial operations within the SAP framework.

## How does this API work?

The official SAP documentation provides multiple links that elucidate the different parameters and essential details required to utilize the API effectively.

- **FI-CA Document – Manage**: This service facilitates the posting and reversal of FI-CA documents. However, modifications to existing FI-CA documents are not supported by this service. [FI-CA Document – Manage](https://api.sap.com/api/FKCMANAGECADOCUMENT/overview)

- **FI-CA Document – Bulk Create**: This asynchronous inbound bulk service allows the transfer of Contract Account document data from external systems to Contract Accounting (FI-CA) in SAP S/4HANA Cloud. It supports the posting of FI-CA documents, but updates to existing documents are not permitted. [FI-CA Document – Bulk Create](https://api.sap.com/api/FKCBULKCREATEREQUESTCADOC_IN/overview)

- **FI-CA Document – Return Status of Bulk Creation to Client System**: This asynchronous outbound service enables the transfer of confirmation data from Contract Accounting (FI-CA) in SAP S/4HANA Cloud to external systems. [FI-CA Document – Return Status](https://api.sap.com/api/CO_FKC_DOC_BLK_CREATE_CONF_OUT/overview)

## Contact information

From the details provided above, you should attain a comprehensive overview of the API's capabilities.

If you're keen on using and collaborating with the API, please reach out so we can assess your application and supply the necessary credentials and details.

For additional support with the API, the BIT technical support SAP team is on standby to address your inquiries during regular business hours.

To get in touch, please email [FachsupportSAP@bit.admin.ch](mailto:FachsupportSAP@bit.admin.ch).

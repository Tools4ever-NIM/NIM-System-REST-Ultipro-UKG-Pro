# NIM-System-REST-Ultipro-UKG-Pro

<p align="center">
  <img src="https://www.tools4ever.nl/connector-logos/ultipro-logo.png" width="500">
</p>

## Getting Started
By using this connector you will have the ability to import data into HelloID:
* Employee Demographics
* Employee Phones
* Employment Details
* Company Information

## Setup API Access 
- Log in with an administration account in UKG Pro
- Create a 'service account' from the "Service Account Administration" page.
    - That user should have a username and a password. Note these 2 pieces of information (we do not need the email address)
    - The permissions for that account should be:
        - "View" role for the "Employee Person Details"
        - "View" role for the "Personnel Integration"
        - "View" role for the "Company Configuration Integration"
        - "View" role for the "Employee Phone Information"
- Navigate to "System Configuration > Security > Web Services"
    - Note the "customer API key" and the "Employee person service endpoint" URL.

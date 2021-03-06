# Version Control

## Version 1.2.0 - 12/11/2020

### **Azure Resource Inventory:**
        1. Added extra data for Azure VM
        2. Added extra data for Disks
        2. Added notes to relevant issues with official Microsoft link

---
## Version 1.1.0 - 12/08/2020

### **Azure Resource Inventory:**
        1. Implemented Jobs during Azure extraction (Jobs were used only in the reporting phase)
        2. Fixed an issue with ImportExcel Module

---
## Version 1.0.7 - 12/07/2020

### **Azure Resource Inventory:**
        1. Added "Running as Admin" validation when installing ImportExcel module.
        2. Fixed a minor issue in the -SkipSecurityCenter parameter

---
## Version 1.0.5 - 12/06/2020

### **Azure Resource Inventory:**
Grinder will no longer be used in the name. It will only be Azure Resource Inventory.During the development phase in private repository Grinder was used at name with reference to "Meat Grinder" but this name is now retired.

---
## Version 1.0.2 - 12/04/2020

### **AzureGrinder:**
        1. Fix issue on single tenant usage
        2. Added SubscriptionID option

---

## Version 1.0 - 12/03/2020
1.0 - Offical release 

---
## Version 0.5 - 11/25/2020

### **AzureGrinder:**
        1. Removal of XML files generation
        2. InMemory capturing and processing of the Inventory
        3. Split between VNET and VNET Peering
        4. Using Progress bar instead console writing

---
## Version 0.4.0 - 11/25/2020

### **AzureGrinder:**
        1. Merge of Extractor and Grinder in the same file

---
## Version 0.3.6 - 11/23/2020

### **AzureGrinder:**
        1. Debugging mode
        2. Added Network Gateway Resource Type
        3. Improvements made in the Load Balancer sheet
        4. Improvements made in the SQL DB Sheet
        5. Added SQL Servers Resource Type

---
## Version 0.3.5 - 11/19/2020

### **AzureGrinder:**
        1. Improvements in Storage Account analyzes, now including:
            a. Public Access
            b. TLS Version
            c. ADDS
            d. Secondary location

---
## Version 0.3.4 - 11/18/2020

### **AzureGrinder:**
        1. Bugfix on VNET version

---
## Version 0.3.3 - 11/17/2020

### **AzureGrinderExtractor:**
        1. Unified Desktop and Cloudshell version 
### **AzureGrinder:**
        1. Modified version of VNET analyzes

---
## Version 0.3.2 - 11/17/2020

### **AzureGrinder:**
        1. Fixed NSG Validation on VMs Sheet

---
## Version 0.3.1 - 11/15/2020

### **AzureGrinder:**
        1. Added "Performance Diagnostics Agent" column to the VMs sheet 

---
## Version 0.3 - 11/12/2020

### **AzureGrinder:**
        1. Fixed all charts in Overview
        2. Added the Subscriptions chart to the Overview sheet
        3. Added Load Balancer sheet
        4. Added Subscriptions sheet
        5. Added Network Interface details to the VMs sheet
        6. Added NSG details to the VMs sheet
        7. Added VM Extensions to the VMs sheet
        8. Added Excel formatting to:
            a. Accelerated Networking column in VMs sheet
            b. Excel style to the AC column (VM Extensions)
        9. Added Network Gateway details to the Public IP sheet
        10. Added VM Scale Sets sheet
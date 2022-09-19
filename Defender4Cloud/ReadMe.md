# Azure Security Training - Microsoft Defender for Cloud Labs

<p align="center">
<img src="./Images/asc-labs-logo.png?raw=true">
</p>

## Introduction
This is a fork from [Microsoft Defender for Cloud Labs!](https://github.com/Azure/Microsoft-Defender-for-Cloud/tree/main/Labs) adjusted to provide a one day workshop with Defender for Cloud training. For full version see the orgiginal repo.


## Prerequisites - OBS! Must be done **before** the workshop

To get full use of this one day you need to come prepared! That means that you must have prepared the lab environment in forhand. Which means that you **must** deploy this lab to a new subscription **before** you meet up for the workshop.

Module 1 represents the prerequesites. the whole module must be completed!
- Step 1: create a new Trial Subscription - this can anly be done if you are eligible for it and have not created a free subscription before. If you are *not* eligibel for a free subscription you can use any other paid subscription you my have or have available thru your employer. The lab will be created within a resourcegroup and can easly be deleted after the workshop.
- Step 2: Provision the resources in this lab
- Step 3: Enable Microsoft Defender for Cloud

See this README for full description of the prerequisites: [**Prerequisites for Azure Security Trainging**](../README.md)



## Modules

[**Module 1 – Prerequisites - Preparing the Environment (L100)**](../README.md)

To be done on the Workshop day:
[**Module 2 – Exploring Microsoft Defender for Cloud (L100)**](./Modules/Module-2-Exploring-Azure-Security-Center.md)
- [Understanding Microsoft Defender for Cloud dashboard](./Modules/Module-2-Exploring-Azure-Security-Center.md#exercise-1-understanding-azure-security-center-dashboard)
- [Exploring Secure Score and Recommendations](./Modules/Module-2-Exploring-Azure-Security-Center.md#exercise-2-exploring-secure-score-and-recommendations)
- [Exploring the Inventory capability](./Modules/Module-2-Exploring-Azure-Security-Center.md#exercise-3-exploring-the-inventory-capability)
 
[**Module 3 – Security Policy (L200)**](./Modules/Module-3-ASC-Security-Policy.md)
- [Overview of the security policy](./Modules/Module-3-ASC-Security-Policy.md#exercise-1-overview-of-the-asc-policy)
- [Explore Azure Policy](./Modules/Module-3-ASC-Security-Policy.md#exercise-2-explore-azure-policy)
- [Create resource exemption for a recommendation](./Modules/Module-3-ASC-Security-Policy.md#exercise-3-create-resource-exemption-for-a-recommendation)
- [Create a policy enforcement and deny](./Modules/Module-3-ASC-Security-Policy.md#exercise-4-create-a-policy-enforcement-and-deny)
- [Create a custom policy](./Modules/Module-3-ASC-Security-Policy.md#exercise-5-create-a-custom-policy)

[**Module 4 – Regulatory Compliance (L200)**](./Modules/Module-4-Regulatory-Compliance.md)
- [Understanding Regulatory Compliance dashboard](./Modules/Module-4-Regulatory-Compliance.md#exercise-1-understanding-regulatory-compliance-dashboard)
- [Adding new standards](./Modules/Module-4-Regulatory-Compliance.md#exercise-2-adding-new-standards)
- [Creating your own benchmark](./Modules/Module-4-Regulatory-Compliance.md#exercise-3-creating-your-own-benchmark)
 
[**Module 5 – Improving your Secure Posture (L300)**](./Modules/Module-5-Improving-your-Secure-Posture.md)
- [Vulnerability assessment for VMs](./Modules/Module-5-Improving-your-Secure-Posture.md#exercise-1-vulnerability-assessment-for-vms)
- [Vulnerability assessment for Containers](./Modules/Module-5-Improving-your-Secure-Posture.md#exercise-2-vulnerability-assessment-for-containers)
- [Automate recommendations with workflow automation](./Modules/Module-5-Improving-your-Secure-Posture.md#exercise-3-automate-recommendations-with-workflow-automation)
- [Accessing your secure score via ARG](./Modules/Module-5-Improving-your-Secure-Posture.md#exercise-4-accessing-your-secure-score-via-arg)
- [Creating Governance Rules and Assigning Owners](./Modules/Module-5-Improving-your-Secure-Posture.md#exercise-4-accessing-your-secure-score-via-arg)
 
[**Module 6 – Microsoft Defender Plans (L300)**](./Modules/Module-6-Azure-Defender.md)
- [Alert validation](./Modules/Module-6-Azure-Defender.md#exercise-1-alert-validation)
- [Alert suppression](./Modules/Module-6-Azure-Defender.md#exercise-2-alert-suppression)
- [Accessing Security Alerts using Graph Security API](./Modules/Module-6-Azure-Defender.md#exercise-3-accessing-security-alerts-using-graph-security-api)

[**Module 8 – Enhanced Security (L300)**](./Modules/Module-8-Advance-Cloud-Defense.md)
- [Using JIT to reduce attack surface](./Modules/Module-8-Advance-Cloud-Defense.md#exercise-1-using-jit-to-reduce-attack-surface)
- [Adaptive Application Control](./Modules/Module-8-Advance-Cloud-Defense.md#exercise-2-adaptive-application-control)
- [File Integrity Monitoring](./Modules/Module-8-Advance-Cloud-Defense.md#exercise-3-file-integrity-monitoring)


[**Module 13 – Simulate Incidents**](./Modules/Module-13-simulate-incidents.md)



## Skill level

<p align="center">
<img src="./Images/asc-labs-levels.png?raw=true">
</p>

Skill | Level | Description
----- | ----- | -----------
Beginner | 100 | You're starting out and want to learn the fundamentals of Microsoft Defender for Cloud
Intermediate | 200 | You have some experience with the product but want to learn more in-depth
Advanced | 300+ | You have lots of experience and are looking to learn about advanced capabilities


## Acronyms

Acronym | Meaning | Description
------- | --- | -----------
MDFC | Microsoft Defender for Cloud | Built-in free service which offer limited security for your Azure resources only
CSPM | Cloud Security Posture Management | Automates the identification and remediation of risks across cloud infrastructures. CSPM in Microsoft Defender for Cloud is available for free to all Azure users. The free experience includes CSPM features such as secure score, detection of security misconfigurations in your Azure machines, asset inventory, and more.
CWP | Cloud Workload Protection | Provides workload-centric security protection solutions such as servers, app service, storage, database and more. All CWP capabilities are covered under Microsoft Defender for Cloud.
JIT | Just-in-time | Feature to reduce exposure to attacks while providing easy access when you need to connect to a VM
ARM | Azure Resource Manager | Deployment and management layer that enables you to create, update, and delete resources in your Azure account.
RBAC | Role-based access control | Authorization system built on Azure Resource Manager that provides fine-grained access management of Azure resources.
VA | Vulnerability Assessment | Provides vulnerability scanning for your virtual machines and container registries.
SIEM | Security information and event management | Tool to provide a central place to collect events and alerts, that aggregates data from multiple systems and analyze that data to catch abnormal behavior or potential cyberattacks. For example, Microsoft Sentinel.


## Last release notes
29.aug 2022 - in preparation for autum caurse for HackCon

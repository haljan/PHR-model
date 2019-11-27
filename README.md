# Prepare, Hunt, and Respond
Prepare, Hunt, and Respond - Conceptual model against cyber attack by [JYVSECTEC](https://jyvsectec.fi)

## Overview
The idea behind the conceptual model is to represent comprehensive model for organizations to defend against modern cyber attacks. The model "PREPARE, HUNT, AND RESPOND" will be evolving from the initial release (from version 1.0) to encompass more detailed information and case examples of tools and techniques to each section. The goal is to gather the best publicly available solutions and tools to represent how different sections of the model can be done. The solutions will be demonstrated using our Cyber Range’s organization environments in the case examples.

!!Illustration of The Model!!
[Download the PDF version]()

JYVSECTEC and our experts have gained a lot experience and knowledge by organizing cyber exercises and trainings for government and private companies past 10 years. This experience has helped us to create a new comprehensive model how organizations should be prepared against cyber attacks and cyber crimes. Even though overview of the model might seem difficult to comprehend, our aim is to provide detailed information and examples how each section of the model can be implemented in organizations. The goal of the model is to integrate traditional cyber security with incident response and threat hunting as a one complete model for preventing, hunting, and responding to threats. Important part of the model is to utilize continuous development of the organization’s capabilities to defend the business.

This model is made available for everyone to utilize in their organization and we are more than happy to welcome any criticism, improvements, ideas, notes, and feedback of the model.

## 1. Preparations
The model starts with preparations that are critical for organization to able protect their critical assets and business services. These preparations include (but are not limited to) essential processes, technologies, and procedures to manage the environment and prepare for handling the attacks.

## 2. Hypotheses
The second section "Hypotheses" encompasses identified threats and attacking vectors against organization. The threats and attacking vectors should analyzed using TTPs (Tactics, Techniques, and Procedures) that the potential threat actor might use against the organization. The TTPs should be identified and prioritized based on the organization's identified risks.

## 3. Data Collection
The third section "Data Collection" is a set of identified data sources and types that helps to detect if the TTPs in hypotheses section are used against organization. These data sources should be specified as precisely as possible so there is no need to collect extensive amounts of log data for Threat hunting and incident response processes. Also identifying the essential data based on potential attack vectors and methods, helps organization to utilize most suitable playbooks in threat hunting and checklists on incident response analysis. The "Data collection" section also include Automated Malware analysis of different samples that are gathered from various data sources. The automated malware analysis can encompass multiple methods (i.e. AI, automated workflows for malware analysis, sandboxing) to detect potential malicious files and activities in the environment.

## 4. Enrichment
The fourth section "Enrichment" is a set of information that can be used to enrich collected data with organization specific information. The "Enrichment" section also includes Threat Intelligence that is utilized to proactively to detect known malicious IoCs (Indicators of Compromise) and TTPs

from the environment. Threat intelligence should tightly integrate to organization's threat hunting and incident response activities to help to identify threat actors and attack vectors. Enrichment can also be tools and solutions to give more information on the malware analysis. Also for example, IPAM information can used to link IP addresses and domain names to organization's assets automatically.

## 5. Playbooks
The fourth section "Enrichment" is a set of information that can be used to enrich collected data with organization specific information. The "Enrichment" section also includes Threat Intelligence that is utilized to proactively to detect known malicious IoCs (Indicators of Compromise) and TTPs

from the environment. Threat intelligence should tightly integrate to organization's threat hunting and incident response activities to help to identify threat actors and attack vectors. Enrichment can also be tools and solutions to give more information on the malware analysis. Also for example, IPAM information can used to link IP addresses and domain names to organization's assets automatically.

## 6. Triage / Respond
The sixth section "Triage / Respond" describes how detected malicious activities are handled in the organization. The detection can be come as an automated alert from security controls, SOC or users, or it can be detected during threat hunting activities performed in the environment. The Incident response starts with Triage process where Incident Response Team member should quickly analyze the nature of the incident (i.e. what has happened, where has it happen, when has the first indications happen). After that the impact against organization's business services should evaluated. Depending on organization's decision the category and priority for incident should be determined. Once the criticalness against business services has been determined the allocation on the resources should be defined for further analysis of the incident. The detailed analysis of incident can a quick process or it can take several days/weeks depending on the nature of the incident. During the detailed analysis it is vital to collect evidence and IoCs of the attack for making proper decisions how to contain the attack and how to countermeasure against it. Also, the actions taken during the investigation and analysis is important to document to incident tracking system so it is possible after the attack to review who has done what during the analysis.

## 7. Eradicate / Recover
The seventh section "Eradicate / Recover" are the actions for isolating and recovering from attack. The aim is to ensure secure operations of the business continuity, confidentiality, and integrity of the data affected by the attack. During the containment and recovery, the thorough documentation of actions performed must be done. Also, all the evidence that has been found from the systems and environment needs to be stored in a secure location. The IoCs that has been identified of the incident should documented and used as a tool to understand more thoroughly how the attack happened and how to prevent similar incidents in the future.

## 8. Lessons Learned
The Eight section "Lessons Learned" should be comprehensive analysis of the whole incident. It should include complete review the threat hunting and incident response activities performed before detection and after the detection. The idea is to use post-analysis as tool to continuously develop the capabilities of the organization and identify detection gaps, data sources or faulty architecture. Also, post-analysis should be used as method to develop new threat hunting playbooks, modify existing tools and guidelines, and update documentation. The post-analysis can identify also new relevant assets for the organization and gaps in personnel's expertise which should be addressed with proper training and exercises.

## 9. Improvements
The improvements are a vital part of the model for organization to improve their capabilities based the incident that has been handled. The improvements should be identified during the lessons learned section to enhance either organization’s environment or processes.

# Road-Map
The up-coming updates for the model:
- Initial release of the overview
  - Open for comments and feedback from community
- More thorough processes and procedures for each section
  - All the sections will be described in more detail during 2020
- Case examples of different solutions for sections
  - Practical examples on how organizations can use the model are provided as case studies during years 2020-2021
- Best practices how to involve police authorities will be implemented as a part of the model during years 2020 - 2021

# Main contributors
The model has been created as a part of Ministry of Education and Culture of Finland funded [CYBERDI](https://jyvsectec.fi/2018/10/cyberdi/) project. The work has been done by specialists of JYVSECTEC and Finland's Police University College.

Logo JYVSECTEC
Logo JAMK.fi
Logo Police University

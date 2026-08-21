<div align="center">

# 🛡️ INTERN SHIELD

## CLOUD COMPUTING & SECURITY
### Practical Laboratory Series

**A Four-Laboratory Journey Through AWS Cloud Security & Container Security**

<br>

**DISCOVER · ASSESS · ANALYZE · REMEDIATE · SECURE**

<br>

![Cloud Computing](https://img.shields.io/badge/Cloud%20Computing-AWS-232F3E?style=for-the-badge&logo=amazonaws&logoColor=white)
![Cloud Security](https://img.shields.io/badge/Cloud%20Security-InternShield-00A9A5?style=for-the-badge)
![S3](https://img.shields.io/badge/Amazon%20S3-Storage%20Security-orange?style=for-the-badge&logo=amazons3&logoColor=white)
![IAM](https://img.shields.io/badge/AWS%20IAM-Identity%20Security-00A9A5?style=for-the-badge&logo=amazonaws&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-Container%20Security-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Trivy](https://img.shields.io/badge/Trivy-Vulnerability%20Assessment-1904DA?style=for-the-badge)

**Version 1.0 · 2026**

</div>

---

## ◈ About the Series

**InternShield Cloud Computing & Security Practical Laboratory Series** is a structured four-laboratory program designed to provide learners with practical exposure to modern **cloud-security assessment and container-security concepts**.

The series progresses from cloud-storage discovery and security assessment to identity security, privilege-escalation risk analysis, and container vulnerability assessment.

Rather than focusing only on theoretical concepts, the laboratories are structured around a practical security workflow:

```text
                  ┌─────────────────┐
                  │     DISCOVER    │
                  └────────┬────────┘
                           ↓
                  ┌─────────────────┐
                  │     ASSESS      │
                  └────────┬────────┘
                           ↓
                  ┌─────────────────┐
                  │     ANALYZE     │
                  └────────┬────────┘
                           ↓
                  ┌─────────────────┐
                  │    REMEDIATE    │
                  └────────┬────────┘
                           ↓
                  ┌─────────────────┐
                  │      SECURE     │
                  └─────────────────┘


◈ Laboratory Roadmap
Lab	Laboratory	Primary Technology	Security Focus
01	Performing S3 Bucket Enumeration	Amazon S3	Cloud Storage Discovery
02	S3 Bucket Security Testing / Exploitation	AWS CLI / S3	Access Control Assessment
03	Assessing IAM Privilege-Escalation Risks	AWS IAM	Identity & Permission Security
04	Docker Image Vulnerability Assessment	Docker / Trivy	Container Security
◈ LAB 01
Performing S3 Bucket Enumeration
AMAZON S3 · CLOUD RECONNAISSANCE · STORAGE EXPOSURE

The first laboratory introduces learners to Amazon S3 bucket enumeration as part of a cloud-security assessment.

Learners explore how S3 resources can be discovered and assessed for potential exposure within an authorized laboratory environment.

Core Topics
Amazon S3
   │
   ├── Bucket Discovery
   ├── Enumeration
   ├── Exposure Identification
   ├── Security Analysis
   └── Findings Documentation
Primary Tool

Lazys3

Learning Path

Discover → Enumerate → Identify Exposure → Analyze → Document

◈ LAB 02
S3 Bucket Security Testing / Exploitation
AMAZON S3 · AWS CLI · ACCESS CONTROL

Lab 02 builds upon the discovery concepts introduced in Lab 01 and moves into controlled S3 security assessment.

Learners examine storage permissions and access-control configurations to understand how cloud-storage misconfigurations can create security and data-exposure risks.

Any access or data-extraction demonstration must use authorized laboratory resources and test data only.

Core Topics
S3 access controls
Bucket policies
Permissions
Public-access configuration
Storage misconfiguration
Controlled security testing
Data-exposure analysis
Security remediation
Primary Technology

AWS CLI + Amazon S3

Learning Path

Identify → Assess → Test → Analyze → Secure

◈ LAB 03
Assessing IAM Privilege-Escalation Risks
AWS IAM · POLICIES · PERMISSIONS · LEAST PRIVILEGE

Lab 03 focuses on the security assessment of AWS Identity and Access Management (IAM) configurations.

Learners analyze users, policies, permissions, and potentially dangerous permission combinations to identify privilege-escalation risk indicators.

The laboratory emphasizes understanding and validating security risks rather than automatically exploiting them.

Core Topics
AWS IAM
 │
 ├── Users
 ├── Groups
 ├── Roles
 ├── Managed Policies
 ├── Inline Policies
 ├── Permissions
 ├── Least Privilege
 └── Escalation Risk
Primary Technology

AWS IAM

Learning Path

Identify → Analyze → Assess → Verify → Secure

◈ LAB 04
Docker Image Vulnerability Assessment
DOCKER · TRIVY · CVEs · CONTAINER SECURITY

The fourth laboratory introduces learners to Docker image security assessment using Trivy.

Learners scan container images, identify known vulnerabilities, interpret CVEs and severity levels, compare vulnerability posture, and develop remediation recommendations.

Core Topics
Docker image fundamentals
Container security
Trivy vulnerability scanning
OS-package vulnerabilities
CVE analysis
Severity classification
Vulnerability triage
Base-image security
Remediation
Re-scanning
Primary Tool

Trivy

Security Lifecycle
BUILD
  ↓
SCAN
  ↓
DETECT
  ↓
TRIAGE
  ↓
REMEDIATE
  ↓
RE-SCAN
  ↓
VERIFY
◈ Technology Stack
<div align="center">
Technology	Purpose
AWS	Cloud infrastructure
Amazon S3	Object storage security
AWS IAM	Identity & access management
AWS CLI	Cloud administration & assessment
Lazys3	S3 enumeration
Docker	Container platform
Trivy	Vulnerability assessment
Linux / Parrot / Kali	Security laboratory environment
</div>
◈ Learning Outcomes

After completing the four laboratories, learners should be able to:

01 Understand fundamental cloud-security assessment concepts.

02 Identify potential S3 storage exposure.

03 Assess cloud-storage access-control configurations.

04 Analyze AWS IAM users, policies, and permissions.

05 Recognize potential IAM privilege-escalation risk indicators.

06 Apply least-privilege security principles.

07 Perform Docker image vulnerability assessments.

08 Interpret CVEs and vulnerability severity.

09 Document security findings professionally.

10 Recommend appropriate security countermeasures.

◈ Practical Laboratory Structure

Each laboratory follows a consistent learning framework:

┌─────────────────────────────────────────┐
│             LAB SCENARIO                │
├─────────────────────────────────────────┤
│              OBJECTIVES                 │
├─────────────────────────────────────────┤
│          TOOL / PLATFORM                │
├─────────────────────────────────────────┤
│       ENVIRONMENT & PREREQUISITES       │
├─────────────────────────────────────────┤
│        PRACTICAL PROCEDURE              │
├─────────────────────────────────────────┤
│         EXPECTED RESULTS                │
├─────────────────────────────────────────┤
│          SECURITY INSIGHT               │
├─────────────────────────────────────────┤
│          SECURITY ANALYSIS              │
├─────────────────────────────────────────┤
│          COUNTERMEASURES                │
├─────────────────────────────────────────┤
│           LEARNING OUTCOMES             │
├─────────────────────────────────────────┤
│       REVIEW & TROUBLESHOOTING          │
└─────────────────────────────────────────┘
◈ Authorized Training Environment

IMPORTANT — AUTHORIZED USE ONLY

All security assessment activities in this repository must be performed only against:

Instructor-provided laboratory resources
Learner-owned resources
Organization-approved environments
Systems for which explicit authorization has been granted

Do not use these laboratories to assess third-party infrastructure or production systems without explicit permission.

The container-security laboratory similarly requires vulnerability scanning to remain within authorized images and targets.

◈ Security Philosophy

InternShield promotes responsible cybersecurity education.

Our approach is:

             KNOWLEDGE
                 │
                 ▼
              PRACTICE
                 │
                 ▼
             ANALYSIS
                 │
                 ▼
            VERIFICATION
                 │
                 ▼
            REMEDIATION
                 │
                 ▼
              SECURITY

The objective is not simply to discover vulnerabilities.

The objective is to understand:

Why the vulnerability exists, what risk it creates, how it can be verified safely, and how it can be remediated.

◈ Documentation & Resources

Each laboratory is accompanied by structured learning material covering practical activities, security observations, analysis, findings, countermeasures, troubleshooting, and review.

The repository is intended to serve as a centralized learning resource for the InternShield Cloud Computing & Security practical program.

◈ Series Information

Series:

InternShield Cloud Computing & Security Practical Laboratory Series

Laboratories: 04

Edition: 2026

Version: 1.0

Organization: InternShield

Contributors:

Vidit Shringi
Kriti Purohit
◈ InternShield
<div align="center">
🛡️ INTERN SHIELD
Learn • Practice • Defend • Secure • Innovate

Cloud Computing · Cloud Security · Cybersecurity Education

2026

</div>
Responsible Use

This repository is provided for educational, research, and authorized security-training purposes.

Users are responsible for ensuring that their activities comply with applicable laws, organizational policies, and the authorization scope of the environment being assessed.

InternShield does not endorse unauthorized access, data extraction, privilege escalation, or security testing against systems without permission.

<div align="center">
DISCOVER → ASSESS → ANALYZE → REMEDIATE → SECURE

InternShield — Your Shield in the Digital World.

</div>

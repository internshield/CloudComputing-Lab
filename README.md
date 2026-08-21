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
```
Laboratory Structure
LAB 01 — Performing S3 Bucket Enumeration

Primary Platform: Amazon S3
Primary Tool: Lazys3
Focus: Cloud-storage exposure discovery

Lab 01 introduces learners to S3 bucket enumeration as part of an authorized cloud-security assessment.

The laboratory focuses on understanding S3 bucket discovery, enumeration concepts, identifying potentially exposed storage resources, analyzing the security implications of exposure, and documenting assessment findings.

Key Topics
Amazon S3 fundamentals
S3 bucket discovery
Bucket enumeration
Cloud reconnaissance concepts
Storage exposure
Security assessment
Findings documentation
S3 security best practices
```
Learning Flow
DISCOVER
   ↓
ENUMERATE
   ↓
IDENTIFY EXPOSURE
   ↓
ANALYZE
   ↓
DOCUMENT
```
LAB 02 — S3 Bucket Security Testing / Exploitation

Primary Platform: Amazon S3
Primary Tool: AWS CLI
Focus: Storage permissions and access-control assessment

Lab 02 progresses from S3 discovery into controlled S3 security testing.

Learners examine access controls and security configurations to understand how improperly configured buckets can create data-exposure risks.

Any testing involving access to objects or data should be performed exclusively against authorized laboratory resources and test data.

Key Topics
S3 access controls
Bucket policies
Permissions
Public-access configuration
Storage misconfiguration
Controlled security testing
Data-exposure risks
Security analysis
Remediation concepts
```
Learning Flow
IDENTIFY
   ↓
ASSESS
   ↓
CONTROLLED TEST
   ↓
ANALYZE
   ↓
SECURE
```
LAB 03 — Assessing IAM Privilege-Escalation Risks

Primary Platform: AWS IAM
Focus: IAM permissions, excessive privileges, and privilege-escalation risk

Lab 03 focuses on AWS Identity and Access Management security assessment.

Learners analyze IAM users, managed policies, inline policies, permissions, and potentially dangerous permission configurations to identify privilege-escalation risk indicators.

The laboratory emphasizes risk identification and analysis, rather than automatically exploiting identified permissions.

Key Topics
AWS IAM
IAM users
IAM groups
IAM roles
Managed policies
Inline policies
Permissions
Excessive privileges
Privilege-escalation risk indicators
Least-privilege principles
Security remediation
```
Learning Flow
IDENTIFY
   ↓
ANALYZE
   ↓
ASSESS RISK
   ↓
VERIFY
   ↓
SECURE
```
LAB 04 — Docker Image Vulnerability Assessment

Primary Platform: Docker Container Runtime
Primary Tool: Trivy
Focus: Docker image vulnerability scanning

Lab 04 introduces learners to container-security assessment using Trivy.

The laboratory focuses on scanning Docker images, identifying known vulnerabilities, understanding CVEs and severity levels, comparing vulnerability posture, documenting findings, and developing remediation recommendations.

The source laboratory identifies Docker Container Runtime as the primary platform and Trivy as the primary tool.
```
Key Topics
Docker image fundamentals
Container security
Trivy
Vulnerability scanning
CVE analysis
Severity classification
Vulnerable dependencies
Base-image security
Vulnerability triage
Remediation
Re-scanning
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
```
The laboratory also covers security countermeasures such as using maintained base images, regularly updating images, integrating scanning into CI/CD, prioritizing critical/high-severity findings, and tracking remediation.

Complete Lab Roadmap
Lab	Laboratory	Platform / Tool	Primary Focus
LAB 01	Performing S3 Bucket Enumeration	Amazon S3 / Lazys3	Storage Discovery
LAB 02	S3 Bucket Security Testing / Exploitation	S3 / AWS CLI	Access-Control Assessment
LAB 03	Assessing IAM Privilege-Escalation Risks	AWS IAM	Identity & Permission Security
LAB 04	Docker Image Vulnerability Assessment	Docker / Trivy	Container Security
```
Technology Stack

┌──────────────────────────────────────────────┐
│              CLOUD COMPUTING                 │
├──────────────────────────────────────────────┤
│ AWS                                          │
│ Amazon S3                                    │
│ AWS IAM                                      │
│ AWS CLI                                      │
├──────────────────────────────────────────────┤
│              SECURITY TOOLS                  │
├──────────────────────────────────────────────┤
│ Lazys3                                       │
│ Trivy                                        │
├──────────────────────────────────────────────┤
│              CONTAINER SECURITY              │
├──────────────────────────────────────────────┤
│ Docker                                       │
│ Container Images                             │
│ Vulnerability Databases                      │
├──────────────────────────────────────────────┤
│              LAB ENVIRONMENT                 │
├──────────────────────────────────────────────┤
│ Linux / Kali Linux / Parrot Security         │
└──────────────────────────────────────────────┘

```
Learning Outcomes

After completing the four laboratories, learners should be able to:

Understand fundamental cloud-security assessment concepts.
Understand Amazon S3 storage-security concepts.
Perform S3 enumeration within an authorized environment.
Assess S3 access-control configurations.
Identify potential cloud-storage exposure.
Analyze AWS IAM policies and permissions.
Recognize potentially dangerous IAM permission configurations.
Understand least-privilege principles.
Perform Docker image vulnerability assessment.
Interpret CVEs and vulnerability severity.
Document security findings.
Recommend appropriate security countermeasures.
Practical Learning Framework

Every laboratory follows a consistent practical-learning structure:
```
┌──────────────────────────┐
│       LAB SCENARIO       │
└────────────┬─────────────┘
             ↓
┌──────────────────────────┐
│       OBJECTIVES         │
└────────────┬─────────────┘
             ↓
┌──────────────────────────┐
│ TOOL / PLATFORM OVERVIEW │
└────────────┬─────────────┘
             ↓
┌──────────────────────────┐
│ ENVIRONMENT & PREREQS    │
└────────────┬─────────────┘
             ↓
┌──────────────────────────┐
│   PRACTICAL PROCEDURE    │
└────────────┬─────────────┘
             ↓
┌──────────────────────────┐
│     EXPECTED RESULTS     │
└────────────┬─────────────┘
             ↓
┌──────────────────────────┐
│    SECURITY ANALYSIS     │
└────────────┬─────────────┘
             ↓
┌──────────────────────────┐
│     COUNTERMEASURES      │
└────────────┬─────────────┘
             ↓
┌──────────────────────────┐
│    REVIEW & ASSESSMENT   │
└──────────────────────────┘
```
```
This laboratory series is suitable for:

Cybersecurity students
Cloud-computing students
Cloud-security learners
Ethical-hacking learners
AWS beginners
Security researchers
Aspiring cloud-security professionals
DevSecOps learners
Technical training programs
Series Information
Information	Details
Organization	InternShield
Series	Cloud Computing & Security Practical Laboratory Series
Laboratories	4
Version	1.0
Edition	2026
Primary Cloud Platform	Amazon Web Services
Security Domains	Cloud, IAM, Storage, Containers
Contributors	Vidit Shringi, Kriti Purohit

```
Contributors
Vidit Shringi

Cloud Computing & Cybersecurity — InternShield

Kriti Purohit

Cloud Computing & Security — InternShield

<div align="center">
🛡️ INTERN SHIELD
CLOUD COMPUTING & SECURITY

LAB 01 · LAB 02 · LAB 03 · LAB 04

<br>

DISCOVER · ASSESS · ANALYZE · REMEDIATE · SECURE

<br>

Learn • Practice • Defend • Secure • Innovate

2026 · Version 1.0
</div>
Responsible Use

This repository is provided for educational, research, and authorized security-training purposes.

Users are responsible for ensuring that all activities comply with applicable laws, organizational policies, and the authorization scope of the environment being assessed.

InternShield does not endorse unauthorized access, data extraction, privilege escalation, or security testing against systems without permission.

<div align="center">

InternShield — Your Shield in the Digital World.

</div>

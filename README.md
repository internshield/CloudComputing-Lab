InternShield Cloud Computing & Security — Practical Laboratory Series

A four-laboratory practical learning program covering AWS cloud security, S3 security assessment, IAM security, and Docker container vulnerability assessment.

<div align="center">

DISCOVER · ASSESS · ANALYZE · REMEDIATE · SECURE

Version 1.0 · 2026

</div>
About InternShield

InternShield Cloud Computing & Security Practical Laboratory Series is a structured hands-on laboratory program designed to help learners develop practical knowledge of cloud computing and cloud security.

The complete laboratory structure consists of four practical labs, progressing from cloud-storage discovery to access-control assessment, IAM security analysis, and container vulnerability assessment.

                         INTERN SHIELD
                              │
                CLOUD COMPUTING & SECURITY
                              │
              ┌───────────────┼───────────────┐
              │               │               │
              ▼               ▼               ▼
          CLOUD           IDENTITY        CONTAINER
         STORAGE          SECURITY         SECURITY
              │               │               │
              ▼               ▼               ▼
             S3              IAM            Docker
              │               │               │
              └───────────────┼───────────────┘
                              ▼
                       SECURITY ANALYSIS
                              │
                              ▼
                          REMEDIATION
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
LAB 04 — Docker Image Vulnerability Assessment

Primary Platform: Docker Container Runtime
Primary Tool: Trivy
Focus: Docker image vulnerability scanning

Lab 04 introduces learners to container-security assessment using Trivy.

The laboratory focuses on scanning Docker images, identifying known vulnerabilities, understanding CVEs and severity levels, comparing vulnerability posture, documenting findings, and developing remediation recommendations.

The source laboratory identifies Docker Container Runtime as the primary platform and Trivy as the primary tool.

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

The laboratory also covers security countermeasures such as using maintained base images, regularly updating images, integrating scanning into CI/CD, prioritizing critical/high-severity findings, and tracking remediation.

Complete Lab Roadmap
Lab	Laboratory	Platform / Tool	Primary Focus
LAB 01	Performing S3 Bucket Enumeration	Amazon S3 / Lazys3	Storage Discovery
LAB 02	S3 Bucket Security Testing / Exploitation	S3 / AWS CLI	Access-Control Assessment
LAB 03	Assessing IAM Privilege-Escalation Risks	AWS IAM	Identity & Permission Security
LAB 04	Docker Image Vulnerability Assessment	Docker / Trivy	Container Security
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
Repository Structure
InternShield-Cloud-Computing/
│
├── README.md
│
├── LAB-01-S3-Bucket-Enumeration/
│   ├── README.md
│   ├── Exercise-01.pdf
│   └── assets/
│
├── LAB-02-S3-Bucket-Security-Testing/
│   ├── README.md
│   ├── Exercise-02.pdf
│   └── assets/
│
├── LAB-03-IAM-Privilege-Escalation-Risk/
│   ├── README.md
│   ├── Exercise-03.pdf
│   └── assets/
│
├── LAB-04-Docker-Vulnerability-Assessment/
│   ├── README.md
│   ├── Exercise-04.pdf
│   └── assets/
│
└── LICENSE
Documentation

Each laboratory is designed as a standalone practical learning module while remaining part of the complete four-lab series.

The laboratory documentation can include:

Scenario
Objectives
Tool overview
Lab environment
Prerequisites
Practical procedure
Expected results
Security insights
Security analysis
Findings
Countermeasures
Learning outcomes
Observation tables
Completion checklist
Review questions
Troubleshooting
Best practices

The uploaded reference laboratory follows this type of structured documentation, including practical procedures, security analysis, countermeasures, learning outcomes, review questions, troubleshooting, and best practices.

Authorized Training Environment
⚠️ AUTHORIZED USE ONLY

All security-assessment activities must be performed only against:

Instructor-provided laboratory resources
Learner-owned resources
Organization-approved resources
Systems for which explicit authorization has been granted

Do not perform security testing against third-party or production infrastructure without explicit authorization.

For container-security activities, only scan approved Docker images and authorized targets.

Security Philosophy

InternShield follows a practical security philosophy:

              LEARN
                │
                ▼
             PRACTICE
                │
                ▼
             ANALYZE
                │
                ▼
            VERIFY
                │
                ▼
           REMEDIATE
                │
                ▼
             SECURE

The goal is not simply to identify a vulnerability.

The goal is to understand:

What is exposed?

Why is it exposed?

What security risk does it create?

How can it be verified safely?

How can it be remediated?

Intended Audience

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

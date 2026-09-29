# SecureWhistle
Secure blockchain-based whistleblower platform using Hyperledger Fabric, encrypted off-chain storage, and Zero-Knowledge Proofs for anonymous employee verification.
Sure. Here is a simple version without emojis or bold formatting:

# Secure Blockchain-Based Whistleblower Reporting System

A secure whistleblower reporting platform that allows employees to report organizational misconduct while maintaining privacy, confidentiality, and data integrity.

## Overview

The system uses blockchain, encryption, and zero-knowledge proofs to provide a secure reporting process.

The system follows a hybrid architecture:

* Report data and files are stored in encrypted off-chain storage.
* Report hashes are stored on Hyperledger Fabric.
* Employee eligibility is verified using zero-knowledge proofs.
* Cases can be reviewed by different authorized parties.

## Objectives

* Protect whistleblower identity
* Maintain confidentiality of reports
* Prevent unauthorized modification of records
* Verify employee eligibility without revealing identity
* Provide transparent case tracking

## Technologies Used

* Frontend: React.js / Blazor
* Backend: Node.js, Express.js
* Blockchain: Hyperledger Fabric
* Smart Contract: Chaincode
* Database: PostgreSQL
* Encryption: AES-256-GCM
* Zero-Knowledge Proofs: Circom, SnarkJS
* Deployment: Docker

## Main Features

1. Anonymous whistleblower reporting
2. Blockchain-based report integrity
3. Encrypted off-chain data storage
4. Zero-knowledge employee verification
5. Permissioned blockchain network
6. Multi-party case oversight

## System Workflow

Employee submits a report

↓

Employee eligibility is verified using a zero-knowledge proof

↓

Report data is encrypted

↓

Encrypted report is stored off-chain

↓

Report hash is stored on Hyperledger Fabric

↓

Authorized parties investigate and manage the case

## Stakeholders

* Corporate Compliance: Investigates reported cases
* Employee Union / Staff Council: Provides employee oversight
* External Legal Auditor / Ombudsman: Provides independent oversight

## Security

The system uses multiple security mechanisms:

* Zero-knowledge proofs for identity privacy
* AES-256-GCM for data encryption
* Blockchain hashes for data integrity
* Permissioned blockchain for controlled access
* Blockchain records for auditability

## Project Status

Final-Year Engineering Project - In Development

The project focuses on system architecture, security design, workflow design, and prototype implementation.

## Team

Team size: 4

Developed as a Final-Year BE Computer Engineering project.

# Awesome-Knowledge-Sharing-Platform

Top KYC (Know Your Customer) Tools Ecosystem

Curated List of SaaS Products & Open-Source GitHub Projects
Focused on Identity Verification, Document OCR, Liveness Detection & AML Compliance
Last updated: September 2026

This repository tracks notable SaaS platforms and open-source projects for Know Your Customer (KYC) verification. These tools help businesses verify user identities through government ID validation, biometric face matching, liveness detection, and anti-money laundering (AML) screening.

Examples include Persona, Trulioo, Sumsub, Veriff, Jumio, Onfido, AU10TIX, IDnow, Shufti Pro, and ComplyCube (the category leaders).

Open-source emphasis: This section is heavily expanded with every major active project for self-hosting, custom biometric pipelines, and transparent identity verification — ideal for fintech startups, privacy-conscious platforms, and developers who want full control over sensitive user data without per-verification fees.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

Table of Contents

SaaS/Hosted Platforms

Open-Source GitHub Projects

How to Contribute

Disclaimer

SaaS/Hosted Platforms

Persona
Identity verification platform with configurable workflows for KYC, KYB, and AML compliance. Known for strong developer experience and global coverage.

Trulioo
Global identity verification platform covering 195+ countries. Provides real-time identity checks, business verification, and AML watchlist screening.

Sumsub
All-in-one verification platform for KYC, KYB, AML, and transaction monitoring. Popular with crypto exchanges and fintechs.

Veriff
AI-powered identity verification with strong liveness detection and document authentication. Serves fintech, crypto, and marketplace clients.

Jumio
End-to-end identity verification and AML platform. Combines ID document verification, biometrics, and risk signals for financial institutions.

Onfido
Identity verification with document and biometric checks. Now part of Entrust, offering KYC for regulated industries.

AU10TIX
Identity verification and document authentication specialist with deep expertise in fraud detection and forensic document analysis.

IDnow
European identity verification platform offering AI-based and video-based KYC. Strong presence in DACH region and regulated markets.

Shufti Pro
Global identity verification with KYC, KYB, and AML services. Supports 10,000+ document types and 150+ languages.

ComplyCube
Identity verification and AML compliance platform with document checks, biometrics, and global watchlist screening.

Stripe Identity
Identity verification integrated with the Stripe ecosystem. Verifies government-issued IDs and matches selfies to documents.

Plaid Identity
Identity verification leveraging Plaid's financial data network. Focused on bank account ownership and income verification.

Open-Source GitHub Projects

Ballerine
Open-source infrastructure for identity and risk management. Provides KYC/KYB UI flows, case management dashboard, rule engine, and integrations with multiple verification vendors. Y Combinator-backed with $5M seed funding. License: Open source.

biometrical-verify
Self-hosted biometric identity verification for digital contracts. Features passive/active liveness detection, deepfake heuristics (FFT), face matching (DeepFace + ArcFace), and Ed25519 signed receipts. Runs on a $5 VPS with zero per-verification fees. License: MIT.

AI-KYC-System
Modern KYC verification system using AI for face matching and document verification. Built with FastAPI, React, OpenCV, face-recognition, and PyTesseract OCR. License: Open source.

AegisKYC
AI-powered KYC automation platform with adaptive risk scoring, multi-layer biometrics, OCR, deepfake detection, and cryptographic credentialing. Reduces verification time from 48–72 hours to 8–12 minutes. License: Open source.

Gatebil KYC Service
Self-hosted identity verification built for East Africa. Go orchestration layer + Python inference layer. Uses DSNT keypoint detection for ID cards, VGGFace2 for face embeddings, and blink/orientation liveness challenges. License: Open source.

zkKYC
Zero-knowledge KYC framework enabling privacy-preserving compliance. Generates proofs that verify identity attributes (age, nationality, document validity) without revealing underlying personal data. Deployed on Midnight blockchain. License: Apache 2.0.

VeriMeZK
Zero-knowledge identity proof toolkit processing passport data client-side in the browser. Combines Tesseract.js OCR, face-api.js biometrics, and ZK proofs for DeFi compliance. No backend required. License: MIT.

FaceVault
Fully open-source identity verification solution with government ID capture, document OCR, selfie liveness, face matching, and anti-spoofing. Offers a hosted verification page with trust scoring (0–100). License: Open source.

Idswyft
Open-source, self-hostable identity verification API. Deterministic pipeline covering OCR, liveness detection, face matching, and AML screening. Integrates in 5 API calls. Docker Compose deployment. License: Open source.

FaydaPass
Modern KYC onboarding web application integrating with Ethiopia's Fayda eSignet OIDC system. Built with Next.js, TypeScript, TailwindCSS, and Supabase. License: Open source.

end-to-end-kyc-data-pipeline
Automated identity verification combining FastAPI and React. Features ID extraction with PaddleOCR and biometric face matching via DeepFace. License: Open source.

Cryptonomica Ethereum-IdentityVerification
Identity verification and KYC for Ethereum blockchain applications. License: Open source.

verifid/graph-vl
Self-hosted identity verification layer with GraphQL API. Provides a developer-friendly interface for building verification workflows. License: Open source.

Additional Strong Open-Source Options

OCR & Document Processing: PaddleOCR, Tesseract, and EasyOCR for extracting data from government-issued IDs.

Face Detection & Matching: DeepFace, face-recognition, InsightFace, and VGGFace2 implementations for biometric comparison.

Liveness Detection: MediaPipe, MiniFASNet, and FaceOnLive SDKs for anti-spoofing and deepfake detection.

Identity Document Validation: IDCard-Recognition-SDK and MiniAiLive ID-Document-Recognition for passport, driver's license, and national ID parsing.

Blockchain Identity: zkKYC and VeriMeZK for privacy-preserving, decentralized identity verification.

Frameworks for building custom systems: Combine Ballerine for workflow orchestration, DeepFace for biometrics, PaddleOCR for document extraction, MediaPipe for liveness, and PostgreSQL + Redis for persistence.

How to Contribute

Fork the repo.

Add/edit entries in README.md (follow existing format).

Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.

Submit PR with a short explanation.

Star the repo if you find it useful!

Disclaimer

This is a community-curated list — not exhaustive and not an endorsement.

KYC tools handle highly sensitive personal data (PII and biometrics); ensure compliance with GDPR, CCPA, BSA/AML, and relevant regional regulations.

Self-hosted open-source solutions require proper security hardening, encryption at rest, and regular audits.

Made for fintech founders, compliance officers, identity engineers, and privacy advocates.
Let's make identity verification more open, transparent, and privacy-preserving.

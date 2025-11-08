# 🌾 AgroChainX – Sustainable Agriculture on BlockDAG

## 🚀 What is AgroChainX?
AgroChainX is a blockchain-powered agriculture platform that helps farmers prove where their crops come from, access fair markets, and get rewarded using digital tokens (AGX). It combines AI + blockchain to make farming smarter and more transparent.

## 🎯 Problem
Farmers in Africa face low trust in produce quality, middlemen exploitation, and no transparent market data. Buyers can’t trace where food truly comes from.

## 💡 Solution
AgroChainX uses **BlockDAG** and **AI** to:
- Give each farm product a unique digital identity (traceable on-chain)
- Allow direct AGX payments between buyers and farmers
- Verify farm data using AI (AgroBot)
- Enable digital reputation for farmers (proof of origin + yield)

## 🔗 Tech Stack
- **Frontend:** Flutter (mobile-first)
- **Backend:** Flask (Python)
- **Blockchain:** BlockDAG (AGX token on ERC-20)
- **AI:** AgroBot assistant for real-time farm insights

## 🧱 Architecture (Simple View)
Flutter ↔ Flask API ↔ BlockDAG Smart Contracts ↔ Farmers’ Wallets

## Folder Structure
AgroChainX/
│
├── README.md
├── LICENSE
├── .gitignore
│
├── frontend/                 ← Flutter app (UI)
│   ├── lib/
│   ├── assets/
│   ├── pubspec.yaml
│   └── README.md
│
├── backend/                  ← Flask server (handles wallet, AI, blockchain)
│   ├── app.py
│   ├── routes/
│   │   ├── wallet.py
│   │   ├── agrobot.py
│   │   ├── traceability.py
│   │   └── user.py
│   ├── requirements.txt
│   └── README.md
│
├── blockchain/               ← AGX token + BlockDAG contract
│   ├── AGXToken.sol
│   ├── deployment_guide.txt
│   └── test_AGXToken.js
│
├── docs/                     ← for concept note, pitch deck, design plans
│   ├── Concept_Note.pdf
│   ├── Pitch_Deck.pdf
│   └── Architecture_Diagram.png
│
└── prototypes/               ← early demo or screenshots
    ├── demo_screens.mp4
    ├── splash_screen.png
    └── wallet_screen.png


## 📸 Demo & Prototype
- Screenshots 
- Demo video: coming soon
- Live UI mock: coming soon

## 📅 Buildathon Phase
This repo covers **Phase 1: Ideation & Scaffold** — architecture, UI design, and concept validation.

## 👥 Team
Team Lead: Halifa Rabiu Ibrahim (Khalifa Elgezy)
Ass Lead: Nufaisah Abdullahi Muhamma
Frontend: Murtala Khalid
Backend: Salim Ahmad
Designer: Hassan Adamu
Designer: Rabia Ibrahim

## 🪙 Token Plan
AGX (AgroChain Token) – Utility token for farm verification, trade, and AI access.

## 🧾 License
MIT License – Open for collaboration

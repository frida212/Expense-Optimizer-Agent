# Gig Economy AI Financial Operating System

AI-powered platform for gig workers to optimize spending, track income, and access micro-lending.

## Overview

This project implements an autonomous AI agent system for gig economy workers using Google Cloud and multi-agent AI orchestration.

## Features

- **Income Intelligence Agent**: Real-time gig platform income tracking
- **Expense Optimizer Agent**: Identifies wasteful spending and negotiates discounts
- **Dynamic Lending Agent**: AI-powered micro-lending with alternative credit scoring
- **Tax & Compliance Agent**: Automated tax tracking and filing

## Repository Structure

.
├── agents/                 # AI agent implementations
│   ├── expense_optimizer/  # Expense optimization agent
│   ├── income_intelligence/
│   ├── lending/
│   └── tax_compliance/
├── services/               # Core services
│   ├── google_cloud/       # Google Cloud integrations
│   ├── database/
│   └── payment/
├── tests/                  # Unit and integration tests
├── config/                 # Configuration files
└── docs/                   # Documentation

## Quick Start

See [SETUP.md](./docs/SETUP.md) for installation and configuration.

## Google Cloud Products Used

- **Vertex AI**: Multi-agent orchestration
- **BigQuery**: Analytics and real-time insights
- **Document AI**: Receipt and invoice processing
- **Cloud Tasks**: Scheduled agent workflows
- **Pub/Sub**: Real-time data streaming
- **Firestore**: Real-time user data storage

## License

MIT

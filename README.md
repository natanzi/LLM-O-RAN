# O-RAN LLM Integration System

## Project Overview

This project implements an innovative integration of Large Language Models (LLMs) into Open Radio Access Network (O-RAN) architectures. It leverages a specialized LLM engine and mediation layer to provide seamless functionality across various O-RAN components, including the RAN Intelligent Controller (RIC) via agent xApp and E2 interfaces.

## Key Features

- LLM-powered dynamic spectrum allocation
- Real-time network data analysis
- Adaptive resource management
- Integration with O-RAN components (RIC, xApp)
- Continuous learning mechanism

## System Architecture

The system consists of several key components:

1. LLM Engine: Utilizes Hugging Face models for network data analysis
2. Mediation Layer: Orchestrates interactions between components
3. Data Management: Handles data preprocessing and InfluxDB interactions
4. API Management: Manages communications with xApp and RIC
5. Training Server: Implements continuous learning mechanisms
6. Additional Services: Content serving, caching optimization, safety management, and system monitoring

## Prerequisites

- Python 3.8+
- InfluxDB
- Access to OAI 5G stack - O-RAN components (RIC, xApp)

## Installation

1. Clone the repository:
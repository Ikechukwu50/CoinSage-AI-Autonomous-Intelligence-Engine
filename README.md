# CoinSage-AI-Autonomous-Intelligence-Engine

Quick Deployment Guide

Prerequisites:
An n8n account (Cloud or Self-hosted).
OpenAI API Key (for GPT-4o synthesis).
Twilio Account (for WhatsApp delivery via Sandbox).

Installation:
Create a new workflow in n8n.
Import the provided workflow.json file.
Configure your Credentials for OpenAI and Twilio.

Twilio Sandbox Activation:
Since the WhatsApp Sandbox expires every 72 hours, ensure your device is connected.
Send the required join <keyword> message to your Twilio number to re-authorize the session.

Environment Variables:
Set the Global Timezone to Africa/Lagos for accurate 08:00 WAT execution.
Adjust the pumpThreshold in the JavaScript node (Default: 10%) to calibrate alert sensitivity.

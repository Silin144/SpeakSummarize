# Privacy Policy for SpeakSummarize

**Last Updated:** November 30, 2025

## Introduction

SpeakSummarize ("we," "our," or "us") is committed to protecting your privacy. This Privacy Policy explains how we collect, use, and safeguard your information when you use our iOS application featuring Echo, your AI memory companion.

## Information We Collect

### Audio Recordings
- **What:** Voice recordings you create within the app
- **Purpose:** To transcribe and summarize your voice notes
- **Storage:** Stored locally on your device; temporarily processed by OpenAI's API
- **Processing:** Sent to OpenAI's API for transcription and AI summarization

### Transcriptions and Summaries
- **What:** Text generated from your audio recordings, including structured summaries, speaker identification, and key insights
- **Purpose:** To provide searchable, organized voice notes with AI-powered analysis
- **Storage:** Stored locally on your device and as vector embeddings in Pinecone (encrypted, anonymized)

### Device Identifier
- **What:** A unique anonymous ID generated on your device
- **Purpose:** To separate your data from other users in shared AI services (Pinecone, Mem0)
- **Storage:** Stored locally on your device
- **Note:** This ID is randomly generated and cannot be linked to your personal identity

### Usage Data
- **What:** Recording count, subscription status, usage statistics (for free tier limits)
- **Purpose:** To enforce free tier limits and provide subscription features
- **Storage:** Stored locally on your device only

### Chat History with Echo
- **What:** Your conversations with Echo (our AI companion)
- **Purpose:** To maintain conversation context and provide personalized assistance
- **Storage:** Stored locally on your device; conversation insights stored in Mem0 (anonymized)
- **Note:** You can create multiple independent chat conversations

### Vector Embeddings
- **What:** Mathematical representations of your transcriptions for search functionality
- **Purpose:** To enable AI-powered search and chat features
- **Storage:** Stored in Pinecone vector database, associated only with your anonymous device ID
- **Note:** These embeddings cannot reconstruct your original audio or text

## How We Use Your Information

1. **Audio Processing:** Your recordings are sent to OpenAI's API for transcription, speaker diarization, and AI summarization
2. **Feature Functionality:** Data is used to provide app features including:
   - Transcription and structured summarization
   - Speaker detection and identification
   - Semantic search across your recordings
   - AI chat with Echo using Retrieval Augmented Generation (RAG)
   - Multi-chat conversations with independent contexts
3. **Search & Memory:** Vector embeddings enable intelligent search and Echo's ability to recall relevant information from your recordings
4. **No Training:** Your data is never used to train AI models

## Third-Party Services

We use the following third-party services to provide app functionality. All data is transmitted securely via our CloudFlare Worker proxy, which keeps API keys secure and encrypted.

### OpenAI
- **Purpose:** Audio transcription (Whisper API), AI summarization, and chat functionality (GPT-4o-mini)
- **Data Sent:** Audio files, transcriptions, and chat messages
- **Privacy Policy:** [https://openai.com/policies/privacy-policy](https://openai.com/policies/privacy-policy)
- **Data Retention:** OpenAI retains API requests for 30 days for abuse monitoring, then permanently deletes them
- **Training:** OpenAI does not use your data to train models (API terms)

### Pinecone (Vector Database)
- **Purpose:** Stores vector embeddings of your transcriptions for semantic search
- **Data Sent:** Mathematical embeddings (not original text or audio) with your anonymous device ID
- **Privacy Policy:** [https://www.pinecone.io/privacy/](https://www.pinecone.io/privacy/)
- **Data Isolation:** Your data is stored in a user-specific namespace, isolated from other users
- **Note:** Vector embeddings cannot be reverse-engineered to reconstruct original content

### Mem0 (AI Memory)
- **Purpose:** Stores Echo's long-term memory of conversation insights to provide personalized assistance
- **Data Sent:** Key facts and patterns from conversations, linked to your anonymous device ID
- **Privacy Policy:** [https://mem0.ai/privacy](https://mem0.ai/privacy)
- **Data Isolation:** Memories are user-specific and cannot be accessed by other users
- **Control:** You can delete all memories via Settings > Clear All Data

### CloudFlare Workers
- **Purpose:** Securely proxies API requests to third-party services without exposing API keys
- **Data Sent:** API requests are passed through (not stored)
- **Privacy Policy:** [https://www.cloudflare.com/privacypolicy/](https://www.cloudflare.com/privacypolicy/)
- **Note:** CloudFlare does not log or store your data

### Apple StoreKit
- **Purpose:** In-app purchases and subscription management
- **Data Handled:** Payment information (handled entirely by Apple)
- **Privacy Policy:** Apple's privacy policy applies to all payment data

## Data Storage and Security

- **Local Storage:** Audio files, full transcriptions, and complete chat histories are stored locally on your device
- **Cloud Storage (Anonymized):** 
  - Vector embeddings stored in Pinecone (cannot reconstruct original content)
  - Echo's conversation insights stored in Mem0 (key facts only, not full conversations)
  - All cloud data is linked only to your anonymous device ID, not your personal identity
- **Encryption:** All data transmission uses HTTPS/TLS encryption
- **Secure Proxy:** API requests route through our CloudFlare Worker, keeping API keys secure
- **No Account Required:** No email, phone number, or personal information required to use the app
- **Device-Specific:** Data is isolated per device; we cannot access your data across devices

## Your Rights

You have the right to:
- **Access Your Data:** View all recordings, transcriptions, and chat history within the app
- **Delete Specific Items:** Delete individual recordings, chat conversations, or summaries
- **Delete All Data:** Remove everything through Settings > Clear All Data, including:
  - Local recordings and transcriptions
  - All chat conversations with Echo
  - Vector embeddings in Pinecone (device-specific)
  - Mem0 memories (device-specific)
- **Export Data:** Export summaries as PDF with full structured data
- **Stop Collection:** Revoke microphone access anytime in iOS Settings
- **Unsubscribe:** Cancel premium subscription through iOS Settings > Subscriptions

## Data Retention

### On Your Device
- Data is retained until you delete it manually
- Deleting the app removes all local data from your device
- Chat conversations persist until you clear them

### Third-Party Services
- **OpenAI:** Retains API requests for 30 days (abuse monitoring), then permanently deletes
- **Pinecone:** Retains vector embeddings until you use "Clear All Data" or delete the app
- **Mem0:** Retains memories until you use "Clear All Data" or delete the app
- **Deletion:** When you delete data via "Clear All Data," we delete your data from Pinecone and Mem0 within 24 hours

### Subscription Data
- Apple manages subscription information
- We do not have access to your payment details
- Subscription records are retained by Apple per their policies

## International Data Transfer

Our third-party services (OpenAI, Pinecone, Mem0, CloudFlare) may process data in various countries, including the United States. By using the app, you consent to the transfer of your data to these jurisdictions. All services comply with applicable data protection regulations.

## California Privacy Rights (CCPA)

If you are a California resident, you have additional rights:
- **Right to Know:** Request details about data we collect (contact us)
- **Right to Delete:** Request deletion of your personal data
- **Right to Opt-Out:** We do not sell your personal information
- **Non-Discrimination:** We will not discriminate for exercising your rights

## European Privacy Rights (GDPR)

If you are in the EEA/UK, you have additional rights under GDPR:
- **Legal Basis:** We process data based on your consent and legitimate interest
- **Data Portability:** Request a copy of your data in a portable format (export as PDF)
- **Rectification:** Correct inaccurate data within the app
- **Objection:** Object to data processing (delete data or uninstall app)

## Children's Privacy

SpeakSummarize is not intended for users under 13 years of age. We do not knowingly collect information from children. If you believe a child has provided information, contact us immediately to delete it.

## Changes to This Policy

We may update this Privacy Policy from time to time. We will notify users of material changes through:
- App Store update notes
- In-app notification
- Updated "Last Updated" date at the top of this document

Continued use of the app after changes constitutes acceptance of the updated policy.

## Contact Us

If you have questions about this Privacy Policy or want to exercise your privacy rights:

- **Email:** silin.gupta14@gmail.com
- **GitHub:** [https://github.com/Silin144/SpeakSummarize](https://github.com/Silin144/SpeakSummarize)
- **Response Time:** We aim to respond within 48 hours

For data deletion requests, please include your device model and iOS version to help us assist you quickly.

## Consent

By using SpeakSummarize, you acknowledge that you have read, understood, and agree to this Privacy Policy.


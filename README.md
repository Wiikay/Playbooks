# 🤖 Dialogflow CX Playbooks

<div align="center">
  
![License](https://img.shields.io/badge/license-MIT-blue)
![Platform](https://img.shields.io/badge/platform-Google%20Cloud-4285F4)
![Status](https://img.shields.io/badge/status-active-success)

*A collection of reusable Dialogflow CX agent configurations and playbooks for building powerful conversational AI experiences*

</div>

## 📋 Overview

This repository contains a collection of Dialogflow CX agent configurations and playbooks that can be imported into your Google Cloud Platform projects. These pre-configured agents provide templates for common conversational AI use cases, allowing for rapid development and deployment of virtual assistants.

## 🔍 Repository Contents

### Agent Playbooks

| Playbook | Description |
|:-------:|:------------|
| 📊 **Open API Data Store Agent** | A virtual agent that can retrieve product information from a Google Data Store and provide answers to user queries |

## 🌟 Features

### Open API Data Store Agent

The Open API Data Store Agent demonstrates how to:

- 🗣️ Greet users with a natural, conversational introduction
- 🔍 Process user queries about products in a data store
- 📱 Answer specific questions about product features and capabilities
- 🔄 Integrate with external APIs using webhooks
- 📝 Record user preferences and information

### Conversation Flows

The agent includes several conversation flows:

- **Default Welcome Flow**: Greets users and introduces the agent's capabilities
- **Product Query Flow**: Handles questions about specific products
- **User Information Collection**: Optionally collects user preferences and contact information

## 🛠️ Technical Details

### Agent Components

- **Entity Types**: Recognizes product names, features, and query types
- **Intents**: Trained to understand various product inquiries
- **Webhooks**: Configured to connect with data stores and external APIs
- **Playbooks**: Pre-built conversation paths for common scenarios

### Integrations

- **Google Data Store**: Connects to product catalog information
- **Record Favorite Flavor API**: Example webhook for collecting user preferences

## ⚙️ Setup & Deployment

### Prerequisites

- Google Cloud Platform account with Dialogflow CX enabled
- Access to webhook endpoints (configured at specific URLs in the blob file)

### Import Instructions

1. Log in to your Google Cloud Console
2. Navigate to Dialogflow CX
3. Create a new agent or select an existing one
4. Go to Agent Settings > Export and Import
5. Select "Import" and upload the `.blob` file from this repository
6. Configure webhook URLs to point to your own endpoints

## 📊 Example Queries

The agent can handle queries such as:

- "What's the battery performance like on the Pixel 7 Pro?"
- "Can I wear the Pixel Watch while swimming or showering?"
- "Can Nest Hub act like a digital photo frame using Google Photos?"

## 🔮 Future Enhancements

- 🌐 Additional language support
- 🔄 More complex conversation flows
- 🧩 Integration with additional APIs and services
- 📱 Expanded product catalog and knowledge base

## 📚 Resources

- [Dialogflow CX Documentation](https://cloud.google.com/dialogflow/cx/docs)
- [Google Cloud Platform](https://cloud.google.com/)
- [Conversational AI Best Practices](https://cloud.google.com/dialogflow/cx/docs/concept/best-practices)

---

<div align="center">

*This repository is maintained for demonstration and learning purposes. The contained playbooks can be customized and extended for your specific use cases.*

[Report an Issue](https://github.com/Wiikay/Playbooks/issues) • [Request a Feature](https://github.com/Wiikay/Playbooks/issues)

</div>
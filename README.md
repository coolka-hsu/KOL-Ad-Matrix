🚀 OmniAd-Core

The open-source infrastructure for AI-automated ad generation, cross-platform deployment, and seamless KOL (Key Opinion Leader) management.

OmniAd-Core is designed to lower the technical barrier for digital marketing. It provides a standardized set of modules to automate the creation of advertising assets using AI, deploy them across multiple ad networks simultaneously, and manage KOL registration processes without the administrative headache.

✨ Key Features

🤖 AI-Powered Asset Generation: Automatically generate ad creatives (copy and imagery) based on basic product data feeds.

🚀 Multi-Channel Deployment: A unified API wrapper to push campaigns directly to major ad platforms (Meta, Google, etc.) without manual asset downloading/uploading.

👥 KOL Sync & Management: A streamlined registration and tracking module to reduce administrative friction between brands and influencers.

🛡️ Privacy-First Architecture: Built-in safeguards for handling sensitive API keys and KOL Personal Identifiable Information (PII).

📦 Installation (Beta)

Currently, OmniAd-Core is in active development and transitioning to a fully public open-source model.

# Clone the repository
git clone [https://github.com/YOUR_USERNAME/OmniAd-Core.git](https://github.com/YOUR_USERNAME/OmniAd-Core.git)

# Navigate to the directory
cd OmniAd-Core

# Install dependencies
npm install


🏗️ Architecture Overview

The system is broken down into three main independent packages:

@omniad/ai-generator: Interfaces with LLMs and image generation APIs.

@omniad/deploy-engine: Manages OAuth tokens and cross-platform API requests.

@omniad/kol-portal: Handles the backend logic for influencer registration and tracking.

(Detailed documentation for each module is currently being migrated to our Wiki.)

🤝 Contributing

We are actively transitioning our private codebase to this public repository. We welcome contributions from the community, especially in the areas of:

Adding new Ad Platform integrations.

Enhancing the AI prompt templates for ad generation.

Improving security and CI/CD pipelines (Security auditing tools like Codex Security are being integrated).

Please read our CONTRIBUTING.md for details on our code of conduct, and the process for submitting pull requests to us.

📄 License

This project is licensed under the MIT License - see the LICENSE file for details.

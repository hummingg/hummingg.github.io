# Privacy Policy for WebRAG

**Last Updated:** January 2026

## Overview

WebRAG is a browser extension that helps users build and query a local knowledge base from web pages. We are committed to protecting your privacy.

## Data Collection

**WebRAG does NOT collect, store, or transmit any user data.**

### What We DON'T Do

❌ We do NOT collect any personal information
❌ We do NOT track your browsing history
❌ We do NOT use analytics or telemetry
❌ We do NOT store any data on remote servers
❌ We do NOT share any information with third parties
❌ We do NOT use cookies or tracking technologies

### How WebRAG Works

✅ **100% Local Processing**
- All data is stored locally in your browser's IndexedDB
- Webpage content you choose to save stays on your device
- AI processing is done by your local Ollama instance
- No internet connection required (except for Ollama download)

✅ **User Control**
- You choose which pages to save
- All data can be cleared through browser settings
- The extension only acts when you trigger it
- No automatic data collection of any kind

### Data Storage

All data created by WebRAG is stored locally on your device:

1. **Knowledge Base Content** - Stored in browser IndexedDB
2. **User Settings** - Stored in browser local storage (Ollama URL, model preferences)
3. **No Cloud Sync** - Nothing is uploaded to any server

### Permissions Explained

WebRAG requests the following permissions, used ONLY for local functionality:

- **activeTab** - To extract content from pages you choose to save
- **storage** - To store your knowledge base locally in the browser
- **scripting** - To read page content when you click "Add Page"
- **contextMenus** - To add right-click menu option for convenience
- **sidePanel** - To display the extension in side panel
- **host_permissions (<all_urls>)** - To save content from any site you choose

### Third-Party Services

WebRAG connects ONLY to:
- **Your local Ollama instance** (default: http://localhost:11434)
- This is YOUR own software running on YOUR computer
- No data is sent to Anthropic, OpenAI, or any other third party

### Changes to This Policy

If we ever change this privacy policy, we will update this document and notify users through the Chrome Web Store update notes.

### Contact

If you have questions about this privacy policy, please contact:
xuhuiming6991@gmail.com

---

## Summary

**WebRAG collects ZERO user data. Everything stays on your device.**

Your privacy is not just important to us—it's fundamental to how WebRAG is designed.

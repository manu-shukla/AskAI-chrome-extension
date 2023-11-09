# AskAI Chrome Extension
This is the production build of the Chrome extension which could be directly installed in the browser.
Tested Browser:
- Microsoft Edge: Version 119

# Demo
[Demo Video](https://github.com/manu-shukla/AskAI-chrome-extension/assets/18571875/c131f125-e712-4c6d-b67a-72264b5f4bdc)

![Demo Screenshot](https://github.com/manu-shukla/AskAI-chrome-extension/assets/18571875/08b8c6e9-c79f-47eb-bf49-d02fbc16c23b)


## Installation

1. Clone the repository to your local machine.

2. Enable developer options in your Chrome browser.

3. Load the extension:

   - Open Chrome and go to chrome://extensions/.
   - Enable "Developer mode" at the top right.
   - Click on "Load unpacked" and select the folder where you cloned the extension.

The AskAI Chrome Extension is now installed.

## Backend API Setup

To enable AI capabilities, connect to the backend API. Follow these steps:

1. Visit the AskAI backend repository: [AskAI-backend](https://github.com/manu-shukla/AskAI-backend).

2. Follow the instructions in the backend repository to set up and run the API server.

3. The extension uses the OpenAssistant/oasst-sft-4-pythia-12b-epoch-3.5 Huggingface API for the AI model in the backend.

Now your AskAI Chrome Extension is ready to respond to your queries using the connected backend API. Enjoy!

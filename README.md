# 🚀 Quick Setup

![N8N Upwork AI Agent Preview](https://i.pinimg.com/736x/c3/c6/28/c3c6280180abc8392ca78acf77ef1e2f.jpg)

Want to get up and running fast? Here are the simple steps to get started:

## Required Files
1. `LIVE_BUILD_UPWORK_AI_AGENT.json` - Main agent workflow
2. `Generate_Application_Copy.json` - Application copy generator
3. `Generate_Google_Doc_Proposal.json` - Google Doc proposal generator
4. `Generate_Mermaid_Code.json` - Mermaid diagram generator
5. Create a copy of the "Google Docs Upwork Proposal Template"

## Prerequisites
1. **OpenAI API Key**
   - Sign up at OpenAI and get your API key
   - Add it to N8N credentials as "OpenAI API"

2. **Google Cloud Platform Setup**
   - Create a project in Google Cloud Console
   - Enable Google Drive and Google Docs APIs
   - Create OAuth 2.0 credentials (Client ID and Client Secret)
   - Add these credentials to N8N for both Google Drive and Google Docs

## Setup Steps

1. **Import Workflows**
   - Open N8N canvas
   - Click top right -> "Import From File"
   - Import each workflow file
   - Save all workflows

2. **Connect Tools**
   - In the main agent workflow, click each Tool node
   - Select the corresponding subflow for each tool
   - Ensure all connections are properly mapped

3. **Personalize**
   - Update the "About Me" variables with your accomplishments
   - Customize any templates as needed

4. **Run the System**
   - Your AI agent is now ready to use!

## Note
The Mermaid diagram code generated can be visualized by:
1. Going to https://whimsical.com/
2. Pasting the generated code
3. Taking a screenshot of the diagram
4. (Optional) Attaching the diagram to your Google Doc proposal

That's it! You're ready to start generating professional Upwork proposals. 🎉

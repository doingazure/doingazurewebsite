---
title: "SWA Lab INSTALLATIONS"
date: 2023-05-06T09:51:21-04:00
draft: false
---
Lab for Boston Azure Bootcamp 13-May-2023. Here are some of the software packages you will need to complete the lab.

Some tools can be installed as needed.

## VS Code

https://code.visualstudio.com/download

:information_source: Tip: if you are new to VS Code, some people like to configure it to autosave files. https://code.visualstudio.com/docs/editor/codebasics#_save-auto-save

## VS Code GitHub Copilot Extension

Consider enabling the FREE TRIAL for GitHub Copilot: https://docs.github.com/en/copilot/configuring-github-copilot/configuring-github-copilot-in-your-environment

Once enabled, you'll want to install the GitHub Copilot extension.

## VS Code SWA Extension

You can aso find this from within VS Code by searching the Extensions marketplace, but here's the direct link:

https://marketplace.visualstudio.com/items?itemName=GitHub.copilot

## SWA CLI

This can be handy. If you are going to install it, you will also need Node.js (npm) installed. See next listing for Node.js.

:information_source: Tip: If you have the CLI installed, local debugging is simplified (otherwise will be complex). This increases in importance if you are using Functions withing you SWA. https://github.com/microsoft/vscode-azurestaticwebapps/wiki/Guide:-Debugging-a-Static-Web-App-with-VS-Code

https://learn.microsoft.com/en-us/azure/static-web-apps/local-development

Install command:

```npm install -g @azure/static-web-apps-cli```

Run:

```swa start src --api-location api```

## Node.js (or Node for short) (Needed to install the SWA CLI above and later for local debugging)

You probably want the "LTS" version. LTS is the version with long-term support.

https://nodejs.org/en/download

If you have a version of Node too new to be compatible with SWA CLI, try this:

```sudo npm install -g node@18.16.0 --force```

18.16.0 is the active LTS version as of this writing (2023).

### Reference if you have Node/SWA CLI version compatibility issues

https://learn.microsoft.com/en-us/azure/azure-functions/functions-reference-node?pivots=nodejs-model-v4&tabs=javascript%2Cwindows-setting-the-node-version#node-version

## VS Code Azure Funcions Extension

You can aso find this from within VS Code by searching the Extensions marketplace, but here's the direct link:
https://marketplace.visualstudio.com/items?itemName=ms-azuretools.vscode-azurefunctions

:information_source: Tip: SWA has built-in support for Azure Functions. Here's some info on how to use it: https://learn.microsoft.com/en-us/azure/static-web-apps/add-api?tabs=vanilla-javascript


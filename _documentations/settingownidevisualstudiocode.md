---
layout: docs
title: Visual Studio Code
description: Setting up your own IDE - Visual Studio Code
keywords: eclipse, application, edit, ide, vsc, visual studio code, intellij, text editor, editor
duration: 1 minute
permalink: settingownidevisualstudiocode
type: document
order: 130
parent: settingownide
---

## Visual Studio Code

1. Download and install [Visual Studio Code](https://code.visualstudio.com/download).
2. Install the following extensions from the Visual Studio Marketplace by using the Extensions page:
   * Java Extension Pack
3. Select ``File->Add Folder to Workspace...``.
4. Select the root of the project directory, for example, for a project named ``myjavamicroservices1``, select the directory ``microclimate-workspace/myjavamicroservices1`` and then click ``Add``.
5. You can now edit the application, for example,  ``src/main/java/application/rest/v1/HealthEndpoint.java``. When you have finished editing, save your changes. Microclimate auto-detects your changes and rebuilds and redeploys the updated app. Refresh your browser to see the results.

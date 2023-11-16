# [Pieces for Developers](https://pieces.app) | JupyterLab Extension

In 2022, our team embarked on a mission to transform the way you code with your personal micro-repo.

With the debut release of our Flagship Desktop App, we laid the foundation, and now our JupyterLab extension is here to revolutionize your coding workflow further by incorporating key capabilities and our users' favorite features directly into their JupyterLab environment.

![Pieces For Developers Banner](https://storage.googleapis.com/pieces_multimedia/PROMOTIONAL/PIECES_FOR_DEVELOPERS/JUPYTER/MACOS/ANY_FEATURE/16X9/PIECES_FOR_DEVELOPERS-JUPYTER-ANY_FEATURE-MACOS-16X9-10_16_2023.png)

Elevate your coding & problem-solving in JupyterLab with the Pieces Copilot. Interact with the Copilot from any code workspace right within your JupyterLab interface. Ask questions about code or content within a file, gain insight on keywords or patterns within code snippets, ask the Copilot to generate a sample using an SDK you’re researching, and even use it to help you understand PRs.

As you move through your workflow, our JupyterLab extension enables you to effortlessly capture, manage, share, and discover code snippets & other developer materials, such as code screenshots, with a simple click.

The Pieces for Developers JupyterLab extension is designed to become your go-to development partner, transforming your workflow with efficiency and organization.

## Table of Contents

- [Recent Updates](#recent-updates)
- [Getting Started](#getting-started)
  - [Requirements](#requirements)
  - [Install Instructions](#install-instructions)
- [Features](#features)
  - [Meet Your New Copilot](#meet-your-new-copilot)
  - [Save Valuable Code](#save-valuable-code)
  - [Find and Reuse Code Snippets](#find-and-reuse-code-snippets)
  - [Share Code from JupyterLab](#share-code-from-jupyterlab)
  - [Keyboard Shortcuts](#keyboard-shortcuts)
- [Explore the Pieces Ecosystem](#explore-the-pieces-ecosystem)
- [Need Help?](#need-help)
- [Stay Connected](#stay-connected)

## Recent Updates

### [v1.6.1 - Improved Pieces Copilot Experience](https://code.pieces.app/updates/improved-pieces-copilot-experiences)
_Oct. 3, 2023_

- Introduction of Quick Actions for easy selection of LLM runtime and file context in Copilot conversations.
- Theme Matching feature to align Copilot's appearance with the environment's theme.
- Styling updates including new icons for an enhanced user experience.

### [v1.4.0 - Filter your Snippet List](https://code.pieces.app/updates/filter-snippet-list-obsidian-jupyterlab)
_Sept. 8, 2023_

- Ability to filter snippet lists based on tags, titles, language, and more.
- Access to filtering options via a filter button and a user-friendly interface for setting up filters.
- Improved search functionality with the search bar now properly accepting user input.

### [v1.1.1 - Introducing Pieces Copilot](https://code.pieces.app/updates/pieces-qgpt-rag-copilot-live-data-synchronization-and-more-pieces-for-developers-jupyterlab-plugin-111)
_Jul. 21, 2023_

- Launch of qGPT RAG Copilot, a chatbot contextualized by the code within a user's notebook(s), facilitating plain text queries.
- Incorporation of live data synchronization to ensure real-time update of modifications made in your Pieces repository via other integrations.
- New Context Menu Enrich Button to allow automatic generation of comments explaining the selected code, aimed at enhancing JupyterLab workflow.

[View all updates](https://code.pieces.app/updates)

## Getting Started

### Requirements

- JupyterLab >= 4.0.0
- **You must have [Pieces OS](https://docs.pieces.app/installation-getting-started/what-am-i-installing) installed**.

Pieces OS facilitates the local operation of Pieces products on your machine and coordinates connections to Pieces extensions. **The extension will not function as intended without Pieces OS active on your machine.**

*_Pieces OS installation comes with the Pieces for Developers Desktop App where your snippets can also be viewed and managed._

### Install Instructions

Execute `pip install jupyter-pieces` in your terminal.

or

Search for `jupyter-pieces` within the JupyterLab Extensions Manager and install.

## Features

### [Meet Your New Copilot](https://docs.pieces.app/features/pieces-copilot)
Your personal copilot, powered by local or cloud-based LLMs (i.e. Llama 2, GPT-3.5, GPT-4, and PaLM 2) for maximum security and privacy, that’s contextualized by your workflow to help solve coding problems, onboard into new projects faster, and connect you with the right people.

![Meet Your New Copilot](https://storage.googleapis.com/pieces_multimedia/PROMOTIONAL/PIECES_FOR_DEVELOPERS/JUPYTER/MACOS/GLOBAL_COPILOT/16X9/PIECES_FOR_DEVELOPERS-JUPYTER-GLOBAL_COPILOT-MACOS-16X9-9_26_2023.GIF)

### [Save Valuable Code](https://docs.pieces.app/product-highlights-and-benefits/saving-useful-developer-materials)

Templates, commands, useful snippets, notes... quickly save aspects of your code for future reference or reuse.

#### How to save

* Highlight code, right-click, and select "Save to Pieces."

![Save with Right Click](https://storage.googleapis.com/pieces_multimedia/PROMOTIONAL/PIECES_FOR_DEVELOPERS/JUPYTER/MACOS/RIGHT-CLICK_SAVE/16X9/PIECES_FOR_DEVELOPERS-JUPYTER-RIGHT-CLICK_SAVE-MACOS-16X9-9_22_2023.GIF)

* Click the Pieces Save button within any code block.

![Save with Pieces Button](https://storage.googleapis.com/pieces_multimedia/PROMOTIONAL/PIECES_FOR_DEVELOPERS/JUPYTER/MACOS/SAVE_TO_PIECES/16X9/PIECES_FOR_DEVELOPERS-JUPYTER-SAVE_TO_PIECES-MACOS-16X9-9_21_2023.GIF)

### [Find and Reuse Code Snippets](https://docs.pieces.app/features/search-modes)

Fast, robust search of your code snippets right within JupyterLab.

![Manage your Snippets](https://storage.googleapis.com/pieces_multimedia/PROMOTIONAL/PIECES_FOR_DEVELOPERS/JUPYTER/MACOS/SEARCH_AND_INSERT/16X9/PIECES_FOR_DEVELOPERS-JUPYTER-SEARCH_AND_INSERT-16X9-MACOS-6_22_2023.gif)

### [Share Code from JupyterLab](https://docs.pieces.app/features/one-click-snippet-sharing)

Share snippets with a simple right-click, complete with relevant context - tags, descriptions, origin, and more!

![Share your Snippets](https://storage.googleapis.com/pieces_multimedia/PROMOTIONAL/PIECES_FOR_DEVELOPERS/JUPYTER/MACOS/SNIPPET_BUTTON_SHARE/16X9/PIECES_FOR_DEVELOPERS-JUPYTER-SNIPPET_BUTTON_SHARE-16X9-MACOS-6_22_2023.gif)

### [Keyboard Shortcuts](https://docs.pieces.app/features/keyboard-shortcuts)

To use a Pieces command, simply highlight code in your editor or hover a snippet in your Pieces List.

| Command                              | macOS            | Windows          |
|--------------------------------------|------------------|------------------|
| Save Selection to Pieces             | Cmd+Shift+S      | Ctrl+Shift+S     |
| Share Selection via Pieces           | Cmd+Shift+K      | Ctrl+Shift+K     |
| Save Cell to Pieces                  | Cmd+Shift+Enter  | Ctrl+Shift+Enter |
| Share Cell via Pieces                | Cmd+Shift+X      | Ctrl+Shift+X     |
| Discover Snippets                    | Cmd+Shift+A      | Ctrl+Shift+A     |
| Refresh Snippets                     | Cmd+Shift+E      | Ctrl+Shift+E     |
| Quick Search                         | Cmd+Shift+M      | Ctrl+Shift+M     |
| Toggle View                          | Cmd+Shift+Y      | Ctrl+Shift+Y     |

## Explore the Pieces Ecosystem

Maximize productivity with our Flagship Desktop App and other products designed to streamline your coding workflow across different platforms.

![Pieces Product Suite](https://storage.googleapis.com/pieces_multimedia/ILLUSTRATIONS/PIECES_FOR_DEVELOPERS/ANY_INTEGRATION/ANY_THEME/PLUGINS/1X1/PIECES_FOR_DEVELOPERS-ANY_INTEGRATION-PLUGINS-ANY_THEME-1X1-10_16_2023.PNG)

For detailed descriptions and features of each product, visit our [docs for JupyterLab](https://docs.pieces.app/extensions-plugins/jupyterlab).

## Need Help?

Encountered a hurdle? We've got you covered. Reach out for support:

- **[Support Form](https://getpieces.typeform.com/to/mCjBSIjF)**
- **[Join our Discord Community](https://discord.gg/getpieces)**

## Stay Connected

Stay in the loop! Follow us for the latest updates, tips, and insights:

- **[Twitter](https://twitter.com/getpieces)**
- **[YouTube](https://youtube.com/@getpieces)**
- **[Facebook](https://facebook.com/getpieces)**
- **[LinkedIn](https://linkedin.com/company/getpieces)**
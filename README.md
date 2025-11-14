# rizzoma-export-notion-import



# Rizzoma static archive exporter and Rizzoma to Notion importer

A production-ready Python notebook to create a complete, self-contained archive of your Rizzoma topics and import them with high fidelity into Notion.

This tool was created in response to Rizzoma's shutdown announcement, to provide the community with a robust way to preserve years of valuable work.

## What's Inside This Repository?

*   **`Rizzoma_export_Notion_import.ipynb`**: The main Google Colab notebook that handles both archiving from Rizzoma and importing into Notion.
*   **`notion-dark-theme.css`**: An optional CSS theme to enhance Notion's appearance, making it cleaner and more similar to Rizzoma's focused interface.

## How to Use

### 1. The Migration Notebook (`.ipynb`)

The notebook contains a complete, step-by-step user manual. To get started, simply open it in Google Colab:

**➡️ [Open Notebook in Google Colab](https://colab.research.google.com/github/brio-plus/rizzoma-export-notion-import/blob/main/Rizzoma_export_Notion_import.ipynb)**

The manual inside the notebook will guide you through:
*   Configuring the necessary API keys.
*   Running the **Acquisition** workflow to create `.zip` archives of your topics.
*   Running the **Notion Import** workflow to create pages from your archives.
*   Resuming an import if it gets interrupted.

### 2. The Optional Dark Theme (`.css`)

This CSS style provides a cleaner dark mode for Notion, with enhanced visibility for nested toggle blocks, inspired by Rizzoma's interface.

1.  **Install the Stylus browser extension:**
    *   [Stylus for Chrome](https://chrome.google.com/webstore/detail/stylus/clngdbkpkpeebahjckkjfobafhncgmne)
    *   [Stylus for Firefox](https://addons.mozilla.org/en-US/firefox/addon/styl-us/)
2.  Click the Stylus icon in your browser, select "Manage", and then "Write new style".
3.  Copy the entire content of the `notion-dark-theme.css` file and paste it into the editor.
4.  Under "Apply to", make sure it is set to URLs starting with `https://www.notion.so`.
5.  Save, and enjoy a cleaner Notion experience.

You can also download the optional font set as a default : [Monaspace](https://monaspace.githubnext.com/)

## The Future: Your Feedback Matters

This tool solves an immediate problem, but it also serves a greater purpose. Rizzoma had a unique vision for collaborative knowledge management. As we transition to other tools, we have a unique opportunity to reflect on what made it special and what the next generation of collaborative tools should look like.

This repository is a place to gather those ideas.

**If you have thoughts on:**
*   What you loved most about Rizzoma.
*   What you feel is missing in tools like Notion for team collaboration.
*   What features a modern, enterprise-grade knowledge management tool should have.

**Please share them by opening an [Issue](https://github.com/brio-plus/rizzoma-export-notion-import/issues).** Your feedback will be invaluable in shaping what comes next.
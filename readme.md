
# TicketPad

![Company Icon](images/iY_full.svg)


## User's Guide



<table align="center" style="border:0px solid #eee;width:100%">
  <tr style="border:0px solid #eee; width:100%">
   <td style="border:0px solid #eee; width:100%">

   </td>
    <td style="border:0px solid #eee; width:100%">

### Table of Contents

- [Getting Started](#getting-started)
  - [Setup](#setup)
  - [Configuration](#configuration)
- [Advanced Features](#advanced-features)
- [FAQ](#faq)


    </td>
   

   <td style="border:0px solid #eee; width:100%">

   </td>

   
  </tr>
</table>


### Table of Contents

1. [Introduction](#introduction)
2. [Getting Started with TicketPad](#getting-started-with-ticketpad)
3. [Context Menu](#context-menu)
    * [Context Search](#context-search)
    * [Context Notes](#context-notes)
4. [SidePanel](#sidepanel)
    * [Search Tab](#search-tab)
    * [Notes Tab](#notes-tab)
5. [Options](#options)
6. [Troubleshooting](#troubleshooting)
7. [FAQs](#faqs)



### Introduction
The following guide provides an overview of the features and functionality of the TicketPad Chrome Extension. This extension uses a context menu and sidePanel to provide quick access to essential Jira features.

This guide will help you understand how to use the Search and Notes tabs in the sidePanel, as well as how to navigate the context menu. By the end of this guide, you should be able to effectively utilize TicketPad to streamline your workflow and improve your productivity.



### Getting Started with TicketPad

### Context Menu
In the Chrome browser (on Windows, macOS, and Linux), you can open the Context Menu by doing a right-click on the browser page.

![Context Menu](images/ContextMenu.png)


**Note**: The Search and Notes menu items will be activated only when the SidePanel is open

#### Context Search
Selecting the Search from the Context menu when:
- From a normal internet page, the Search tab in the SidePanel will be opened.
- From a html page where a ticket is displayed:
    https://issues.apache.org/jira/browse/HELIX-871
The Sidepanel Search Tap will be displayed and automatically the following will happen:
    - `Project:` This field will be populated with the Project ID, in this case HELIX, it HELIX will also be saved in the pulldown menu if it is not already present.
    - Both `Reporter:` and `Assignee:` pulldown menus will be updated with names present in the ticket.
    - The `Look Up`, url will also be selected to match the ticket's side url.



#### Context Notes
edsdsdsdsd
Context Notes


### SidePanel

#### Search Tab
(Insert detailed information about the Search tab, including examples and screenshots if necessary)

#### Notes Tab
(Insert detailed information about the Notes tab, including examples and screenshots if necessary)

g


### Options
To access the Options dialog for TicketPad:

1. Go to the TicketPad icon in the Chrome Extensions panel, top right in Chrome Browser.
2. Right-click (or Ctrl+Click) on the icon to open the context menu.
3. Select "Options" from the drop-down menu.

![Options Dialog](images/options.png)

This will open a popup panel with the following options:

#### Note Managemen
* **Max Notes**: Set the maximum number of notes that can be created.
* **Max Note Size**: Set the maximum size each note can be.
* **Backup Notes**: Create a backup of all your notes, allowing you to restore them later.

#### Export and Restore

* **Export Notes**: Download a CSV file containing all your notes.
* **HTML Report**: Export all your notes as an HTML table.
* **Restore Notes**: Restore all notes previously backed up.

By adjusting these options, you can customize the behavior of TicketPad to suit your needs.

#### Troubleshooting
(Insert troubleshooting tips and solutions here)

#### FAQs
(Insert frequently asked questions and their answers here)


> [!NOTE]
> Useful information that users should know, even when skimming content.

> [!TIP]
> Helpful advice for doing things better or more easily.

> [!IMPORTANT]
> Key information users need to know to achieve their goal.

> [!WARNING]
> Urgent info that needs immediate user attention to avoid problems.

> [!CAUTION]
> Advises about risks or negative outcomes of certain actions.
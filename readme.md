![Company Icon](images/iY_full.svg)

# TicketPad - User's Guide

<table align="center" style="border:0px solid #eee;width:100%">
  <tr style="border:0px solid #eee; width:100%">
   <td style="border:0px solid #eee;width:20%;">
&nbsp;
   </td>
    <td style="border:0px solid #eee; width:60%">

### Table of Contents

1. [Introduction](#introduction)
2. [Getting Started with TicketPad](#getting-started-with-ticketpad)
3. [Context Menu](#context-menu)
    * [Behaviour: Context Search](#behavior-when-selecting-search-from-the-context-menu)
    * [Behaviour: Context Notes](#behavior-when-selecting-notes-from-the-context-menu)
4. [Side Panel](#side-panel)
    * [Search Tab](#search-tab)
    * [Notes Tab](#notes-tab)
5. [Options](#options)
6. [Troubleshooting](#troubleshooting)
7. [FAQs](#faqs)

    </td>
   <td style="border:0px solid #eee; width:20%">
&nbsp;
   </td>
  </tr>
</table>


# Introduction
The following guide provides an overview of the features and functionality of the TicketPad Chrome Extension. This extension uses a context menu and Side Panel to provide quick access to essential Jira features.

This guide will help you understand how to use the Search and Notes tabs in the Side Panel, as well as how to navigate the context menu. By the end of this guide, you should be able to effectively utilize TicketPad to streamline your workflow and improve your productivity.



# Getting Started with TicketPad

## Context Menu
In the Chrome browser (on Windows, macOS, and Linux), you can open the Context Menu by doing a right-click on the browser page.

![Context Menu](images/ContextMenu.png)


**Note**: The Search and Notes menu items will be activated only when the Side Panel is open



### Behavior When Selecting "Search" from the Context Menu

- **From a normal web page**:

    The Search tab in the Side Panel will open.

- **From an HTML page displaying a Jira ticket** (e.g., https://[URL]/jira/browse/HELIX-871):

    The Search tab in the Side Panel will open, and the following fields will be automatically populated/updated based on the ticket details:

    - `Project:`: This field will be filled with the ticket's Project ID (in this example, HELIX). The value will also be saved in the dropdown menu if it is not already present.

    - `Look Up` **URL**: This will be automatically selected to match the ticket's site URL

    - `Reporter:`, `Assignee:`, and other relevant fields:
    The corresponding dropdown menus (including Reporter, Assignee, and any other applicable fields) will be automatically updated with the details from the current ticket. New values will be added to the dropdown menus if they are not already present.

![alt text](images/status_dropdown.png)

        From the example we see the `Project:` field has been updated with the project name _HELIX_ and the `Status:` dropdown will be be updated with the status type, in this case, _Open_.


> [!NOTE]
> The dropdown menus will gradually populate with recent or frequently used items as you continue searching.


### Behavior When Selecting "Notes" from the Context Menu

- **From a normal web page**:
    The Notes tab in the Side Panel will open

- **From an HTML page displaying a Jira ticket** (e.g., https://[URL]/jira/browse/HELIX-871):
    The Notes tab in the Side Panel will be selected and if there is already a Note for this particular ticket, this note will be opened. If there is not already a Note for this particular ticket then a new note will be created with some ticket details:

![Ticket Note](images/ticket_note.png)

> [!TIP]
> If you select text in a Ticket that contains a ticket key then the Note will be for the selected ticket.


## Side Panel
Chrome Side Panel for extensions is a feature introduced in Chrome version 114 that allows browser extensions to display their own custom user interface in the browser's built-in side panel.

### Search Tab
![Search Tab](images/search_numbers.png)

1. Tabs to switch between the Ticket Search aid and the Notes.
2. the Project code will be pre-filled if you are coming here from the Context menu Search and on a valid ticket.
3. The Status field has been filled, this can be done either form the dropdown list or typed.
4. Type, this is where you can select from the dropdown list or written. If it is left blank it will not be used then querying tickets.
5. The Reporter and Assignee names can be added by typing or selected from the dropdown list. The dropdown lists are continuesly being updated when you click on the Context Menu Search or Notes.
6. This is where you can add text to search in the tickets.
7. Where the text can be search is specified here, in `Summary`, `Text`, `Description` or `Comments`. The boolean can also be switch between `AND` and `OR`. The condition can also be modified betwwen `~` and `!~`, equal or not equal respectfully.
8. Here Labels can be selected or typed and added to the search.
9. As this Browser Extension supports more than one Ticket Server at one time, the URLs are also set so you can search on more than one server.
10. `Look Up`, clicking this button generates the search pattern and the search is executed in the browser's main window.

### Notes Tab
![Note Tab](images/notes_numbers.png)

1. Search Field, this field allows you to search all your notes. 
2. Case Sensitive checkbox.
3. Searched words will be highlighted.
4. Click to open ticket in browser.
5. Click ticket number will open popup with ticket status.
6. Click to open or close Note.
7. Editor toolbar for Note.
8. Change Note's title bar colour.
9. Delete Note.


## Options
To access the Options dialog for TicketPad:

1. Go to the TicketPad icon in the Chrome Extensions panel, top right in Chrome Browser.
2. Right-click (or Ctrl+Click) on the icon to open the context menu.
3. Select "Options" from the drop-down menu.

![Options Dialog](images/options.png)

This will open a popup panel with the following options:

### Note Managemen
* **Max Notes**: Set the maximum number of notes that can be created.
* **Max Note Size**: Set the maximum size each note can be.
* **Backup Notes**: Create a backup of all your notes, allowing you to restore them later.

### Export and Restore

* **Export Notes**: Download a CSV file containing all your notes.
* **HTML Report**: Export all your notes as an HTML table.
* **Restore Notes**: Restore all notes previously backed up.

By adjusting these options, you can customize the behavior of TicketPad to suit your needs.

> [!CAUTION]
> Restoring Notes will overwrite existing notes. Make sure you Backup Notes first.

## Troubleshooting
(Insert troubleshooting tips and solutions here)

## FAQs
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
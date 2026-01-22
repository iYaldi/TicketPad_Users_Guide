# Privacy Policy

**Last updated: January 18, 2026**

This browser extension TicketPad is designed with a very simple privacy philosophy:

**We collect, store, process, share or transmit absolutely no personal data from you.**

## Key Facts in Plain Language

| What we do with your data                          | Status     | Details                                                                 |
|----------------------------------------------------|------------|-------------------------------------------------------------------------|
| Collect any personal information                   | ✗ No       | No names, emails, IDs, IP addresses, browsing history, etc.            |
| Store any data on our servers                      | ✗ No       | We operate zero servers that receive data from the Extension            |
| Send any data to third parties                     | ✗ No       | No analytics, no tracking pixels, no advertising networks              |
| Use any telemetry / usage statistics               | ✗ No       | Not even anonymous usage counts                                         |
| Read or store browsing history                     | ✗ No       | The Extension does not use the `history` permission                     |
| Access list of visited sites / tabs                | ✗ No       | Unless explicitly required for the core functionality (see below)      |
| Use any external tracking/analytics services       | ✗ No       | No Google Analytics, Plausible, Mixpanel, PostHog, Fathom, etc.        |
| Sell, rent or monetize user data                   | ✗ No       | We have no user data to sell                                            |

## What data is actually handled?

### Scenario A – Completely offline extension
Nothing leaves your computer. Period.  
→ No privacy policy would even be needed, but we still provide this document for transparency.

### Scenario B – Extension needs to read current page content or specific tab information  
(Example: content script that reads/modifies the current webpage)

In this case the Extension may **temporarily**:

- see the content of the web page you are currently visiting  
- see the URL of the tab that is currently active  

**This information:**

- never leaves your device  
- is not logged  
- is not stored persistently  
- is not sent anywhere  
- is discarded as soon as the current execution context ends (usually milliseconds to seconds)

## Permissions explanation (if any are requested)

Common permissions you might see and their actual usage in this extension:

- `"sidePanel"`          → only used to allow for the creation of the side panel
- `"contextMenus"`       → only used to add menu items to the Context Menu
- `"storage"`            → only for local user settings / preferences (saved only on your device)
- `"https://*/*"`        → required to work with every type of Jira website

None of these permissions are used to track you, profile you, or send information off-device.

## Changes to this policy

Because we promise to never collect any personal data, this policy is very unlikely to ever require substantial changes.  
Should the extension ever add any data-collection feature in the future (which is **not** planned), we will:

1. release a major version update
2. clearly notify users in advance
3. publish a new privacy policy
4. ask for your explicit consent where legally required

## Contact

If you have any questions about this privacy policy (or just want to say hi because you appreciate zero-data extensions), feel free to contact us at:

**contact@iyaldi.com**  
(or through the contact method listed in the Chrome Web Store page)

Thank you for choosing a privacy-respecting extension! 🛡️


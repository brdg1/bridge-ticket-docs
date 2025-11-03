# Terms of Service – Bridge Ticket Bot

**Last Updated:** November 4, 2025  

---

## 1. Introduction
Welcome to **Bridge Ticket Bot** (“the Bot”, “we”, “us”, “our”).  
Bridge Ticket Bot is a Discord-based automated ticket management system developed to support structured communication and support operations within the **Bridge Community Network**.

By using Bridge Ticket Bot (the “Service”), you agree to these Terms of Service (“Terms”). Please read them carefully before using the Service.  
If you do not agree to these Terms, you may not use the Bot.

---

## 2. Authorized Use and Availability
Bridge Ticket Bot is **exclusively authorized for use within the Bridge Community Network**, which includes:
- The **main community hub server**, and  
- Up to **three officially designated sub-category servers** within the same network.

The Bot is **not authorized for use on any other Discord servers**.  
Any attempt to self-host, redistribute, or deploy the Bot outside the Bridge Community Network is strictly prohibited.

---

## 3. Service Description
Bridge Ticket Bot provides a structured, automated ticket management system designed for internal community operations.  
The Bot performs the following core functions:

- Sends configurable informational messages and interactive ticket panels.  
- Allows users to create tickets via these panels.  
- Sends a **mandatory disclaimer** prior to ticket creation.  
- Once the disclaimer is accepted:
  - A **ticket template message** containing predefined questions or structure is automatically posted to guide the user.  
  - A temporary **ticket role** is generated, labeled with the ticket number and category.  
- If the disclaimer is **not accepted**:
  - The ticket, associated role, and temporary messages are deleted.  
  - A minimal **log emblem** (record) is still created, containing the user ID, staff ID, and timestamp — **without including any channel or server identifiers.**

When a ticket is closed, either manually via `/close-ticket` or automatically after 30 minutes of inactivity:
- The ticket and role are deleted on the originating server.  
- An **HTML transcript** of the ticket conversation is created and stored on an external, secured log server.  
- The external log server maintains a **ticket counter**, tracking total tickets and per-category statistics.

---

## 4. Data Collection and Processing
Bridge Ticket Bot collects and processes only the minimal data required to perform its ticket management functions.  
This data may include:

- **Discord User IDs** (ticket creator and assigned staff member)  
- **Timestamps** (ticket creation and closure times)  
- **Ticket messages** (content within the ticket)  
- **HTML ticket transcripts** (generated upon ticket closure)

Bridge Ticket Bot **does not collect or display**:
- Server IDs  
- Channel IDs  
- IP addresses or other personal identifiers

All collected data is used exclusively for moderation, transparency, and support purposes.  
No information is shared with third parties, sold, or used for analytics or advertising.

---

## 5. Data Storage and Retention
All ticket data and transcripts are stored on a **dedicated external Discord server** operated by the Bridge Ticket Bot development team within the Bridge Community Network.  

Data is retained only for as long as necessary for moderation or administrative transparency.  
Once a ticket is closed or deleted:
- The ticket and role are removed from the active server.  
- The transcript and emblem record remain only on the external log server for record-keeping.

The development team is currently implementing a **controlled and accelerated data deletion system** to ensure that data can be securely and efficiently removed upon request or in accordance with automated retention policies.

---

## 6. User Consent and Disclaimer
Before a ticket is created, the user must review and accept a **mandatory disclaimer**.  
By accepting the disclaimer, the user explicitly consents to:

1. The temporary processing and storage of ticket data (messages, timestamps, user/staff IDs) on an external Discord server.  
2. The generation of an HTML transcript upon ticket closure, visible to authorized staff members on the external server.  
3. The use of anonymized, minimal identifiers for moderation transparency.

If the user **declines** the disclaimer:
- The ticket and associated role are deleted immediately.  
- A minimal log emblem is created, containing only the user ID, staff ID, and timestamp.  
- No message content, server ID, or channel ID is stored.

---

## 7. Ticket Templates
Upon acceptance of the disclaimer, Bridge Ticket Bot automatically sends a **ticket template message** within the new ticket channel.  
This message provides standard questions and guidelines to help users communicate effectively with staff.  
Templates are configurable by authorized administrators within the Bridge Community Network.

---

## 8. User Responsibilities
Users and administrators agree to:
- Use Bridge Ticket Bot **only** within authorized Bridge Community Network servers.  
- Comply with Discord’s [Terms of Service](https://discord.com/terms) and [Community Guidelines](https://discord.com/guidelines).  
- Not misuse, exploit, or attempt to bypass the disclaimer, data consent, or log mechanisms.  
- Not modify, copy, or reverse-engineer the Bot or its systems.

Violation of these rules may result in access revocation, blacklisting, or permanent banning from the Service.

---

## 9. Limitation of Liability
Bridge Ticket Bot and its developers provide the Service **“as is”** and **“as available.”**  
We make no guarantees regarding uptime, performance, or uninterrupted access.  

We are not liable for:
- Data loss caused by Discord API outages, errors, or misconfigurations.  
- Unauthorized access resulting from server permission issues.  
- Any indirect, incidental, or consequential damages resulting from use or misuse of the Bot.

Users acknowledge that they use Bridge Ticket Bot at their own risk.

---

## 10. Data Deletion Requests and Contact
Users may request deletion of their stored transcripts or associated data by contacting the development team.  
Requests will be reviewed and processed as quickly as possible, provided that removal does not conflict with moderation or record-keeping requirements.

**Contact Information:**  
- **Discord Support Server:** [Insert Invite Link]  
- **Developer Contact:** [Your Discord Tag or Team Name]  
- **Email (optional):** [Your Email Address]

---

## 11. Updates to These Terms
We may modify or update these Terms as needed to reflect technical, legal, or procedural changes.  
Updates will be posted with a new “Last Updated” date.  
Continued use of Bridge Ticket Bot after updates constitutes acceptance of the revised Terms.

---

**By using Bridge Ticket Bot, you confirm that you have read, understood, and agreed to these Terms of Service.**
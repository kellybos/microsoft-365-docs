---
title: "End-user spam notifications in Microsoft 365"
f1.keywords:
- NOCSH
ms.author: chrisda
author: chrisda
manager: dansimp
ms.date:
audience: Admin
ms.topic: article
ms.service: O365-seccomp
localization_priority: Normal
search.appverid:
- MOE150
- MED150
- MET150
ms.assetid: 56de4ed5-b0aa-4195-9f46-033d7cc086bc
ms.collection:
- M365-security-compliance
ms.custom:
- seo-marvel-apr2020
description: "Admins can learn about end-user spam notifications for quarantined messages in Exchange Online Protection (EOP)."
---

# Use user spam notifications to release and report quarantined messages

In Microsoft 365 organizations with mailboxes in Exchange Online or standalone Exchange Online Protection (EOP) organizations without Exchange Online mailboxes, quarantine holds potentially dangerous or unwanted messages. For more information, see [Quarantined messages in EOP](quarantine-email-messages.md).

By default, end-user spam notifications are disabled in anti-spam policies. When an admin [enables end-user spam notifications](configure-your-spam-filter-policies.md#configure-end-user-spam-notifications), recipients (including shared mailboxes) will receive periodic notifications about their messages that were quarantined as spam, bulk email, or (as of April 2020) phishing.

> [!NOTE]
> Messages that were quarantined as high confidence phishing, malware, or by mail flow rules (also known as transport rules) are only available to admins. For more information, see [Manage quarantined messages and files as an admin in EOP](manage-quarantined-messages-and-files.md).

An end-user spam notification contains the following information for each quarantined message:

- **Sender**: The send name and email address of the quarantined message.

- **Subject**: The subject line text of the quarantined message.

- **Date**: The date and time (in UTC) that the message was quarantined.

- **Block Sender**: Click this link to add the sender to your Blocked Senders list. For more information as a user about blocked senders, see [Block a mail sender in Outlook](https://support.office.com/article/b29fd867-cac9-40d8-aed1-659e06a706e4). Admins can learn more about managing blocked senders for users at [Configure junk email settings on Exchange Online mailboxes] (https://docs.microsoft.com/en-us/microsoft-365/security/office-365-security/configure-junk-email-settings-on-exo-mailboxes?view=o365-worldwide). 

- **Release**: For spam (not phish) messages, you can release the message here without going to Quarantine the Security & Compliance Center.

- **Review**: Click this link to go to Quarantine in the Security & Compliance Center, where you can release, delete or report your quarantined messages. For more information, see [Find and release quarantined messages as a user in EOP](find-and-release-quarantined-messages-as-a-user.md).

![Example end-user spam notification](../../media/end-user-spam-notification.png)

---
title: "Threat Trackers - New and Noteworthy"
ms.author: deniseb
author: denisebmsft
manager: laurawi
ms.date: 6/15/2018
ms.audience: ITPro
ms.topic: overview
ms.service: o365-administration
localization_priority: Normal
search.appverid:
- MET150
- MOE150
ms.assetid: a097f5ca-eac0-44a4-bbce-365f35b79ed1
description: "Learn about Threat Trackers, including new Noteworthy Trackers, to help your organization stay on top of security concerns."
---

# Threat Trackers - New and Noteworthy

[Office 365 Threat Intelligence](office-365-ti.md) enables your organization's security team to discover and take action against cybersecurity threats. **Beginning in late March 2018 and over the next several weeks, Office 365 Threat Intelligence will include new Threat Tracker features**, including Noteworthy trackers. Read this article to get an overview of these new features and next steps. 
  
## What are Threat Trackers?

Threat Trackers are informative widgets and views that provide you with intelligence on different cybersecurity issues that might impact your company. For example, you can view information about trending malware campaigns using Threat Trackers.
  
![Example of Threat Tracker showing malware campaigns](media/a883b5ac-8e2b-469a-90e0-f8ad39bb63b7.png)
  
Most tracker pages include trending numbers that are updated periodically, widgets to help you understand which issues are the biggest or have grown the most, and a quick link in the **Actions** column that takes you to Explorer, where you can view more detailed information. 
  
![Example of campaign information in Explorer](media/e426f220-fdcb-4dd9-99a2-db97dbcf71d5.png)
  
Trackers are just a few of the many great features you get with [Office 365 Threat Intelligence](office-365-ti.md). When available, your new Threat Trackers will include [Noteworthy trackers](threat-trackers.md#notey), [Trending trackers](threat-trackers.md#trending), [Tracked queries](threat-trackers.md#trackedq), and [Saved queries](threat-trackers.md#savedq).
  
To view and use your Threat Trackers when they are available for your organization, go to the Security &amp; Compliance Center ([https://protection.office.com](https://protection.office.com)) and choose **Threat management** \> **Threat tracker**.
  
> [!NOTE]
> To use Threat Trackers, you must be an Office 365 global administrator, security administrator, or security reader. See [Permissions in the Office 365 Security &amp; Compliance Center](permissions-in-the-security-and-compliance-center.md). 
  
### Noteworthy trackers

Noteworthy trackers are where you'll find big and smaller threats and risks that we think you should know about. Noteworthy trackers help you find whether these issues exist in your Office 365 environment, plus link to articles (like this one) that give you more details on what is happening, and how they'll impact your organization's use of Office 365. Whether it's a big new threat (e.g. Wannacry, Petya) or an existing threat that might create some new challenges (like our other inaugural Noteworthy item - Nemucod), this is where you'll find important new items you and your security team should review and examine periodically.
  
Typically Noteworthy trackers will be posted for just a couple of weeks when we identify new threats and think you might need the extra visibility that this feature provides. Once the biggest risk for a threat has passed, we'll remove that Noteworthy item. This way, we can keep the list fresh and up to date with other relevant new items.
  
### Trending trackers

Trending trackers (formerly called Campaigns) highlight new threats that haven't been seen in your organization's email in the past week.
  
![Example of trending malware campaigns widget](media/d2ccc1a0-2a1d-4e36-99b5-6766c207772f.png)
  
Trending trackers give you an idea of new threats you should review to ensure your broader corporate environment is prepared against attacks.
  
### Tracked queries

Tracked queries leverage your saved queries to periodically assess Office 365 activity in your organization. This gives you event trending, with more to come in the coming months. Tracked queries run automatically, giving you up-to-date information without having to remember to re-run your queries.
  
![Example of tracked queries with one selected](media/0c556174-06eb-4ae5-b32a-5ff76b9e4f13.png)
  
### Saved queries

Saved queries are also found in the Trackers section. You can use Saved queries to store the common Explorer searches that you want to get back to quicker and repeatedly, without having to re-create the search every time.
  
![Example of saved queries with one selected](media/188cf3ff-58f1-41ea-81aa-76158d8f40c3.png)
  
You can always save a Noteworthy tracker query or any of your own Explorer queries using the **Save query** button at the top of the Explorer page. Anything saved there will show up in the **Saved queries** list on the Tracker page. 
  
## Trackers and Explorer

Whether you're reviewing email, content, or Office activities (coming soon), Explorer and Trackers work together to help you investigate and track security risks and threats. All together, Trackers provide you with information to protect your Office 365 users by highlighting new, notable, and frequently searched issues - ensuring your business is better protected as it moves to the cloud.
  
When Threat Trackers are available to you, please try them out - and remember that you can always provide us feedback on this or other Office 365 security features by clicking on the **Feedback** button in the lower right corner of the [Overview of the Office 365 Security &amp; Compliance Center](https://support.office.com/article/a5f2fd18-b029-4257-b5a8-ae83e7768c85).
  
![Office 365 Security &amp; Compliance Center](media/86c330db-8132-4150-8475-220258fe04fb.png)
  
## Trackers and Office 365 Advanced Threat Protection

With our inaugural Noteworthy threat, we're highlighting advanced malware threats detected by [Office 365 ATP Safe Attachments](atp-safe-attachments.md). If you're an Office 365 Enterprise E5 customer and you're not using [Office 365 Advanced Threat Protection](office-365-atp.md) (ATP), you should be - it's included in your subscription. ATP provides value even if you have other security tools filtering email flow with your Office 365 services. However, anti-spam and [Office 365 ATP safe links](atp-safe-links.md) features work best when your main email security solution is through Office 365. 
  
![ATP in the Security &amp; Compliance Center](media/cee70d07-f0c1-459b-843c-2d10c253349f.png)
  
In today's threat-riddled world, running only traditional anti-malware scans means you are not protected well enough against attacks. Today's more sophisticated attackers use commonly available tools to create new, obfuscated, or delayed attacks that won't be recognized by traditional signature-based anti-malware engines. The ATP Safe Attachments feature takes email attachments and detonates them in a virtual environment to determine whether they're safe or malicious. This detonation process opens each file in a virtual computer environment, then watches what happens after the file is opened. Whether it's a PDF, and compressed file, or an Office document, malicious code can be hidden in a file, activating only once the victim opens it on their computer. By detonating and analyzing the file in the email flow, Office 365 ATP capabilities finds these threats based on behaviors, file reputation, and a number of heuristic rules.
  
The new Noteworthy threat filter highlights items that were recently detected through ATP Safe Attachments. These detections represent items that are new malicious files, not previously found by Office 365 in either your email flow or other customers' email. Pay attention to the items in the Noteworthy Threat Tracker, see who was targeted by them, and review the detonation details shown on the Advanced Analysis tab (found by clicking on the subject of the email in Explorer). Note you'll only find this tab on emails detected by the ATP Safe Attachments capability - this Noteworthy tracker includes that filter, but you can also use that filter for other searches in Explorer.
  
## Next steps

- If your organization doesn't already have Office 365 Threat Intelligence, see [How do we get Office 365 Threat Intelligence?](get-started-with-ti.md).
    
- Make sure that your security team has the correct roles and permissions assigned. You must be an Office 365 global administrator, or have the Security Administrator or Search and Purge role assigned in the Security &amp; Compliance Center. See [Permissions in the Office 365 Security &amp; Compliance Center](permissions-in-the-security-and-compliance-center.md).
    
- Watch for the new Trackers to show up in your Office 365 environment. When available, you'll find your Trackers [here](https://protection.office.com/). Go to **Threat management** \> **Threat trackers**.
    
- If you haven't already done so, learn more about and configure [Office 365 Advanced Threat Protection](office-365-atp.md) for your organization, including [Office 365 ATP safe links](atp-safe-links.md) and [Office 365 ATP Safe Attachments](atp-safe-attachments.md).
  

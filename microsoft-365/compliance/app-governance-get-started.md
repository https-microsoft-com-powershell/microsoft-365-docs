---
title: "Get Started with app governance"
f1.keywords:
- NOCSH
ms.author: v-tophillips
author: JoeDavies-MSFT
manager: laurawi
audience: Admin
ms.topic: hub-page
ms.service: O365-seccomp
ms.collection: m365-security-compliance
localization_priority: Priority
search.appverid: 
- MOE150
- MET150
description: "Get started with app governance capabilities to govern your apps."
---

# Get started with app governance (in preview)

To begin using the app governance add-on to Microsoft Cloud App Security:

1. Verify your account has the appropriate level of licensing. App governance is an add-on feature for Microsoft Cloud App Security (MCAS), and thus MCAS must be present in your account as either a standalone product or as part of the various license packages listed below.
1. You must have one of the administrator roles listed below to access the app governance pages in the portal.
1. Your organization's tenant registration must be within one of the [supported areas of North America, Europe, or Africa](app-governance-countries.md).

## Licensing for app governance

Before you get started with app governance, you should confirm your [Microsoft 365 admin center - subscriptions](https://admin.microsoft.com/Adminportal/Home?source=applauncher#/subscriptions) and any add-ons. To access and use app governance, your organization must have one of the following subscriptions or add-ons:

- Microsoft Cloud App Security
- Microsoft 365 E5
- Microsoft 365 E5 Compliance
- Microsoft 365 E5 Developer (without Windows and Audio Conferencing)
- Microsoft 365 E5 Information Protection and Governance
- Microsoft 365 E5 Security
- Microsoft 365 E5 with Calling Minutes
- Microsoft 365 E5 without Audio Conferencing
- Microsoft 365 A5 Compliance for faculty
- Microsoft 365 A5 Compliance for students
- Microsoft 365 A5 for faculty
- Microsoft 365 A5 for students
- Microsoft 365 A5 Information Protection and Governance for faculty
- Microsoft 365 A5 Information Protection and Governance for students
- Microsoft 365 A5 Security for faculty
- Microsoft 365 A5 Security for students
- Microsoft 365 A5 student use benefits
- Microsoft 365 A5 with Calling Minutes for Faculty
- Microsoft 365 A5 with Calling Minutes for Students
- Microsoft 365 A5 without Audio Conferencing for faculty
- Microsoft 365 A5 without Audio Conferencing for students
- Microsoft 365 A5 without Audio Conferencing for students use benefit

## Administrator roles

One of the following administrator roles is required to see app governance pages or manage policies and settings:

- Application Administrator
- Cloud Application Administrator
- Company Administrator
- Compliance Administrator
- Compliance Data Administrator
- Compliance Reader (read-only)
- Global Reader
- Security Administrator
- Security Operator
- Security Reader (read-only)

> [!NOTE]
> Only a Global Admin can activate the app governance free trial.

Here are the capabilities for each role.

| Role | Read the dashboard | Read all apps |Read policies | Create, update, or delete policies | Read alerts | Update alerts | Read settings | Update settings | Read Remediation | Update Remediation |
|:-------|:-----|:-------|:-------|:-------|:-------|:-------|:-------|:-------|:-------|:-------|
| Application Administrator | ![Check mark](..\media\checkmark.png) | ![Check mark](..\media\checkmark.png) | ![Check mark](..\media\checkmark.png) | ![Check mark](..\media\checkmark.png) | ![Check mark](..\media\checkmark.png) | ![Check mark](..\media\checkmark.png) | ![Check mark](..\media\checkmark.png) | ![Check mark](..\media\checkmark.png) | ![Check mark](..\media\checkmark.png) | ![Check mark](..\media\checkmark.png) |
| Cloud Application Administrator | ![Check mark](..\media\checkmark.png) | | | | | | | | | |
| Company Administrator | ![Check mark](..\media\checkmark.png) | ![Check mark](..\media\checkmark.png) | ![Check mark](..\media\checkmark.png) | ![Check mark](..\media\checkmark.png) | ![Check mark](..\media\checkmark.png) | ![Check mark](..\media\checkmark.png) | ![Check mark](..\media\checkmark.png) | ![Check mark](..\media\checkmark.png) | ![Check mark](..\media\checkmark.png) | ![Check mark](..\media\checkmark.png) |
| Compliance Administrator | ![Check mark](..\media\checkmark.png) | ![Check mark](..\media\checkmark.png) | ![Check mark](..\media\checkmark.png) | ![Check mark](..\media\checkmark.png) | ![Check mark](..\media\checkmark.png) |  | ![Check mark](..\media\checkmark.png) | ![Check mark](..\media\checkmark.png) | ![Check mark](..\media\checkmark.png) | |
| Compliance Data Administrator | ![Check mark](..\media\checkmark.png) | ![Check mark](..\media\checkmark.png) | ![Check mark](..\media\checkmark.png) | ![Check mark](..\media\checkmark.png) | ![Check mark](..\media\checkmark.png) |  | ![Check mark](..\media\checkmark.png) | ![Check mark](..\media\checkmark.png) | ![Check mark](..\media\checkmark.png) | |
| Compliance Reader | ![Check mark](..\media\checkmark.png) | ![Check mark](..\media\checkmark.png) | ![Check mark](..\media\checkmark.png) |  | ![Check mark](..\media\checkmark.png) |  | ![Check mark](..\media\checkmark.png) |  | | |
| Global Reader  | ![Check mark](..\media\checkmark.png) | ![Check mark](..\media\checkmark.png) | ![Check mark](..\media\checkmark.png) |  | ![Check mark](..\media\checkmark.png) |  | ![Check mark](..\media\checkmark.png) |  | | |
| Security Administrator | ![Check mark](..\media\checkmark.png) | ![Check mark](..\media\checkmark.png) | ![Check mark](..\media\checkmark.png) | ![Check mark](..\media\checkmark.png) | ![Check mark](..\media\checkmark.png) |  | ![Check mark](..\media\checkmark.png) | ![Check mark](..\media\checkmark.png) | ![Check mark](..\media\checkmark.png) | |
| Security Operator | ![Check mark](..\media\checkmark.png) | ![Check mark](..\media\checkmark.png) | ![Check mark](..\media\checkmark.png) | ![Check mark](..\media\checkmark.png) | ![Check mark](..\media\checkmark.png) | ![Check mark](..\media\checkmark.png) | ![Check mark](..\media\checkmark.png) | ![Check mark](..\media\checkmark.png) | ![Check mark](..\media\checkmark.png) | |
| Security Reader  | ![Check mark](..\media\checkmark.png) | ![Check mark](..\media\checkmark.png) | ![Check mark](..\media\checkmark.png) |  | ![Check mark](..\media\checkmark.png) |  | ![Check mark](..\media\checkmark.png) |  | ![Check mark](..\media\checkmark.png) | |
|||||||||| | |

For additional information about each role, see [Administrator role permissions](/azure/active-directory/roles/permissions-reference).

## Add app governance to your Microsoft 365 account

For existing Microsoft 365 customers:

1. In your [Microsoft 365 admin center](https://admin.microsoft.com), navigate to **Billing - Purchase services** and click **Add-ons**.
1. In the app governance card, click **Details**.
1. Click **Start free trial**.
1. Complete the requested information to add app governance to your selected tenant. I you are a new customer, you must first provide information to establish an account and create a tenant for your trial period. Once this is done you can add app governance to the trial.

For new Microsoft 365 customers:

1. At the top of this page, click the **Free Account** button.
1. Under **Try Microsoft 365 for business** click **Try 1 month free**.

For both:

1. In the sign-up portal, provide your email address to use for the trial. If you are an existing customer, use the email associated with your account. Click **Next**
1. Once you have signed in, click **Try now** to get the free trial.
1. Click **Continue** to close page and begin trial setup. For new app governance customers, it will take up to two hours for your app governance instance to become available. For existing customers, there will be no interruption of existing services.

  > [!NOTE]
  If you do not already have an account you will be prompted to set up a new account before you can proceed with the trial.

1. Enter in an available domain name for your AAD tenant and click **Check availability**. You will automatically be assigned an Admin role (if you don’t have an existing role for app governance) and can always change the domain name and/or purchase more tenants later through the Microsoft 365 admin center.
1. Enter the username and password you would like to use to login to your account. Click **Sign up**.
1. Click **Get started** to go to the app governance portal or **Manage your subscription** to go to the Microsoft 365 admin center.

## Add integration with MCAS 

Pre requisites:

- Office 365 is connected in Cloud App Security
- Office 365 Azure AD apps are enabled

To enable app governance sync with Cloud App Security follow these steps:

1. Go to your Microsoft Cloud App Security portal – [https://portal.cloudappsecurity.com](https://portal.cloudappsecurity.com)
1. Click the gear icon (top right corner) and select **Settings**.
1. Under **Threat Protection**, select **App Governance**.
1. Click **Enable App Governance integration**, and then select **Save**.

Next, review newly enabled policies in MCAS. The new policies might take few minutes to appear once integration is enabled.

- Microsoft 365 OAuth app Reputation
- Microsoft 365 OAuth Phishing Detection
- Microsoft 365 OAuth App Governance
- Review App Governance widget in MCAS dashboard
- Review newly generated App Governance alerts in MCAS alerts
- Review MCAS M365 OAuth policies in App Governance policy list
- Review newly generated  MCAS M365 OAuth alerts  in App Governance alerts

## Canceling your trial

If you did not participate in private preview and would like to cancel your trial of app governance, you can communicate with your CXE contact, or use these steps:

1. In the Microsoft 365 admin center, navigate to **Billing** > **Your products**.
1. Navigate to the app governance trial, click the three dots, and select **Cancel subscription**.
1. In the resulting fly-out pane, provide a reason for cancellation, any additional feedback, and select **Cancel subscription**.
1. Select **Cancel subscription** in the resulting pop up screen. Your trial is cancelled, you will lose access to app governance, and your app governance data will be deleted (log data that is used to create the app governance insights and detections - no emails or other files will be affected).

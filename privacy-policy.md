# Dup Privacy Policy

**Effective: September 3, 2026**

This Privacy Policy explains how Stratoxphere Lab (**“Stratoxphere,” “we,” “us,”** or **“our”**) handles personal data when you use Dup, the Stratoxphere account platform, and related account, commerce, access, device, and licensing services (collectively, the **“Service”**). The operator's legal identity is disclosed in the Contact section below.

Stratoxphere is the controller of the personal data described as Platform Data below. Our privacy contact is **support@stratoxphere.app**.

## 1. The Important Distinction: Dup Content and Platform Data

Dup has two separate data paths.

**Gemini processing happens directly from your device.** Dup uses your own Gemini API key to send content from your device to Google. Audio, selected text, optional screenshots, transcripts submitted for rewriting, custom vocabulary, prompts, and Gemini output do not pass through the Stratoxphere Platform. Stratoxphere does not receive or store that content on its servers through this path.

**Account and access data goes to Stratoxphere.** The Stratoxphere Platform processes information needed to sign you in, manage access and purchases, activate devices, validate licenses, prevent abuse, provide support, and maintain security and transaction records.

Data stored only on your device is described separately below. It is not collected by Stratoxphere unless you deliberately send it to us, for example in a support request.

## 2. Data Stored or Processed on Your Device

Dup stores or handles the following locally:

| Data | What Dup does with it |
| --- | --- |
| Gemini API key | Stores it using secure storage provided by your operating system, or uses another source you deliberately configure. Dup uses the key to authenticate requests sent directly to Google. |
| Account and access credentials | Stores the credentials needed to connect Dup to your Stratoxphere account and confirm access using secure storage provided by your operating system. Dup does not store your Google sign-in password. |
| Device identifier | Generates and stores an identifier used to distinguish the installation for account, security, and licensing purposes. |
| Settings and application state | Stores your shortcut, microphone selection, language preferences, custom vocabulary, screen-context choice, writing style, clipboard choice, history choice, and onboarding state in local application files. |
| Dictation history | By default, Dup stores a local history containing transcripts, modifications, relevant application context, settings used for the request, output, timing, outcome, and errors. You can disable history, inspect it, or clear it at any time. Older entries may be removed automatically to keep the history bounded. |
| Microphone audio | Holds audio in memory while sending it to the Gemini API. Dup does not save a local audio recording as part of dictation history. |
| Screen Context screenshot | When you turn Screen Context on, captures the active window or current display. The screenshot is held in memory, sent directly to Google, and not written to disk by Dup. Screen Context is off by default. |
| Clipboard and selected text | Reads or changes selected text when you use the modification feature. Dup may place generated text on the clipboard. Depending on your settings and system capabilities, it may restore the previous clipboard contents or leave the generated text there for you to paste. Selected text may also appear in local dictation history. |

Removing the application may not remove its data automatically. Use Dup's clear controls or your operating system's application-data tools if you want to remove local data.

## 3. Content Sent Directly to Google

Depending on what you do and which features you enable, Dup sends the following directly to the Gemini API under your API key:

- microphone audio and the settings or vocabulary needed for transcription;
- a transcript and your selected writing style or instruction for a rewrite;
- selected text and a spoken instruction for the modification feature; and
- an in-memory screenshot when Screen Context is enabled.

Google handles this content under its current [Gemini API Terms](https://ai.google.dev/gemini-api/terms) and [Privacy Policy](https://policies.google.com/privacy). Those documents may change independently of this Policy. Review them before deciding what content to process through Dup. Stratoxphere does not restate or control Google's data practices.

Because you choose and control the Google account, API key, related configuration, and content sent through that key, Stratoxphere cannot access, delete, export, or control content held by Google on your behalf.

## 4. Platform Data We Collect

We collect or generate the following categories of Platform Data:

| Category | Examples | Source |
| --- | --- | --- |
| Account and identity | Account identifier, verified email address, display name, and sign-in information needed to authenticate you | You and our authentication providers |
| App connection and device | App and device identifiers, device name, connection or activation status, and related timestamps | Dup and the Platform |
| Access and eligibility | Entitlement status and information needed to determine or administer access, offers, referrals, or other product eligibility | You, other participating users, and the Platform |
| Transactions and licenses | Customer, checkout, order, transaction, license, and activation identifiers or status; records needed to issue, verify, refund, revoke, or support a purchase or license | Creem and the Platform |
| Security and operations | Audit events, request and webhook metadata, status, errors, IP address, user agent, and other information needed to secure and operate the Service | Your device, the Platform, Creem, and our infrastructure providers |
| Support communications | Your message, contact details, and any files or diagnostic information you choose to provide | You |

Some sensitive commerce and licensing values are stored in protected form. We do not receive the Gemini content described in Section 3 through the Stratoxphere Platform.

## 5. Why We Process Platform Data

We use Platform Data to:

- create, authenticate, secure, and maintain your Stratoxphere account;
- connect Dup to your account and confirm current access;
- administer purchases, licenses, device activations, offers, and referrals made available through the Service;
- match commerce confirmations to the correct account and product;
- prevent duplicate, fraudulent, unauthorized, or abusive use;
- respond to refunds, payment disputes, security events, privacy requests, and support requests;
- diagnose failures and protect users, the Service, and third parties;
- maintain transaction, audit, accounting, and legal records; and
- comply with law and enforce the [Dup Terms of Service](./terms-of-service.md).

Where the European Economic Area, United Kingdom, or similar law applies, our legal bases are performance of a contract when processing is needed to provide your account and Dup access; legitimate interests in securing, operating, improving, and preventing abuse of the Service; compliance with legal obligations for transaction and regulatory records; and consent where law requires it for a specific optional activity. You can disable Screen Context and local history without withdrawing from the account or license contract.

Product access and eligibility rules may be applied automatically. Contact us if you believe a rule was applied incorrectly.

## 6. When We Share Data

We disclose Platform Data only as needed for the purposes described below. Each provider's current terms and privacy notices govern its own services and may change independently of this Policy.

- **Google and Firebase Authentication** provide account authentication. See [Firebase Privacy and Security](https://firebase.google.com/support/privacy) and the [Google Privacy Policy](https://policies.google.com/privacy).
- **Creem** acts as merchant of record and supports payments, tax, orders, refunds, customer access, and licensing. See the current [Creem Privacy Notice](https://www.creem.io/privacy) and [Creem Buyer Terms](https://www.creem.io/buyer-terms).
- **Cloudflare** hosts and protects the Stratoxphere Platform. See the current [Cloudflare Privacy Policy](https://www.cloudflare.com/policies/privacy/).
- **GitHub** distributes official Dup downloads and versioned legal documents. See the current [GitHub Privacy Statement](https://docs.github.com/en/site-policy/privacy-policies/github-general-privacy-statement).
- **Professional advisers and service providers** may receive data when needed to provide legal, accounting, security, support, or infrastructure services and subject to appropriate duties.
- **Legal and safety recipients** may receive data where reasonably necessary to comply with law or legal process, protect rights and safety, investigate fraud, or establish and defend legal claims.
- **Business-transfer recipients** may receive data as part of a merger, financing, reorganization, acquisition, bankruptcy, or sale of assets, subject to applicable law and appropriate notice.

We do not sell personal data. We do not share personal data for cross-context behavioral advertising and do not use Platform Data to serve targeted ads.

## 7. International Processing

Our providers operate internationally, so Platform Data may be processed outside your country. Each provider describes its locations and transfer practices in its current privacy documentation linked above.

## 8. Retention

Local data remains on your device until you clear it, it is replaced or pruned by Dup, or you remove it using your operating system. Access credentials remain only while needed for their purpose or until they expire, are revoked, or are removed.

We retain Platform Data only for as long as reasonably necessary for the purposes described in this Policy, including to provide and secure the Service, maintain an account or license, prevent fraud and repeated misuse, resolve disputes, and meet tax, accounting, consumer-protection, and other legal obligations. Retention depends on the type of data, why it was collected, the sensitivity and risk of keeping it, and applicable legal requirements.

Account and access records are generally retained while the related account or service relationship remains active and for a reasonable period afterward. Transaction and accounting records may be retained for longer where required by law. Expired connection requests, operational logs, audit records, and support communications are deleted or minimized when they are no longer needed for security, support, dispute resolution, or legal compliance.

We may retain specific data longer when required by law, needed to establish or defend legal claims, or necessary to address fraud or security incidents. Where possible, we will restrict use during that extended period.

## 9. Your Controls and Choices

You can:

- leave Screen Context off or disable it at any time;
- disable, inspect, or clear local dictation history;
- remove the locally stored Gemini API key or revoke it through Google;
- change Dup settings and custom vocabulary;
- edit the display name associated with your Stratoxphere account;
- manage supported device activations through your account;
- disconnect Dup from your account; and
- request account deletion by emailing **support@stratoxphere.app** from the email address associated with your Stratoxphere account.

Clearing Dup's local data does not delete data held by Google under your API key, Platform Data stored by Stratoxphere, or transaction records held by Creem. Requests concerning data controlled by Google or Creem may need to be directed to those providers.

## 10. Your Privacy Rights

Depending on where you live, you may have rights to request access, correction, deletion, restriction, objection, or portability; withdraw consent where processing relies on consent; opt out of certain sharing; or appeal our response. You may also have the right to complain to a data protection or consumer authority.

Submit a request to **support@stratoxphere.app**. We may need to verify that you control the relevant account. We will not discriminate against you for exercising a privacy right. Some data may be exempt from a request or retained where required for security, fraud prevention, transactions, legal compliance, or legal claims.

If we process data based on legitimate interests, you may object based on your circumstances. If we use consent, withdrawing consent does not affect processing that occurred before withdrawal.

## 11. Security

We use administrative, technical, and organizational safeguards designed to protect Platform Data, including protections for data in transit and at rest, access controls, credential management, and separation between public application code and server-side credentials.

Dup uses secure storage provided by the operating system for supported credentials. No method of storage or transmission is completely secure, and we cannot guarantee absolute security. You are responsible for protecting your device, Stratoxphere account, Google account, and Gemini API key.

## 12. Children

Dup is not directed to children. You must meet the eligibility requirements in the [Dup Terms of Service](./terms-of-service.md) and the current terms of any third-party service you use with Dup. If you believe a child has provided Platform Data in violation of those requirements, contact **support@stratoxphere.app**.

## 13. Changes to This Policy

We may update this Policy when Dup, our providers, law, or our data practices change. The effective date identifies the current version. We will provide notice of material changes when required by law.

The Policy committed with a tagged Dup release provides a versioned record for that release. The current policy will also be available from the official Dup repository and Stratoxphere website.

## 14. Contact

**Stratoxphere Lab**

Founded and operated by **JHEN-KE LIN**

Privacy and support: **support@stratoxphere.app**

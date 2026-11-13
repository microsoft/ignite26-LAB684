# Zero Trust for AI: Securing agents in your organization

## The Zero Trust Workshop

The Workshop and Assessment work together: the Assessment provides evidence about security settings; the Workshop provides guidance for planning improvements.

In this lab, you will explore the Zero Trust Workshop, review a sample Assessment report, and see how findings inform a security improvement plan. The session focuses on AI readiness, including the new DevSecOps and AI memory guidance.

| Tool | What it does |
| --- | --- |
| **Zero Trust Assessment** | Checks tenant configuration and produces a report with findings, supporting evidence, and recommended remediation. |
| **Zero Trust Workshop** | Organizes implementation guidance by pillar and lets you record task statuses, decisions, and next steps. |

Both support Microsoft's Zero Trust approach: **verify explicitly**, **use least privilege access**, and **assume breach**.

## Get started

For the guided session, sign in to your **lab VM** using the credentials provided by your lab platform. Use **Microsoft Edge** inside the VM for the following tasks.

For self-paced learning without a lab VM, use Microsoft Edge to explore the public Workshop and sample Assessment report. Skip the Cloud Admin sign-in section if you do not have an assigned lab environment. You do not need to collect tenant data or install PowerShell to complete the sample-report tasks.

Keep lab credentials, Temporary Access Passes, authenticator QR codes, and verification codes private. Do not add them to this repository, screenshots, task notes, or reports.

## Explore the Zero Trust Workshop

1. Open **Microsoft Edge**.
2. Navigate to the [Microsoft Zero Trust Workshop](https://zerotrust.microsoft.com/).
3. Explore the pillar tabs: **Identity**, **Devices**, **Data**, **Network**, **Infrastructure**, **Security Operations**, **AI**, and **DevSecOps**.
4. Open a task card to see its recommended work, status, and notes. Select **View details** to read the implementation guidance.
5. Review a **DevSecOps** recommendation about securing software development and delivery, including repositories, dependencies, and pipelines.
6. Review the **AI memory** guidance about protecting information agents store and recall. Identify who can write it, who can access it, and how it is checked before reuse.

Record which recommendations you reviewed and the questions you would need to answer before applying them in an organization. Use sample information rather than sensitive organizational data.

## Explore the Zero Trust Assessment

The Workshop describes recommended improvements. The Assessment helps identify which security settings need attention.

1. In Microsoft Edge, open the [sample Microsoft Zero Trust Assessment report](https://microsoft.github.io/zerotrustassessment/demo/).
2. Start with **Overview** to see the report's summaries, then select a pillar to explore its findings.
3. Open a finding and review what was checked, its result, the supporting evidence, and the recommended remediation and links to further guidance.
4. Record one finding, the evidence supporting it, and a recommended next step.

Read the evidence alongside the result. For example, a check showing that users have registered phishing-resistant authentication methods does not establish that those methods are required at sign-in.

The Assessment uses PowerShell to collect tenant data and generate a report. This introduction uses a prepared sample report, not a live assessment of your lab tenant.

## Cloud Admin account and admin portals

Use your **Cloud Admin** account only for the admin portals specified by your instructor.

1. In Microsoft Edge inside your lab VM, open the admin portal as instructed by your instructor.
2. Sign in using the **Cloud Admin** username and password, or **Temporary Access Pass** when instructed, provided by your lab platform.

The public sample-report tasks do not require an admin account. If you are working independently without an assigned lab tenant, continue to [Return to the Workshop](#return-to-the-workshop).

> **If prompted to set up multifactor authentication in the assigned lab:**
>
> 1. On **Install Microsoft Authenticator**, select **Set up a different authenticator app**, then **Next**.
> 2. When the QR code appears, open **Contoso Authenticator App** from the VM taskbar. Keep the QR code visible.
> 3. Select **Scan QR from Screen** and copy the six-digit code.
> 4. Return to the browser, select **Next**, and enter the code. Complete the remaining prompts to finish setup.

## Return to the Workshop

1. In Microsoft Edge, return to the [Microsoft Zero Trust Workshop](https://zerotrust.microsoft.com/).
2. Use the sample Assessment finding you reviewed to identify a related Workshop recommendation. Do not assume the sample finding describes your lab tenant or organization.
3. Review the recommendation's task status and notes. Record your current position, the decision to investigate or improve the setting, and the next step. For self-paced exploration, label these as sample planning notes.
4. Include the DevSecOps and AI memory recommendations you reviewed in your planning notes.
5. Select **Actions > Report** to see the recommendations alongside any saved statuses and notes.
6. Use the report as a starting point for a prioritized **12-24 month roadmap** across identity, devices, data, network, AI, and security operations. Identify the first recommendation you would address and explain the evidence behind that choice.

## Completion checklist

- Reviewed DevSecOps and AI memory guidance in the Workshop.
- Read a sample Assessment finding, its evidence, and recommended remediation.
- Connected a finding to a Workshop recommendation and recorded a next step.
- Reviewed **Actions > Report** and identified a first priority for the roadmap.

## Learn more

- [Zero Trust Workshop](https://aka.ms/ztworkshop)
- [Get started with the Zero Trust Assessment](https://learn.microsoft.com/security/zero-trust/assessment/get-started)
- [Zero Trust Assessment source and issues](https://github.com/microsoft/zerotrustassessment)
- [Microsoft Zero Trust overview](https://learn.microsoft.com/security/zero-trust/zero-trust-overview)

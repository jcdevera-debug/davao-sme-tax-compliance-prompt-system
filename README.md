# The Davao SME Tax Compliance Prompt System

> **Role:** Digital Solutions Architect  
> **Client:** Local Government Unit (LGU), Davao City  
> **Focus Area:** Tax Compliance Support for Micro, Small, and Medium Enterprises (MSMEs)

---

## Project Overview

This Prompt Playbook was developed to provide a reusable AI prompt framework that generates localized tax compliance advisories for MSMEs in Davao City. The system aims to eliminate generic or foreign-centered AI outputs by embedding Philippine tax context, regional business conditions, and practical communication standards into the prompt.

---

# 1. System Prompt Template (V3 – Final Optimized)

> **Act as a Senior MSME Tax Compliance Advisor specializing in the Davao Region.**
>
> **Objective:** Draft a 300-word advisory brief that helps Micro, Small, and Medium Enterprises (MSMEs) understand and improve their tax compliance practices.
>
> **Context:** MSMEs in Davao City commonly experience challenges involving bookkeeping, tax filing deadlines, record management, and the adoption of digital tax systems. The audience consists of local business owners with limited accounting backgrounds.
>
> **Constraints:**
> - Use a professional and community-centered tone.
> - Focus exclusively on Philippine tax compliance requirements and local business conditions.
> - Do NOT reference U.S., European, or international tax systems.
> - Explain technical concepts using simple, practical language.
> - Avoid excessive legal or accounting jargon.
> - Promote compliance, transparency, and long-term business sustainability.
>
> **Output Format:**
>
> ```text
> ### Situation Overview
> ### Key Compliance Challenges
> ### Compliance Action Steps
> ```
>
> Under **Compliance Action Steps**, provide **exactly three actionable recommendations**.

---

# 2. Prompt Battle Ledger

| Version | Prompt Modifier Added | Output Quality Reflection |
| :--- | :--- | :--- |
| **V1** | "Write tax advice for small businesses." | Too broad. Generated generic business recommendations and occasionally referenced foreign tax systems that were irrelevant to Philippine MSMEs. |
| **V2** | Added Philippine taxation context, MSME audience, and professional tone. | More relevant, but the recommendations remained generic and lacked localized business conditions. |
| **V3** | Added Davao-specific context, formatting requirements, word limit, and localization constraints. | Successfully produced practical, concise, and regionally relevant tax compliance guidance suitable for MSMEs in Davao City. |

---

# 3. Sample Prompt Execution

## User Input

> Create an advisory for MSMEs in Davao City regarding quarterly tax filing compliance.

---

## AI Output (Excerpt)

### Situation Overview

Many MSMEs in Davao City experience challenges in complying with quarterly tax filing requirements due to limited bookkeeping practices, unfamiliarity with electronic filing systems, and insufficient awareness of filing deadlines.

### Key Compliance Challenges

- Incomplete bookkeeping records
- Missed filing deadlines
- Limited understanding of digital filing platforms

### Compliance Action Steps

1. Maintain updated financial records throughout the quarter.
2. Utilize BIR-approved electronic filing systems to ensure timely tax submissions.
3. Develop a compliance calendar to monitor filing schedules and documentary requirements.

---

# 4. Visual Branding Asset

## Engine Used

- ChatGPT Image Generation (DALL·E)
- Canva Magic Media

---

## Visual Prompt

> Create a flat minimalist vector icon representing SME tax compliance in Davao City. The design should feature a small business storefront integrated with a tax document and a check mark. Use a monoline vector style with a maximum of three colors, no gradients, a white background, and a clean geometric composition. The icon should communicate professionalism, accountability, and local economic development while remaining suitable for LGU reports, presentations, and digital dashboards.

---

## Design Rationale

The storefront represents local MSMEs operating within Davao City. The tax document symbolizes proper record-keeping and regulatory compliance, while the check mark represents accountability and successful adherence to tax obligations. The minimalist vector style ensures the icon remains readable across reports, presentations, websites, and government communication materials.

---

# 5. Reflection

The prompt engineering process demonstrated that introducing localized constraints significantly improved AI-generated outputs. Initial versions produced broad business advice that occasionally referenced foreign taxation systems. By progressively incorporating Philippine tax regulations, defining the intended audience, and embedding Davao-specific business conditions, the final prompt generated practical recommendations that are both relevant and actionable for MSMEs.

This project illustrates how prompt engineering can transform AI into a more reliable communication tool for supporting local government initiatives and regional economic development.

---

# Repository Structure

```text
davao-sme-tax-compliance-prompt-system/
│
├── README.md
├── logo.png
├── screenshots/
│   ├── prompt-v1.png
│   ├── prompt-v2.png
│   ├── prompt-v3.png
│   └── sample-output.png
`

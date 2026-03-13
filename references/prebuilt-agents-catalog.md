# Pre-Built AI Agents Catalog — Oracle Fusion Cloud Applications

This catalog lists Oracle's pre-built agent templates available in AI Agent Studio.
All templates can be copied and customized.

## Table of Contents
1. [ERP / Finance](#erp--finance)
2. [HCM — Recruiting](#hcm--recruiting)
3. [HCM — Skills, Career & Talent](#hcm--skills-career--talent)
4. [HCM — HR & Workforce Management](#hcm--hr--workforce-management)
5. [HCM — Employee Experience & Onboarding](#hcm--employee-experience--onboarding)
6. [SCM & Manufacturing](#scm--manufacturing)
7. [CX / Service](#cx--service)

---

## ERP / Finance

| Agent | Description |
|-------|-------------|
| Payables Agent | Automates multichannel invoice processing: ingest from email/portals/EDI/PDFs, extract and normalize data, match to POs/receipts, create distributions, apply tax/policy/fraud checks, route for approval |
| Ledger Agent | Shifts accountants from report-chasing to continuous insight. Sets natural language monitoring prompts, delivers context-aware inquiries, autocreates adjustment journals |
| Planning Agent | Enables continuous connected planning. Real-time trend and variance analysis via natural language, event-driven predictions on Fusion data, "what if" simulations |
| Payments Agent | Optimizes cash outflows. Evaluates early pay, virtual cards, financing options. Enables bank system interactions for supplier onboarding |
| Expense Policy Agent | Addresses policy questions from employees with contextual answers before incurring expenses |
| PCM Agent | Conversational interface for building, modifying, calculating, and analyzing profitability and cost models |
| Receipt Capture and Matching | Automated matching of credit card charges during expense creation |
| Access Request Assistant | Helps users create access requests to ERP roles with separation-of-duties analysis |

## HCM — Recruiting

| Agent | Description |
|-------|-------------|
| Career Coach | Recommends best-fit roles to candidates, supports real-time Q&A, interview prep, career summary generation |
| Compensation Guidelines Analyst | Insights on market trends and company compensation policies |
| Employee Hiring Advisor | Insights and recommendations to streamline recruitment |
| Interview Management Assistant | Automates interview scheduling, manages calendar invites, resolves conflicts |
| Job Applicant Screening Advisor | Real-time context-specific responses about individual applicants |
| Job Offer Analyst | Support and answers for offer and compensation policy questions |
| Job Requisition Analyst | Support for hiring managers creating job requisitions |

## HCM — Skills, Career & Talent

| Agent | Description |
|-------|-------------|
| Career Planning Guide | Guides employees in setting career goals and development roadmaps |
| Job Discovery Advisor | Matches employees to open roles based on experience and interests |
| Job Fit Advisor | Assesses employee job fit, provides policy guidance, recommends skill-building |
| Job Seeker Analyst | Assists job seekers with resume tips, interview coaching, job search strategies |
| Learning and Training Advisor | Recommends training and development opportunities |
| Learning Tutor | Responds to employee questions about online training materials |
| Performance and Goals Assistant | Helps employees set and achieve performance goals |
| Succession Planning Advisor | Identifies succession needs, assesses pipeline health, automates plan creation |
| Talent Advisor | Guides managers through talent reviews with tools and insights |
| Talent Review Assistant | Tools to assist managers in gathering and summarizing performance reviews |
| Team Goals Assistant | Supports managers in setting, tracking, aligning team goals |
| Team Sync Advisor | Collects weekly updates, provides actionable meeting digests |
| Skill Recommendation Agent | Recommends skills using generative AI (template: SKILL_RECOMMENDATION_AGENT) |

## HCM — HR & Workforce Management

| Agent | Description |
|-------|-------------|
| Benefits Certification Assistant | Automates benefits verification and certification status updates |
| Benefits Plan Advisor | Helps employees understand and maximize benefits packages |
| Benefits Policy Advisor | Interprets company-specific benefits documents for eligibility and compliance |
| Collective Agreements Analyst | Understanding collective bargaining agreements |
| Compensation Advisor | Data-driven insights on salary, stock options, additional payments |
| Compensation Statement Analyst | Clarifying questions about total compensation statements |
| Court Order Assistant | Manages court-ordered payroll deductions |
| Employee Contracts Analyst | Clarity on employment contract terms and conditions |
| Employment Information Advisor | Retrieves employment data with role-based access |
| Employment Lifecycle Policy Analyst | Step-by-step guidance on hiring, onboarding, development, offboarding policies |
| Leave and Absence Analyst | Navigates leave policies, assists with time-off requests |
| Leave and Absence Policy Advisor | Explains leave policies and employee rights |
| Org Chart Analyst | Understanding organizational structures and reporting lines |
| Pay Policy Advisor | Retrieves and analyzes pay policy documents |
| Payroll Run Analyst | Explains payroll anomalies and supports root cause analysis |
| Payslip Analyst | Clarifies salary breakdown and deductions |
| Personal Information Advisor | Manages employee personal and employment information updates |
| Positions Assistant | Data-driven decisions for position management, backfills, new roles |
| Promotion Advisor | Identifies and recommends employees for promotion |
| Resignation Assistant | Guides employees through resignation and offboarding |
| Shift Scheduling Assistant | Creates and manages employee shift schedules |
| Time Entry Assistant | Automates time entry from signed timesheets |
| Timecard Assistant | Facilitates accurate timecard submission, explains pay calculations |
| Transaction Administration Assistant | Manages and troubleshoots in-flight transactions |

## HCM — Employee Experience & Onboarding

| Agent | Description |
|-------|-------------|
| Employee Concierge | Triages employee inquiries and routes to the right agent |
| Manager Concierge | Routes manager inquiries about team management to correct agents |
| Onboarding Assistant | Supports new employees with policy info, culture, key resources |
| Perks and Awards Analyst | Information about available perks, recognition programs |
| Retirement and Pensions Analyst | Retirement planning guidance including 401(k) and pension options |
| Tax Withholding Guide | Guidance through W-4 elections and tax withholding |

## SCM & Manufacturing

| Agent | Description |
|-------|-------------|
| Costing Period Close Assistant | Expedites period end close with conversational answers from procedures |
| Costing Setup Assistant | Guidance on setup options during costing configuration |
| Item Shortages Analysis Advisor | Identifies inventory stockouts and shortages |
| Material Expiration Analysis | Identifies lots nearing expiration, recommends actions |
| Outbound Compliance Advisor | Assesses shipment compliance, summarizes handling requirements |
| ASN Creation Assistant | Creates advanced shipment notifications |
| Fulfillment Processing Assistant | Executes picking, packing, and shipping |
| Maintenance Work Order Builder | Creates/updates work orders with operations, materials, resources |
| Post-maintenance Work Reporting | Records parts issued, labor, operations after maintenance |
| Disposition Assistant for Rejects | Assesses production rejections and automates rework |
| Create Work Instructions | Summarizes operation steps from source attachments |
| Maintenance Advisor | Answers from multiple repair/maintenance sources |
| Operational Procedure Advisor | Access to operating procedure information |
| Purchase Requisition Status Advisor | Identifies requisitions requiring action |

## CX / Service

Service-specific agents are typically configured through Service Center Administration.
See the main SKILL.md for integration instructions.

---

## Using Templates

To use any pre-built template:

1. Open AI Agent Studio (Navigator > Tools > AI Agent Studio)
2. Search for the template agent by name
3. Click **Copy Template**
4. Enter a suffix (appended to the agent name)
5. Review agent details in the Agent Designer
6. Customize prompts, topics, instructions, and tools
7. Publish
8. Add to an Agent Team for deployment

## Marketplace Template Editing Rules

When working with Marketplace (partner) templates:

- Artifacts (agents, tools, topics) within a template are NOT directly editable
- To modify an artifact: create a copy, edit the copy, remove the original from
  the agent team, then add the edited copy
- Oracle recommends not changing the basic functionality of template artifacts,
  as that might impact the agent team's performance
- You can use the **Use Template** option for a full setup, or **Copy Template**
  to automatically add a suffix to the name
- After publishing, end users can view the agentic flow from the AI Agents page
  (add `agent-explore` to the AI Agent Studio URL)

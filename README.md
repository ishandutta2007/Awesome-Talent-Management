# Awesome-Talent-Management

# Top Talent Management Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**  
*Focused on Performance Reviews, Competency Frameworks & Employee Development*  
**Last updated: October 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **Talent Management**. These tools enable organizations to assess performance, develop competencies, run 360-degree feedback, manage career tracks, and align individual growth with business objectives—moving beyond annual reviews to continuous talent development.

**Examples** include Workday Talent Management, SAP SuccessFactors, Cornerstone OnDemand, Oracle Cloud HCM, Lattice, Culture Amp, 15Five, ClearCompany, Cegid, and Talentsoft (the category leaders).

**Open-source emphasis**: Talent Management is a domain where open-source tooling is **fragmented and largely immature**. Unlike LMS or HRMS, which have mature open-source platforms, talent management—spanning performance reviews, competency frameworks, succession planning, and career development—lacks a comprehensive self-hosted alternative. The projects below address specific niches (360 feedback, OKRs, engineering management) but none provide the full talent suite. Organizations seeking complete talent management capability should plan for commercial platforms or significant custom assembly.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saas-products)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

- **[Workday Talent Management](https://www.workday.com/)**  
  Talent management within Workday's HCM suite, covering performance reviews, goal management, career development, succession planning, and skills tracking integrated with workforce data.

- **[SAP SuccessFactors](https://www.sap.com/)**  
  Comprehensive HXM suite with Performance & Goals, Succession & Development, Compensation, and Learning modules for end-to-end talent management.

- **[Cornerstone OnDemand](https://www.cornerstoneondemand.com/)**  
  Talent management platform with performance, learning, recruiting, and succession modules; strong for skills-based talent strategies.

- **[Oracle Cloud HCM](https://www.oracle.com/)**  
  Talent management within Oracle's HCM suite, covering performance, goals, talent review, and succession planning.

- **[Lattice](https://lattice.com/)**  
  Performance management platform with reviews, goals/OKRs, 1:1s, and engagement surveys for continuous performance development.

- **[Culture Amp](https://www.cultureamp.com/)**  
  Employee experience platform with engagement surveys, performance reviews, and development tools.

- **[15Five](https://www.15five.com/)**  
  Performance management with weekly check-ins, OKRs, and review cycles focused on manager-employee conversations.

- **[ClearCompany](https://www.clearcompany.com/)**  
  Talent management suite covering recruiting, onboarding, performance, and goals.

- **[Cegid](https://www.cegid.com/)**  
  HR and talent management platform for European enterprises, covering performance, training, and career development.

- **[Talentsoft](https://www.talentsoft.com/)**  
  Cegid's talent management platform (now Cegid Talentsoft) with performance, learning, and career modules.

## Open-Source GitHub Projects

- **[HRPulsar](https://www.linkedin.com/posts/hrpulsar_after-4-years-building-hr-software-we-made-activity-7460637448080048128-0bON)**  
  Open-source talent management platform (launched beta 2026); combines competency assessments and grading, testing and certification, employee training, career tracks, internal mobility, and recruiting in one self-hosted platform; notably includes AI agent performance evaluation and management of hybrid teams (humans + AI agents); core version free for SMBs; GitHub repo expected public . **This is the closest to a full open-source talent management platform currently emerging**, though it is in beta and not yet production-proven.

- **[MintHCM](https://github.com/lawotwe/minthcm)**  
  AI-enabled open-source Human Capital Management system (AGPL-3.0) built on SuiteCRM; covers recruitment, time management, onboarding/offboarding, competences & skills, employment history, **employee evaluations**, and analytics; self-hostable with mobile apps; the most complete open-source HR foundation that includes evaluation and competency tracking .

- **[Caliber](https://github.com/shiphrahx/Caliber)**  
  Lightweight open-source web platform for engineering managers (open-source); tracks teams, 1:1s, tasks, delivery signals, and **personal growth**; features career framework and goals tracking with gap analysis, evidence logging per person for performance conversations, and AI-assisted weekly summaries; not a full talent management system but a practical tool for manager-driven development .

- **[Avalia 360](https://github.com/JohnPitter/avalia-360)**  
  Open-source 360-degree feedback application for teams; enables all team members to evaluate each other with encrypted data (AES-256), anonymous feedback, Excel import, automated email invitations, and consolidated results with charts; Firebase/EmailJS stack; focused specifically on 360 reviews rather than broader talent management .

- **[Moodle mod_threesixo](https://github.com/junpataleta/moodle-mod_threesixo)**  
  Open-source 360-degree feedback plugin for Moodle; provides a shared question bank, anonymous feedback options, self-review, configurable report releasing, and submission tracking within the Moodle course environment; useful for educational institutions or organizations already using Moodle for training .

- **[OKR Tracker (Oslo Kommune)](https://repos.ecosyste.ms/hosts/GitHub/topics/okr-tracker)**  
  Open-source front-end application for tracking Objectives and Key Results (OKRs) and KPIs for product teams, built with Vue and Google Firebase; useful for goal management and alignment, a component of talent management but not a complete platform .

### Additional Strong Open-Source Options

- **Farik** — Open-source HRMS (MIT) for growing teams with people directory, recruitment pipeline, employee helpdesk, attendance/leave, and dashboard analytics; Pro tier adds AI attrition prediction and burnout heatmaps; not a talent management platform per se, but provides HR data foundations .
- **GradEval360** — Open-source performance management platform for graduate assistants at Saint Louis University; covers expectation setting, self-evaluation, and review workflows; narrow scope but demonstrates open-source performance review patterns .

**Frameworks for building custom systems**: No open-source platform provides the full talent management lifecycle (performance reviews + competency frameworks + career development + succession). **HRPulsar** is the most ambitious emerging option but remains beta. For organizations assembling a stack: **MintHCM** for HR data and employee evaluations, **Avalia 360** or **Moodle mod_threesixo** for 360 feedback, **OKR Tracker** for goal alignment, and **Caliber** for manager-driven development conversations. Full talent management would require custom integration and development atop these foundations.

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- Talent management platforms handling performance reviews and employee development data must comply with applicable privacy regulations (GDPR, CCPA) and organizational data governance policies; performance data is highly sensitive and requires strict access controls.
- **Open-source talent management is significantly underdeveloped** compared to LMS, HRMS, or GRC—the projects listed above address specific components (360 feedback, OKRs, employee evaluations) but none provide a complete talent suite with performance cycles, competency frameworks, succession planning, and career pathing. Organizations requiring full talent management should budget for commercial platforms like Lattice, Culture Amp, or Workday.
- Verify license terms for commercial use; MintHCM uses AGPL-3.0 , Caliber and Avalia 360 are open-source (check repositories), and HRPulsar's licensing will be confirmed when its GitHub repo goes public .

---

**Made for HR leaders, talent development managers, people operations teams, and organizational development practitioners.**  
Let's make talent management more open, but with realistic expectations about what open-source can currently deliver.

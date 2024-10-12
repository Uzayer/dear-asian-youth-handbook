---
{"dg-publish":true,"permalink":"/engineering/operations/operations-overview/"}
---

## Operations Overview

Day-0 focuses on planning,
Day-1 on deployment,
Day-2 on ongoing maintenance and optimization.

Each phase plays a crucial role in ensuring that software is successfully delivered and maintained throughout its lifecycle.


# [[Engineering/Operations/Day 0 Operations\| Day 0]]

<div class="transclusion internal-embed is-loaded"><a class="markdown-embed-link" href="/engineering/operations/day-0-operations/#overview" aria-label="Open link"><svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="svg-icon lucide-link"><path d="M10 13a5 5 0 0 0 7.54.54l3-3a5 5 0 0 0-7.07-7.07l-1.72 1.71"></path><path d="M14 11a5 5 0 0 0-7.54-.54l-3 3a5 5 0 0 0 7.07 7.07l1.71-1.71"></path></svg></a><div class="markdown-embed">



# Overview
## Planning Phase
This phase is centered around planning and preparation before any actual software is developed or deployed.
## Responsibilities
- Define system architecture, ensuring it meets scalability, security, and compliance needs
- Identify and choose appropriate tools for infrastructure management, CI/CD, and monitoring.
- Plan the necessary infrastructure components, including cloud services or on-premises resources.
- Collaborate with stakeholders to determine what is needed for successful software performance
#todo

</div></div>


# [[Engineering/Operations/Day 1 Operations\| Day 1]]

<div class="transclusion internal-embed is-loaded"><a class="markdown-embed-link" href="/engineering/operations/day-1-operations/#overview" aria-label="Open link"><svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="svg-icon lucide-link"><path d="M10 13a5 5 0 0 0 7.54.54l3-3a5 5 0 0 0-7.07-7.07l-1.72 1.71"></path><path d="M14 11a5 5 0 0 0-7.54-.54l-3 3a5 5 0 0 0 7.07 7.07l1.71-1.71"></path></svg></a><div class="markdown-embed">



# Overview
## Deployment Phase
This phase transitions from planning to **actual deployment** of the software.
## Responsibilities
  - Create or configure new infrastructure as required for the application.
  - Oversee the deployment process, including starting deployments and managing rollbacks if issues arise.
  - Handle pre-deployment backups and post-deployment restores to ensure data integrity.
  - Ensure that the deployment pipeline works correctly and that the application meets quality standards before going live
#todo

</div></div>


## [[Engineering/Operations/Day 2 Operations\| Day 2]]

<div class="transclusion internal-embed is-loaded"><a class="markdown-embed-link" href="/engineering/operations/day-2-operations/#overview" aria-label="Open link"><svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="svg-icon lucide-link"><path d="M10 13a5 5 0 0 0 7.54.54l3-3a5 5 0 0 0-7.07-7.07l-1.72 1.71"></path><path d="M14 11a5 5 0 0 0-7.54-.54l-3 3a5 5 0 0 0 7.07 7.07l1.71-1.71"></path></svg></a><div class="markdown-embed">



# Overview
## Maintenance Phase
This phase involves ongoing maintenance and optimization of the deployed application.
## Responsibilities
  - Continuously monitor application performance and respond to incidents to maintain uptime.
  - Perform regular updates, apply security patches, and optimize system resources to ensure smooth operation.
- Gather user feedback and system performance data to inform future improvements and iterations of the software.
- Restore service in case of infrastructure failures by spinning up new resources or executing rollbacks as necessary
  #todo

</div></div>




## Performance Monitoring
### Metrics Tracking
#todo
The team uses metrics to monitor performance, identify bottlenecks, and implement improvements. This includes tracking velocity in Agile sprints and assessing the effectiveness of deployments.
### Feedback Loops
Continuous feedback mechanisms are in place to gather insights from all team members, ensuring that everyone has a voice in the operational processes.

## Cross-Functional Collaboration
Team members from different roles ([[Roles/Engineering/UI-UX Designer\|UI-UX Designer]], [[Roles/Engineering/Frontend Developer\|Frontend Developer]] for example) collaborate closely on projects. This helps in aligning technical specifications with design goals.
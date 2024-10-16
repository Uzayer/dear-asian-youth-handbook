---
{"dg-publish":true,"permalink":"/engineering/engineering-overview/","updated":"2024-10-12T19:36:26.239+06:00"}
---

DAY is a fully remote organization, with technology underpinning our every move. The DAY engineering team's mission is to create, maintain and scale DAY's digital infrastructure to support our members and mission. We prioritize user experience, and work with an agile philosophy. We ensure that software is not only delivered effectively but also maintained at high standards throughout its lifecycle.

Additionally, at DAY we believe that opensource software is the backbone of all digital infrastructure and a key factor in democratizing access to technology. We strive to implement opensource solutions in our stack, and as a result we hope to contribute back to the software and the shoulders on top of which we stand. 

# [[Engineering/Onboarding\|Onboarding]]
#todo

<div class="transclusion internal-embed is-loaded"><a class="markdown-embed-link" href="/engineering/onboarding/#overview" aria-label="Open link"><svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="svg-icon lucide-link"><path d="M10 13a5 5 0 0 0 7.54.54l3-3a5 5 0 0 0-7.07-7.07l-1.72 1.71"></path><path d="M14 11a5 5 0 0 0-7.54-.54l-3 3a5 5 0 0 0 7.07 7.07l1.71-1.71"></path></svg></a><div class="markdown-embed">



# Overview
Engineering roles come with an extensive training period on the stack for members before they are introduced and given access to the codebase. We regularly track progress for new members.

Refer to [Fall Recruitment Timeline](https://docs.google.com/document/d/1tIheQz-j-ikxgTW-kd9RsOML3uf8ej6QcbxRsjYuQc4/edit?usp=drive_link) for additional details.

</div></div>

# [[Roles/Engineering/Engineering Roles\|Engineering Roles]]
We have technical roles now. We might expand to non-technical ones in the future.
# Team Meetings:
We meet weekly to align on project goals, discuss progress, and address any challenges. We also encourage async 1:1s to facilitate collaboration
## Agile Workflow
We follow the Agile methodology for project management as it enables us to be flexible and develop iteratively. We regularly plan sprints and review sessions as requirements can change over a time.

Here's an intro explainer on [agile methodology](https://youtu.be/8eVXTyIZ1Hs)

# [[Engineering/Operations/Operations Overview\|Operations Overview]]

<div class="transclusion internal-embed is-loaded"><a class="markdown-embed-link" href="/engineering/operations/operations-overview/#operations-overview" aria-label="Open link"><svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="svg-icon lucide-link"><path d="M10 13a5 5 0 0 0 7.54.54l3-3a5 5 0 0 0-7.07-7.07l-1.72 1.71"></path><path d="M14 11a5 5 0 0 0-7.54-.54l-3 3a5 5 0 0 0 7.07 7.07l1.71-1.71"></path></svg></a><div class="markdown-embed">



## Operations Overview

Day-0 focuses on planning,
Day-1 on deployment,
Day-2 on ongoing maintenance and optimization.

Each phase plays a crucial role in ensuring that software is successfully delivered and maintained throughout its lifecycle.



</div></div>


# Key Practices
## Test Driven Development
We test our code at **every stage**, not just before pushing to production. This makes sure that the website and servers don't blow up when we try to merge.
## Development Stages
We want to have three instances running - Developer, QA and Production.
We're still getting started with the team so Dev and QA happen at the same time.
## CI/CD
#todo 
I'm thinking Gitlab  for DevSecOps.
## [[Engineering/Documentation Guidelines\|Documentation Guidelines]]
#todo
**All team members** are responsible for maintaining clear and comprehensive documentation of processes, designs, and implementation plans.

We use Writerside from Jetbrains.
## Code Style Guide
#todo 
There's style guides and conventions for each part of the stack. Each framework's documentation usually has best practices. Frontend masters also teaches how to write enterprise-grade code.

## Code Reviews
We regularly hold peer and lead code reviews to uphold code quality standards and foster collaboration among team members.
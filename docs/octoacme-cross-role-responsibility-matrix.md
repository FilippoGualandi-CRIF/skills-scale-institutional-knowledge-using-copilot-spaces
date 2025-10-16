# OctoAcme Cross-Role Responsibility Matrix

## Purpose
This document clarifies responsibilities and handoffs across roles to improve accountability, reduce gaps, and ensure smooth collaboration throughout the project lifecycle.

## How to Use This Matrix
- **R** = Responsible (owns the work)
- **A** = Accountable (final decision-maker)
- **C** = Consulted (provides input)
- **I** = Informed (kept updated)

---

## Project Initiation Phase

| Activity | Project Manager | Product Manager | Developer | QA/Testing | Scrum Master | Release Manager | Business Analyst | UX Designer | Stakeholder |
|----------|----------------|-----------------|-----------|------------|--------------|-----------------|------------------|-------------|-------------|
| Define problem statement | C | R/A | I | I | C | I | R | C | C |
| Create project one-pager | R | A | I | I | C | I | C | I | C |
| Identify stakeholders | R/A | C | I | I | I | I | C | I | C |
| Initial risk assessment | R/A | C | C | C | C | C | C | C | I |
| Resource allocation | R/A | C | I | I | C | I | I | I | A |

---

## Project Planning Phase

| Activity | Project Manager | Product Manager | Developer | QA/Testing | Scrum Master | Release Manager | Business Analyst | UX Designer | Stakeholder |
|----------|----------------|-----------------|-----------|------------|--------------|-----------------|------------------|-------------|-------------|
| Define scope and timeline | R/A | C | C | C | C | C | C | C | I |
| Prioritize backlog | C | R/A | C | C | C | I | C | C | C |
| Create sprint plan | C | C | R | C | R/A | I | I | I | I |
| Estimate effort | C | C | R/A | R | C | I | C | I | I |
| Define acceptance criteria | C | R | C | R | C | I | R | C | C |
| Plan test strategy | C | C | C | R/A | C | C | C | C | I |
| Design user experience | I | C | C | I | I | I | C | R/A | C |
| Document requirements | C | C | C | C | I | I | R/A | C | C |

---

## Execution & Development Phase

| Activity | Project Manager | Product Manager | Developer | QA/Testing | Scrum Master | Release Manager | Business Analyst | UX Designer | Stakeholder |
|----------|----------------|-----------------|-----------|------------|--------------|-----------------|------------------|-------------|-------------|
| Implement features | C | C | R/A | C | C | I | I | C | I |
| Write unit tests | I | I | R/A | C | C | I | I | I | I |
| Conduct code reviews | I | I | R/A | C | C | I | I | I | I |
| Manual/automated testing | C | C | C | R/A | C | C | C | C | I |
| Report and track defects | C | I | C | R/A | C | I | I | C | I |
| Facilitate standups | C | I | C | C | R/A | I | I | I | I |
| Remove blockers | R | C | I | I | R/A | C | C | I | C |
| Update project status | R/A | C | I | I | C | C | I | I | I |
| Clarify requirements | C | R | C | C | C | I | R/A | C | C |
| Validate UX implementation | I | C | C | C | I | I | I | R/A | I |

---

## Release & Deployment Phase

| Activity | Project Manager | Product Manager | Developer | QA/Testing | Scrum Master | Release Manager | Business Analyst | UX Designer | Stakeholder |
|----------|----------------|-----------------|-----------|------------|--------------|-----------------|------------------|-------------|-------------|
| Plan release schedule | C | C | C | C | I | R/A | I | I | C |
| Validate release readiness | C | C | C | R | C | R/A | C | C | I |
| Create release notes | C | R | C | C | I | R/A | C | C | I |
| Execute deployment | C | I | C | C | I | R/A | I | I | I |
| Smoke testing | C | C | C | R/A | I | C | I | C | I |
| Rollback (if needed) | C | C | C | C | I | R/A | I | I | I |
| Release communication | R | C | I | I | I | C | I | I | A |

---

## Retrospective & Continuous Improvement

| Activity | Project Manager | Product Manager | Developer | QA/Testing | Scrum Master | Release Manager | Business Analyst | UX Designer | Stakeholder |
|----------|----------------|-----------------|-----------|------------|--------------|-----------------|------------------|-------------|-------------|
| Facilitate retrospective | C | C | C | C | R/A | C | C | C | I |
| Capture learnings | R | C | C | C | C | C | C | C | C |
| Define action items | C | C | C | C | R | C | C | C | I |
| Track improvements | R/A | C | C | C | C | C | C | C | I |
| Measure impact | R | R/A | I | I | C | C | I | C | I |

---

## Key Handoff Points

### Requirements → Development
- **From**: Business Analyst, Product Manager
- **To**: Developers, UX Designer
- **Artifacts**: User stories, acceptance criteria, wireframes
- **Validation**: Requirements review meeting, backlog refinement

### Development → Testing
- **From**: Developers
- **To**: QA/Testing
- **Artifacts**: Completed features, test data, deployment instructions
- **Validation**: Code review approved, unit tests passing

### Testing → Release
- **From**: QA/Testing
- **To**: Release Manager
- **Artifacts**: Test reports, defect log, sign-off approval
- **Validation**: All acceptance criteria met, no critical defects

### Release → Operations
- **From**: Release Manager
- **To**: Stakeholders, Support Teams
- **Artifacts**: Release notes, runbooks, rollback procedures
- **Validation**: Deployment checklist completed, smoke tests passed

---

## Cross-Role Collaboration Best Practices

### Daily Collaboration
- **Scrum Master + Project Manager**: Align on impediments and cross-team dependencies
- **Product Manager + Business Analyst**: Validate requirements and business value
- **Developer + QA/Testing**: Pair on testability and defect reproduction
- **UX Designer + Developer**: Collaborate on implementation details

### Weekly Collaboration
- **Product Manager + UX Designer**: Review user research and design decisions
- **Project Manager + Release Manager**: Coordinate release planning and timelines
- **Business Analyst + Stakeholders**: Validate requirements and gather feedback

### As-Needed Collaboration
- **All roles**: Participate in retrospectives and continuous improvement discussions
- **Release Manager + Operations**: Coordinate deployments and incident response
- **Scrum Master + Team**: Address process improvements and team dynamics

---

## Using This Matrix

1. **Reference during project kickoff** to clarify role expectations
2. **Review when handoffs fail** to identify gaps in accountability
3. **Update based on retrospective findings** to improve collaboration
4. **Use in onboarding** to help new team members understand their responsibilities
5. **Adapt for your team's context** - this is a starting point, not a rigid framework

---

**Note**: While this matrix provides general guidance, specific responsibilities may vary by project size, team structure, and organizational context. Teams should adapt this framework to their needs.

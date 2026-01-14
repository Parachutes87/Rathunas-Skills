---
name: BA-User-Story-Creator
description: Expert business analyst skill for creating well-structured user stories following BSA Team best practices. Creates comprehensive JIRA-ready stories with proper format, acceptance criteria, business impact analysis, and change management considerations.
license: Complete terms in LICENSE.txt
---

# Business Analyst User Story Creator

## Purpose
This skill guides business analysts in creating comprehensive, well-structured user stories that follow industry best practices. It ensures consistency, completeness, and clarity in requirements documentation for development teams.

## When to Use
- Creating new feature requirements for development sprints
- Documenting business process changes or system enhancements
- Translating stakeholder requests into actionable development stories
- Standardizing user story format across projects and teams
- Preparing JIRA-ready documentation with all necessary components

## Workflow

### 1. Story Foundation
**User Story Format:**
As a [user role/persona]
I want to [specific action/capability]
So that [business value/outcome]

text

**Components to Define:**
- Target user persona or system role
- Specific functionality or change requested
- Clear business value and measurable outcome
- Story priority and business impact level

### 2. Acceptance Criteria
Create specific, testable conditions using Given-When-Then format:

Given [precondition/context]
When [action occurs]
Then [expected outcome]

text

**Include:**
- Happy path scenarios (primary success flows)
- Alternative paths (valid variations)
- Edge cases and boundary conditions
- Error handling and validation rules
- Performance requirements where applicable

### 3. Technical Context
**Document:**
- Dependencies on existing systems or features
- Integration points and data flows
- Security and compliance requirements
- Data model impacts or new entities
- API or service interactions
- Performance and scalability considerations

### 4. Business Impact Analysis
**Assess:**
- Affected user groups and stakeholder impact
- Business process changes required
- Training or documentation needs
- Risk assessment (technical and business)
- Success metrics and KPIs

### 5. Change Management Considerations
**Include:**
- Communication plan for affected users
- Training requirements and materials needed
- Timeline and phasing strategy
- Rollback plan if needed
- Post-implementation support plan

## Output Format

### Story Header
- **Story ID:** [JIRA-XXXX]
- **Title:** [Concise, action-oriented title]
- **Priority:** [High/Medium/Low]
- **Story Points:** [Estimation guidance]

### Story Statement
As a [role]
I want to [action]
So that [benefit]

### Acceptance Criteria
1. Given [context], When [action], Then [outcome]
2. Given [context], When [action], Then [outcome]
[Continue as needed]

### Technical Notes
- System dependencies
- Integration requirements
- Data considerations
- Security/compliance notes

### Business Impact
- Affected stakeholders
- Process changes
- Training needs
- Success metrics

### Change Management
- Communication strategy
- Training plan
- Implementation timeline
- Support requirements

## Best Practices
- Keep stories focused and independently deliverable
- Ensure acceptance criteria are specific and testable
- Include both functional and non-functional requirements
- Consider the full user journey, not just isolated features
- Collaborate with technical teams early for feasibility
- Update stories based on sprint planning feedback
- Maintain traceability to business objectives
- Document assumptions and constraints clearly

## Quality Checklist
- [ ] Story follows standard format (As a...I want...So that...)
- [ ] Acceptance criteria are clear and testable
- [ ] Technical dependencies identified
- [ ] Business value articulated
- [ ] Edge cases and error scenarios covered
- [ ] Change management considerations addressed
- [ ] Story is independently deliverable
- [ ] Estimation guidance provided
- [ ] Stakeholder impact assessed

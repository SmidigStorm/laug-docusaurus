---
sidebar_position: 1
sidebar_label: Team & Product Structure
title: Team and Product Group Structure
---

# Team and Product Group Structure

This lens examines how teams are organized, how they relate to products and services, and how work flows through the organization.

## Overview

The way teams are structured and organized has a profound impact on an organization's ability to deliver value. This lens helps you understand and optimize your team topology - the arrangement and interaction of teams within your organization.

---

## Theory

### Fundamental Concepts

#### Team Topology
Team topology refers to the organizational design of teams and their interaction modes. It encompasses:
- Team types and their purposes
- Team boundaries and interfaces
- Communication and collaboration patterns
- Dependencies and handoffs

#### Conway's Law
"Organizations which design systems are constrained to produce designs which are copies of the communication structures of these organizations." 
- Melvin Conway, 1967

This fundamental principle means that your team structure will directly influence your system architecture.

#### Cognitive Load
Teams have limited cognitive capacity. Effective team design considers:
- **Intrinsic cognitive load** - fundamental complexity of the problem space
- **Extraneous cognitive load** - complexity from the way tasks are presented
- **Germane cognitive load** - complexity from learning and improvement

### Types of Teams

#### Stream-Aligned Teams
- Aligned to a flow of work from a business domain
- Responsible for end-to-end delivery
- Have clear, valuable outcomes to achieve

#### Platform Teams
- Provide underlying platforms for stream-aligned teams
- Reduce cognitive load by handling infrastructure complexity
- Enable stream-aligned teams to deliver faster

#### Enabling Teams
- Help stream-aligned teams overcome obstacles
- Provide expertise and guidance
- Typically work temporarily with other teams

#### Complicated Subsystem Teams
- Handle parts of the system requiring specialized knowledge
- Reduce cognitive load of stream-aligned teams
- Focus on specific technical areas

---

## Tools

### Team Topology Mapping

A visual tool for understanding your current team structure:

1. **Identify all teams** in your organization
2. **Classify each team** using the four fundamental types
3. **Map dependencies** between teams
4. **Identify interaction modes**:
   - Collaboration (working closely together)
   - X-as-a-Service (one team provides service to another)
   - Facilitating (one team helps another)

### Value Stream Mapping

Visualize how work flows through your teams:

1. **Map the value stream** from idea to customer value
2. **Identify which teams** are involved at each stage
3. **Measure wait times** between teams
4. **Find bottlenecks** and constraints

### Team Cognitive Load Assessment

Evaluate if teams are overloaded:

1. **Domain complexity** - How complex is the business domain?
2. **Technical complexity** - How complex are the technical solutions?
3. **Team experience** - How experienced is the team?
4. **Team stability** - How stable is team membership?
5. **Dependencies** - How many dependencies does the team have?

Rate each factor 1-5 and identify teams with high cognitive load.

### Team API Canvas

Define clear interfaces between teams:
- **Purpose**: What is the team's mission?
- **Responsibilities**: What does the team own?
- **Consumers**: Who uses the team's services?
- **Provided services**: What does the team offer?
- **Quality metrics**: How is success measured?

---

## Patterns & Anti-patterns

### Patterns (Best Practices)

#### ✅ Stream-Aligned Teams with Clear Domains
**Context**: Organizations need to deliver value quickly and independently

**Solution**: Create teams aligned to business value streams with:
- Clear ownership of business outcomes
- Minimal dependencies on other teams
- Authority to make decisions within their domain
- Direct contact with users/customers

**Benefits**:
- Faster delivery
- Higher quality
- Better customer focus
- Increased team motivation

#### ✅ Platform as a Product
**Context**: Multiple teams need similar infrastructure or tooling

**Solution**: Create platform teams that:
- Treat the platform as a product with internal customers
- Focus on developer experience
- Provide self-service capabilities
- Maintain clear documentation and APIs

**Benefits**:
- Reduced cognitive load for stream teams
- Consistent infrastructure
- Faster onboarding
- Economy of scale

#### ✅ Enabling Teams for Capability Building
**Context**: Teams need to adopt new practices or technologies

**Solution**: Form temporary enabling teams that:
- Coach and mentor other teams
- Transfer knowledge and skills
- Help establish new practices
- Gradually reduce involvement as teams become self-sufficient

**Benefits**:
- Faster capability development
- Consistent practices across teams
- Reduced external dependency

### Anti-patterns (Pitfalls to Avoid)

#### ❌ Component Team Proliferation
**Problem**: Having too many teams organized around technical components or layers

**Why it happens**:
- Following system architecture rather than value streams
- Technical specialists wanting to work together
- Traditional IT organizational structures

**Consequences**:
- High coordination overhead
- Slow delivery due to dependencies
- Unclear ownership of business outcomes
- Increased wait times and handoffs

**Alternative**: Reorganize into stream-aligned teams with full-stack capabilities

#### ❌ Matrix Organization Confusion
**Problem**: Team members report to multiple managers with conflicting priorities

**Consequences**:
- Unclear accountability
- Conflicting priorities
- Reduced team cohesion
- Slower decision-making

**Alternative**: Clear, single reporting lines with dotted-line relationships where needed

#### ❌ Feature Factory Teams
**Problem**: Teams focused solely on output without understanding outcomes

**Consequences**:
- Building features nobody uses
- Lack of ownership and motivation
- Missing learning opportunities
- Poor product quality

**Alternative**: Give teams ownership of outcomes, not just outputs

#### ❌ Shared Team Members
**Problem**: Individuals split across multiple teams

**Consequences**:
- Context switching overhead
- Reduced team cohesion
- Bottlenecks when person is unavailable
- Difficulty in planning and commitment

**Alternative**: Dedicated team members with clear home teams

---

## Assessment Questions

Use these questions to evaluate your current team and product structure:

1. Can teams deliver value independently, or do they frequently wait for other teams?
2. Do teams understand and own business outcomes, or just technical components?
3. Is the cognitive load on teams manageable, or are they overwhelmed?
4. Are team boundaries clear and well-defined?
5. Do teams have the skills and authority to deliver end-to-end?
6. How many handoffs are required to deliver value to customers?
7. Are platform capabilities provided as self-service, or do they require coordination?
8. Do teams have direct contact with their users/customers?

---

## Next Steps

After analyzing your organization through this lens:

1. **Map your current state** using the tools provided
2. **Identify anti-patterns** in your current structure
3. **Design target state** based on patterns and principles
4. **Plan transformation** with incremental steps
5. **Measure impact** on delivery speed and quality

---

## Further Reading

- "Team Topologies" by Matthew Skelton and Manuel Pais
- "The DevOps Handbook" by Gene Kim, Patrick Debois, John Willis, and Jez Humble
- "Accelerate" by Nicole Forsgren, Jez Humble, and Gene Kim
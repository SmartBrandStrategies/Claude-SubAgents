# Claude Code Subagents

A comprehensive collection of specialized AI subagents for Claude Code, designed to enhance development workflows through role-based, context-aware assistance.

## Overview

This repository contains 12 specialized subagents that can be invoked within Claude Code to provide expert-level assistance across different software engineering disciplines. Each subagent is crafted with specific expertise, workflows, and output templates to deliver focused, actionable results.

## Available Subagents

### 🏗️ Architecture & Development
- **[senior-swe-architect](senior-swe-architect.md)** - System design, architecture decisions, technical leadership
- **[backend-dev](backend-dev.md)** - API development, database design, server-side logic
- **[frontend-dev](frontend-dev.md)** - UI/UX engineering, component architecture, performance optimization

### 🔧 Engineering & Operations  
- **[devops-eng](devops-eng.md)** - Infrastructure, CI/CD, deployment automation
- **[qa-eng](qa-eng.md)** - Testing strategies, quality assurance, test automation
- **[security-eng](security-eng.md)** - Security audits, threat modeling, compliance

### 🚀 Specialized Roles
- **[codebase-maintainer](codebase-maintainer.md)** - Code quality, refactoring, technical debt management
- **[debugger](debugger.md)** - Issue diagnosis, root cause analysis, problem resolution
- **[error-pattern-analyst](error-pattern-analyst.md)** - Error analysis, pattern recognition, systematic debugging

### 📋 Strategy & Management
- **[pm-agent](pm-agent.md)** - Project management, requirements analysis, stakeholder communication
- **[prod-strategist](prod-strategist.md)** - Product strategy, roadmap planning, business alignment
- **[code-roaster](code-roaster.md)** - Code review, constructive feedback, improvement suggestions

## Usage

### In Claude Code
Invoke any subagent using the Task tool:

```
Use the Task tool with subagent_type: "backend-developer" 
Description: "Create user authentication API"
Prompt: "Design and implement a secure JWT-based authentication system with rate limiting and multi-tenant support"
```

### Key Features
- **Specialized Expertise**: Each agent focuses on specific domain knowledge
- **Consistent Workflows**: Structured approaches with clear inputs/outputs  
- **Integration Patterns**: Agents work together through defined handoff points
- **Template Outputs**: Standardized deliverable formats
- **Best Practices**: Industry-standard patterns and security considerations

## Agent Architecture

Each subagent follows a consistent structure:

- **Role Definition**: Clear scope and responsibilities
- **Specialties**: Technical expertise areas
- **Input/Output Specs**: What the agent expects and produces
- **Synergies**: How it collaborates with other agents
- **Workflows**: Step-by-step processes
- **Constraints**: Boundaries and limitations
- **Templates**: Standardized output formats

## Integration Patterns

Agents are designed to work together in common development workflows:

```
Requirements → PM Agent → Senior Architect → Backend/Frontend Devs
                ↓                              ↓
          QA Engineer ← DevOps Engineer ← Security Engineer
```

## Best Practices

1. **Choose the Right Agent**: Match the task to the agent's specialized expertise
2. **Provide Context**: Include relevant project details and constraints
3. **Chain Agents**: Use multiple agents for complex, multi-stage tasks
4. **Review Outputs**: Validate deliverables against your specific requirements

## Contributing

When adding new subagents:

1. Follow the established markdown structure
2. Define clear role boundaries and expertise areas
3. Specify integration points with existing agents
4. Include practical workflow examples
5. Provide output templates and examples

## License

This collection is part of the SmartBrandStrategies AI Worker project and follows the same licensing terms.
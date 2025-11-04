---
title: "[AI-ML SYSTEMS 2025] Zero to Production: Building Secure, ScalableMCP Servers and AI Agents with Open-Source Templates"
authors:
  - admin
event: 5 International Conference on Al-ML Systems
event_url: https://www.aimlsystems.org/2025/workshop-agentic-ai/
location: Bangalore, India


summary: Building Secure, ScalableMCP Servers and AI Agents with Open-Source Templates
abstract: "The gap between experimental AI agents and production-ready systems remains a critical challenge for enterprises adopting agentic solutions for software engineering with 95% of the GenAI pilots failing to make it to production. This hands-on tutorial demonstrates how applying rigorous software engineering practices to AI agent development can transform experimental prototypes into enterprise-ready systems that meet strict reliability, security, and performance requirements."

# Talk start and end times.
#   End time can optionally be hidden by prefixing the line with `#`.
date: "2025-10-08"
date_end: "2025-10-08"
all_day: false

# Schedule page publish date (NOT talk date).
publishDate: "2025-10-08T00:00:00Z"


tags: [ aimlsystems2025 ]

# Is this a featured talk? (true/false)
featured: true



links:
- name: mcp-code
  url: https://github.com/redhat-data-and-ai/template-mcp-server
- name: agent-code
  url: https://github.com/redhat-data-and-ai/template-agent
- name: ui-code
  url: https://github.com/redhat-data-and-ai/template-ui
url_slides: "talks/aimlsystems2025.pdf"
#url_video: ""

# Markdown Slides (optional).
#   Associate this talk with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
#slides: files/cv.pdf

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
#projects:
#- internal-project

# Enable math on this page?
math: true
---

<h3> Description </h3>

Our tutorial presents two battle-tested, extensible templates (MCP and AI Agents) that have been developed and refined through real-world production deployments. These templates, openly available, provide a proven architectural foundation that accelerates the journey from concept to production while enforcing security best practices and operational excellence.

Participants will gain practical experience building a complete agentic ecosystem comprising:
Part 1: MCP Server Development - Using our open-source template-mcp-server repository, attendees will create robust MCP servers that enable AI agents to interact securely with external systems. The template includes FastAPI-based HTTP servers, modular tool systems, comprehensive testing frameworks, and enterprise deployment configurations supporting OpenShift/Kubernetes environments.
Part 2: Agent Implementation - Leveraging our  template-agent framework, participants will build production-ready conversational agents with real-time streaming capabilities, multi-turn conversation management, and enterprise integration features including SSO authentication, PostgreSQL persistence, and Langfuse observability.

<h3> Key Technical Contributions </h3>

- *Rapid Deployment Framework*: Automation scripts that transform base templates into domain-specific implementations, reducing development time from weeks to hours
- *Security-First Architecture*: Rootless containers using Red Hat UBI, comprehensive authentication patterns, and secure tool execution environments
- *Production Observability*: Built-in tracing, logging, and monitoring capabilities essential for maintaining agents in production
- *Universal Compatibility*: Tool-first design ensuring seamless integration with LangGraph, CrewAI, FastMCP, and other major agent frameworks
- *Enterprise-Ready Features*: Session management, checkpointing, error recovery, and scalable deployment patterns tested in production environments

<h3> Practical Outcomes </h3>

Each participant will complete the tutorial with:
- A fully functional MCP server with custom tools deployed to a container platform
- A streaming AI agent with enterprise authentication and conversation persistence
- Access to reusable template repositories with comprehensive documentation
- Automation scripts for rapid customization and deployment 
- Best practices documentation for maintaining agentic systems in production

By providing open-source, extensible templates rather than rigid frameworks, we enable teams to rapidly prototype while maintaining production standards, significantly accelerating the adoption of agentic solutions in software engineering workflows.

<h3> Open Source Commitment </h3>

Both templates are actively maintained and openly available:
- MCP Server Template: https://github.com/redhat-data-and-ai/template-mcp-server
- Agent Template: https://github.com/redhat-data-and-ai/template-agent

These repositories include comprehensive documentation, example implementations, and deployment manifests, enabling participants to immediately apply tutorial learnings in their organizations.

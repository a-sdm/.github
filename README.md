# ASDM .github Repository

This repository contains shared GitHub configurations and resources for the [ASDM (AI-Powered System Development Methodology)](https://asdm.ai) organization.

## About ASDM

ASDM (AI-Powered System Development Methodology) is a modern framework designed to integrate artificial intelligence throughout the entire software development lifecycle. Unlike traditional methodologies that treat AI as just an add-on tool, ASDM positions AI as a central collaborator and teammate to achieve better productivity, innovation, and quality in software projects.

### Core Values

- **Efficiency**: Streamline workflows and reduce repetitive effort with intelligent automation
- **Quality**: Improve reliability through AI-assisted testing, reviews, and analysis
- **Innovation**: Enable faster exploration and iteration with AI as a creative partner
- **Scalability**: Design systems and processes that adapt as AI capabilities evolve
- **Human-AI Collaboration**: Keep humans in control while using AI for high-leverage support
- **Outcome-Driven**: Measure what matters and continuously optimize for results
- **Continuous Learning**: Build feedback loops so people, processes, and models improve over time
- **Ethical AI**: Ensure transparency, fairness, privacy, and accountability in AI use

### Key Principles

- **AI-First Philosophy**: AI is a core driver in every phase of software creation, not just an assistant
- **Entire Lifecycle Integration**: AI is integrated across planning, design, architecture, implementation, testing, delivery, deployment, and continuous improvement
- **Context Management**: Preserving the "why" behind every technical decision to reduce technical debt
- **Human Oversight**: Humans remain critical decision-makers while AI accelerates execution and feedback loops

### Benefits

- **Faster delivery** without sacrificing quality or maintainability
- **Reduced technical debt** by aligning systems with well-documented context and rationale
- **Continuous improvement** as AI learns from each cycle and helps teams iterate more intelligently

## ASDM Project Ecosystem

The ASDM organization contains several key projects that work together to provide a complete AI-powered development methodology:

### asdm-official-website

The official ASDM documentation website built with Vite + React + TypeScript and Tailwind CSS.

- **Purpose**: Provides comprehensive documentation, guides, and resources for ASDM methodology
- **Features**:
  - Landing page with ASDM concept introduction
  - Documents page that renders Markdown content at runtime
  - Hierarchical document structure with sidebar navigation
  - GitHub-flavored Markdown support with code highlighting
- **Tech Stack**: React 19, TypeScript, Vite, TailwindCSS, react-markdown, Prism
- **Repository**: `github/asdm-official-website`

### asdm-bootstrapper

A command-line interface (CLI) tool that helps developers quickly set up their development environment for ASDM projects.

- **Purpose**: Automates the process of downloading and configuring necessary toolsets
- **Features**:
  - **List Command**: View all available ASDM toolsets from the registry
  - **Install Command**: Download and install specific toolsets to your workspace
  - **Local Storage**: Toolsets installed to `.asdm/toolsets/{toolset-id}`
  - **GitHub Integration**: Fetches toolsets directly from GitHub repository
- **Registry System**: JSON-based registry (`registry.json`) defining available toolsets with metadata
- **Tech Stack**: Node.js, TypeScript
- **Repository**: `github/asdm-bootstrapper`

### asdm-admin

ASDM Admin is a modern management backend system providing administrative interface and monitoring capabilities for the ASDM platform.

- **Purpose**: Centralized management console for ASDM platform operations
- **Architecture**: Frontend-backend separated architecture
- **Backend Services**:
  - User & Permission Management (asdm-admin-user)
  - Enterprise Specification Management (asdm-admin-spec)
  - R&D Process Tracking (asdm-admin-process)
  - Intermediate Deliverable Management (asdm-admin-artifact)
  - Observability Management (asdm-admin-observability)
  - System Settings & Configuration (asdm-admin-setting)
  - System Monitoring & Logging (asdm-admin-monitor)
- **Frontend Tech Stack**: React 19, TypeScript, Vite, TailwindCSS 4, React Router 7
- **Frontend Dependencies**: ApexCharts, FullCalendar, React DnD, React Dropzone, React JVectorMap
- **Repository**: `ads/asdm-admin`

## Purpose of This Repository

The `.github` repository serves as a special organizational repository that provides:

- **Default community health files**: Shared templates and guidelines for all repositories in the ASDM organization
- **Reusable workflows**: GitHub Actions workflows that can be referenced across multiple projects
- **Organization-wide configurations**: Standardized settings that promote consistency and best practices

By centralizing these resources, we ensure that all ASDM projects follow consistent practices aligned with our AI-first methodology.

## What's Included

This repository may contain:

- **Issue Templates**: Standardized templates for bug reports, feature requests, and other issue types
- **Pull Request Templates**: Guidelines for contributing code changes
- **GitHub Actions Workflows**: Reusable automation workflows
- **Community Guidelines**: Code of conduct, contributing guidelines, and security policies
- **Documentation**: Standards and best practices for ASDM projects

## Using These Resources

Resources in this repository are automatically available to all repositories in the ASDM organization. When a repository doesn't have its own community health files, GitHub will use the defaults from this repository.

For more information about ASDM and our approach to AI-powered software development, visit [asdm.ai](https://asdm.ai).

## Contributing

Improvements to our shared resources are welcome! Please follow ASDM principles when proposing changes:

1. Clearly document the context and rationale for your changes
2. Consider how AI can enhance or automate the proposed workflow
3. Ensure changes align with our AI-first development philosophy

## License

Unless otherwise noted, the content in this repository is available for use by ASDM organization members and collaborators.
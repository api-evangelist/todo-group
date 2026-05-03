# TODO Group (todo-group)
The TODO Group is an open community of practitioners under the Linux Foundation who collaborate on best practices, tools, and guidance for running successful Open Source Program Offices (OSPOs). It provides open source tooling including Repolinter for repository linting, the OSPO Landscape mapping OSPO adopters and tools, comprehensive OSPO guides and case studies, and OSPOlogy community programs. The TODO Group serves organizations managing enterprise open source strategies across 120+ member organizations.

**URL:** [https://todogroup.org/](https://todogroup.org/)

## Tags:

 - Community, Linux Foundation, Open Source, OSPO

## Timestamps

- **Created:** 2026-03-16
- **Modified:** 2026-05-03

## Tools and Resources

### Repolinter
Repolinter is an open source linting tool for repositories that validates compliance with open source best practices. It checks repositories for standard files like LICENSE, README, CONTRIBUTING, and CODE-OF-CONDUCT, and supports configurable rulesets. Available as a CLI tool (repolinter lint) and a JavaScript API for programmatic integration. Installable via npm as the repolinter package.

**Human URL:** [https://github.com/todogroup/repolinter](https://github.com/todogroup/repolinter)

#### Tags:

 - Linting, Open Source, Repository, Compliance

#### Properties

- [Documentation](https://github.com/todogroup/repolinter)
- [GitHubRepository](https://github.com/todogroup/repolinter)
- [NpmPackage](https://www.npmjs.com/package/repolinter)

### Repolinter Action
A GitHub Action that runs Repolinter on repositories as part of CI/CD workflows. Validates repositories against configurable rulesets to enforce open source compliance policies. Supports outputting results as exit codes for PR status checks or creating GitHub issues for non-intrusive notifications. Originally created by New Relic, maintained by TODO Group.

**Human URL:** [https://github.com/todogroup/repolinter-action](https://github.com/todogroup/repolinter-action)

#### Tags:

 - GitHub Actions, Linting, CI/CD, Compliance

#### Properties

- [Documentation](https://github.com/todogroup/repolinter-action)
- [GitHubRepository](https://github.com/todogroup/repolinter-action)
- [GitHubMarketplace](https://github.com/marketplace/actions/repolinter-action)

### OSPO Landscape
An interactive landscape mapping the Open Source Program Office ecosystem, including OSPO adopter organizations and tools supporting OSPO operations. Data is maintained in landscape.yml and browsable at landscape.todogroup.org. Modeled after the CNCF landscape approach, covering companies, governments, academic institutions, and supporting tooling.

**Human URL:** [https://landscape.todogroup.org/](https://landscape.todogroup.org/)

#### Tags:

 - Landscape, OSPO, Ecosystem, Data

#### Properties

- [Documentation](https://landscape.todogroup.org/)
- [GitHubRepository](https://github.com/todogroup/ospolandscape)
- [Website](https://landscape.todogroup.org/)

### OSPO Guides
A comprehensive collection of 23+ practitioner guides covering all aspects of running Open Source Program Offices. Topics include creating an OSPO, setting open source strategy, measuring program success, managing career development, recruiting open source developers, legal compliance, and community engagement. All guides are open source and community-contributed.

**Human URL:** [https://todogroup.org/guides/](https://todogroup.org/guides/)

#### Tags:

 - Guides, OSPO, Best Practices, Documentation

#### Properties

- [Documentation](https://todogroup.org/guides/)
- [GitHubRepository](https://github.com/todogroup/guides)

### OSPOlogy
The OSPOlogy program provides monthly community webinars, working group meetings, and collaborative sessions focused on OSPO practices and challenges. It serves as the primary community engagement platform for TODO Group members and OSPO practitioners worldwide, covering topics from OSPO maturity models to specific industry challenges.

**Human URL:** [https://community.linuxfoundation.org/todo-group-ospology/](https://community.linuxfoundation.org/todo-group-ospology/)

#### Tags:

 - Community, Webinars, OSPO, Education

#### Properties

- [Documentation](https://github.com/todogroup/ospology)
- [GitHubRepository](https://github.com/todogroup/ospology)
- [Website](https://community.linuxfoundation.org/todo-group-ospology/)

### OSPO Career Path
An open source career development framework defining roles, skills, and progression paths for OSPO professionals. Covers job functions from open source program manager to legal counsel, providing organizations with a structured approach to building and growing OSPO teams with defined competencies and seniority levels.

**Human URL:** [https://github.com/todogroup/ospo-career-path](https://github.com/todogroup/ospo-career-path)

#### Tags:

 - Career Development, OSPO, Human Resources, Skills Framework

#### Properties

- [Documentation](https://github.com/todogroup/ospo-career-path)
- [GitHubRepository](https://github.com/todogroup/ospo-career-path)

## Common Properties

- [Website](https://todogroup.org/)
- [Documentation](https://todogroup.org/guides/)
- [GitHub Organization](https://github.com/todogroup)
- [Slack](https://slack.todogroup.org/)
- [Newsletter](https://todogroup.org/community/newsletter/)

## Features

| Name | Description |
|------|-------------|
| Repolinter CLI | Command-line tool for linting open source repositories against configurable compliance rulesets. |
| Repolinter JavaScript API | Programmatic Node.js API for integrating repository linting into custom workflows and tools. |
| Repolinter GitHub Action | CI/CD integration for automated repository compliance checks in GitHub workflows. |
| OSPO Landscape | Interactive ecosystem map of OSPO adopter organizations and supporting tools worldwide. |
| OSPO Guides | Comprehensive practitioner guides covering all aspects of running an Open Source Program Office. |
| OSPOlogy Webinars | Monthly community webinars and working group sessions for OSPO practitioners. |
| OSPO Career Path | Structured career framework defining roles, skills, and progression paths for OSPO professionals. |
| Awesome OSPO | Curated list of tools and resources for open source program management. |

## Use Cases

| Name | Description |
|------|-------------|
| Repository Compliance Automation | Use Repolinter and Repolinter Action to automate checks that all repos have required open source files and follow organizational policies. |
| OSPO Program Launch | Use TODO Group guides and case studies to establish and launch a new Open Source Program Office within an organization. |
| OSPO Ecosystem Mapping | Reference the OSPO Landscape to discover tools, peer organizations, and adopters in the OSPO ecosystem. |
| Developer Career Development | Apply the OSPO Career Path framework to define roles and progression for open source professionals. |
| Open Source Strategy Development | Leverage TODO Group best practice guides to define and implement an enterprise open source strategy. |
| Community Building | Participate in OSPOlogy webinars and TODO Group working groups to learn from and contribute to the OSPO community. |

## Integrations

| Name | Description |
|------|-------------|
| GitHub Actions | Repolinter Action integrates repository linting into GitHub CI/CD workflows. |
| Linux Foundation | TODO Group operates under the Linux Foundation governance and community infrastructure. |
| CNCF Landscape | OSPO Landscape follows the CNCF landscape pattern for ecosystem visualization. |
| Node.js / npm | Repolinter is distributed as an npm package and supports Node.js 12+ runtime. |
| OpenSSF | Collaboration with Open Source Security Foundation on best practices for open source security and compliance. |

## Artifacts

Machine-readable specification artifacts organized by format.

### Rules

- [TODO Group Spectral Rules](rules/todo-group-spectral-rules.yml)

## Vocabulary

- [TODO Group Vocabulary](vocabulary/todo-group-vocabulary.yaml) — Unified taxonomy mapping 7 resources, 7 actions, 3 workflows, and 5 personas across OSPO operational and capability dimensions

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com

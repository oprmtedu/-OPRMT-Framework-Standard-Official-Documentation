# Tools

**Document ID:** OPRMT-SPEC-TOOLS-v1.0  
**Document Type:** Framework Specification  
**Framework:** OPRMT™  
**Component:** Tools  
**Owner:** Michael W. Fleming  
**Repository:** OPRMT™ Framework Standard Official Documentation  
**Recommended File Name:** tools.md  
**Recommended File Path:** /specification/tools.md  
**Status:** Draft / Ready for Repository Use  
**Version:** 1.0  
**Last Updated:** 2026-05-07  

---

## 1. Purpose

The **Tools** component defines the supporting resources, platforms, systems, files, references, applications, and execution environments required to complete a prompt, workflow, or structured AI task.

In the OPRMT™ Framework, **Tools** answers the question:

> What resources, systems, or platforms should support execution?

The Tools section prevents disconnected execution, missing reference material, unsupported assumptions, and incomplete implementation by identifying the resources that should be used, referenced, connected, or considered during execution.

Tools are not the task itself.  
Tools are the supporting execution infrastructure.

---

## 2. Framework Placement

OPRMT™ stands for:

| Letter | Component | Function |
|---|---|---|
| O | Objective | Defines the goal |
| P | Parameters | Defines the rules, context, boundaries, and constraints |
| R | Results | Defines the required output |
| M | Method | Defines the execution process |
| T | Tools | Defines supporting resources, systems, and references |

The **Tools** component is the fifth core element of the OPRMT™ Framework.

It connects the prompt to the resources needed for accurate, usable, and implementation-ready execution.

---

## 3. Definition

**Tools** are the supporting systems, resources, files, platforms, applications, references, datasets, templates, automations, or environments that assist execution.

A proper Tools section defines:

- Required platforms
- Required files
- Reference documents
- Software systems
- Data sources
- Templates
- APIs
- Automations
- Repository locations
- Output destinations
- Design tools
- Development environments
- Validation tools
- Collaboration tools
- Publishing tools
- Optional supporting resources

In practical terms, Tools tell the AI system what resources should be used or considered while completing the task.

---

## 4. Core Function

The core function of Tools is to connect the prompt to the execution environment.

An Objective defines what needs to be accomplished.  
Parameters define the rules and boundaries.  
Results define what must be returned.  
Method defines how the task should be executed.  
Tools define what resources support the execution.

Without a clearly defined Tools section, the AI may:

- Ignore required documents
- Use the wrong platform assumptions
- Produce outputs that do not fit the destination system
- Fail to reference required materials
- Miss available templates
- Generate content incompatible with the user’s software stack
- Produce implementation steps for the wrong toolset
- Create unsupported or non-executable workflows
- Assume tools that are not available

A structured Tools section reduces execution gaps by identifying the systems and resources required for successful completion.

---

## 5. Tools in Plain Language

The Tools section tells the AI:

> “Use or account for these resources while doing the work.”

It does not only name software.

It defines the support environment for the task.

A strong Tools section makes the output more accurate, deployable, compatible, and implementation-ready.

---

## 6. Why Tools Matter

The Tools component is essential because many AI outputs fail not because the idea is wrong, but because the output does not fit the platform, file system, workflow, or technical environment where it will be used.

Tools improve:

- Execution accuracy
- Platform compatibility
- Workflow implementation
- Automation readiness
- Documentation alignment
- Repository consistency
- Output usability
- System integration
- Validation quality
- Deployment readiness
- Business execution reliability

In business, education, governance, automation, software, and documentation environments, the Tools component ensures that the AI output is designed for the actual resources available.

---

## 7. Required Elements of a Tools Section

A complete Tools section should include the following elements.

| Element | Description |
|---|---|
| Required Tools | Defines tools that must be used |
| Optional Tools | Defines tools that may support execution |
| Reference Materials | Defines documents, files, or repositories to reference |
| Platform Constraints | Defines platform-specific limitations or formatting needs |
| Input Sources | Defines where information should come from |
| Output Destination | Defines where the result will be used or placed |
| Automation Support | Defines scripts, APIs, integrations, or workflow tools |
| Validation Tools | Defines tools used to test, review, or verify the output |
| Access Requirements | Defines required permissions, accounts, or credentials |
| Tool Limitations | Defines known limits or prohibited tool use |

Not every prompt requires every element, but implementation-heavy, technical, repository-based, business-critical, or platform-specific prompts should include most or all of them.

---

## 8. Required Tools

Required tools are resources that must be used or accounted for during execution.

Examples include:

- GitHub
- Google Drive
- Google Docs
- Google Sheets
- Google Apps Script
- Payhip
- Canva
- Figma
- Notion
- Airtable
- Zapier
- Make
- ChatGPT
- Claude
- ElevenLabs
- WordPress
- VS Code
- Linux terminal
- Markdown editor
- JSON validator
- Browser developer tools
- API documentation
- Repository templates
- Internal brand files

### Example

Use GitHub Markdown conventions and structure the output for placement in the official OPRMT™ documentation repository.

### Stronger Example

Use GitHub as the target repository environment, Markdown as the documentation format, and the OPRMT™ Framework Standard Official Documentation repository as the final destination.

---

## 9. Optional Tools

Optional tools are resources that may help execution but are not required.

Examples include:

- Canva for visual assets
- Figma for diagrams
- Notion for planning
- Google Sheets for tracking
- Airtable for structured records
- Zapier for automation
- Make for workflow routing
- Grammarly or spelling tools for proofreading
- Markdown preview tools
- Link checkers
- Accessibility checkers
- Browser testing tools

### Example

Optional supporting tools may include Canva for diagrams, Google Docs for drafting, and GitHub preview for Markdown review.

Optional tools should not be treated as required unless the prompt explicitly says they are mandatory.

---

## 10. Reference Materials

Reference materials are files, documents, websites, repositories, or sources that should guide execution.

Examples include:

- Existing repository files
- Brand guidelines
- Style guides
- Course outlines
- Prompt templates
- Policy documents
- Product pages
- Prior drafts
- Technical documentation
- Official specifications
- Customer requirements
- Uploaded files
- Internal notes
- Public documentation
- API references

### Example

Reference the existing OPRMT™ framework documentation and maintain consistent terminology across Objective, Parameters, Results, Method, and Tools.

### Stronger Example

Use the official OPRMT™ Framework Standard Official Documentation repository as the authoritative documentation source for terminology, structure, and file placement.

---

## 11. Platform Constraints

Platform constraints define the limitations or requirements of the system where the output will be used.

Examples include:

| Platform | Common Constraint |
|---|---|
| GitHub | Markdown formatting, repository file paths, relative links |
| Payhip | Embed-safe HTML/CSS, limited custom layout control |
| Google Docs | Copy-paste readability, document formatting |
| Google Sheets | Column structure, formulas, Apps Script compatibility |
| Google Apps Script | Execution time limits, service permissions, script properties |
| Canva | Visual layout, brand colors, export format |
| Figma | Design system structure, frames, components |
| ElevenLabs | Voiceover pacing, pronunciation, script clarity |
| WordPress | Theme compatibility, shortcode behavior, plugin limitations |
| Linux Terminal | Command syntax, package availability, permissions |

### Example

The output must be compatible with GitHub Markdown and should avoid formatting that breaks repository preview.

### Payhip Example

The output must use Payhip-compatible HTML and CSS, avoid unsupported JavaScript, and keep CTA text visible on dark backgrounds.

---

## 12. Input Sources

Input sources define where the AI should get the information needed to complete the task.

Examples include:

- User-provided text
- Uploaded files
- Existing code
- GitHub repository files
- Google Drive documents
- Brand standards
- Prompt templates
- Product descriptions
- Course curriculum notes
- Website links
- Public documentation
- Internal datasets
- Spreadsheet records
- API responses

### Example

Use only the user-provided source text and do not invent missing repository details.

### Stronger Example

Use the provided OPRMT™ documentation content as the primary source, preserve official terminology, and flag any missing information instead of inventing unsupported details.

---

## 13. Output Destination

The output destination defines where the result will be used.

Examples include:

- GitHub repository
- Payhip page
- Google Classroom
- Google Drive folder
- Google Doc
- PDF document
- Course module
- Sales page
- README file
- Documentation folder
- Apps Script project
- Website embed section
- Voiceover production system
- Automation workflow
- Customer deliverable

### Example

The final output must be ready to paste into `/specification/tools.md`.

### Stronger Example

The final output must be a complete `tools.md` file that can be copied directly into the `/specification/` folder of the official OPRMT™ GitHub documentation repository.

---

## 14. Automation Support

Automation support defines whether the task should account for scripts, workflows, integrations, or repeatable execution systems.

Automation tools may include:

- Google Apps Script
- GitHub Actions
- Zapier
- Make
- Airtable automations
- Notion automations
- API connectors
- Webhooks
- CLI scripts
- Python scripts
- Shell scripts
- JSON schemas
- Validation workflows

### Example

If automation is relevant, identify the script, trigger, input source, output destination, and validation step.

### Stronger Example

When writing implementation guidance, include the automation tool, required trigger, expected input, generated output, and failure-handling notes.

---

## 15. Validation Tools

Validation tools help confirm that the final output works, complies, or meets quality standards.

Examples include:

- Markdown preview
- Link checker
- JSON validator
- HTML validator
- CSS checker
- GitHub Actions
- Spell check
- Accessibility checker
- Prompt compliance checklist
- DOAS scoring system
- Manual reviewer checklist
- Browser testing
- Apps Script execution logs
- Repository issue templates

### Example

Validate the final Markdown using GitHub preview and confirm that headings, tables, internal links, and code blocks display correctly.

### Stronger Example

Before publishing, validate the file against repository formatting standards, internal link expectations, terminology consistency, and OPRMT™ governance requirements.

---

## 16. Access Requirements

Access requirements define what permissions, credentials, accounts, or file access may be required.

Examples include:

- GitHub repository write access
- Google Drive folder access
- Payhip account access
- Google Apps Script authorization
- API keys
- Workspace permissions
- Admin access
- File ownership
- Canva design access
- Figma project access
- Classroom admin rights

### Example

Publishing this file requires write access to the target GitHub repository.

### Security Note

Sensitive credentials, API keys, tokens, passwords, and private access links should not be placed directly inside public documentation.

---

## 17. Tool Limitations

Tool limitations define what the selected resources cannot do or should not be used for.

Examples include:

- Payhip may restrict layout control compared to a custom-coded website.
- Google Apps Script may have execution time limits.
- GitHub Markdown does not support all HTML/CSS behaviors.
- Canva assets may not remain editable outside Canva.
- Voiceover tools may require pronunciation cleanup.
- API tools may require authentication and rate-limit handling.
- Browser previews may differ from mobile rendering.
- Public repositories should not contain private credentials.

### Example

Do not include private API keys, credentials, or access tokens in repository documentation.

### Stronger Example

If a workflow requires credentials, describe them as required environment variables or secret configuration values rather than placing actual credentials in the document.

---

## 18. Weak Tools Section Example

Use whatever tools are needed.

### Problems

- No required tools are named
- No platform destination is defined
- No reference materials are identified
- No validation tools are included
- No access requirements are stated
- No tool limitations are acknowledged
- No implementation environment is defined

---

## 19. Strong Tools Section Example

Use the following tools and resources:

1. GitHub for repository storage and version control.
2. Markdown for documentation formatting.
3. The official OPRMT™ Framework Standard Official Documentation repository as the target location.
4. GitHub preview to validate formatting.
5. Repository governance files to confirm terminology and contribution requirements.

Do not include credentials, unsupported third-party claims, or private access links.

The final file must be ready to place at `/specification/tools.md`.

### Why This Works

This Tools section is effective because it defines:

- The required platform
- The file format
- The reference source
- The validation tool
- The target destination
- The prohibited content
- The implementation standard

---

## 20. Tools Section Template

Use the following reusable template when writing the Tools component of an OPRMT™ prompt.

~~~md
## [T] Tools

Use or account for the following tools and resources:

Required tools:
- {{REQUIRED_TOOL_1}}
- {{REQUIRED_TOOL_2}}
- {{REQUIRED_TOOL_3}}

Optional tools:
- {{OPTIONAL_TOOL_1}}
- {{OPTIONAL_TOOL_2}}
- {{OPTIONAL_TOOL_3}}

Reference materials:
- {{REFERENCE_MATERIAL_1}}
- {{REFERENCE_MATERIAL_2}}
- {{REFERENCE_MATERIAL_3}}

Input sources:
- {{INPUT_SOURCE_1}}
- {{INPUT_SOURCE_2}}

Output destination:
- {{OUTPUT_DESTINATION}}

Platform constraints:
- {{PLATFORM_CONSTRAINT_1}}
- {{PLATFORM_CONSTRAINT_2}}

Validation tools or checks:
- {{VALIDATION_TOOL_OR_CHECK_1}}
- {{VALIDATION_TOOL_OR_CHECK_2}}

Access requirements:
- {{ACCESS_REQUIREMENT_1}}
- {{ACCESS_REQUIREMENT_2}}

Tool limitations:
- {{TOOL_LIMITATION_1}}
- {{TOOL_LIMITATION_2}}

Security rule:
- Do not include private credentials, API keys, passwords, tokens, or confidential access links in the final output.
~~~

---

## 21. Tools Design Checklist

Before finalizing a Tools section, confirm the following:

~~~md
## Tools Checklist

- [ ] Required tools are clearly identified
- [ ] Optional tools are separated from required tools
- [ ] Reference materials are listed
- [ ] Input sources are defined
- [ ] Output destination is specified
- [ ] Platform constraints are included
- [ ] Automation support is identified if relevant
- [ ] Validation tools or checks are included
- [ ] Access requirements are stated if applicable
- [ ] Tool limitations are acknowledged
- [ ] Security rules are included
~~~

---

## 22. Common Tools Failures

| Failure | Description | Correction |
|---|---|---|
| No Tool Context | The AI does not know what platform the output is for | Define the required platform |
| Wrong Platform Assumption | The AI creates output for the wrong environment | Specify the destination system |
| Missing References | The AI ignores important source material | List required reference materials |
| No Validation Tool | The output is not checked before publishing | Add validation tools or review checks |
| Credentials Included | Sensitive information is exposed | Use environment variables or placeholders |
| Optional Tools Treated as Required | The workflow becomes unnecessarily complex | Separate required and optional tools |
| No Platform Constraints | Output may not work where it is used | Define platform limitations |
| No Access Notes | The user may not know what permissions are needed | Add access requirements |
| No Output Destination | The file may not match its final placement | Define the target folder or platform |

---

## 23. Relationship to Objective

The Objective defines the goal.  
Tools define the resources needed to support that goal.

| Component | Example |
|---|---|
| Objective | Create a documentation file for the Tools component |
| Tools | Use GitHub Markdown, repository structure, and OPRMT™ documentation standards |

The Objective tells the AI what to accomplish.  
The Tools section tells the AI what resources support the accomplishment.

---

## 24. Relationship to Parameters

Parameters define constraints.  
Tools define the systems and resources that must operate within those constraints.

| Component | Example |
|---|---|
| Parameters | Use professional tone, Markdown format, and no private credentials |
| Tools | Use GitHub Markdown and avoid exposing API keys, tokens, or private links |

Parameters establish the rules.  
Tools define the resource environment where those rules apply.

---

## 25. Relationship to Results

Results define the final deliverable.  
Tools define the systems and resources needed to produce or place that deliverable.

| Component | Example |
|---|---|
| Results | Produce a complete `tools.md` file with metadata, definitions, examples, checklist, and revision history |
| Tools | Use GitHub as the destination and Markdown as the file format |

Results govern the output.  
Tools govern the supporting resources and final environment.

---

## 26. Relationship to Method

Method defines how the AI should execute.  
Tools define what systems or references should support that execution.

| Component | Example |
|---|---|
| Method | Draft, validate, revise, and finalize the Markdown document |
| Tools | Use Markdown preview, repository conventions, and OPRMT™ documentation references |

Method controls the process.  
Tools support the process.

---

## 27. Tools Quality Levels

The Tools component can be written at different quality levels depending on the task.

### Basic Tools

Use Markdown.

### Standard Tools

Use Markdown and GitHub formatting conventions.

### Advanced Tools

Use GitHub Markdown, the official repository structure, existing OPRMT™ documentation, and a validation checklist before finalizing.

### Enterprise Tools

Use repository standards, canonical documentation sources, version control, Markdown preview, link validation, governance files, security rules, access controls, and publishing workflow requirements.

---

## 28. Recommended Tools Language

Use direct, implementation-specific language.

### Recommended Phrases

- “Use the following tools…”
- “Reference the following files…”
- “The final output is intended for…”
- “Validate using…”
- “Do not include credentials…”
- “Use this platform as the output destination…”
- “Account for the following platform constraints…”
- “Use these source materials as authoritative…”
- “Optional tools may include…”
- “Required tools include…”

### Avoid

- “Use any tool”
- “Use whatever works”
- “Use online resources”
- “Just make it compatible”
- “Use the best platform”
- “Use professional tools”
- “Find what you need”
- “Use common software”

These phrases are too vague unless paired with specific resource or platform requirements.

---

## 29. Tools as a Compliance Layer

In Prompt Compliance Engineering, the Tools component functions as an execution-resource compliance layer.

It gives reviewers a clear standard for determining whether the AI used, referenced, or accounted for the correct resources.

A Tools section supports compliance by answering:

- Did the system use the required platform?
- Did the system reference the correct materials?
- Did the output fit the destination environment?
- Did the system avoid unavailable or prohibited tools?
- Did the system account for platform constraints?
- Did the system avoid exposing private credentials?
- Did the system validate the output using the required tools?
- Did the tool selection support the Objective, Parameters, Results, and Method?

Without a Tools section, resource usage becomes inconsistent.

With a Tools section, resource usage becomes more structured, auditable, and repeatable.

---

## 30. Tools and DOAS Scoring

When paired with a scoring or audit system, the Tools component may be evaluated for resource alignment and implementation readiness.

A Tools-focused review may evaluate:

| Review Area | Question |
|---|---|
| Tool Identification | Were the required tools clearly defined? |
| Tool Relevance | Do the tools support the Objective and Results? |
| Platform Fit | Does the output fit the intended platform? |
| Reference Accuracy | Were the correct source materials used or referenced? |
| Constraint Awareness | Were platform limits and requirements acknowledged? |
| Validation Support | Were validation tools or checks included? |
| Security Compliance | Were credentials, tokens, and private access details protected? |
| Implementation Readiness | Can the output be used in the stated tool environment? |

This makes Tools important for implementation, validation, governance, and prompt compliance review.

---

## 31. Repository Usage

This file should be used as the official documentation reference for the **Tools** component of the OPRMT™ Framework.

Recommended file placement:

~~~text
/specification/tools.md
~~~

Alternative placements:

~~~text
/docs/framework/tools.md
/framework/tools.md
/standard/tools.md
~~~

---

## 32. Implementation Notes

When using this document in the official repository:

1. Confirm that terminology matches the current OPRMT™ specification.
2. Link this file from the main framework overview.
3. Reference this document in prompt templates.
4. Include this file in any framework education or certification materials.
5. Update the revision history whenever the Tools component changes.
6. Avoid changing canonical definitions without governance review.
7. Use this file as a teaching reference for the Tools component.
8. Use this file as a review standard when auditing prompt resource alignment.
9. Pair this file with `method.md` when teaching execution process and execution infrastructure together.
10. Pair this file with `results.md` when teaching final deliverables and output destinations.

---

## 33. Suggested Internal Links

When this file is placed in the repository, it should be linked to related framework files.

Suggested related files:

- `objective.md`
- `parameters.md`
- `results.md`
- `method.md`
- `framework-overview.md`
- `prompt-template.md`
- `prompt-compliance-engineering.md`
- `doas-scoring.md`
- `governance.md`
- `contribution-review-process.md`
- `security.md`
- `license.md`

---

## 34. Validation Checklist

Use this checklist before approving or publishing this file.

~~~md
## Validation Checklist

- [ ] The Tools component is clearly defined
- [ ] The document explains why Tools matter
- [ ] Required elements are listed
- [ ] Weak and strong examples are included
- [ ] A reusable Tools template is included
- [ ] A checklist is included
- [ ] Relationships to Objective, Parameters, Results, and Method are explained
- [ ] Prompt Compliance Engineering relevance is explained
- [ ] DOAS scoring relevance is explained
- [ ] Repository placement guidance is included
- [ ] Suggested internal links are included
- [ ] Security rules for credentials and access are included
- [ ] Revision history is included
- [ ] The document is ready for GitHub Markdown use
~~~

---

## 35. Revision History

| Version | Date | Description | Owner |
|---|---:|---|---|
| 1.0 | 2026-05-07 | Initial Tools component documentation created | Michael W. Fleming |

---

## 36. Official Notice

OPRMT™ and related framework materials are proprietary intellectual property of Michael W. Fleming unless otherwise stated in writing.

This document is provided as part of the OPRMT™ Framework Standard Official Documentation system. Use of this document does not transfer ownership, trademark rights, certification authority, commercial rights, or governance authority.

All contributions, modifications, and republication requests should follow the official OPRMT™ contribution and governance process.

---

## 37. End of Document

This file defines the **Tools** component of the OPRMT™ Framework and is intended for use as repository-ready Markdown documentation.

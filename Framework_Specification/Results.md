# Results

**Document ID:** OPRMT-SPEC-RESULTS-v1.0  
**Document Type:** Framework Specification  
**Framework:** OPRMT™  
**Component:** Results  
**Owner:** Michael W. Fleming  
**Repository:** OPRMT™ Framework Standard Official Documentation  
**Recommended File Name:** results.md  
**Recommended File Path:** /specification/results.md  
**Status:** Draft / Ready for Repository Use  
**Version:** 1.0  
**Last Updated:** 2026-05-07  

---

## 1. Purpose

The **Results** component defines the required output of an AI prompt, workflow, or structured execution request.

In the OPRMT™ Framework, **Results** answers the question:

> What must the system produce, and what does a successful output look like?

The Results section prevents vague, incomplete, inconsistent, or unusable outputs by specifying the expected deliverable, format, structure, scope, quality standard, and completion criteria before execution begins.

Results are not optional output suggestions. They are execution requirements.

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

The **Results** component is the third core element of the OPRMT™ Framework.

It translates the Objective and Parameters into a measurable deliverable.

---

## 3. Definition

**Results** are the explicit output requirements that determine what the AI system must return after executing a prompt.

A proper Results section defines:

- The final deliverable
- The required structure
- The expected format
- The level of detail
- The success criteria
- The required sections
- The required exclusions
- The usability standard
- The review or validation requirements

In practical terms, Results tell the AI system exactly what the finished product must look like.

---

## 4. Core Function

The core function of Results is to convert intent into an output specification.

An Objective may tell the AI what to accomplish.  
Parameters may tell the AI what rules to follow.  
Results tell the AI what to return.

Without a clearly defined Results section, the AI may understand the task but still return the wrong type of answer.

For example:

| Weak Prompt | Problem |
|---|---|
| “Explain OPRMT.” | No format, depth, audience, or deliverable is defined |
| “Write a business plan.” | No required sections, assumptions, length, or output standard are defined |
| “Create a prompt.” | No required structure, metadata, variables, testing criteria, or output format are defined |
| “Make a document.” | No file type, purpose, section structure, or completion criteria are defined |

A structured Results section prevents these failures by specifying the exact expected output.

---

## 5. Results in Plain Language

The Results section tells the AI:

> “When you are done, this is exactly what I need you to give me.”

It does not only describe the topic.

It describes the finished product.

A strong Results section should make the expected output measurable, reviewable, and reusable.

---

## 6. Why Results Matter

The Results component is essential because AI systems often produce incomplete or misaligned outputs when the final deliverable is not clearly defined.

Results improve:

- Output consistency
- Prompt reliability
- Workflow repeatability
- Documentation quality
- Business usability
- Review accuracy
- Prompt compliance
- User satisfaction
- System auditability

In business, education, governance, automation, and certification environments, the Results component helps ensure that the AI output can be used directly or reviewed against a known standard.

---

## 7. Required Elements of a Results Section

A complete Results section should include the following elements.

| Element | Description |
|---|---|
| Deliverable Type | Defines what the output should be |
| Output Format | Defines how the output should be formatted |
| Required Sections | Defines what sections must be included |
| Detail Level | Defines how deep or advanced the response should be |
| Completion Criteria | Defines what must be true for the output to be complete |
| Quality Standard | Defines the level of quality the output must meet |
| Exclusions | Defines what should not be included |
| Validation Requirements | Defines how the output should be checked |

Not every prompt requires every element, but high-value, public-facing, technical, or business-critical prompts should include all of them.

---

## 8. Deliverable Type

The deliverable type defines what the AI must produce.

Examples include:

- Markdown document
- Sales page copy
- Prompt template
- HTML/CSS embed
- Business plan
- Course outline
- Email sequence
- Compliance checklist
- GitHub repository file
- Standard operating procedure
- Voiceover script
- PDF-ready document
- Spreadsheet structure
- JSON schema
- Implementation guide
- Training module
- Audit report
- Policy document
- Technical specification
- Product description
- Automation workflow

### Example

The output must be a complete Markdown document suitable for placement in a GitHub repository.

### Stronger Example

The output must be a complete `results.md` file written in Markdown format and structured for placement in the official OPRMT™ Framework Standard Official Documentation repository.

---

## 9. Output Format

The output format defines how the result must be structured.

Common output formats include:

| Format | Use Case |
|---|---|
| Markdown | GitHub documentation, guides, specs, README files |
| HTML/CSS | Website embeds, landing pages, Payhip sections |
| JSON | Schemas, structured data, automation systems |
| Tables | Comparison, taxonomy, scoring systems, requirements |
| Numbered Sections | Policies, procedures, standards, formal documentation |
| Bullets | Checklists, summaries, requirements |
| Plain Text | Email, SMS, voiceover scripts, simple copy |
| YAML | Config files, metadata, workflow definitions |
| CSV | Data exports, simple databases, spreadsheet imports |
| PDF-Ready Text | Documents intended for formatted PDF conversion |

### Example

Return the output in Markdown format using H1, H2, and H3 headings, tables where useful, and clearly labeled sections.

---

## 10. Required Sections

Required sections define the internal structure of the output.

This is especially important when the deliverable must be used in a repository, course, product, documentation system, or compliance workflow.

### Example

The output must include the following sections:

1. Purpose
2. Scope
3. Definitions
4. Framework Placement
5. Required Elements
6. Examples
7. Validation Checklist
8. Revision History

Required sections are especially important for:

- Documentation
- Prompt libraries
- Course materials
- Business systems
- Legal or policy-style documents
- Repository files
- Certification materials
- Standard operating procedures
- Governance documents

---

## 11. Detail Level

The Results section should define the depth of the expected answer.

| Detail Level | Description |
|---|---|
| Brief | Short, direct, minimal explanation |
| Standard | Complete but not excessive |
| Detailed | Thorough, professional-level explanation |
| Advanced | Technical, structured, implementation-ready |
| Enterprise | Formal, reusable, documented, governance-ready |

### Example

The output must be detailed enough for direct use in a public GitHub repository without requiring major rewriting.

### Enterprise-Level Example

The output must be written at an enterprise documentation standard, with clear metadata, numbered sections, reusable definitions, implementation notes, validation criteria, and revision history.

---

## 12. Completion Criteria

Completion criteria define what must be true before the output can be considered finished.

Completion criteria create a measurable standard instead of relying on subjective judgment.

### Example

The output is complete only if it includes:

- A clear definition of the Results component
- A framework placement table
- Required elements
- Weak and strong examples
- A validation checklist
- Repository-ready Markdown formatting

### Stronger Example

The output is complete only if it can be copied into a file named `results.md`, committed to the official OPRMT™ documentation repository, and understood by a reader without additional explanation.

---

## 13. Quality Standard

The quality standard defines the professional expectation for the output.

A strong Results section may require the output to be:

- Clear
- Structured
- Complete
- Reusable
- Auditable
- Professional
- Implementation-ready
- Brand-aligned
- Repository-ready
- Suitable for public documentation
- Free from unsupported claims
- Consistent with the OPRMT™ Framework
- Suitable for education, training, or reference use

### Example

The output must use professional documentation language, avoid vague claims, and be suitable for public-facing OPRMT™ repository use.

---

## 14. Exclusions

Exclusions define what the AI should not include.

This prevents unwanted content, unsupported assumptions, formatting errors, or compliance risks.

### Example

Do not include:

- Unsupported legal claims
- Claims of accreditation
- Testimonials
- Financial guarantees
- Informal language
- Placeholder filler text
- Unverified third-party claims

Exclusions are critical for compliance, brand control, and public-facing documentation.

---

## 15. Validation Requirements

Validation requirements define how the output should be reviewed.

Examples include:

- Include a checklist
- Verify all links are working
- Confirm all required sections are present
- Confirm terminology matches OPRMT™ standards
- Flag assumptions
- Identify missing information
- Provide a revision history
- Confirm the output is ready for GitHub use
- Confirm that the document follows the required file naming convention
- Confirm that the document does not include unsupported claims

### Example

At the end of the output, include a validation checklist confirming whether the required sections, formatting, and quality standards were met.

---

## 16. Weak Results Section Example

Give me a good document about OPRMT.

### Problems

- No deliverable type
- No required structure
- No detail level
- No success criteria
- No exclusions
- No repository standard
- No validation requirements
- No audience definition
- No file destination
- No completion standard

---

## 17. Strong Results Section Example

The output must be a complete Markdown document suitable for placement in the official OPRMT™ GitHub repository.

The document must include:

1. Title
2. Metadata block
3. Purpose
4. Scope
5. Definition
6. Framework placement
7. Required elements
8. Examples
9. Validation checklist
10. Revision history

The document must use professional documentation language, avoid unsupported claims, and be ready for repository use without major rewriting.

### Why This Works

This Results section is effective because it defines:

- The deliverable
- The file format
- The required structure
- The intended destination
- The quality level
- The prohibited content
- The completion standard

---

## 18. Results Section Template

Use the following reusable template when writing the Results component of an OPRMT™ prompt.

~~~md
## [R] Results

The output must be a complete {{DELIVERABLE_TYPE}}.

The result must include:

1. {{REQUIRED_SECTION_1}}
2. {{REQUIRED_SECTION_2}}
3. {{REQUIRED_SECTION_3}}
4. {{REQUIRED_SECTION_4}}
5. {{REQUIRED_SECTION_5}}

Output format:

- Format: {{OUTPUT_FORMAT}}
- Length: {{EXPECTED_LENGTH}}
- Detail level: {{DETAIL_LEVEL}}
- Audience: {{TARGET_AUDIENCE}}
- Destination: {{FINAL_USE_LOCATION}}

Quality requirements:

- {{QUALITY_REQUIREMENT_1}}
- {{QUALITY_REQUIREMENT_2}}
- {{QUALITY_REQUIREMENT_3}}

Do not include:

- {{EXCLUSION_1}}
- {{EXCLUSION_2}}
- {{EXCLUSION_3}}

The result is complete only if:

- {{COMPLETION_CRITERION_1}}
- {{COMPLETION_CRITERION_2}}
- {{COMPLETION_CRITERION_3}}
~~~

---

## 19. Results Design Checklist

Before finalizing a Results section, confirm the following:

~~~md
## Results Checklist

- [ ] The deliverable type is clearly defined
- [ ] The required output format is specified
- [ ] Required sections are listed
- [ ] The detail level is stated
- [ ] The target audience is identified
- [ ] The intended use or destination is clear
- [ ] Quality requirements are included
- [ ] Exclusions are listed
- [ ] Completion criteria are measurable
- [ ] The output can be evaluated after generation
~~~

---

## 20. Common Results Failures

| Failure | Description | Correction |
|---|---|---|
| Vague Output | The prompt does not define what should be produced | Specify the deliverable type |
| Missing Format | The AI chooses an unwanted format | Define Markdown, HTML, JSON, table, etc. |
| No Required Sections | Output may be incomplete | List required sections |
| No Detail Standard | Output may be too shallow or too long | Define detail level |
| No Exclusions | AI may include unwanted claims | Add prohibited content |
| No Completion Criteria | Output cannot be objectively reviewed | Add success conditions |
| No Audience | Output may use the wrong tone or depth | Define the target reader |
| No Destination | Output may not fit its final use | Define where the output will be used |
| No Validation | Output cannot be checked consistently | Add review requirements |

---

## 21. Relationship to Objective

The Objective defines the goal.  
The Results section defines the finished output.

| Component | Example |
|---|---|
| Objective | Create a documentation file for the Results component |
| Results | Return a complete `results.md` file with metadata, definitions, examples, checklist, and revision history |

The Objective tells the AI what the task is.  
The Results section tells the AI what to return.

---

## 22. Relationship to Parameters

Parameters define constraints.  
Results define the final deliverable.

| Component | Example |
|---|---|
| Parameters | Use professional tone, do not include legal claims, use Markdown |
| Results | Produce a repository-ready Markdown document with required sections |

Parameters control boundaries.  
Results control output.

---

## 23. Relationship to Method

Method defines how the AI should execute.  
Results define what the AI should produce.

| Component | Example |
|---|---|
| Method | Analyze the topic, structure the content, validate completeness |
| Results | Return the final structured documentation file |

Method governs the process.  
Results governs the deliverable.

---

## 24. Relationship to Tools

Tools define supporting resources.  
Results define what should be created from those resources.

| Component | Example |
|---|---|
| Tools | Use GitHub Markdown conventions and OPRMT™ documentation standards |
| Results | Produce a Markdown file ready for repository placement |

Tools support execution.  
Results define the expected output.

---

## 25. Results Quality Levels

The Results component can be written at different quality levels depending on the task.

### Basic Results

Return a short summary in bullet points.

### Standard Results

Return a structured Markdown summary with headings, bullet points, and a conclusion.

### Advanced Results

Return a repository-ready Markdown document with metadata, numbered sections, examples, validation checklist, and revision history.

### Enterprise Results

Return a governance-ready Markdown specification with metadata, scope, definitions, compliance requirements, versioning notes, implementation guidance, quality controls, and maintainability standards.

---

## 26. Recommended Results Language

Use direct, measurable language.

### Recommended Phrases

- “The output must include…”
- “Return the result as…”
- “The final deliverable must be…”
- “The response is complete only if…”
- “Use the following structure…”
- “Do not include…”
- “Include a validation checklist…”
- “Format the result as…”
- “The final file must be named…”
- “The output must be suitable for…”
- “The result must be ready for…”

### Avoid

- “Make it good”
- “Do your best”
- “Give me something professional”
- “Write a complete answer”
- “Make it detailed”
- “Explain everything”
- “Make it nice”
- “Make it high quality”

These phrases are too vague unless paired with specific output requirements.

---

## 27. Results as a Compliance Layer

In Prompt Compliance Engineering, the Results component functions as an output compliance layer.

It gives reviewers a clear standard for determining whether the AI output satisfied the prompt.

A Results section supports compliance by answering:

- Did the system return the correct deliverable?
- Did the system use the required format?
- Did the system include all required sections?
- Did the system avoid prohibited content?
- Did the system satisfy the completion criteria?
- Did the system produce a usable output?
- Did the system align with the stated Objective and Parameters?

Without a Results section, prompt review becomes subjective.

With a Results section, prompt review becomes more structured, auditable, and repeatable.

---

## 28. Results and DOAS Scoring

When paired with a scoring or audit system, the Results component may be evaluated for output alignment.

A Results-focused review may evaluate:

| Review Area | Question |
|---|---|
| Deliverable Accuracy | Did the output match the requested deliverable type? |
| Format Compliance | Did the output use the requested format? |
| Section Completeness | Were all required sections included? |
| Quality Alignment | Did the output meet the defined quality level? |
| Exclusion Compliance | Did the output avoid prohibited content? |
| Completion Standard | Did the output satisfy all completion criteria? |
| Usability | Can the output be used for its intended purpose? |

This makes Results one of the most important components for validation, scoring, and prompt improvement.

---

## 29. Repository Usage

This file should be used as the official documentation reference for the **Results** component of the OPRMT™ Framework.

Recommended file placement:

~~~text
/specification/results.md
~~~

Alternative placements:

~~~text
/docs/framework/results.md
/framework/results.md
/standard/results.md
~~~

---

## 30. Implementation Notes

When using this document in the official repository:

1. Confirm that terminology matches the current OPRMT™ specification.
2. Link this file from the main framework overview.
3. Reference this document in prompt templates.
4. Include this file in any framework education or certification materials.
5. Update the revision history whenever the Results component changes.
6. Avoid changing canonical definitions without governance review.
7. Use this file as a teaching reference for the Results component.
8. Use this file as a review standard when auditing prompt outputs.

---

## 31. Suggested Internal Links

When this file is placed in the repository, it should be linked to related framework files.

Suggested related files:

- `objective.md`
- `parameters.md`
- `method.md`
- `tools.md`
- `framework-overview.md`
- `prompt-template.md`
- `prompt-compliance-engineering.md`
- `doas-scoring.md`
- `governance.md`
- `contribution-review-process.md`

---

## 32. Validation Checklist

Use this checklist before approving or publishing this file.

~~~md
## Validation Checklist

- [ ] The Results component is clearly defined
- [ ] The document explains why Results matter
- [ ] Required elements are listed
- [ ] Weak and strong examples are included
- [ ] A reusable Results template is included
- [ ] A checklist is included
- [ ] Relationships to Objective, Parameters, Method, and Tools are explained
- [ ] Prompt Compliance Engineering relevance is explained
- [ ] DOAS scoring relevance is explained
- [ ] Repository placement guidance is included
- [ ] Suggested internal links are included
- [ ] Revision history is included
- [ ] The document is ready for GitHub Markdown use
~~~

---

## 33. Revision History

| Version | Date | Description | Owner |
|---|---:|---|---|
| 1.0 | 2026-05-07 | Initial Results component documentation created | Michael W. Fleming |

---

## 34. Official Notice

OPRMT™ and related framework materials are proprietary intellectual property of Michael W. Fleming unless otherwise stated in writing.

This document is provided as part of the OPRMT™ Framework Standard Official Documentation system. Use of this document does not transfer ownership, trademark rights, certification authority, commercial rights, or governance authority.

All contributions, modifications, and republication requests should follow the official OPRMT™ contribution and governance process.

---

## 35. End of Document

This file defines the **Results** component of the OPRMT™ Framework and is intended for use as repository-ready Markdown documentation.

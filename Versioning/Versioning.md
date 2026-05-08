# Versioning

**Document ID:** OPRMT-GOV-VERSIONING-v1.0  
**Document Type:** Governance / Version Control Policy  
**Framework:** OPRMT™  
**Repository:** OPRMT™ Framework Standard Official Documentation  
**Owner:** Michael W. Fleming  
**Recommended File Name:** versioning.md  
**Recommended File Path:** /governance/versioning.md  
**Status:** Draft / Ready for Repository Use  
**Version:** 1.0  
**Last Updated:** 2026-05-07  

---

## 1. Purpose

This document defines the versioning policy for the **OPRMT™ Framework Standard Official Documentation** repository.

The purpose of this file is to establish a clear, repeatable, and auditable version control system for OPRMT™ framework documents, governance files, templates, specifications, examples, and related repository materials.

Versioning ensures that changes to the OPRMT™ Framework are traceable, controlled, reviewable, and properly documented.

---

## 2. Versioning Objective

The objective of OPRMT™ versioning is to preserve the integrity of the framework while allowing controlled improvement over time.

Versioning exists to:

- Track changes across documents
- Identify current official versions
- Preserve historical context
- Support governance review
- Prevent uncontrolled framework drift
- Distinguish minor edits from major framework changes
- Support public repository transparency
- Support release management
- Support citation, documentation, and implementation consistency
- Protect the canonical meaning of OPRMT™

---

## 3. Scope

This versioning policy applies to:

- Framework specifications
- Governance documents
- README files
- Contribution documents
- Templates
- Prompt examples
- Educational materials
- Documentation style guides
- Repository policies
- Change request records
- Release notes
- Changelog entries
- Framework-related reference files

This policy applies to any document that may affect how OPRMT™ is defined, explained, used, taught, implemented, or governed.

---

## 4. Versioning Authority

Versioning authority belongs to the repository owner or authorized maintainers.

The owner or authorized maintainers control:

- Version numbering
- Release approval
- Major version changes
- Minor version changes
- Patch version changes
- Deprecation status
- Archived version status
- Official release labels
- Changelog entries
- Document version metadata
- Repository tag creation

No version becomes official until it is reviewed and approved through the repository governance process.

---

## 5. Versioning Model

The OPRMT™ repository should use a structured versioning model based on the following pattern:

~~~text
MAJOR.MINOR.PATCH
~~~

Example:

~~~text
1.0.0
1.1.0
1.1.1
2.0.0
~~~

For individual documents, a simplified form may be used in metadata:

~~~text
v1.0
v1.1
v1.0.1
~~~

The repository may use full semantic versioning for formal releases and simplified document versioning for individual files.

---

## 6. Version Number Definitions

| Version Level | Format Position | Meaning |
|---|---:|---|
| Major | `X.0.0` | Significant framework, governance, or structural change |
| Minor | `0.X.0` | New content, clarification, or feature addition without breaking existing meaning |
| Patch | `0.0.X` | Typo fix, formatting correction, link repair, or minor cleanup |

---

## 7. Major Version Changes

A **major version change** occurs when a change affects core framework meaning, governance authority, repository structure, licensing rules, or compatibility with previous documentation.

Major version changes may include:

- Redefining Objective
- Redefining Parameters
- Redefining Results
- Redefining Method
- Redefining Tools
- Adding a new official framework component
- Removing an official framework component
- Changing the canonical meaning of OPRMT™
- Changing governance authority
- Changing licensing or commercial use terms
- Reorganizing the repository in a way that breaks existing links
- Changing certification rules in a material way
- Replacing an official standard with a new standard
- Introducing breaking terminology changes

### Example

~~~text
1.0.0 → 2.0.0
~~~

A change from `1.0.0` to `2.0.0` indicates that users should review compatibility, definitions, and implementation guidance before relying on the new version.

---

## 8. Minor Version Changes

A **minor version change** occurs when new content is added or existing content is clarified without changing the core meaning of the framework.

Minor version changes may include:

- Adding examples
- Adding templates
- Adding implementation notes
- Adding educational explanations
- Adding new documentation sections
- Improving clarity
- Expanding guidance
- Adding validation checklists
- Adding non-breaking references
- Adding repository usage notes
- Adding new supporting files

### Example

~~~text
1.0.0 → 1.1.0
~~~

A change from `1.0.0` to `1.1.0` indicates that the documentation has expanded, but the core framework meaning remains compatible.

---

## 9. Patch Version Changes

A **patch version change** occurs when a document is corrected without changing meaning.

Patch version changes may include:

- Typo corrections
- Grammar corrections
- Formatting fixes
- Broken link repairs
- Table formatting cleanup
- Metadata correction
- Minor wording cleanup
- File path correction
- Heading formatting repair
- Markdown rendering correction

### Example

~~~text
1.0.0 → 1.0.1
~~~

A patch change should not affect framework meaning, usage guidance, governance rules, or implementation expectations.

---

## 10. Document-Level Versioning

Each important repository document should include a metadata block near the top of the file.

Recommended metadata fields:

~~~md
**Document ID:** OPRMT-AREA-DOCUMENT-NAME-v1.0  
**Document Type:** Specification / Governance / Guide / Template  
**Framework:** OPRMT™  
**Repository:** OPRMT™ Framework Standard Official Documentation  
**Owner:** Michael W. Fleming  
**Recommended File Name:** example.md  
**Recommended File Path:** /example/example.md  
**Status:** Draft / Active / Deprecated / Archived  
**Version:** 1.0  
**Last Updated:** YYYY-MM-DD
~~~

Document-level versioning helps readers determine whether a file is current, draft, deprecated, or archived.

---

## 11. Repository-Level Versioning

The repository may also maintain repository-level versions.

Repository-level versioning should be used when a coordinated set of files represents an official release.

A repository-level release may include:

- Updated specification files
- Updated governance files
- Updated templates
- Updated examples
- Updated README
- Updated changelog
- Updated release notes
- Updated repository tags

### Example Repository Release

~~~text
OPRMT Framework Standard Documentation v1.0.0
~~~

Repository-level releases should be recorded through GitHub releases or equivalent release documentation.

---

## 12. Document Status Values

Official documents should use clear status labels.

| Status | Meaning |
|---|---|
| Draft | File is being prepared and is not yet final |
| Ready for Repository Use | File is ready to place in the repository |
| Active | File is approved and currently valid |
| Under Review | File is being reviewed before acceptance |
| Deprecated | File has been replaced or is no longer current |
| Archived | File is retained for historical reference only |
| Experimental | File is being tested and should not be treated as canonical |
| Superseded | File has been replaced by a newer version |

Status labels should be updated when a file moves through the repository lifecycle.

---

## 13. Release Labels

Repository releases should use clear labels.

Recommended release label format:

~~~text
vMAJOR.MINOR.PATCH
~~~

Examples:

~~~text
v1.0.0
v1.1.0
v1.1.1
v2.0.0
~~~

Optional release naming format:

~~~text
OPRMT Framework Standard Documentation v1.0.0
~~~

---

## 14. Version Tags

Git tags may be used to mark official releases.

Recommended tag format:

~~~text
v1.0.0
~~~

Examples:

~~~text
git tag v1.0.0
git tag v1.1.0
git tag v2.0.0
~~~

Tags should only be created for approved releases.

---

## 15. Changelog Requirements

A `CHANGELOG.md` file should record meaningful repository changes.

The changelog should include:

- Version number
- Release date
- Summary of changes
- Added files
- Changed files
- Deprecated files
- Removed files
- Fixed issues
- Governance notes
- Breaking changes, if applicable

Recommended changelog format:

~~~md
## v1.0.0 - YYYY-MM-DD

### Added
- Added initial framework specification files.
- Added governance documentation.
- Added contribution review process.

### Changed
- Updated README structure.

### Fixed
- Fixed broken internal links.

### Deprecated
- Deprecated older draft files.

### Removed
- Removed outdated placeholder content.

### Governance Notes
- Established owner approval requirement for framework-level changes.
~~~

---

## 16. Revision History Requirements

Important documents should include a revision history near the end of the file.

Recommended format:

| Version | Date | Description | Owner |
|---|---:|---|---|
| 1.0 | 2026-05-07 | Initial document created | Michael W. Fleming |

Revision history should be updated when meaningful document changes occur.

Patch-level typo fixes may be recorded if the repository requires strict documentation traceability.

---

## 17. Breaking Changes

A breaking change is any change that may affect existing references, implementations, links, definitions, templates, or educational materials.

Breaking changes may include:

- Renaming files used by internal links
- Moving files to new folders
- Changing core framework definitions
- Changing official terminology
- Removing required sections from a specification
- Changing governance authority
- Changing licensing rules
- Changing certification-related requirements
- Replacing official templates with incompatible versions

Breaking changes should be documented clearly in:

- `CHANGELOG.md`
- Release notes
- Affected document revision histories
- Migration notes, if needed

---

## 18. Non-Breaking Changes

A non-breaking change improves or expands documentation without disrupting existing usage.

Non-breaking changes may include:

- Adding examples
- Adding implementation notes
- Clarifying existing text
- Adding diagrams or tables
- Adding related document links
- Improving formatting
- Fixing broken links
- Correcting spelling
- Adding validation checklists

Non-breaking changes may still require review if they affect public documentation quality or framework interpretation.

---

## 19. Version Metadata Rules

Version metadata should be placed near the top of official Markdown files.

The metadata should include:

- Document ID
- Document Type
- Framework
- Repository
- Owner
- Recommended File Name
- Recommended File Path
- Status
- Version
- Last Updated

The version number in metadata must match the revision history unless the file is being actively prepared and clearly marked as Draft.

---

## 20. Document ID Versioning

Document IDs should include a version marker.

Recommended format:

~~~text
OPRMT-AREA-DOCUMENT-NAME-v1.0
~~~

Examples:

~~~text
OPRMT-SPEC-OBJECTIVE-v1.0
OPRMT-SPEC-PARAMETERS-v1.0
OPRMT-SPEC-RESULTS-v1.0
OPRMT-SPEC-METHOD-v1.0
OPRMT-SPEC-TOOLS-v1.0
OPRMT-GOV-GOVERNANCE-v1.0
OPRMT-GOV-VERSIONING-v1.0
~~~

Document IDs help identify official files even when filenames or folder locations change.

---

## 21. Versioning and File Naming

Version numbers should normally appear in document metadata, not in active filenames.

Recommended active filenames:

~~~text
objective.md
parameters.md
results.md
method.md
tools.md
governance.md
versioning.md
~~~

Avoid active filenames such as:

~~~text
objective-v1.md
objective-final.md
objective-new.md
objective-updated-2.md
~~~

Versioned filenames may be used inside archive folders when preserving historical versions.

Example:

~~~text
/archive/specification/objective-v0.9-draft.md
~~~

---

## 22. Draft Versioning

Draft files should be clearly marked.

Draft metadata example:

~~~md
**Status:** Draft  
**Version:** 0.9  
**Last Updated:** YYYY-MM-DD
~~~

Drafts should not be treated as canonical documentation until approved.

Recommended draft version patterns:

| Version | Meaning |
|---|---|
| 0.1 | Early draft |
| 0.5 | Working draft |
| 0.9 | Pre-release draft |
| 1.0 | First approved release |

---

## 23. Pre-Release Versioning

Pre-release versions may be used before official publication.

Examples:

~~~text
v1.0.0-alpha
v1.0.0-beta
v1.0.0-rc.1
~~~

Recommended meanings:

| Label | Meaning |
|---|---|
| alpha | Early test version |
| beta | Public or limited review version |
| rc | Release candidate |
| final | Approved release, although formal tags should avoid using “final” |

Avoid informal labels such as:

~~~text
final-final
new-final
last-version
real-version
fixed-final
~~~

---

## 24. Deprecation Versioning

When a document is deprecated, update its status and provide replacement guidance.

Recommended deprecation notice:

~~~md
> **Deprecated:** This document has been replaced by `new-document.md` as of version X.X.X. It is retained for historical reference only.
~~~

A deprecated document should include:

- Deprecation date
- Replacement file, if applicable
- Reason for deprecation
- Last valid version
- Migration note, if needed

Deprecated documents should not be presented as current canonical guidance.

---

## 25. Archive Versioning

Archived files should be separated from active documentation.

Suggested archive folder:

~~~text
/archive/
~~~

Archived files may include:

- Old drafts
- Superseded files
- Deprecated versions
- Experimental documents
- Historical release notes
- Prior templates

Archived files should clearly state that they are not current documentation.

---

## 26. Versioning and Internal Links

When files are moved, renamed, deprecated, or archived, internal links should be checked and updated.

Versioning updates should include:

- Link review
- README link updates
- Related document updates
- Changelog entry
- Redirect or replacement notes, if needed
- Archive notice, if applicable

Broken internal links reduce repository reliability and should be corrected before release.

---

## 27. Versioning and Governance

Versioning must follow repository governance.

Major and high-impact version changes require owner or authorized maintainer approval.

Governance review is required for:

- Framework definition changes
- Repository structure changes
- Licensing changes
- Certification policy changes
- Contributor policy changes
- Public documentation standard changes
- Major release approvals

Versioning decisions should not be made casually because they affect canonical documentation and public interpretation.

---

## 28. Versioning and Licensing

License changes are high-impact changes and should normally trigger a major version review.

Licensing updates may affect:

- Use rights
- Commercial restrictions
- Attribution rules
- Redistribution rules
- Contribution ownership
- Fork permissions
- Certification usage
- Enforcement rights

Any license-related version change should be clearly documented in the changelog and release notes.

---

## 29. Versioning and Certification Materials

Certification-related materials should be versioned carefully because learners, instructors, and reviewers may rely on specific documentation versions.

Certification files may include:

- Curriculum documents
- Student handbooks
- Assessment rubrics
- Capstone requirements
- Instructor guides
- Certificate usage rules
- Completion standards
- Prompt engineering specifications

Certification-related updates should identify whether the change affects:

- Existing learners
- Future learners
- Assessment criteria
- Completion requirements
- Certificate usage
- Instructor guidance
- Course positioning

Certification changes must not imply accreditation or external recognition unless verified and approved.

---

## 30. Versioning and Prompt Compliance Engineering

Prompt Compliance Engineering documentation should maintain clear version history.

PCE versioning should track:

- Definitions
- Review criteria
- Compliance language
- Audit methods
- Prompt quality standards
- Scoring references
- Limitations and disclaimers
- Relationship to OPRMT™

If PCE documentation changes the way prompt compliance is reviewed, the update may require a minor or major version change depending on impact.

---

## 31. Versioning and DOAS Scoring

DOAS Scoring documentation should be versioned when scoring criteria, interpretation, or implementation changes.

DOAS versioning should track:

- Scoring categories
- Weighting rules
- Score interpretation
- Audit process
- Manual review guidance
- Automation rules
- Limitations
- Disclaimer language

If a scoring update changes how outputs are evaluated, it should be documented as at least a minor version change.

If a scoring update changes the entire scoring model, it may require a major version change.

---

## 32. Version Control Workflow

Recommended workflow for versioned changes:

1. Identify the change.
2. Classify the change as patch, minor, or major.
3. Update the affected document.
4. Update the document metadata.
5. Update the revision history.
6. Update internal links if needed.
7. Update `CHANGELOG.md` if the change is meaningful.
8. Review the change under governance rules.
9. Approve or request revisions.
10. Merge the change.
11. Create a release tag if the change is part of an official release.

---

## 33. Version Classification Checklist

Use this checklist to classify a change.

~~~md
## Version Classification Checklist

- [ ] Does the change alter a core OPRMT™ definition?
- [ ] Does the change affect governance authority?
- [ ] Does the change affect licensing or commercial rights?
- [ ] Does the change affect certification requirements?
- [ ] Does the change break existing links or file paths?
- [ ] Does the change remove or replace official content?
- [ ] Does the change add new guidance without changing existing meaning?
- [ ] Does the change only fix spelling, grammar, formatting, or links?
- [ ] Has the required version level been identified?
- [ ] Has the version impact been recorded?
~~~

---

## 34. Version Decision Table

| Change Scenario | Recommended Version Impact |
|---|---|
| Typo correction | Patch |
| Broken link fix | Patch |
| Table formatting correction | Patch |
| Minor explanation improvement | Patch or Minor |
| Adding examples | Minor |
| Adding a new template | Minor |
| Adding a new guide | Minor |
| Adding a new governance rule | Minor or Major |
| Changing a core definition | Major |
| Changing licensing terms | Major |
| Changing certification requirements | Major |
| Renaming major folders | Major |
| Deprecating an official file | Minor or Major |
| Removing official documentation | Major |

---

## 35. Release Notes Template

Use this template when preparing release notes.

~~~md
# Release Notes — OPRMT™ Framework Standard Documentation v{{VERSION}}

**Release Date:** {{YYYY-MM-DD}}  
**Release Type:** {{Major / Minor / Patch}}  
**Approved By:** {{APPROVER_NAME}}  

---

## Summary

{{RELEASE_SUMMARY}}

---

## Added

- {{ADDED_ITEM_1}}
- {{ADDED_ITEM_2}}

---

## Changed

- {{CHANGED_ITEM_1}}
- {{CHANGED_ITEM_2}}

---

## Fixed

- {{FIXED_ITEM_1}}
- {{FIXED_ITEM_2}}

---

## Deprecated

- {{DEPRECATED_ITEM_1}}

---

## Removed

- {{REMOVED_ITEM_1}}

---

## Breaking Changes

- {{BREAKING_CHANGE_1}}

---

## Governance Notes

{{GOVERNANCE_NOTES}}

---

## Migration Notes

{{MIGRATION_NOTES}}
~~~

---

## 36. Changelog Entry Template

Use this template for `CHANGELOG.md`.

~~~md
## v{{VERSION}} - {{YYYY-MM-DD}}

### Added
- {{ADDED_ITEM}}

### Changed
- {{CHANGED_ITEM}}

### Fixed
- {{FIXED_ITEM}}

### Deprecated
- {{DEPRECATED_ITEM}}

### Removed
- {{REMOVED_ITEM}}

### Governance Notes
- {{GOVERNANCE_NOTE}}
~~~

---

## 37. Versioning Review Checklist

Use this checklist before approving a versioned release.

~~~md
## Versioning Review Checklist

- [ ] Version number is correct
- [ ] Version impact has been classified
- [ ] Document metadata has been updated
- [ ] Revision history has been updated
- [ ] Changelog has been updated if required
- [ ] Release notes have been prepared if required
- [ ] Internal links have been checked
- [ ] Deprecated documents are marked correctly
- [ ] Archived documents are separated from active documentation
- [ ] Governance approval has been recorded
- [ ] No unsupported claims were added
- [ ] No private credentials or sensitive data were added
- [ ] Repository tag is prepared if this is an official release
~~~

---

## 38. Common Versioning Failures

| Failure | Description | Correction |
|---|---|---|
| No Version Metadata | Document lacks version information | Add metadata block |
| Informal Version Names | Files use labels like “final” or “new” | Use structured version numbers |
| Missing Revision History | Changes cannot be traced | Add revision history |
| Unrecorded Breaking Change | Users are not warned about major change | Add release notes and changelog entry |
| Inconsistent Version Numbers | Metadata, changelog, and release notes do not match | Synchronize all version references |
| Deprecated File Not Marked | Users may rely on outdated guidance | Add deprecation notice |
| Archived File Appears Current | Old files may be mistaken for active docs | Move to archive and mark status |
| No Governance Approval | Version may not be official | Require owner or maintainer approval |

---

## 39. Related Documents

This versioning file should be used alongside:

- `README.md`
- `CHANGELOG.md`
- `CONTRIBUTING.md`
- `governance.md`
- `contribution-review-process.md`
- `documentation-style-guide.md`
- `objective.md`
- `parameters.md`
- `results.md`
- `method.md`
- `tools.md`
- `prompt-compliance-engineering.md`
- `doas-scoring.md`

---

## 40. Recommended Repository Placement

Recommended file placement:

~~~text
/governance/versioning.md
~~~

Alternative root-level placement:

~~~text
VERSIONING.md
VERSION.md
~~~

If both are used, the root-level version file may provide a short summary and link to the full versioning policy inside `/governance/`.

---

## 41. Revision History

| Version | Date | Description | Owner |
|---|---:|---|---|
| 1.0 | 2026-05-07 | Initial versioning policy created | Michael W. Fleming |

---

## 42. Official Notice

OPRMT™ and related framework materials are proprietary intellectual property of Michael W. Fleming unless otherwise stated in writing.

This versioning document is provided as part of the OPRMT™ Framework Standard Official Documentation system. Use of this repository, documentation, examples, templates, or contribution process does not transfer ownership, trademark rights, certification authority, commercial rights, licensing authority, or governance authority.

All version changes, releases, modifications, forks, references, and republication requests must follow the official OPRMT™ contribution, licensing, and governance process.

---

## 43. End of Document

This file defines the versioning policy for the **OPRMT™ Framework Standard Official Documentation** repository and is intended for use as repository-ready Markdown documentation.

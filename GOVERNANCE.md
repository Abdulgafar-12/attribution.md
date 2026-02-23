# Governance

## Overview

The AI Attribution Protocol is an open convention maintained by its contributors. It is vendor-neutral and not affiliated with any company, product, or platform.

No commercial entity may claim exclusive ownership or branding rights over the protocol.

All governance discussions and version decisions must be publicly documented in this repository.

## Principles

1. **Vendor neutrality.** The protocol does not favour any AI tool, platform, or organisation.
2. **User consent first.** No version of this specification will permit actions on a user's account without their explicit approval.
3. **Platform compliance.** The protocol cannot override, circumvent, or conflict with any platform's Terms of Service or Acceptable Use Policies.
4. **Backward compatibility.** New versions will be additive. Existing implementations must not break when the specification is updated.
5. **Simplicity.** The specification should remain minimal and easy to implement. Complexity is introduced only when clearly justified by adoption needs.

## Versioning

The protocol uses semantic versioning:

- **Patch versions** (0.1.1): Clarifications, typo fixes, and non-functional changes.
- **Minor versions** (0.2): New action types, optional fields, and additive features. Backward compatible.
- **Major versions** (1.0): Breaking changes to the schema or parsing rules. These require broad community discussion.

The `protocol_version` field in `ATTRIBUTION.md` files maps directly to tagged releases in this repository.

## Decision Making

Changes to the specification are proposed through GitHub issues and pull requests. Significant changes (new action types, schema modifications, policy changes) require discussion in an open issue before a pull request is submitted.

The maintainers aim for consensus. Where consensus cannot be reached, decisions are made by the core maintainers with clear reasoning documented in the issue thread.

## Becoming a Maintainer

Contributors who demonstrate sustained, constructive engagement with the project may be invited to become maintainers. The protocol benefits from diverse perspectives, particularly from open source maintainers, AI agent developers, and platform operators.

## Code of Conduct

All participants in this project are expected to treat each other with respect and professionalism. Harassment, discrimination, and bad-faith engagement are not tolerated.

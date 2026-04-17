# 🚫 DEPRECATED — kortix-everest

**Status**: REJECTED on license review Apr 16 2026
**Reason**: Elastic License 2.0 (source-available commercial, NOT OSI open-source)
**License risk**: POISON per [mem:24] — blocks Everest SaaS + multi-tenant use

## What happened

This repo was forked from `kortix-ai/suna` as part of MOS-03 (Agent Chain master hub) on Apr 16 2026. 

Original spec assumed Apache 2.0 based on older documentation. Actual current license is **Elastic License 2.0**.

Elastic License 2.0 restrictions that block Everest use:

> "You may not provide the software to third parties as a hosted or managed service, where the service provides users with access to any substantial set of the features or functionality of the software."

This violates the [mem:30] Agent Chain + Marketing OS plan which requires multi-tenant hosted service for 8 Everest tenants.

## Replacement

**CrewAI** adopted as master hub replacement (REPOEVAL score: 92, ADOPT).

- Source: `crewAIInc/crewAI` (MIT, 49K stars)
- Fork: [`breverdbidder/crewai-everest`](https://github.com/breverdbidder/crewai-everest)
- Rationale: Purpose-built multi-agent orchestration, MIT clean, active (pushed today), Python matches BidDeed stack

## Do not use this repo

Archived as read-only. Do not merge, deploy, or integrate code from this repo.

For questions, see HUB-DAY0 inventory issue #517 on `breverdbidder/cli-anything-biddeed`.

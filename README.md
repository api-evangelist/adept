# Adept (adept)

Adept was an AI research lab building action-taking foundation models (the ACT family) that can use software tools and complete tasks across business applications. In mid-2024, several Adept co-founders and senior researchers joined Amazon's AGI organization in a non-acquisition arrangement, and Amazon licensed Adept's technology. Adept the entity continues to exist, but it has no current public commercial API; its primary remaining footprint is open-source models published on Hugging Face (Fuyu-8B, Persimmon-8B) and historical research outputs (ACT-1, ACT-2).

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/adept/refs/heads/main/apis.yml)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=adept-api-evangelist&utm_content=repo)

## Type

- **x-type:** company

## Tags:

 - AI, Agents, Foundation Models, Action Models, Workflow Automation, Multimodal

## Timestamps

- **Created:** 2026-05-08
- **Modified:** 2026-05-08

## APIs

| API | Description |
|---|---|
| Adept Fuyu-8B Model | Open-source 9B image-text-to-text multimodal model (self-hosted). |
| Adept Persimmon-8B Base Model | Open-source 8B base text generation model (self-hosted). |
| Adept Persimmon-8B Chat Model | Open-source 8B chat-tuned variant (self-hosted). |
| Adept ACT Research | Historical research outputs and demos for ACT-1 and ACT-2 (no public API). |
| Adept Website | Company / research blog site. |

## Common Properties

- [Website](https://www.adept.ai/)
- [Hugging Face](https://huggingface.co/adept)
- [Plans](plans/adept-plans-pricing.yml) — API Commons Plans 0.1
- [RateLimits](rate-limits/adept-rate-limits.yml) — API Commons Rate Limits 0.1
- [FinOps](finops/adept-finops.yml) — FOCUS-aligned FinOps Framework 1.0

## Artifacts

| Artifact | Path | Notes |
|---|---|---|
| Plans | `plans/adept-plans-pricing.yml` | Open-source models (free) on HF; no commercial / hosted API. |
| Rate Limits | `rate-limits/adept-rate-limits.yml` | No commercial API; HF download limits + self-hosted GPU capacity. |
| FinOps | `finops/adept-finops.yml` | No Adept invoice surface; track via self-hosted inference provider spend. |

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com

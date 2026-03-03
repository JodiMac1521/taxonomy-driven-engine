# Case Study: Scaling Revenue Without Scaling Headcount

## The Problem

Work Simplr maintained strong retention (86%) and completion (98%) across 5,000 projects, but growth stalled due to a scoping bottleneck.

Operations spent 3–5 days clarifying project scope before work could begin. Revenue capacity was directly tied to headcount.

## The Business Constraint

Growth target: $1M ARR  
Capacity ceiling: 6 projects/week  
Headcount expansion required $264K annual cost  

Alternative: Build a scoping agent for $40K and reduce intake time from 3–5 days to 24 hours.

## Strategic Decision

We chose infrastructure over headcount.

Rather than hiring more ops staff, we built a taxonomy-driven, AI-augmented scoping system designed to:

- Standardize project templates  
- Improve scope clarity  
- Reduce operational time  
- Preserve trust  

## Architecture Choice: Human-in-Loop

Full automation risked AI hallucinations and trust breakdown.

We implemented a hybrid model:
- AI generates draft scope
- Ops reviews and refines (~30 min)
- Customer receives polished scope within 24 hours

This preserved quality while reducing time by 80%+.

## Execution

Phase 1: Template foundation (200 project analysis → 5 industry templates)  
Phase 2: AI layer integration  
Phase 3: Ops review interface  
Phase 4: Beta launch with 20 customers  

Distributed engineering team across UK/Italy with async-first documentation.

## Metrics & Outcomes

- 83% reduction in intake time  
- 89% scope accuracy (up from 70%)  
- 40% increase in average project value  
- 4.7/5 customer satisfaction  
- 100% ops team retention  

## Key Learnings

- Trust signals matter more than feature velocity  
- Instrumentation architecture must be built early  
- Hybrid AI systems outperform full automation in marketplace environments  
- Change management is product management  

---

This initiative demonstrated how structured taxonomy, governance, and human-in-loop AI can unlock scalable growth without increasing fixed costs.

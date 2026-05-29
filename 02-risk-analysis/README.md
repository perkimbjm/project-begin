*# README.md*



*# Risk Analysis Workspace*



*Source of truth for:*



*\* Risks*

*\* Assumptions*

*\* Constraints*



*Rules*



*1. Identify risks before implementation.*

*2. Validate high-impact risks early.*

*3. Convert unknowns into spikes.*

*4. Update risks when architecture changes.*



*Files*



*\* risk-register.md*

*\* assumptions.md*

*\* constraints.md*



*## Spike Trigger Rules*



*Create a spike only if at least one condition is true:*



*- High technical uncertainty.*

*- High implementation cost.*

*- High performance risk.*

*- New or unfamiliar technology.*

*- External dependency with unknown behavior.*

*- Architecture decision cannot be made confidently.*



*Do NOT create a spike for:*



*- Routine CRUD features.*

*- Well-known frameworks or patterns.*

*- Low-impact implementation details.*

*- Problems already validated in previous spikes.*



*Prefer implementation over investigation when risk is low.*



*### Only For AI Agent, Implement Risk Scoring*



*Impact:*

*- Low = 1*

*- Medium = 2*

*- High = 3*



*Likelihood:*

*- Low = 1*

*- Medium = 2*

*- High = 3*



*Risk Score = Impact × Likelihood*



*Rules:*



*1-2   → No spike needed*

*3-4   → Optional spike*

*6-9   → Spike recommended*

*9+    → Spike required*



*When uncertain, estimate risk first.*

*Do not create a spike without a documented risk.*


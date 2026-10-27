# AI-Enhanced IT Intake Modernization Roadmap

**Research and proposal** · Enterprise IT, Americas region · Role: Supervisor, Onsite IT & Automation Systems (2024–2026)

**Status:** Proposed. Submitted to my manager and director; not implemented. Figures in the ROI model are illustrative assumptions, not measured results.

A phased roadmap for modernizing ServiceNow intake, built from my research into the platform's AI capabilities. It was written to help build the case for adopting those capabilities, which would require additional licensing.

---

## Situation

I saw a significant gap in our ServiceNow intake experience. Users submitted vague, unstructured requests, technicians had to ask for device information by hand, and tickets were often misrouted, which led to repeated back-and-forth and delays. That also meant the organization had no structured foundation for AI-assisted service delivery.

## Task

Research ServiceNow's native AI capabilities and propose a phased plan for guiding users to the right workflow, capturing device context automatically, and routing requests accurately, across the Americas region.

## Action

- **Guided intake:** proposed Virtual Agent dialogs (keyword detection, catalog redirection, conversational intake) to steer users to the correct catalog workflow.
- **Smarter routing:** proposed Predictive Intelligence to classify requests and automate assignment.
- **Automatic device capture:** proposed device lookup through SCCM, Intune and Discovery so device CI data attaches to tickets without technician follow-up.
- **Adaptive forms and proactive notifications:** proposed forms that show only relevant fields, and notices for known outages and common SaaS disruptions to deflect unnecessary tickets.
- **12-month phasing:** quick wins first (AI intercept for Copilot and SaaS requests, device auto-capture), then Predictive Intelligence routing and adaptive forms, then ticket deflection and process mining.
- **Illustrative ROI model:** built a model to show the potential impact, using stated assumptions (below).

## Outcome

- Research and proposal **submitted to my manager and director**
- A phased 12-month roadmap aligned with ServiceNow's native capabilities
- Not implemented; adoption would depend on additional licensing

## Illustrative ROI model

These are projections from assumed inputs, not measured results: a 10,000-ticket annual baseline, 30% deflection, $12 per ticket, and 0.5 hr MTTR improvement.

- 30% deflection: an estimated 3,000 avoided tickets a year
- $12 per ticket: an estimated $36,000 in labor savings
- 0.5 hr MTTR improvement across 7,000 remaining tickets: an estimated 3,500 hours returned

## Lessons learned

- **Start from the user's first click.** Most of the downstream cost (misrouting, follow-up questions) begins at intake.
- **Label every assumption.** A model with stated inputs is easier to discuss and harder to misread.
- **Know the licensing before you promise the features.** Capability in the platform is not the same as capability the organization has bought.

## Files

- [Case study PDF](docs/it-intake-modernization-roadmap-case-study.pdf)

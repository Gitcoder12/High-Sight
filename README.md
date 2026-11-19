# High-Sight
AI-powered eye health companion that protects your vision by monitoring screen habits, detecting eye strain, and promoting healthier digital behavior.


---

## AI-maintained project notes (secondary — 2026-11-13)

This section supplements the maintainer-authored README above. The original text has been restored verbatim from Git-history baseline `47f15475c18383001ab55ab622840dcc1457d620`; this addendum does not replace or certify the original claims.

- The current source tree, runtime data and tests are the implementation source of truth. A roadmap item, draft PR or AI-generated description is not a shipped feature by itself.
- Preserve real and maintainer-provided data. Never substitute generated or placeholder data silently. Clearly label and isolate synthetic fixtures.
- Mark unverified sources, IDs, metrics, benchmark results and external claims as unknown/unverified rather than guessing.
- Verify setup, execution, tests and public claims against the exact current commit before relying on this repository for hiring, research or academic evaluation.
- See [MODEL_AUDIT_ROUTER.md](MODEL_AUDIT_ROUTER.md) for independent model review instructions and the merge gate.

---

## Engineering Audit & Handover — 2026-11-17

**Review scope:** default branch `main`; repository tree and README reviewed. Runtime tests were not executed.

### Confirmed findings
- The reviewed default-branch tree contains project documentation and audit guidance but no executable application source was found.
- The README describes an AI-powered eye-health companion, but the inspected branch does not contain an implementation that demonstrates screen monitoring, eye-strain detection, or personalized recommendations.

### Next actions
1. Define the intended inputs and outputs, privacy model, and non-medical scope of the MVP.
2. Implement a minimal runnable feature and add tests before describing it as an available capability.
3. Avoid diagnostic or medical claims unless supported by appropriate validation and expert review.

**Verification status:** source-tree inspection only; no runnable product or automated test suite was verified on the reviewed branch.

---

## Examples Used
- Taking a screen break after a long study session
- Tracking screen-time patterns across a workday
- Exploring reminders for prolonged near-screen activity


---

## Comparison with Existing Open-Source Projects

High-Sight is described as an eye-health companion focused on screen habits and healthier digital behavior. The following projects are relevant adjacent tools for screen breaks and digital wellbeing, not clinical eye-health systems.

| Project | Established focus | Relationship to High-Sight |
|---|---|---|
| [Stretchly](https://github.com/hovancik/stretchly) | Cross-platform break-reminder application | A mature reminder tool; High-Sight's proposed distinction is using screen-behavior signals to make reminders more context-aware. |
| [Workrave](https://github.com/rcaelers/workrave) | Micro-break, rest-break and ergonomic reminder software | Stronger established break scheduling and ergonomics workflow; High-Sight aims to focus more specifically on screen-use patterns. |
| [ActivityWatch](https://github.com/ActivityWatch/activitywatch) | Open-source automatic time-tracking and activity monitoring | Provides local activity-data infrastructure; High-Sight could use privacy-preserving activity summaries rather than claiming direct eye-strain measurement. |

### Where High-Sight is different
- **Screen-health framing:** the concept connects screen habits with reminders intended to encourage healthier digital behavior.
- **Potential context awareness:** activity duration and break patterns could inform reminders beyond fixed timers, if implemented with transparent signals.
- **Wellbeing-first experience:** the goal is to encourage breaks, not merely record productivity or application usage.

### Where established projects are stronger
Stretchly and Workrave already provide mature break-reminder workflows; ActivityWatch has an established local activity-monitoring model. The current High-Sight repository audit found documentation but no executable application source, so screen monitoring and eye-strain detection are not yet demonstrated.

### Health, privacy and evidence requirements
Do not describe the product as diagnosing, detecting or preventing eye disease. Use non-medical language such as screen-break reminders. Minimize collected data, keep it local where practical, explain permissions and add user controls. Any claim about reducing eye strain needs appropriate clinical/ergonomic evidence. This is a concept comparison, not a health-efficacy assessment.

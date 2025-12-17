# Section 7 – Events and Alarms

## 7.1 Purpose of Events and Alarms

The **First Watch® Platform** continuously monitors activity across the OT environment
and records observations in the form of **events** and **alarms**.

Events and alarms provide:
- Situational awareness
- Early indication of abnormal or unauthorized activity
- Evidence for investigation and auditing
- Input for operational and security decision-making

Understanding how events and alarms are generated, displayed, and handled
is essential for effective platform operation.

---

## 7.2 Events

An **event** represents a recorded observation made by the platform
based on system activity or policy evaluation.

Events are generated for a wide range of actions, including:
- Process execution attempts
- Policy evaluations and decisions
- Configuration updates
- Agent status changes
- Communication activity

Events are informational by default and do not necessarily indicate a problem.
They provide the raw data used for analysis, correlation, and reporting.

---

## 7.3 Alarms

An **alarm** represents an event that requires attention,
investigation, or response.

Alarms are typically generated when:
- A policy violation occurs
- An unauthorized action is detected
- A critical system condition is observed
- An agent reports an abnormal state

Alarms are prioritized and highlighted in the user interface
to ensure timely awareness and response.

---

## 7.4 Event and Alarm Severity

Events and alarms may be assigned different severity levels
to help users assess importance and urgency.

Severity levels are used to:
- Prioritize investigation efforts
- Filter and sort views
- Trigger operational or procedural responses

Severity classification supports efficient handling
of large volumes of information in complex environments.

---

## 7.5 Events and Alarms View

The **Events and Alarms** view provides centralized access
to all recorded activity.

From this view, users can:
- Browse real-time and historical events
- Identify active and acknowledged alarms
- Filter by asset, severity, time range, or category
- Inspect detailed event and alarm information

This view is a primary tool for monitoring
and incident investigation.

---

## 7.6 Alarm Acknowledgment and Handling

Alarms can be acknowledged by authorized users
to indicate that they have been reviewed.

Acknowledgment:
- Does not remove the alarm record
- Provides traceability of operator response
- Supports coordinated incident handling

Depending on platform configuration,
alarms may remain visible until explicitly cleared
or until the underlying condition is resolved.

---

## 7.7 Event Correlation and Context

The platform correlates events and alarms
across assets, agents, and time.

Correlation provides:
- Context for understanding complex incidents
- Visibility into cause-and-effect relationships
- Improved root-cause analysis

By linking events to assets, policies, and accounts,
the platform helps users interpret activity
within the operational environment.

---

## 7.8 Playbooks and Guidance

In some configurations, alarms may be associated
with **playbooks** or guidance.

Playbooks provide:
- Recommended investigation steps
- Operational response guidance
- Consistent handling procedures

This supports standardized responses
and reduces reliance on ad-hoc decision-making.

---

## 7.9 Event Retention and History

Events and alarms are retained according to
configured retention policies.

Historical data supports:
- Long-term analysis
- Compliance and audit requirements
- Trend identification
- Post-incident review

Retention settings are managed
through administrative configuration.

---

## 7.10 Best Practices for Events and Alarms

To effectively use events and alarms,
the following practices are recommended:

- Regularly review active alarms
- Use filtering to focus on relevant activity
- Acknowledge alarms consistently
- Correlate related events during investigations
- Periodically review historical trends

These practices help maintain situational awareness
and support timely, informed responses.

---

⬅ [Previous: Section 6 – Policies](section-6-policies.md)  
➡ [Next: Section 8 – Administration and Settings](section-8-administration.md)

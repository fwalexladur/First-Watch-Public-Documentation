# Section 6 – Policies

## 6.1 Purpose of Policies

Policies define the rules that govern **allowed and disallowed behavior**
within the **First Watch® Platform**.

They are the primary mechanism used to:
- Control software execution
- Restrict or permit specific actions
- Detect policy violations
- Enforce security decisions consistently across assets

Policies are centrally managed by the **Controller**
and distributed to agents for local enforcement.

---

## 6.2 Policy Scope and Application

Policies can apply to different parts of the environment,
depending on the protected asset and agent type.

At a high level, policies may govern:
- Application execution on endpoints
- Script and tool usage
- Communication with industrial controllers
- Temporary operational exceptions

Each policy is evaluated in context,
based on the asset, agent, and observed activity.

---

## 6.3 ControlGuard™ Policies

ControlGuard™ policies focus on **endpoint protection**
for Windows-based OT systems.

Typical ControlGuard policy objectives include:
- Allowing only approved applications to run
- Restricting use of system utilities and scripting tools
- Monitoring execution attempts and outcomes
- Enforcing deterministic application control

ControlGuard policies can operate in different modes,
such as monitoring or enforcement,
depending on operational requirements.

---

## 6.4 PLC Guard™ Policies

PLC Guard™ policies focus on protecting
the **industrial control layer**.

These policies are used to:
- Monitor PLC communication
- Detect unauthorized programming activity
- Restrict access to control logic and firmware
- Enforce approved engineering workflows

PLC Guard policies help ensure that
only authorized systems and actions
can influence control processes.

---

## 6.5 Policy Lifecycle

Policies follow a defined lifecycle
from creation to enforcement.

Typical stages include:
1. Policy creation or modification
2. Review and validation
3. Distribution to agents
4. Activation and enforcement
5. Monitoring and adjustment

All policy changes are centrally coordinated
and tracked through the Controller.

---

## 6.6 Policy Deployment and Synchronization

Once approved, policies are distributed
from the Controller to all relevant agents.

Agents:
- Receive updated policy configurations
- Verify policy integrity
- Apply changes locally

Policy synchronization status is visible in the platform interface,
allowing administrators to confirm successful deployment.

---

## 6.7 Temporary Policy Overrides

In some operational scenarios,
temporary policy adjustments may be required.

Examples include:
- Maintenance activities
- Software updates
- Emergency troubleshooting

Temporary overrides allow specific actions
to be permitted for a limited time
while maintaining overall policy control.

Overrides are:
- Time-bound
- Logged and traceable
- Automatically reverted when expired

---

## 6.8 Policy Events and Visibility

Policy evaluation generates events
that provide visibility into system behavior.

These events may include:
- Allowed actions
- Blocked actions
- Policy mismatches
- Override usage

Policy-related events support
incident investigation, auditing,
and compliance reporting.

---

## 6.9 Best Practices for Policy Management

To ensure effective policy enforcement,
the following practices are recommended:

- Start with monitoring mode before enforcing new policies
- Apply changes gradually and in a controlled manner
- Review policy-related events regularly
- Use temporary overrides sparingly and document their purpose

Following these practices helps balance
security, usability, and operational continuity.

---

⬅ [Previous: Section 5 – Agents](section-5-agents.md)  
➡ [Next: Section 7 – Events and Alarms](section-7-events-and-alarms.md)

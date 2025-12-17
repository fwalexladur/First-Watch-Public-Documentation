# Section 9 – Operating Procedures

## 9.1 Purpose of Operating Procedures

Operating procedures describe the **standard actions** required to
install, operate, and maintain the **First Watch® Platform**
in a controlled and predictable manner.

These procedures are intended to:
- Support safe day-to-day operation
- Reduce the risk of misconfiguration
- Ensure consistency across environments
- Provide traceable operational practices

Detailed deployment automation and engineering internals
are documented separately in restricted documentation.

---

## 9.2 Agent Installation Overview

Agents must be installed on supported systems
before the platform can provide visibility or protection.

Agent installation typically involves:
- Preparing the target system
- Installing the appropriate agent package
- Verifying successful startup
- Enrolling the agent with the Controller

Once installed and enrolled,
the agent becomes visible in the platform interface
and begins reporting status and telemetry.

---

## 9.3 Agent Enrollment

Enrollment establishes a trusted relationship
between an agent and the Controller.

During enrollment:
- The agent registers its identity
- The Controller assigns default configuration
- Initial policies are applied
- Secure communication is established

Successful enrollment is required
before any monitoring or enforcement can occur.

---

## 9.4 Verifying Agent Operation

After installation and enrollment,
operators should verify that agents are functioning correctly.

Typical verification steps include:
- Confirming agent visibility in the platform interface
- Checking agent connectivity and health status
- Reviewing initial events and telemetry
- Ensuring policy synchronization is successful

Verification helps identify issues early
and ensures consistent protection.

---

## 9.5 Operating Modes

Agents may operate in different modes
depending on policy configuration and operational needs.

Common modes include:
- **Monitoring Mode** – Activity is observed and recorded without enforcement
- **Enforcement Mode** – Policies are actively enforced and violations are blocked

Selecting the appropriate mode
allows organizations to balance visibility,
control, and operational risk.

---

## 9.6 Maintenance Activities

Routine maintenance activities may be required
to ensure continued platform effectiveness.

Examples include:
- Updating policies
- Reviewing events and alarms
- Monitoring agent health
- Performing planned system updates

Maintenance activities should be performed
according to approved operational procedures
and, where applicable, within defined maintenance windows.

---

## 9.7 Handling Maintenance Windows

In operational environments,
certain activities must be restricted to maintenance windows.

Maintenance windows may be used for:
- System updates
- Policy adjustments
- Controlled testing activities

Proper coordination of maintenance windows
helps minimize disruption
and ensures predictable system behavior.

---

## 9.8 Decommissioning Agents

When a system is retired or removed from service,
its associated agent should be properly decommissioned.

Decommissioning typically includes:
- Disabling or removing the agent
- Removing associated assets from the inventory
- Verifying that no residual policies remain active

Proper decommissioning maintains
the accuracy and integrity of the asset inventory.

---

## 9.9 Operational Best Practices

To ensure reliable and secure operation,
the following practices are recommended:

- Verify agent status after configuration changes
- Introduce new policies in monitoring mode first
- Use enforcement mode only after validation
- Review events and alarms regularly
- Document operational changes and decisions

These practices support operational stability
and reduce the likelihood of unintended impact.

---

⬅ [Previous: Section 8 – Administration and Settings](section-8-administration.md)  
🔝 [Back to Development Index](README.md)



# Section 5 – Agents

## 5.1 Purpose of Agents

Agents are the primary mechanism through which the **First Watch® Platform**
interacts with and protects operational assets.

An agent provides:
- Visibility into system activity
- Local policy enforcement
- Secure communication with the Controller
- Telemetry required for monitoring and auditing

Agents enable the platform to operate directly within OT environments
while maintaining deterministic and controlled behavior.

---

## 5.2 Agent Types

The First Watch Platform supports multiple agent types,
each designed to protect a specific layer of the OT environment.

### 5.2.1 ControlGuard™

**ControlGuard™** is an endpoint agent installed on
Windows-based OT systems such as:
- SCADA servers
- HMIs
- Engineering workstations

Its primary responsibilities include:
- Monitoring process execution and module loading
- Enforcing application control and whitelisting policies
- Collecting file, process, and user activity data
- Reporting events and status to the Controller

ControlGuard operates deterministically, ensuring that only
explicitly authorized actions are permitted when enforcement is enabled.

---

### 5.2.2 PLC Guard™

**PLC Guard™** protects the industrial control layer
by monitoring PLC communication and configuration activity.

Its responsibilities include:
- Observing communication between engineering stations and PLCs
- Detecting unauthorized logic or firmware changes
- Enforcing access restrictions based on policy
- Providing visibility into control-level activity

PLC Guard extends platform protection beyond endpoints
into the process control domain.

---

## 5.3 Agent Installation and Enrollment

Before an agent becomes operational, it must be
installed and enrolled with the Controller.

The enrollment process:
- Establishes a trusted relationship with the Controller
- Registers the agent as a managed asset
- Applies the default configuration and policies

After enrollment, agents appear in the platform interface
with a name that reflects the system they protect
(for example, *Windows Agent – SCADA-01*).

---

## 5.4 Agent Status and Health

Each agent continuously reports its status to the Controller.

Typical status indicators include:
- Connectivity state
- Module availability
- Policy synchronization status
- Operational health

Monitoring agent health ensures that protection remains active
and that gaps in visibility are identified promptly.

---

## 5.5 Agent Configuration and Policies

Agents receive their configuration and policies
from the Controller.

This includes:
- Application control rules
- Monitoring and enforcement modes
- Update and maintenance settings

Configuration changes are centrally managed
and automatically distributed to enrolled agents.

---

## 5.6 Agent Events and Telemetry

Agents generate events based on observed activity
and policy evaluation.

Examples include:
- Process execution attempts
- Policy enforcement actions
- Configuration updates
- Connectivity changes

These events are forwarded to the Controller
for correlation, visualization, and investigation.

---

## 5.7 Agent Lifecycle Management

Throughout their lifecycle, agents may require:
- Updates or upgrades
- Certificate renewal
- Temporary disablement
- Decommissioning

All lifecycle actions are coordinated through the Controller
to ensure consistency and traceability.

---

## 5.8 Best Practices for Agent Management

To ensure effective agent operation, the following practices are recommended:

- Keep agents continuously connected to the Controller
- Monitor agent health and synchronization status
- Apply configuration changes in a controlled manner
- Investigate agents reporting repeated errors or disconnections

Following these practices helps maintain
reliable protection and operational stability.

---

⬅ [Previous: Section 4 – Assets](section-4-assets.md)  
➡ [Next: Section 6 – Policies](section-6-policies.md)

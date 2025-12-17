# Section 2 – Core Concepts

## 2.1 Purpose of Core Concepts

This section introduces the foundational concepts used throughout the **First Watch® Platform**.
Understanding these concepts is essential for correctly interpreting platform behavior,
configuring policies, and responding to events.

The core concepts define **what is protected**, **how protection is applied**, and **how
the platform represents operational environments**.

---

## 2.2 Assets

An **Asset** represents any entity within the monitored OT environment that is relevant
from a security or operational perspective.

Assets provide the contextual foundation for monitoring, policy enforcement,
event correlation, and reporting.

### 2.2.1 Hardware Assets

Hardware assets represent physical or virtual devices, including but not limited to:
- SCADA servers
- HMIs
- Engineering workstations
- PLCs and controllers
- Network devices

Hardware assets are identified through agents, network discovery, or manual registration.
Each hardware asset contains attributes such as hostname, IP address, operating system,
and communication interfaces.

---

### 2.2.2 Software Assets

Software assets represent applications, services, or components installed or executed
on hardware assets.

Examples include:
- SCADA and HMI applications
- Engineering tools
- System services
- Runtime components

Software assets are used to support application control, whitelisting,
and execution monitoring.

---

### 2.2.3 Accounts

Accounts represent users or service identities associated with asset activity.

Examples include:
- Local operating system users
- Domain users
- Service accounts
- SYSTEM-level accounts

Account information is used for attribution, access control,
and policy decision-making.

---

## 2.3 Agents

Agents are the primary mechanism through which the First Watch Platform
interacts with operational assets.

An agent provides visibility, telemetry, and enforcement capabilities
directly on or near the protected system.

### 2.3.1 ControlGuard™

**ControlGuard™** is an endpoint agent installed on Windows-based OT systems.

Its primary responsibilities include:
- Monitoring process execution and module loading
- Enforcing application control and whitelisting policies
- Collecting file, process, and user activity data
- Reporting events and status to the Controller

ControlGuard operates in a deterministic manner, ensuring that only
explicitly authorized actions are permitted when enforcement is enabled.

---

### 2.3.2 PLC Guard™

**PLC Guard™** is responsible for protecting programmable logic controllers
and industrial communication channels.

Its core functions include:
- Monitoring PLC communication
- Detecting unauthorized logic or firmware changes
- Enforcing policy-based access restrictions
- Providing visibility into control-level activity

PLC Guard extends platform protection from endpoints
into the industrial control layer.

---

## 2.4 Policies

A **Policy** defines the rules that govern allowed and disallowed actions
within the environment.

Policies are centrally managed by the Controller and distributed
to agents for enforcement.

At a high level, policies may control:
- Software execution
- Script usage
- Device communication
- Temporary exceptions and overrides

Detailed policy configuration and management
are covered in **Section 6 – Policies**.

---

## 2.5 Events and Alarms

The First Watch Platform continuously generates **events**
based on observed activity and policy evaluation.

- **Events** represent recorded actions or observations.
- **Alarms** represent events that require attention,
  investigation, or response.

Events and alarms are used for:
- Situational awareness
- Incident investigation
- Compliance reporting

Event and alarm handling is described in detail
in **Section 7 – Events and Alarms**.

---

## 2.6 Controller

The **Controller** is the central management component
of the First Watch Platform.

Its responsibilities include:
- Managing assets and agents
- Distributing policies
- Collecting and correlating events
- Providing user interface and reporting

All configuration changes and security decisions
are coordinated through the Controller.

---

## 2.7 Relationship Between Core Concepts

The relationship between core concepts can be summarized as follows:

- **Assets** represent what is protected
- **Agents** enforce protection on assets
- **Policies** define allowed behavior
- **Events and alarms** report observed activity
- **The Controller** orchestrates and correlates all components

Understanding these relationships is critical for
effective platform operation.

---

⬅ [Previous: Section 1 – Introduction](section-1-introduction.md)  
➡ [Next: Section 3 – Platform Interface Overview](section-3-platform-interface.md)

# Section 4 – Assets

## 4.1 Purpose of Asset Management

Asset management is a foundational capability of the **First Watch® Platform**.
Assets provide the contextual baseline required for monitoring, policy enforcement,
event correlation, and reporting.

By maintaining an accurate and up-to-date inventory of assets,
the platform enables operators and security teams to understand
**what exists in the environment**, **how components are related**,
and **where security-relevant activity occurs**.

---

## 4.2 Asset Types

The First Watch Platform categorizes assets into several logical types.
Each type represents a different aspect of the operational environment.

### 4.2.1 Hardware Assets

Hardware assets represent physical or virtual devices within the OT environment.

Typical examples include:
- SCADA servers
- Human–Machine Interfaces (HMIs)
- Engineering workstations
- Programmable Logic Controllers (PLCs)
- Network devices and communication gateways

Hardware assets are identified by attributes such as hostname,
IP address, operating system, and network interfaces.
They form the primary anchor point for associating software,
accounts, agents, and events.

---

### 4.2.2 Software Assets

Software assets represent applications, services, and components
installed or executed on hardware assets.

Examples include:
- SCADA and HMI applications
- Engineering and maintenance tools
- Runtime services and background processes
- System libraries and supporting components

Software assets are used to:
- Support application control and whitelisting
- Track execution behavior
- Provide visibility into software changes over time

---

### 4.2.3 Account Assets

Account assets represent identities associated with activity
on hardware or software assets.

These may include:
- Local operating system accounts
- Domain accounts
- Service accounts
- SYSTEM-level identities

Account assets enable attribution of actions,
support access control decisions,
and assist in incident investigation.

---

## 4.3 Asset Discovery and Registration

Assets can be discovered and registered through multiple mechanisms,
depending on deployment configuration and enabled components.

Common discovery sources include:
- Agent-based discovery via ControlGuard™
- Network-based observation via PLC Guard™
- Manual registration by administrators

Discovered assets are automatically added to the asset inventory
and updated as new information becomes available.

---

## 4.4 Asset Attributes and Details

Each asset contains a set of attributes that describe its identity,
state, and relationships.

Typical asset attributes may include:
- Identification details (name, type, ID)
- Network information (IP address, interfaces)
- Operating system or firmware information
- Associated agents
- Related software and accounts

Asset detail views allow users to inspect this information
and understand how the asset fits within the broader environment.

---

## 4.5 Asset Relationships

The First Watch Platform maintains relationships between assets
to provide contextual awareness.

Examples of asset relationships include:
- Software running on specific hardware
- Accounts associated with user activity
- Agents protecting specific systems
- Events and alarms linked to assets

These relationships enable effective filtering,
correlation, and root-cause analysis.

---

## 4.6 Asset History and Snapshots

Assets maintain historical records that capture changes over time.
This includes:
- Attribute changes
- Software additions or removals
- Agent status updates
- Communication and activity history

Historical snapshots support:
- Incident investigation
- Change tracking
- Compliance and audit requirements

---

## 4.7 Using Assets for Monitoring and Security

Assets serve as the foundation for most platform functionality.

They are used to:
- Scope policies and enforcement
- Filter events and alarms
- Generate reports
- Identify affected systems during incidents

Accurate asset management is therefore critical
to effective platform operation.

---

## 4.8 Best Practices for Asset Management

To maintain an accurate and reliable asset inventory,
the following practices are recommended:

- Ensure agents remain connected and operational
- Periodically review asset attributes for accuracy
- Investigate unknown or unexpected assets promptly
- Use asset relationships to validate system topology

These practices help maintain situational awareness
and reduce operational risk.

---

⬅ [Previous: Section 3 – Platform Interface Overview](section-3-platform-interface.md)  
➡ [Next: Section 5 – Agents](section-5-agents.md)

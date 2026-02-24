# Release Notes 4.3.6 – Security Monitoring & Policy Baseline Update

**Status:** Internal / Customer Review  
**Target Version:** 4.3.6  
**Release Type:** Feature / Security / Maintenance

---

## Summary

This release strengthens the platform’s **security monitoring baseline and policy consistency**, with a focus on improved visibility into endpoint security activity, safer default configurations, and operational correctness. Several internal improvements and fixes contribute to more reliable system behaviour without increasing deployment complexity.

---

## New Capabilities

### Baseline Policy Management
- Improved baseline policy management to support consistent and controlled establishment of a secure posture.
- Simplifies onboarding and ensures predictable initial configuration across deployments.

---

### Operational Control Enhancements
- Enhanced management workflows to support safer and more intuitive execution of security-related actions.
- Reduces reliance on manual procedures and backend access.

---

## Security Monitoring Improvements

### Enhanced Endpoint Security Visibility
- Expanded security monitoring coverage for endpoint operating systems.
- Improves detection and visibility of security-relevant system activity.

---

### Default Security Policies
- Updated default security policies to reflect a curated and reviewed baseline.
- Default configurations prioritise relevance, stability, and signal quality.

---

### Improved Alerting
- Introduced additional security alerts aligned with the updated monitoring baseline.
- Alerts are designed to surface meaningful conditions while minimising operational noise.

---

## Configuration & Policy Updates

### Default Policy Set Rationalisation
- Cleaned up legacy default configurations and introduced a simplified, intentional set of baseline policies.
- Improves clarity and reduces the risk of unintended behaviour in new deployments.

---

## Stability & Reliability Fixes

### Asset Identity Consistency
- Improved handling of asset identity updates to ensure consistent representation across the platform.
- Reduces discrepancies in environments where system attributes may change during operation.

---

## Compliance & Assurance Summary

This release supports alignment with recognised cybersecurity and information security frameworks, including **IEC 62443** and **ISO/IEC 27001**, by strengthening baseline controls, monitoring visibility, and operational consistency.

### Alignment with IEC 62443 (Industrial Automation & Control Systems)

The updates in this release contribute to the following IEC 62443 security concepts:

- **Security Baseline Establishment**  
  Supports the definition and application of a consistent baseline security configuration across assets, aligning with the principle of defined security levels and system hardening.

- **Continuous Security Monitoring**  
  Enhances visibility into security-relevant activity at the system level, supporting ongoing monitoring and detection of abnormal or undesirable behaviour.

- **Reduced Configuration Complexity**  
  Rationalisation of default policies reduces the likelihood of misconfiguration, supporting secure system integration and maintenance.

- **Operational Integrity**  
  Improvements in asset identity consistency support accurate system representation and reliable security monitoring.

---

### Alignment with ISO/IEC 27001 (Information Security Management)

The changes introduced in this release support several ISO/IEC 27001 control objectives:

- **A.5 – Organisational Controls**  
  Improved baseline management contributes to consistent application of security policies.

- **A.8 – Asset Management**  
  Enhanced asset identity handling supports accurate identification and management of information assets.

- **A.12 – Operations Security**  
  Expanded monitoring capabilities support logging, monitoring, and operational oversight.

- **A.14 – System Acquisition, Development and Maintenance**  
  Controlled introduction and rationalisation of default configurations support secure system lifecycle practices.

---

### Assurance Note

These enhancements are designed to **support** compliance and assurance activities.  
They do not, by themselves, constitute certification or formal compliance with IEC 62443 or ISO/IEC 27001, which depend on organisational processes, governance, and independent assessment.

---

## Notes

- This release focuses on **baseline hardening and correctness**, rather than expanding functional scope.
- Security monitoring behaviour remains configurable to suit customer-specific requirements.
- No changes are required to existing deployments unless adopting the updated default baseline.

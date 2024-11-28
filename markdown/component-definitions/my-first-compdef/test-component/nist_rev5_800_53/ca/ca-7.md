---
x-trestle-comp-def-rules:
  test-component:
    - name: rule-ca-7
      description: Rule for ca-7
x-trestle-param-values:
  ca-7_prm_4:
  ca-7_prm_5:
  ca-07_odp.01:
  ca-07_odp.02:
  ca-07_odp.03:
  ca-07_odp.04:
  ca-07_odp.05:
  ca-07_odp.06:
  ca-07_odp.07:
x-trestle-global:
  profile:
    title: NIST Special Publication 800-53 Revision 5 HIGH IMPACT BASELINE
    href: trestle://profiles/nist_rev5_800_53/profile.json
  sort-id: ca-07
---

# ca-7 - \[Assessment, Authorization, and Monitoring\] Continuous Monitoring

## Control Statement

Develop a system-level continuous monitoring strategy and implement continuous monitoring in accordance with the organization-level continuous monitoring strategy that includes:

- \[a.\] Establishing the following system-level metrics to be monitored: {{ insert: param, ca-07_odp.01 }};

- \[b.\] Establishing {{ insert: param, ca-07_odp.02 }} for monitoring and {{ insert: param, ca-07_odp.03 }} for assessment of control effectiveness;

- \[c.\] Ongoing control assessments in accordance with the continuous monitoring strategy;

- \[d.\] Ongoing monitoring of system and organization-defined metrics in accordance with the continuous monitoring strategy;

- \[e.\] Correlation and analysis of information generated by control assessments and monitoring;

- \[f.\] Response actions to address results of the analysis of control assessment and monitoring information; and

- \[g.\] Reporting the security and privacy status of the system to {{ insert: param, ca-7_prm_4 }} {{ insert: param, ca-7_prm_5 }}.

## Control Assessment Objective

- \[CA-07[01]\] a system-level continuous monitoring strategy is developed;

- \[CA-07[02]\] system-level continuous monitoring is implemented in accordance with the organization-level continuous monitoring strategy;

- \[CA-07a.\] system-level continuous monitoring includes establishment of the following system-level metrics to be monitored: {{ insert: param, ca-07_odp.01 }};

- \[CA-07b.\]

  - \[CA-07b.[01]\] system-level continuous monitoring includes established {{ insert: param, ca-07_odp.02 }} for monitoring;
  - \[CA-07b.[02]\] system-level continuous monitoring includes established {{ insert: param, ca-07_odp.03 }} for assessment of control effectiveness;

- \[CA-07c.\] system-level continuous monitoring includes ongoing control assessments in accordance with the continuous monitoring strategy;

- \[CA-07d.\] system-level continuous monitoring includes ongoing monitoring of system and organization-defined metrics in accordance with the continuous monitoring strategy;

- \[CA-07e.\] system-level continuous monitoring includes correlation and analysis of information generated by control assessments and monitoring;

- \[CA-07f.\] system-level continuous monitoring includes response actions to address the results of the analysis of control assessment and monitoring information;

- \[CA-07g.\]

  - \[CA-07g.[01]\] system-level continuous monitoring includes reporting the security status of the system to {{ insert: param, ca-07_odp.04 }} {{ insert: param, ca-07_odp.05 }};
  - \[CA-07g.[02]\] system-level continuous monitoring includes reporting the privacy status of the system to {{ insert: param, ca-07_odp.06 }} {{ insert: param, ca-07_odp.07 }}.

## Control guidance

Continuous monitoring at the system level facilitates ongoing awareness of the system security and privacy posture to support organizational risk management decisions. The terms "continuous" and "ongoing" imply that organizations assess and monitor their controls and risks at a frequency sufficient to support risk-based decisions. Different types of controls may require different monitoring frequencies. The results of continuous monitoring generate risk response actions by organizations. When monitoring the effectiveness of multiple controls that have been grouped into capabilities, a root-cause analysis may be needed to determine the specific control that has failed. Continuous monitoring programs allow organizations to maintain the authorizations of systems and common controls in highly dynamic environments of operation with changing mission and business needs, threats, vulnerabilities, and technologies. Having access to security and privacy information on a continuing basis through reports and dashboards gives organizational officials the ability to make effective and timely risk management decisions, including ongoing authorization decisions.

Automation supports more frequent updates to hardware, software, and firmware inventories, authorization packages, and other system information. Effectiveness is further enhanced when continuous monitoring outputs are formatted to provide information that is specific, measurable, actionable, relevant, and timely. Continuous monitoring activities are scaled in accordance with the security categories of systems. Monitoring requirements, including the need for specific monitoring, may be referenced in other controls and control enhancements, such as [AC-2g](#ac-2_smt.g), [AC-2(7)](#ac-2.7), [AC-2(12)(a)](#ac-2.12_smt.a), [AC-2(7)(b)](#ac-2.7_smt.b), [AC-2(7)(c)](#ac-2.7_smt.c), [AC-17(1)](#ac-17.1), [AT-4a](#at-4_smt.a), [AU-13](#au-13), [AU-13(1)](#au-13.1), [AU-13(2)](#au-13.2), [CM-3f](#cm-3_smt.f), [CM-6d](#cm-6_smt.d), [CM-11c](#cm-11_smt.c), [IR-5](#ir-5), [MA-2b](#ma-2_smt.b), [MA-3a](#ma-3_smt.a), [MA-4a](#ma-4_smt.a), [PE-3d](#pe-3_smt.d), [PE-6](#pe-6), [PE-14b](#pe-14_smt.b), [PE-16](#pe-16), [PE-20](#pe-20), [PM-6](#pm-6), [PM-23](#pm-23), [PM-31](#pm-31), [PS-7e](#ps-7_smt.e), [SA-9c](#sa-9_smt.c), [SR-4](#sr-4), [SC-5(3)(b)](#sc-5.3_smt.b), [SC-7a](#sc-7_smt.a), [SC-7(24)(b)](#sc-7.24_smt.b), [SC-18b](#sc-18_smt.b), [SC-43b](#sc-43_smt.b) , and [SI-4](#si-4).

______________________________________________________________________

## What is the solution and how is it implemented?

<!-- For implementation status enter one of: implemented, partial, planned, alternative, not-applicable -->

<!-- Note that the list of rules under ### Rules: is read-only and changes will not be captured after assembly to JSON -->

<!-- Add control implementation description here for control: ca-7 -->

### Rules:

  - rule-ca-7

### Implementation Status: planned

______________________________________________________________________
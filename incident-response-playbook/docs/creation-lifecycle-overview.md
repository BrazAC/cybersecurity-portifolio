## The incident response life cycle
The NIST **Incident Response Recommendations and Considerations for Cybersecurity Risk Management: A CSF 2.0 Community Profile** [1] describes an incident response process divided into phases: preparation, detection and analysis, containment, eradication and recovery. This document describes briefly each of these phases.

## Preparation
Here the organization must prepare for the incident **before** its ocurrence. Creating and documenting policies and courses of action, defining systems and network baselines to define normal activity, instrumenting the environment to detect suspicious activity, establishing means to collect forensic data after the incident, preparing additional infrastructure to deal with complex incidents. The objective is diminish detection, containment and recovery time.  

## Detection and analysis
With sufficient baseline information, detection technology and documented procedures, the CIRT personnel must be able to detect suspicious activity and correctly classify it as malicious or not. In cases of malicious activity, data about the perimeter, internal network and endpoint (server and host) must be collected as evidence for any potential law enforcement investigation. The investigation scope must evolve as new indicators of compromise appear. That way, **an incident is scoped over time, and his scope must be shared with stakeholders to ensure a common operating picture**.  

## Containment
The objective of this phase is reduce immediate impact and prevent further damage by removing adversary access. The containment strategy varies with the complexity of the incident. The course of action choice must consider: additional negative impacts to mission operations and availability of services, duration of containment process and impact on the collection and preservation of evidence.  
The response strategy may "tip off" the adversary detection, some adversaries may see that and change their methods. **Defenders should take a profile of possible attacker capabilities** and consider it while planning the course of action.  

## Eradication and recovery
 This phase ensures all attackers means of network access are ceased, all incident artifacts were removed and all evidence has been collected. This phase is likely a iterative proccess, with hardening and changes of environment. See NIST **Guide for Cybersecurity Event Recovery** [2] for additional guidance.  
 The recovery part consists of restoring systems to normal operations and confirm they are functioning normally. It may include rebuilding systems, restoring or recreating data and reconnecting networks. Furthermore, vigilance and controls must be enhanced to validate the recovery plan execution and confirm that all adversary activity was ceased.

## References
 - **[1]**  Nelson A, Rekhi S, Souppaya M, Scarfone K (2025) Incident Response Recommendations and Considerations for Cybersecurity Risk Management: A CSF 2.0 Community Profile. (National Institute of Standards and Technology, Gaithersburg, MD), NIST Special Publication (SP) NIST SP 800-61r3. https://doi.org/10.6028/NIST.SP.800-61r3  
 - **[2]** Bartock M, Cichonski J, Souppaya M, Smith MC, Witte G, Scarfone K (2016) *Guide for Cybersecurity Event Recovery*. National Institute of Standards and Technology, Gaithersburg, MD, NIST Special Publication (SP) 800-184. https://doi.org/10.6028/NIST.SP.800-184

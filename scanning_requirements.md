# Scanning Requirements

Scanning requirements are also outlined in the FedRAMP Continuous
Monitoring Strategy Guide and the FedRAMP Low, Moderate, and High
security control baselines.

This document expands on the original requirements:

- **Scanner Resiliency:** Scanners should be hardened to resist
  unauthorized use or modiﬁcation (i.e., unnecessary ports and/or
  unnecessary services should be closed).

- **Authenticated Scanning:** For Moderate and High systems, the CSP
  must ensure authenticated scans are performed wherever possible.
  \[RA-5(5)\]

- **Scanning with Full Authorization:** For all Moderate and High
  systems, the CSP must ensure that scans are being performed with full
  system authorization. \[RA-5(5)\]

  - Scanning must avoid typical lack of authorization issues (including
    lack of access to remote registry, limited registry access,
    limited ﬁle access, etc.).

- **Machine-Readable Findings:** The scan output must display all scan
  ﬁndings with a low risk or higher in a structured, machine-readable
  format (such as XML, CSV, or JSON).

  - If the scanner is able to output/export ﬁndings in more than one
    machine-readable format, the CSP must select the format that
    provides the greatest amount of information.

  - Where possible, the machine-readable data must include the
    authentication and authorization status of the scans to
    demonstrate the degree to which an authenticated scan was
    performed on each host.

- **National Vulnerability Database (NVD):** For any vulnerability
  listed in the latest version of the National Institute of Standards
  and Technology (NIST) NVD, the Common Vulnerabilities and Exposures
  (CVE) reference number must be included with the machine-readable
  ﬁndings data for that vulnerability.

- **Common Vulnerability Scoring System (CVSS) Risk Scoring:** For any
  vulnerability with a CVSSv3 base score assigned in the latest version
  of the NVD, the CVSSv3 base score must be used as the original risk
  rating. If no CVSSv3 score is available, a CVSSv2 base score is
  acceptable where available. If no CVSS score is available, the native
  scanner base risk score can be used.

- **Conﬁguration Settings:** The CSP must provide machine-readable
  evidence that the scanner’s conﬁguration settings have not been
  altered from the 3PAO-validated conﬁguration settings approved during
  the initial authorization assessment.

- **Conﬁguration Changes:** If a scanner conﬁguration change is required
  (above and beyond normal patching and updates) the AO must be notiﬁed
  and approve of the change.

- **Signature Updates:** For each deliverable, the CSP must update the
  list of vulnerabilities scanned to the latest available list.
  \[RA-5(2)\]

  - The CSP must use a vulnerability scanner that checks for automatic
    signature updates of the scanner’s vulnerability database at least
    monthly.

  - The CSP must provide automated machine-readable evidence of the most
    recent update performed prior to scanning.

- **Adequate Asset Identiﬁcation:** The scanner ﬁndings must contain
  unique asset identiﬁers that map to an inventory.

  - The CSP must have an automated mechanism to identify and catalog all
    assets, within the authorization boundary, every month in order to
    ensure that everything is being scanned appropriately

  - For Web scans, a dynamically updated catalog of Web services should
    be maintained to include the ports where Web services reside.

- **Types of Scans:** CSPs must scan operating systems, Web
  applications, and databases monthly. All scan reports must be sent to
  the AO/JAB monthly. \[RA-5\]

  - The entire inventory (or approved sampling percentage) within the
    boundary must be scanned at the operating system (OS) level at
    least once a month.

  - All Web interfaces and services (or approved sampling percentage)
    must be scanned.

  - All databases (or approved sampling percentage) must be scanned,
    including those required to support the infrastructure.

- **Plan of Action and Milestones (POA&M) Entries:** The CSP must track
  each unique vulnerability as an individual POA&M item.

  - Individual vulnerabilities must be based on the scanning tool’s
    unique vulnerability reference identiﬁer (ID).

  - The CSP may break a unique vulnerability into multiple POA&M items,
    such as for a vulnerability that applies to different asset types
    that will be remediated in different ways.

  - The CSP must not group multiple unique vulnerabilities into a single
    POA&M item.

- **All Non-Destructive Detections:** The CSP must enable all
  non-destructive detections within the scanner.

- **Image Scanning:** Where the CSP offers services, such as virtual
  images, and where the customer is responsible for scanning but is
  reliant on the CSP for patching, the CSP must scan the source image
  for all available customer leveraged images.

  - This applies to all images in use or available for use by federal
    government customers.

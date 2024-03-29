# FedRAMP<sup>®</sup> Vulnerability Scanning Requirements

## Version 2.0 02/15/2024

### [info@fedramp.gov](mailto:Info@fedRAMP.gov)

### fedramp.gov

# DOCUMENT REVISION HISTORY

<table>
<colgroup>
<col style="width: 14%" />
<col style="width: 13%" />
<col style="width: 11%" />
<col style="width: 37%" />
<col style="width: 23%" />
</colgroup>
<thead>
<tr class="header">
<th><blockquote>
<p><strong>Date</strong></p>
</blockquote></th>
<th><blockquote>
<p><strong>Version</strong></p>
</blockquote></th>
<th><blockquote>
<p><strong>Page(s)</strong></p>
</blockquote></th>
<th><blockquote>
<p><strong>Description</strong></p>
</blockquote></th>
<th><blockquote>
<p><strong>Author</strong></p>
</blockquote></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td>03/20/2018</td>
<td><blockquote>
<p>1.0</p>
</blockquote></td>
<td><blockquote>
<p>All</p>
</blockquote></td>
<td><blockquote>
<p>Initial document that replaces FedRAMP JAB P-ATO Vulnerability Scan
Requirements Guide</p>
</blockquote></td>
<td>FedRAMP PMO</td>
</tr>
</tbody>
</table>

<table>
<colgroup>
<col style="width: 14%" />
<col style="width: 11%" />
<col style="width: 11%" />
<col style="width: 39%" />
<col style="width: 23%" />
</colgroup>
<thead>
<tr class="header">
<th>07/14/2022</th>
<th><blockquote>
<p>2.0</p>
</blockquote></th>
<th>All</th>
<th><blockquote>
<p>Added in Container guidance and</p>
</blockquote></th>
<th>FedRAMP PMO</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td></td>
<td></td>
<td></td>
<td><blockquote>
<p>updated language throughout</p>
</blockquote></td>
<td></td>
</tr>
<tr class="even">
<td>02/15/2024</td>
<td><blockquote>
<p>3.0</p>
</blockquote></td>
<td>All</td>
<td><blockquote>
<p>Consolidated all required scanning</p>
</blockquote></td>
<td>FedRAMP PMO</td>
</tr>
<tr class="odd">
<td colspan="3" rowspan="5"></td>
<td><blockquote>
<p>requirements. Added and reﬁned</p>
</blockquote></td>
<td></td>
</tr>
<tr class="even">
<td><blockquote>
<p>language for container scanning,</p>
</blockquote></td>
<td></td>
</tr>
<tr class="odd">
<td><blockquote>
<p>encryption and reporting. Clariﬁed</p>
</blockquote></td>
<td></td>
</tr>
<tr class="even">
<td><blockquote>
<p>supplemental scanning</p>
</blockquote></td>
<td></td>
</tr>
<tr class="odd">
<td><blockquote>
<p>remediation reporting.</p>
</blockquote></td>
<td></td>
</tr>
</tbody>
</table>

# ABOUT THIS DOCUMENT

This document has been developed to provide guidance on vulnerability
scanning policy, procedures, and tools in support of achieving and
maintaining a security authorization that meets the Federal Risk and
Authorization Management Program (FedRAMP) requirements.

Some cloud service providers (CSPs) may need to transition from their
current vulnerability scanners or work with their vendors in order to
meet the requirements.

This document is not a FedRAMP template – there is nothing to ﬁll out
in this document.

This document uses the term authorizing ofﬁcial (AO). For systems with
a Joint Authorization Board (JAB) provisional authorization to operate
(P-ATO), AO refers primarily to the JAB unless this document
explicitly says agency AO. For systems with a FedRAMP Agency
Authorization to Operate (ATO), AO refers to each leveraging agency’s
AO.

# WHO SHOULD USE THIS DOCUMENT?

This document is intended to be used by CSPs, third party assessment
organizations (3PAOs), government contractors working on FedRAMP
projects, and government employees working on FedRAMP projects.

### How to Contact Us
Questions about FedRAMP or this document should be directed to
<info@fedramp.gov>. For more information about FedRAMP, visit the
website at [http://www.fedramp.gov](http://www.fedramp.gov/).


# TABLE OF CONTENTS

1. [Purpose](#purpose) 
2. [Background](#background) 
3. [Scanning Requirements](#scanning-requirements) 
4. [Scanning Requirements for Systems Using Container Technology](#scanning-requirements-for-systems-using-container-technology) 
5. [Appendix A: Glossary](#appendix-a-glossary)

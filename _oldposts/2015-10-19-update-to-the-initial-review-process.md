---
id: 38922
title: 'Lessons Learned: Initial Reviews'
date: 2015-10-19T15:28:41+00:00
author: FedRAMP
layout: default
guid: https://www.fedramp.gov/?p=38922
permalink: /update-to-the-initial-review-process/
make_faq_page:
  - ""
hide_title:
  - 'No'
header_layout:
  - Default
centercatnav:
  - 'No'
remove_thumb:
  - 'No'
hide_auth_bio:
  - 'No'
post_featcontent:
  - 'No'
post_featpages:
  - 'No'
amazonS3_cache:
  - 'a:4:{s:113:"https://s3.amazonaws.com/sitesusa/wp-content/uploads/sites/482/2015/03/Guide-to-Understanding-FedRAMP-v2.0-4.docx";i:18842;s:119:"https://s3.amazonaws.com/sitesusa/wp-content/uploads/sites/482/2015/07/FedRAMP-General-Document-Acceptance-Criteria.pdf";i:32722;s:106:"https://s3.amazonaws.com/sitesusa/wp-content/uploads/sites/482/2015/08/FedRAMP-Initial-Review-SOP-v1-3.pdf";i:35702;s:126:"https://s3.amazonaws.com/sitesusa/wp-content/uploads/sites/482/2015/08/FedRAMP-SAR-Initial-Review-Checklist-Template-v1-0.xlsx";a:1:{s:9:"timestamp";i:1485468728;}}'
categories:
  - FedRAMP
  - FedRAMP Process
  - FedRAMP Status
  - Newsletter
  - Resource
---
Over the past few months, the FedRAMP PMO has conducted nearly 20 [Initial Reviews](https://s3.amazonaws.com/sitesusa/wp-content/uploads/sites/482/2015/08/FedRAMP-Initial-Review-SOP-v1-3.pdf) of CSP packages. These reviews evaluated twenty-one Critical Controls for readability, relevance, sufficiency, and consistency. FedRAMP’s definition of each criteria is as follows:

<li style="font-weight: 400">
  <b>Readable: </b>Can we understand what was written?
</li>
<li style="font-weight: 400">
  <b>Relevant: </b>Did the statement actually address the control requirement?
</li>
<li style="font-weight: 400">
  <b>Sufficient:</b> Is there enough detail to fully address all portions of the requirement and meet any security related needs?  <ul>
    <li style="font-weight: 400">
      Tip: This is usually the “how” of a control statement.
    </li>
  </ul>
</li>

<li style="font-weight: 400">
  <b>Consistent:</b> Do the implementation statements and the control template checkboxes match? <ul>
    <li style="font-weight: 400">
      Tip: Is &#8220;Implemented&#8221; checked when a response describes the solution is in place?
    </li>
  </ul>
</li>

The Critical Controls evaluated were:

<li style="font-weight: 400">
  Access Control &#8211; AC-2, AC-4, AC-17 
</li>
<li style="font-weight: 400">
  Certification Authority &#8211; CA-1
</li>
<li style="font-weight: 400">
  Configuration Management &#8211; CM-6
</li>
<li style="font-weight: 400">
  Contingency Planning &#8211; CP-7, CP-9
</li>
<li style="font-weight: 400">
  Identification and Authentication &#8211; IA-2(1), IA-2(2), IA-2(3), IA-2(11), IA-2(12)
</li>
<li style="font-weight: 400">
  Incident Response Plan &#8211; IR-8
</li>
<li style="font-weight: 400">
  Risk Assessment &#8211; RA-5, RA-5(5), RA-5(8)
</li>
<li style="font-weight: 400">
  System and Services Acquisition &#8211; SA-11, SA-11(1)
</li>
<li style="font-weight: 400">
  System and Communications Protection &#8211; SC-4, SC-7, SC-13
</li>

The PMO was able to gain some key insights from the analysis of these reviews. While most authorization packages passed the readability and relevancy requirements, many were unable to pass the requirements for sufficiency and consistency. 

<li style="font-weight: 400">
  <b>Readability: </b>Nearly all of the packages passed the readability test for all of the evaluated Critical Controls. <ul>
    <li style="font-weight: 400">
      AC-17 was the easiest for vendors &#8211; receiving a 100% score on readability for all reviews. 
    </li>
    <li style="font-weight: 400">
      SA-11, on the other hand, seemed to be the hardest &#8211; only receiving a passing readability rating of 47%.
    </li>
  </ul>
</li>

<li style="font-weight: 400">
  <b>Relevance: </b>More than half of the evaluated packages passed the relevance test for all of the Critical Controls. <ul>
    <li style="font-weight: 400">
      Eleven of the twenty-one controls received a 71% or higher relevance rating. 
    </li>
  </ul>
</li>

<li style="font-weight: 400">
  <b>Sufficiency and Consistency: </b>Nearly all of the packages were unable to prove sufficiency or consistency for all the of the Critical Controls. <ul>
    <li style="font-weight: 400">
      SC-13 (FIPS-validated or NSA-Approved Cryptography) was the only Critical Control to received passing marks above 70% across the packages for readability, relevance, sufficiency, and consistency. 
    </li>
    <li style="font-weight: 400">
      Four controls (CA-1, CM-6, CP-9, and RA-5) proved to be the most problematic for our vendors when examining sufficiency and consistency reviews. Only about 10% of the packages reviewed were deemed sufficient for these four controls.
    </li>
  </ul>
</li>

**SO WHAT’S THE TAKEAWAY HERE?**

From the PMO, we’re going to revise some of our guidance to give clearer information and insights on how to appropriately address these critical controls. These initial reviews are also continually being adjusted to include more automation, and where possible we’ll be making these tools publicly available. 

However, it’s not all just on us at the PMO. We need our CSPs to review our guidance and come prepared. We’re continually working to provide self-help tools and guidance for CSPs to review in order to be able to provide CSP packages that will pass these reviews the first time. Below is a list of the key tools and documents every CSP should ensure they review prior to submission for an initial review:

<li style="font-weight: 400">
  <a href="https://www.fedramp.gov/resources/training/">Training Module on SSP Development</a>
</li>
<li style="font-weight: 400">
  <a href="https://s3.amazonaws.com/sitesusa/wp-content/uploads/sites/482/2015/03/Guide-to-Understanding-FedRAMP-v2.0-4.docx">The Guide to Understanding FedRAMP</a>
</li>
<li style="font-weight: 400">
  <a href="https://s3.amazonaws.com/sitesusa/wp-content/uploads/sites/482/2015/07/FedRAMP-General-Document-Acceptance-Criteria.pdf">FedRAMP General Document Acceptance Criteria</a>
</li>
<li style="font-weight: 400">
  <a href="https://s3.amazonaws.com/sitesusa/wp-content/uploads/sites/482/2015/08/FedRAMP-Initial-Review-SOP-v1-3.pdf">FedRAMP Initial Review Standard Operating Procedure</a> and <a href="https://s3.amazonaws.com/sitesusa/wp-content/uploads/sites/482/2015/08/FedRAMP-SAR-Initial-Review-Checklist-Template-v1-0.xlsx">Checklist</a>
</li>
<li style="font-weight: 400">
  <a href="https://www.fedramp.gov/category/tips/">Weekly Tips and Cues</a>
</li>

As always, we also welcome your feedback and would like to see any other suggestions for additional information you feel is missing or would be helpful for FedRAMP to provide. Please don’t hesitate to send any suggestions to info@fedramp.gov!

&nbsp;

&nbsp;
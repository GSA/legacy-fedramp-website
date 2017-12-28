---
id: 62181
title: How Much Does It Cost to Go Through FedRAMP?
date: 2016-09-08T11:02:24+00:00
author: Matt Goodrich
layout: default
guid: https://www.fedramp.gov/?p=62181
permalink: /how-much-does-it-cost-to-go-through-fedramp/
make_faq_page:
  - null
make_faq_shortcode:
  - ""
bgFAQfoldup:
  - default
bgFAQvisualCue:
  - default
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
  - 'a:2:{s:112:"https://s3.amazonaws.com/sitesusa/wp-content/uploads/sites/482/2016/09/Screen-Shot-2016-09-08-at-10.34.00-AM.png";i:62211;s:120:"https://s3.amazonaws.com/sitesusa/wp-content/uploads/sites/482/2016/09/Screen-Shot-2016-09-08-at-10.34.00-AM-300x293.png";i:62211;}'
categories:
  - Cloud Service Provider
  - FedRAMP Blog
  - Focus on FedRAMP
---
<img class="wp-image-62211 alignright" src="https://s3.amazonaws.com/sitesusa/wp-content/uploads/sites/482/2016/09/Screen-Shot-2016-09-08-at-10.34.00-AM.png" alt="screen-shot-2016-09-08-at-10-34-00-am" width="295" height="289" srcset="https://s3.amazonaws.com/sitesusa/wp-content/uploads/sites/482/2016/09/Screen-Shot-2016-09-08-at-10.34.00-AM.png 440w, https://s3.amazonaws.com/sitesusa/wp-content/uploads/sites/482/2016/09/Screen-Shot-2016-09-08-at-10.34.00-AM-300x293.png 300w" sizes="(max-width: 295px) 100vw, 295px" />One of the questions we get asked the most at FedRAMP from our vendors is: “How much will it cost me to get through FedRAMP?” One of the reasons this is a hard question to answer is that comparing cloud providers to each other isn’t even like trying to compare apples to oranges &#8211; those are both at least fruit. Comparing a global content distribution network to a government only ticketing and CRM solution and then comparing to a web-based agile project management tool is like comparing an apple to a bike to a television. The size, complexity, and scope of services of the systems varies greatly and makes a comparison incredibly hard.

But, just because a question is hard to answer doesn’t mean I shy away from trying to answer it. Recently I engaged with 4 of our cloud service providers to ask them to help us identify the overall costs for going through FedRAMP. In order to have a good place to start, I chose 4 vendors who were relatively similar. All 4 vendors owned their own infrastructure, three were IaaS solutions, one a SaaS solution. **They all also went through the JAB for their authorization through the old process prior to** [**FedRAMP Accelerated**](https://www.fedramp.gov/participate/fedramp-accelerated-process/). When talking to these providers, we knew there were lots of factors to consider in overall cost, so we tried to break it down into five main areas:

<li style="font-weight: 400">
  <b>Engineering</b> <ul>
    <li style="font-weight: 400">
      $1,100,000 average cost.
    </li>
    <li style="font-weight: 400">
      These are costs associated with implementing technical changes to a system to meet the Federal requirements at the moderate impact level (e.g. FIPS 140-2 encryption, PIV/CAC for authentication, etc.)
    </li>
  </ul>
</li>

<li style="font-weight: 400">
  <b>Documentation</b> <ul>
    <li style="font-weight: 400">
      $400,000 average cost
    </li>
    <li style="font-weight: 400">
      These are costs associated with documenting the system in policies and procedures, the System Security Plan, Incident Response Plan, etc.
    </li>
  </ul>
</li>

<li style="font-weight: 400">
  <b>3PAO Assessment</b> <ul>
    <li style="font-weight: 400">
      $500,000 average cost
    </li>
    <li style="font-weight: 400">
      These are costs associated with the independent assessment by a FedRAMP Accredited 3PAO including the development of a test plan, onsite assessment, creation of the security assessment report and briefings to authorizing officials.
    </li>
  </ul>
</li>

<li style="font-weight: 400">
  <b>FedRAMP JAB Review</b> <ul>
    <li style="font-weight: 400">
      $250,000 average cost
    </li>
    <li style="font-weight: 400">
      These are costs associated with updates required due to meeting the JAB requirements (e.g. areas where a CSP didn’t fully meet the FedRAMP requirements prior to entering the assessment process).
    </li>
  </ul>
</li>

<li style="font-weight: 400">
  <b>Continuous Monitoring</b> <ul>
    <li style="font-weight: 400">
      $1,000,000 average cost
    </li>
    <li style="font-weight: 400">
      This is the yearly ongoing costs associated with monthly vulnerability scans, POA&M management, significant changes, and annual assessments.
    </li>
  </ul>
</li>

So the total median cost for a mid-range CSP was $2,250,000 to achieve a FedRAMP authorization. This splits pretty cleanly with about 50% of that being on engineering costs and 50% on the process itself. Additionally, about $1,000,000 a year maintaining an acceptable risk posture through Continuous Monitoring. 

However, even with vendors with similar scopes and services &#8211; the variance between the four was large. The costs ranged from just under $500,000 for one vendor to a little over $4,000,000 for another vendor. When digging into these variances, there were three areas that significantly changed the costs for vendors: 

<li style="font-weight: 400">
  Outside consultants helping with documentation increased the documentation cost but decreased the 3PAO Assessment and JAB Review costs. 
</li>
<li style="font-weight: 400">
  3PAO assessments ranged from one to six months for the CSPs, and (not shockingly) the cost associated with the audit was correlated to the length of the audit.
</li>
<li style="font-weight: 400">
  Engineering costs were greater for those companies whose systems were not initially built according to FedRAMP requirements (e.g. traditionally commercial system being “retrofitted” to meet Federal requirements).
</li>

One important thing to note, again, is that these baseline costs are associated with the old FedRAMP process and was before we introduced FedRAMP Accelerated. With the redesigned, reimagined process now being tested with three CSPs, we will ensure that Accelerated works for everyone. One way we’re going about this is to to compare and contrast the costs of the old process to Accelerated and to ensure we’re getting a greater ROI for both government and industry.

As we continue to iterate and upgrade FedRAMP Accelerated, we&#8217;ll be re-baselining the costs associated with the vendors currently involved to ensure that not only is the process faster and more transparent, but that it&#8217;s becoming more cost efficient as well. If you’re a vendor who would like to help us build out our baseline costs to better understand more factors that contribute to cost and nuances to our model, please reach out to <a href="mailto:info@fedramp.gov">info@fedramp.gov</a>!
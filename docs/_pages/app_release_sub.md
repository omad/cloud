---
title: Application Release
layout: page
permalink: app_release_sub.html
---

### Communications checklist

1. If the site is GA-branded, get approval from Products & Promotions - this includes sites that use the GA crest and sites that are hosted on ga.gov.au
2. Consult IP/Copyright and Contracts regarding IP and licensing issues - this can be bypassed if the following conditions are met:
  * No 3rd-party code
  * No algorithms with ambiguous licencing
  * No algorithms that are related to pending publications
  * No code with ambiguous IP (e.g. developed in partnership with external stakeholders, 3rd-party funding)
  * Recommended licence in place - this is [Apache Version 2.0](https://www.apache.org/licenses/LICENSE-2.0)
3. Create a GeoCat record for the release 
4. Make any appropriate announcements to forums, partner agencies and notify Communications and Client Services of the release

### Technical checklist

1. Get the code into version control
2. Ensure the software has automated tests
3. Decide on a release process for the project - this should ideally use a [Continuous Delivery pipeline](setting_up_cd_sub.html)
4. Decide on a decommissioning strategy for the project
5. Prepare your codebase - this includes:
  * Well-documented code
  * Consistent style
  * Appropriate licence
  * Appropriate language, for example profanity or derogatory comments
  * No hard-coded GA-specifics, such as passwords, file paths, AWS keys
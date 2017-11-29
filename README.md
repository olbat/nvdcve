# NVD/CVE® as JSON files


## About
This repository contains JSON files describing vulnerabilities from the [NVD](https://nvd.nist.gov/general/faq) and [CVE®](https://cve.mitre.org/about/faqs.html) dictionaries.

It has two main goals:
- allow to easilly get the description of a vulnerability in the JSON format ([schema](https://scap.nist.gov/schema/nvd/feed/0.1/nvd_cve_feed_json_0.1_beta.schema))
- allow to explore CVE®/NVD modification history using git

The JSON files from this repository are generated and update daily using the [NVD's JSON feeds](https://nvd.nist.gov/vuln/data-feeds).

__Data access__: JSON files can also be fetched at [https://olbat.github.io/nvdcve/CVE-YYYY-NNN.json](https://olbat.github.io/nvdcve/CVE-YYYY-NNN.json).


## Licensing
### Common Vulnerabilities and Exposures (CVE®)
The [CVE®](https://cve.mitre.org/) is maintained by the Mitre Corporation.

The usage of this resource -as well as the JSON files in this repository- is restricted and described in Mitre CVE®'s [Terms of use](https://cve.mitre.org/about/termsofuse.html):
```
CVE Usage: MITRE hereby grants you a perpetual, worldwide, non-exclusive,
no-charge, royalty-free, irrevocable copyright license to reproduce, prepare
derivative works of, publicly display, publicly perform, sublicense, and
distribute Common Vulnerabilities and Exposures (CVE®). Any copy you make for
such purposes is authorized provided that you reproduce MITRE's copyright
designation and this license in any such copy.
```

### National Vulnerabilitiy Database (NVD)
The [National Vulnerability Database](https://nvd.nist.gov/) is the U.S. government repository of standards-based vulnerability management data represented using the Security Content Automation Protocol ([SCAP](https://en.wikipedia.org/wiki/Security_Content_Automation_Protocol)).

It is a superset of the CVE® dictionary augmented with additional analysis, a database, and a fine-grained search engine.

Usage restrictions of this resource are described in the NVD's [FAQ](https://nvd.nist.gov/general/faq#1f2488ea-0492-45a7-ae5b-ad29bc31dd05):
```
All NVD data is freely available from our XML Data Feeds. There are no fees,
licensing restrictions, or even a requirement to register. All NIST
publications are available in the public domain according to Title 17 of the
United States Code. Acknowledgment of the NVD  when using our information is
appreciated. In addition, please email nvd@nist.gov to let us know how the
information is being used.
```

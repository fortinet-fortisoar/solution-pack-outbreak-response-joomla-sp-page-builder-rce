# Release Information 

- **Version**: 1.0.0 
- **Certified**: No 
- **Publisher**: Fortinet 
- **Compatible Version**: FortiSOAR 7.4.0 and later 

# Overview 

FortiGuard Labs continues to observe active exploitation of CVE-2026-48908, a critical unauthenticated remote code execution vulnerability affecting the JoomShaper SP Page Builder extension for Joomla. At the time of release, FortiGuard telemetry recorded 1,210 blocked exploitation attempts in the last 24 hours and 15,626 attempts over the past 7 days.

 

 The **Outbreak Response - Joomla SP Page Builder RCE** solution pack works with the Threat Hunt rules in [Outbreak Response Framework](https://github.com/fortinet-fortisoar/solution-pack-outbreak-response-framework/blob/release/2.0.0/docs/background-information.md#threat-hunt-rules) solution pack to conduct hunts that identify and help investigate potential Indicators of Compromise (IOCs) associated with this vulnerability within operational environments of *FortiSIEM*, *FortiAnalyzer*.

 The [FortiGuard Outbreak Page](https://www.fortiguard.com/outbreak-alert/joomla-sp-page-builder-rce) contains information about the outbreak alert **Outbreak Response - Joomla SP Page Builder RCE**. 

## Background: 

CVE-2026-48908 is a critical (CVSS 10.0) unauthenticated remote code execution (RCE) vulnerability affecting the JoomShaper SP Page Builder extension for Joomla. The vulnerability stems from an unrestricted file upload in the asset.uploadCustomIcon endpoint, allowing remote attackers to upload and execute arbitrary PHP files without authentication. The flaw is actively exploited in the wild and has been added to CISA's Known Exploited Vulnerabilities (KEV) catalog. 

At the time of release, the highest attack volumes targeted organizations in Poland, Turkey, Australia, and the United States, with the Telecommunications/Carrier and Technology sectors experiencing the greatest activity. 

## Announced: 

Organizations should immediately upgrade to SP Page Builder 6.6.2 or later and investigate systems for web shells, unauthorized administrator accounts, and other persistence mechanisms, as patching alone does not remove an existing compromise.
 

## Latest Developments: 

July 7, 2026: CISA adds CVE-2026-48908 to the Known Exploited Vulnerabilities (KEV) Catalog, confirming evidence of active exploitation in the wild and requiring rapid remediation by U.S. federal agencies.

June 20, 2026: JoomShaper releases SP Page Builder 6.6.2, which fixes the unrestricted file upload vulnerability
https://www.joomshaper.com/forum/question/45152 

# Next Steps
 | [Installation](./docs/setup.md#installation) | [Configuration](./docs/setup.md#configuration) | [Usage](./docs/usage.md) | [Contents](./docs/contents.md) | 
 |--------------------------------------------|----------------------------------------------|------------------------|------------------------------|
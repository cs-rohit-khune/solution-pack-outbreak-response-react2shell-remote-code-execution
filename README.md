# Release Information 

- **Version**: 1.0.0 
- **Certified**: No 
- **Publisher**: Fortinet 
- **Compatible Version**: FortiSOAR 7.4.0 and later 

# Overview 

React2Shell is a critical unauthenticated remote code execution (RCE) vulnerability affecting React Server Components (RSC) and frameworks that implement the Flight protocol, including specific vulnerable versions of Next.js. A remote attacker can craft a malicious RSC request that triggers server-side deserialization, leading to arbitrary code execution without authentication or user interaction. 

 The **Outbreak Response - React2Shell Remote Code Execution** solution pack works with the Threat Hunt rules in [Outbreak Response Framework](https://github.com/fortinet-fortisoar/solution-pack-outbreak-response-framework/blob/release/2.3.0/docs/background-information.md#threat-hunt-rules) solution pack to conduct hunts that identify and help investigate potential Indicators of Compromise (IOCs) associated with this vulnerability within operational environments of *FortiSIEM*, *FortiAnalyzer*.

 The [FortiGuard Outbreak Page](https://www.fortiguard.com/outbreak-alert/react2shell-rce) contains information about the outbreak alert **Outbreak Response - React2Shell Remote Code Execution**. 

## Background: 

Due to the widespread use of React and Next.js in production environments, organizations are strongly urged to apply patches immediately, enforce WAF protections on RSC/Flight endpoints, and conduct proactive threat hunting. CISA has added CVE-2025-55182 to the Known Exploited Vulnerabilities (KEV) catalog following confirmed evidence of active exploitation. AWS Security has also reported exploitation activity originating from infrastructure historically linked to China state-nexus threat actors.

Successful exploitation can lead to:
- Full server compromise, including deployment of persistent backdoors
- Credential harvesting and access to sensitive application data
- Execution of arbitrary Node.js commands on the affected server
- Lateral movement across connected systems and cloud environments 

## Announced: 

Organizations should review the vendor advisories for complete version details, mitigation steps, and updated guidance. FortiGuard customers are protected by multiple layers of defense against these exploits. Refer to the Solutions tab for for information. 

## Latest Developments: 

December 5, 2025: CISA has added CVE-2025-55182 to the Known Exploited Vulnerabilities (KEV) catalog following evidence of active exploitation.

December 5, 2025: FortiGuard Labs released a Threat Signal for React2Shell Remote Code Execution (RCE) Vulnerability.
https://www.fortiguard.com/threat-signal-report/6281/react2shell-remote-code-execution-rce-vulnerability

December 4, 2025: Lacework FortiCNAPP Protection update and response added for React & NextJS Remote Code Execution Vulnerability.
https://community.fortinet.com/t5/Lacework/Technical-Tip-How-does-Lacework-FortiCNAPP-Protect-from-CVE-2025/ta-p/421658

December 4, 2025: AWS Security has observed exploitation activity originating from infrastructure historically linked to China-nexus threat actors, noting rapid mass exploitation of vulnerable internet-facing RSC/Next.js deployments.

December 3, 2025: Security Advisory released by Next.js and  fix was published to npm and the publicly disclosed as CVE-2025-55182.
https://nextjs.org/blog/CVE-2025-66478

November 30, 2025: Meta security researchers confirmed and began working with the React team on a fix.

November 29, 2025:  Lachlan Davidson reported the security vulnerability via Meta Bug Bounty.
https://react.dev/blog/2025/12/03/critical-security-vulnerability-in-react-server-components 

# Next Steps
 | [Installation](./docs/setup.md#installation) | [Configuration](./docs/setup.md#configuration) | [Usage](./docs/usage.md) | [Contents](./docs/contents.md) | 
 |--------------------------------------------|----------------------------------------------|------------------------|------------------------------|

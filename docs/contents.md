| [Home](../README.md) |
 | -------------------------------------------- |

# Contents

The **Outbreak Response - React2Shell Remote Code Execution** solution pack contains the following resources.

## Outbreak Alerts Record Set

| Name | Description |
|:-------------------------|:------------------|
| React2Shell Remote Code Execution  | React2Shell is a critical unauthenticated remote code execution (RCE) vulnerability affecting React Server Components (RSC) and frameworks that implement the Flight protocol, including specific vulnerable versions of Next.js. A remote attacker can craft a malicious RSC request that triggers server-side deserialization, leading to arbitrary code execution without authentication or user interaction. |

## Threat Hunt Rules Record set

| Name | Rule Type |
|:-------------------------|:------------------|
| Suspicious Command from Node.Js | Sigma |
| React2Shell CVE-2025-55182 Exploitation Attempt Detection | Sigma |
| Suspicious Shell Process from Next.js | Sigma |
| FortiAnalyzer Threat Hunting - React2Shell RCE Event-Handler | Fortinet Fabric |
| React2Shell Vulnerability Exploitation Attempt | Sigma |


 <table><th>NOTE</th><td>These SIGMA and Yara rules are sourced from public community repositories are not independently verified or validated by Fortinet. While community-contributed rules can be valuable for timely threat detection, they may vary in quality, accuracy, and relevance. Fortinet is not responsible for any inaccuracies, errors, or omissions in these rules, nor for any damage or loss that may result from their application. We encourage users to conduct their own validation and adapt these rules as necessary to meet specific security needs and contexts</td></table> 

# Next Steps
| [Installation](./setup.md#installation) | [Configuration](./setup.md#configuration) | [Usage](./usage.md) |
| ----------------------------------------- | ------------------------------------------- | --------------------- |

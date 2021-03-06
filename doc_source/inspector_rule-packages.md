# Amazon Inspector Rules Packages and Rules<a name="inspector_rule-packages"></a>

You can use Amazon Inspector to assess your assessment targets \(collections of AWS resources\) for potential security issues and vulnerabilities\. Amazon Inspector compares the behavior and the security configuration of the assessment targets to selected security *rules packages*\. In the context of Amazon Inspector, a *rule* is a security check that Amazon Inspector performs during the assessment run\.

In Amazon Inspector, rules are grouped together into distinct *rules packages* either by category, severity, or pricing\. This gives you choices for the kinds of analysis that you can perform\. For example, Amazon Inspector offers a large number of rules that you can use to assess your applications\. But you might want to include a smaller subset of the available rules to target a specific area of concern or to uncover specific security problems\. Companies with large IT departments might want to determine whether their application is exposed to any security threat, while others might want to concentrate only on issues with the severity level of **High**\.
+ [Severity Levels for Rules in Amazon Inspector](#SeverityLevels)
+ [Rules Packages in Amazon Inspector](#InspectorRulePackages)

## Severity Levels for Rules in Amazon Inspector<a name="SeverityLevels"></a>

Each Amazon Inspector rule has an assigned severity level\. This reduces the need to prioritize one rule over another in your analyses\. It can also help you determine your response when a rule highlights a potential problem\. **High**, **Medium**, and **Low** levels all indicate a security issue that can result in compromised information confidentiality, integrity, and availability within your assessment target\. The **Informational** level simply highlights a security configuration detail of your assessment target\. Following are recommended ways to respond to each:
+ **High** – Describes a security issue that can result in a compromise of the information confidentiality, integrity, and availability within your assessment target\. We recommend that you treat this security issue as an emergency and implement an immediate remediation\.
+ **Medium** – Describes a security issue that can result in a compromise of the information confidentiality, integrity, and availability within your assessment target\. We recommend that you fix this issue at the next possible opportunity, for example, during your next service update\.
+ **Low** \- Describes a security issue that can result in a compromise of the information confidentiality, integrity, and availability within your assessment target\. We recommend that you fix this issue as part of one of your future service updates\.
+ **Informational** – Describes a particular security configuration detail of your assessment target\. Based on your business and organization goals, you can either simply make note of this information or use it to improve the security of your assessment target\.

## Rules Packages in Amazon Inspector<a name="InspectorRulePackages"></a>

The following are the rules packages available in Amazon Inspector:
+ [Common Vulnerabilities and Exposures](inspector_cves.md)
+ [Center for Internet Security \(CIS\) Benchmarks](inspector_cis.md)
+ [Security Best Practices](inspector_security-best-practices.md)
+ [Runtime Behavior Analysis](inspector_runtime-behavior-analysis.md)
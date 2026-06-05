# Email Forensics & Threat Intelligence Investigation

## Portfolio Case Study

### Overview

This case study demonstrates a comprehensive email-forensics and threat-intelligence investigation conducted on a suspicious business communication that exhibited multiple indicators of financial and social-engineering risk.

The objective was to determine whether the email represented a legitimate business inquiry or a potentially deceptive communication designed to obtain financial commitments, sensitive information, or business cooperation under false pretenses.

### Investigation Objectives
The investigation sought to:

Validate sender authenticity </br>
Analyze email authentication mechanisms  </br>
Examine delivery infrastructure </br>
Assess domain legitimacy </br>
Evaluate IP reputation </br>
Identify social-engineering indicators </br>
Determine overall fraud risk </br>


## Methodology

The investigation followed a structured forensic workflow:

### Phase 1 – Email Header Analysis

The complete raw email headers were examined to identify:

Message routing path</br>
Relay infrastructure</br>
Authentication results</br>
Message identifiers</br>
Time zone indicators</br>
Delivery anomalies</br>

### Phase 2 – Email Authentication Review

The following controls were analyzed:

SPF (Sender Policy Framework)</br>
DKIM (DomainKeys Identified Mail)</br>
DMARC (Domain-based Message Authentication, Reporting and Conformance)</br>
ARC (Authenticated Received Chain)</br>
Return-Path alignment</br>


### Phase 3 – Infrastructure Intelligence

The sender domain infrastructure was assessed through:

DNS analysis</br>
MX record enumeration</br>
WHOIS investigation</br>
Hosting footprint review</br>
Historical infrastructure observations</br>
Phase 4 – Threat Intelligence Collection</br>

### External intelligence sources were consulted to evaluate:

IP reputation</br>
Abuse history</br>
Historical reports</br>
Infrastructure trustworthiness</br>
Known malicious associations</br>
Phase 5 – Behavioral Analysis</br>

### The email content was reviewed for:

Social-engineering tactics</br>
Financial manipulation indicators</br>
Trust-building mechanisms</br>
Urgency cues</br>
Information-harvesting attempts</br>
Business legitimacy signals</br>
Technical Findings</br>
Email Delivery Infrastructure</br>

Analysis revealed that the message was delivered through a major cloud-based email provider's infrastructure.

Key observations:</br>

Message delivery occurred through legitimate shared mail-relay systems.</br>
The relay infrastructure itself was not malicious.</br>
The sender's originating IP address was not exposed within standard email headers.</br>
Attribution of the physical sender location was therefore not possible through header analysis alone.</br>

## Important Observation

Use of trusted cloud-email infrastructure does not independently establish sender legitimacy. Modern fraud campaigns frequently leverage reputable email providers to increase deliverability and user trust.

Authentication Assessment
SPF

Result:

No effective SPF protection observed.

Impact:

Reduced ability to verify authorized sending systems.
DMARC

Result:

No effective DMARC policy observed.

Impact:

Reduced protection against domain impersonation and abuse.
DKIM

Result:

Domain-level DKIM configuration appeared incomplete or improperly implemented.

Impact:

Weakens cryptographic verification of sender authenticity.
Overall Authentication Posture

The sender domain demonstrated weak email-security controls compared with industry best practices.

Assessment:

High Authentication Risk

Domain Intelligence Analysis
Domain Characteristics

Investigation identified several notable observations:

Limited public web presence
Minimal discoverable business footprint
Restricted publicly verifiable corporate information
Primarily email-focused infrastructure
Analytical Interpretation

While these findings do not independently prove malicious intent, they reduce confidence in the legitimacy of the organization and increase overall risk when combined with other indicators.

IP Reputation Assessment

The mail relay infrastructure showed historical abuse reports associated with the shared service environment.

Important context:

Shared cloud infrastructure serves millions of users.
Abuse reports cannot automatically be attributed to a specific sender.
Reputation findings must therefore be considered alongside other evidence.

Assessment:

Contextual Risk Indicator — Not Direct Attribution Evidence

Social Engineering Assessment

Content analysis identified multiple behavioral indicators commonly observed in business-email fraud and financial-manipulation schemes.

Examples included:

Requests involving financial liability or guarantees
Reliance on third-party trust references
Limited independent verification opportunities
Collection of business-related information
Reassurance-focused language regarding financial risk
Minimal verifiable organizational identity
Pressure to establish trust before verification
Behavioral Pattern Analysis

No single indicator conclusively demonstrated malicious intent.

However, the cumulative pattern was consistent with techniques frequently observed in:

Business Email Compromise (BEC)
Investment-related fraud
Advance-fee fraud schemes
Social-engineering operations

Assessment:

High Social Engineering Risk

Attribution Limitations

A critical principle of digital forensics is acknowledging evidentiary limitations.

Based solely on standard email headers:

Physical sender location could not be determined.
Device attribution could not be established.
Identity attribution could not be confirmed.

Additional legal process and service-provider records would be required for definitive attribution.

Risk Assessment
Category	Assessment
Malware Risk	Low
Credential Theft Risk	Low
Infrastructure Risk	Moderate
Authentication Risk	High
Financial Fraud Risk	High
Social Engineering Risk	Critical
Final Assessment

The investigation identified numerous technical and behavioral indicators that collectively elevated the overall risk profile of the communication.

While no malware payloads or credential-harvesting mechanisms were identified, the combination of:

Weak authentication controls
Limited business verifiability
Reliance on trusted third-party infrastructure
Multiple social-engineering indicators
Financial-risk-related communication

resulted in a high-confidence assessment that the communication posed significant business and financial risk.

## Conclusion

The email was assessed as a likely social-engineering communication and was considered unsuitable for engagement without extensive independent verification and due diligence.

Skills Demonstrated</br>
Email Header Analysis</br>
Email Authentication Validation</br>
SPF/DKIM/DMARC Assessment</br>
Threat Intelligence Research</br>
DNS & MX Analysis</br>
Infrastructure Investigation</br>
Open-Source Intelligence (OSINT)</br>
Social Engineering Detection</br>
Risk Assessment</br>
Digital Forensic Reporting</br>
Tools Utilized</br>
Email Header Analysis Tools</br>
DNS Lookup Utilities</br>
WHOIS Intelligence Sources</br>
Threat Intelligence Platforms</br>
Reputation Analysis Services</br>
Mail Authentication Validators</br>
OSINT Research Frameworks</br>


## Portfolio Note

This case study has been sanitized for educational and portfolio purposes. All identifying information, domains, email addresses, and personal data have been removed. The focus of this publication is to demonstrate forensic methodology, analytical reasoning, and threat-intelligence workflow rather than disclose client-specific information.

---
eleventyComputed:
  title: RDP entry authentication properties
  description: RDP entry authentication properties can be configured when creating or editing the RDP entry.
---
{% snippet icon.badgeInfo %}
The following properties can be configured when creating or editing the RDP entry. Most of the general properties require you to close the RDP entry completely, then reopen it to take effect.
{% endsnippet %}  

![RDP entry authentication properties](https://webdevolutions.blob.core.windows.net/docs/docs_en_kb_KB6219.png)

## Authentication       

| SETTINGS      | DESCRIPTION |
|-------------|-------------|                                                                                                   
| ***Connect and don't warn me***                | Automatically connects to the remote desktop without any security warnings.                                 |
| ***Do not connect***                           | Prevents the connection if authentication issues are detected.                                              |
| ***Warn me***                                  | Provides a warning if there are any concerns with the authentication but allows the option to proceed.      |
| ***Default (Connect and don't warn me)***      | Uses the default setting to connect without warning about authentication issues.                            |
| ***Enable Network Level Authentication (NLA)***| Enables ***NLA***, which enhances security by requiring authentication before establishing a remote desktop session. |
| ***Enable Azure AD SSO***                      | Enables ***Single Sign-On (SSO)*** with Azure Active Directory credentials for a seamless login experience.       |

### Transport Security

| SETTINGS      | DESCRIPTION |
|-------------|-------------|  
| ***Enable Transport Layer Security (TLS)***    | Secures the connection using ***TLS***, providing encryption and integrity protection.                            |
| ***Enable Remote Desktop Protocol Security (RDP)***| Uses ***RDP Security*** Layer for encryption to protect the data transmitted between client and server.       |

### SSPI

| SETTINGS      | DESCRIPTION |
|-------------|-------------| 
| ***RD Gateway is KDC proxy***                  | Indicates that the ***RD Gateway*** serves as a ***Key Distribution Center (KDC)*** proxy for Kerberos authentication.  |
| ***SSPI Module***                              | Specifies the ***Security Support Provider Interface (SSPI)*** module to be used for authentication.              |
| ***Authentication Package***                   | Defines the ***authentication package*** (e.g., Kerberos, NTLM) used for verifying user credentials.              |
| ***KDC Detection Method***                     | Determines the method for detecting the Key Distribution Center in Kerberos authentication scenarios.       |
| ***KDC Server URL***                           | Specifies the ***URL of the KDC server*** to be used for Kerberos authentication, if applicable.                  |
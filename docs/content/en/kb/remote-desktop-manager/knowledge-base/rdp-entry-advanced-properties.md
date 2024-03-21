---
eleventyComputed:
  title: RDP entry advanced properties
  description: RDP entry advanced properties can be configured when creating or editing the RDP entry.
---

{% snippet icon.badgeInfo %}
The following properties can be configured when creating or editing the RDP entry. Most of the general properties require you to close the RDP entry completely, then reopen it to take effect.
{% endsnippet %}  

![RDP entry advanced properties](https://webdevolutions.blob.core.windows.net/docs/docs_en_kb_KB6222.png)

### Log off mode 

| SETTINGS                       | DESCRIPTION |
|------------------------------|-------------|
| Default                      | [Description Needed] |
| Automatic                    | [Description Needed] |
| RDM Agent                    | [Description Needed] |
| Remote Desktop Services API  | [Description Needed] |
| Macro                        | [Description Needed] |


### Automatically log off when disconnecting

| SETTINGS  | DESCRIPTION |
|---------|-------------|
| Default | [Description Needed] |
| Yes     | [Description Needed] |
| No      | [Description Needed] |


### Reconnect mode 

| SETTINGS         | DESCRIPTION |
|----------------|-------------|
| Standard       | [Description Needed] |
| Full           | [Description Needed] |
| Smart Reconnect| [Description Needed] |
| Legacy         | [Description Needed] |


### RDP Version

| SETTINGS                | DESCRIPTION |
|-----------------------|-------------|
| RDP (6.1)             | [Description Needed] |
| RDP (7.0)             | [Description Needed] |
| RDP (8.1)             | [Description Needed] |
| Latest                | [Description Needed] |
| RDP (FreeRDP Latest)  | [Description Needed] |
| RDP (FreeRDP 7.0)     | [Description Needed] |
| MSRDC                 | [Description Needed] |
| RDP (10.10)           | [Description Needed] |
| RDP (10.11)           | [Description Needed] |


### Minimap unput send interval

| SETTINGS                        | DESCRIPTION |
|-------------------------------|-------------|
| Minimap Input Send Interval   | The interval (in milliseconds) at which the minimap feature sends input data to the application or server. |

### Maximum TL version

| SETTINGS               | DESCRIPTION |
|----------------------|-------------|
| Maximum TLS version  | Defines the highest version of the TLS protocol that can be utilized for securing connections. This setting ensures compatibility with the latest security standards while allowing backward compatibility with older versions up to the specified maximum. |

### Public mode

| SETTINGS     | DESCRIPTION |
|------------|-------------|
| Public mode| |


### Prompt for credentials on client

| SETTINGS                          | DESCRIPTION |
|---------------------------------|-------------|
| Prompt for credentials on client| Requires the entry of credentials on the client-side prior to establishing a remote connection, enhancing security protocols by verifying authentication early in the connection process. |

### Restricted admin mode

| SETTINGS                          | DESCRIPTION |
|---------------------------------|-------------|
| Restricted admin mode           | A security configuration that permits administrative connections to a remote system without transmitting actual credentials to the remote system, mitigating the risk of credential theft. |

### Remote credential Guard

| SETTINGS                          | DESCRIPTION |
|---------------------------------|-------------|
| Remote Credential Guard         | A security feature that safeguards credentials over a Remote Desktop connection by redirecting Kerberos requests back to the originating client, preventing credentials from being exposed to the remote host. |

### Background input
| SETTINGS                          | DESCRIPTION |
|---------------------------------|-------------|
| Background input                | Allows for the transmission of input commands to applications operating in the background, ensuring continuous interaction even when the application is not the active window.  |

### Enable super pan

| SETTINGS                          | DESCRIPTION |
|---------------------------------|-------------|
| Enable super pan                | Activates a functionality that facilitates the navigation across a large remote desktop environment by allowing panning over the display area, improving the user interface on devices with limited screen sizes. |

### Connection Broker - High Availability 

| SETTINGS                          | DESCRIPTION |
|-----------------------------------|-------------|
| Workspace ID                      | Serves as a unique identifier for the workspace, utilized in environments that employ Remote Desktop Connection Broker to achieve high availability and load balancing. |
| Use redirection server            | Determines the employment of a redirection server to distribute session loads evenly across servers or to provide failover capabilities. |
| Alternate full address            | Offers an alternative address for establishing a connection to a remote session, employed in cases where the primary connection point is not accessible. |
| Load balance info                 | Provides details used by the connection broker to allocate the session to the most appropriate server, based on current load balancing strategies. |


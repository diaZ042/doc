---
eleventyComputed:
  title: RDP entry programs properties
  description: RDP entry programs properties can be configured when creating or editing the RDP entry.
---

{% snippet icon.badgeInfo %}
The following properties can be configured when creating or editing the RDP entry. Most of the general properties require you to close the RDP entry completely, then reopen it to take effect.
{% endsnippet %}  

![RDP entry programs properties](https://webdevolutions.blob.core.windows.net/docs/docs_en_kb_KB6215.png)

| SETTINGS                                | DESCRIPTION                                                    |
|-----------------------------------------|-----------------------------------------------------------------|
| ***Start this program on connection (alternate shell)*** | Enables the automatic launching of a specified program instead of the full desktop environment upon RDP session initiation.                                 |
| ***Program path and filename***             | Specifies the full path and filename of the program that should be started automatically upon connection.                                                            |
| ***Start in the following folder***         | Sets the default starting directory for the program. This path is used when the program is launched.                                                                  |
| ***Use RemoteApp (seamless mode)***         | Enables RemoteApp to provide a seamless integration of the remote application with the local desktop, making the remote program appear as if it is running locally.     |
| ***Program***                               | Specifies the program to be used with RemoteApp for a seamless application experience, requiring the path and filename.                                     |
| ***Parameters***                            | Allows for the specification of command-line arguments or parameters that should be passed to the program upon startup.                                      |
| ***Execute the following program after login*** | Defines an additional program to be executed after the initial login process is complete, offering further customization of the startup process.                       |
| ***After login delay***                     | Specifies a delay (in seconds) before executing the program defined to run after login, allowing the system or initial programs time to initialize.                  |
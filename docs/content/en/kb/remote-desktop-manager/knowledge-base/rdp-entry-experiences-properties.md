---
eleventyComputed:
  title: RDP entry experience properties
  description: RDP entry experience properties can be configured when creating or editing the RDP entry.
---
{% snippet icon.badgeInfo %}
The following properties can be configured when creating or editing the RDP entry. Most of the general properties require you to close the RDP entry completely, then reopen it to take effect.
{% endsnippet %}  

![RDP entry experience properties](https://webdevolutions.blob.core.windows.net/docs/en/kb/KB6218.png)

| SETTINGS                                 | DESCRIPTION                                                                                                           |
|------------------------------------------|-----------------------------------------------------------------------------------------------------------------------|
| ***Default***                                  | Uses default settings that are automatically chosen based on the RDP client's assessment of the network conditions.   |
| ***Modern (56 kps)***                          | Optimizes for very low bandwidth connections, minimizing data usage to accommodate extremely limited speeds.          |
| ***Low-speed broadband (256 kps - 2Mbps)***    | Tailors the experience for lower broadband speeds, adjusting visual quality and other settings for improved performance. |
| ***Satellite (2 - 16 Mbps with high latency)***| Designed for satellite connections, which typically have higher bandwidth but also suffer from significant latency.   |
| ***High-speed broadband (2-10 Mbps)***         | Enhances the session for users with high-speed broadband, enabling more detailed graphics and smoother interactions.  |
| ***WAN (>10 Mbps with high latency)***         | Optimizes for WAN connections that have high bandwidth and high latency, balancing quality and responsiveness.        |
| ***LAN (>10 Mbps with low latency)***          | Provides the highest quality experience for LAN connections, allowing for full feature use with minimal latency.      |
| ***Detect network automatically***             | Automatically detects the network conditions and selects the most suitable settings to optimize performance.          |


| SETTINGS                             | DESCRIPTION                                                                                             |
|--------------------------------------|---------------------------------------------------------------------------------------------------------|
| ***Desktop background***                   | Displays the desktop background from the remote computer.                                               |
| ***Font smoothing***                       | Enables font smoothing to improve text readability.                                                     |
| ***Desktop composition***                  | Allows the use of Windows Aero features such as transparency and other visual effects.                  |
| ***Show window contents while dragging***  | Displays the contents of windows as they are moved or resized, rather than just an outline.             |
| ***Menu and window animation***            | Enables animations when opening or closing windows and accessing menus.                                 |
| ***Visual styles***                        | Applies the visual style and theme of the remote desktop, such as colors and control button appearances.|
| ***Persistent bitmap caching***            | Stores images or parts of the remote desktop to improve performance during the session.                 |
| ***Redirect video playback***              | Optimizes the playback of video content from the remote desktop on the local machine.                   |
| ***Reconnect if connection is dropped***   | Automatically attempts to reconnect to the remote session if the connection is temporarily lost.        |
| ***Detect bandwidth automatically***       | Automatically adjusts session settings based on the estimated bandwidth of the connection.              |
| ***Enable data compression***              | Compresses data to improve performance over slower connections.                                         |
| ***Load plug-ins embedded mode***          | (Option description might vary, typically relates to loading specific plug-ins for enhanced functionality within the RDP session.) |
| ***Cache***                                | Utilizes caching to improve performance by storing frequently accessed data.  ***Default***: Uses the standard caching strategy determined by the RDP client, balancing performance and resource use. ***Full mode***: Maximizes the use of cache to enhance session responsiveness, ideal for high-bandwidth connections where memory resources are plentiful. ***Thin client***: Minimizes the amount of data cached, tailored for low-resource computing devices or very low bandwidth connections. ***Small cache***: Offers a compromise between no caching and full caching, designed for scenarios with limited memory or when conserving bandwidth is a priority but some caching benefits are desired.                                                                                         |
| ***Keep alive***                           | Sends keep-alive packets to maintain the connection active during periods of inactivity.                |
| ***Enable mouse jiggler***                 | Prevents the remote session from going idle by simulating mouse movement.                               |
| ***Mouse jiggler method***                 | Specifies the technique used by the mouse jiggler, e.g., random movement, specific pattern, etc.        |
| ***Mouse jiggler interval***               | Defines the time interval between simulated mouse movements.                                            |
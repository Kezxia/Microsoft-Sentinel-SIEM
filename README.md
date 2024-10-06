# Microsoft-Sentinel-SIEM

![Architecture Diagram](https://imgur.com/Qa1MyLI.png)
### World Maps Construction
> [!NOTE]
> In this lab, we will create four distinct workbooks in Sentinel using pre-built JSON maps to display various types of malicious traffic from around the world targeting our resources since they’ve been online. The first map will show failed authentication attempts against the Windows VM. The second will highlight SSH authentication failures from the Linux VM. The third will focus on authentication failures from the Microsoft SQL Server hosted within the Windows VM. The final map will display malicious inbound traffic identified by the Network Security Groups.



<details>
<summary>Part 1: Within Azure Sentinel, first observe the Data Connectors, then do the following steps.</summary>

</details>

<details>
<summary>Part 2: Use the windows-rdp-auth-fail.json to create the “Windows RDP/SMB Authentication Failures” map.</summary>

</details>

<details>
<summary>Part 3: Use the linux-ssh-auth-fail.json to create the “Linux SSH Authentication Failures” map.</summary>

</details>

<details>
<summary>Part 4: Use the ssql-auth-fail.json to create the “MS SQL Server Authentication Failures” map.</summary>

</details>

<details>
<summary>Part 5: Use the nsg-malicious-allowed-in.json to create the “NSG Allowed Malicious Inbound Flows” map.</summary>

</details>

<details>
<summary>Part 6: Observe any pre-existing malicious attack traffic on these maps from the Internet. Ensure an appropriate time-frame is being selected (30 days). </summary>

</details>

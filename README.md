## NICProber: Ensuring Optimal Network Performance
##### Part of our [RMMProberScripts](https://github.com/InviseLabs/RMMProberScripts) – A collection of deployable Windows-based command-line scripts designed to warn you of concerning hardware or sensor problems. Each tool outputs the associated raw troubleshooting values, along with a PASS or FAIL and proper exit codes. Use with RMM or IT Admin software to alert you when a script check FAILs.

A small command-line diagnostic tool which **verifies the ethernet adapter is operating at 1000+ Mbps (gigabit)**; or if the device is on wifi, it **verifies the wifi card is operating at 100+ Mbps**. It differentiates between gigabit connections (1000 Mbps) and suboptimal speeds (10/100 Mbps), and provides the information as the output text. If the adapter is running at suboptimal speeds, an exit code is thrown with error text, which should be interpretted by any RMM MSP dashboard software as a check failure, allowing you to be alerted if such a scenario were to happen. 

Running a workstation at 10/100 speeds can be a huge bottleneck to network operations, running/streaming applications to or from a server, copying files over the network, etc. In many cases, the downgrade to slower speeds can occur due to seemingly minor oversights, such as the use of outdated Cat5 cables instead of Cat5e, or connecting to switches that only support FastEthernet. Such scenarios are surprisingly common and can significantly impede your network's capabilities.

For clients who may not be tech-savvy, particularly those with a box of legacy "computer stuff," the inadvertent use of an obsolete Cat5 cable can occur without notice. Similarly, during the onboarding process, it's possible to overlook a client's use of dated routers or switches that lack gigabit support. Despite the advancements in technology, 10/100 switches are still available on the market, and a well-intentioned purchase of a cost-effective switch could inadvertently lead to a severe bottleneck in network throughput.

With NICProber, you'll be equipped to detect these issues almost immediately. Deploy this script across your client networks through your own methods or through an RMM MSP dashboard software, and you can monitor the output to ensure that such network bottlenecks are identified and addressed promptly, safeguarding the integrity of your network infrastructure and maintaining the high standard of service your clients expect.

Screenshot of our tools return when using Solarwinds: **URL-PLACEHOLDER**

---
#### 👉🏼 Follow our projects and related discussions on the Invise Labs Discord: https://discord.gg/gK7NQ7h
#### 👉🏼 Follow @MikeLierman on Twitter: https://twitter.com/MikeLierman
#### 👉🏼 Visit [InviseLabs.com](https://InviseLabs.com/):- IT and Technician Software, designed to make your life as an IT professional easier.
---

.
.

## Placeholder - Information Coming Soon



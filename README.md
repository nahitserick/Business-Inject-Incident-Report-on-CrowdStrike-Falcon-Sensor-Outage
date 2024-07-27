# Business-Inject-Incident-Report-on-CrowdStrike-Falcon-Sensor-Outage

### Scenario:

It is 2am…you just got paged…
- You work in the SOC at a bank
- CrowdStrike update went wrong
- 200 Windows machines are now bricked

### Objectives:
- Write a 1 page report in 30 minutes
- It must be a technical report briefing your manager on the incident detailing any known information at the moment in regards to the incident.

### Report to management:
As of 12:34 pm last night 7/19/24, 200 of our Windows computers companywide are displaying the BSOD. This issue has been traced to our company-wide usage of the End Point Detection System (EDR), the CrowdStrike Falcon Sensor. According to CrowdStrike this outage is due to a new software update for the Falcon sensor, and we are being reassured that this is not a security incident or cyber-attack. Instead, the outage is due to an update that was rolled out at around 10 pm last night that contains a defect in a single content update for Windows hosts forcing all Windows machines into a recovery boot loop, not allowing them to start properly. 

Affected systems include ATM OS and End-user systems at our physical banking locations running all versions of Windows OS. It appears that Mac and Linux systems are unaffected by this update and our internal IT team is currently weighing options for remediation. Current remediation options include rolling back the software update company-wide, invoking our disaster recovery plan, and migrating services to backup devices using our most recent backup, or coordinating with the CrowdStrike IT team to find the issue within the content update and physically remediate.

Communications with CrowdStrike have been commenced and it seems this issue is not isolated as other organizations nationwide and potentially globally are experiencing the same issue, CrowdStrike currently states “Our Engineering teams are actively working to resolve this issue and there is no need to open a support ticket”.

With no current fix in sight, we are maintaining an open channel with CrowdStrike support to get updates and ensure the quickest remediation possible. Internal communications have been relayed to management staff detailing the issues we are experiencing with the Falcon sensor on the Windows devices to ensure company-wide transparency and that communications are being carried out through official channels to avoid any potential phishing attempts during this time.

We are currently working with the PR and marketing teams to provide them with the necessary information so that they can make a public statement regarding the outage. As a financial organization, the availability of resources is of the utmost importance. We need to ensure that stakeholders are made aware of this current situation and that a timeline for remediation is established as soon as possible to address customer concerns.
If you have any additional questions or concerns in regards to this issue, please feel free to reach out.

Regards,

Erick Rodriguez


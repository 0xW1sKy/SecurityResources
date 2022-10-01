## Business Continuity - Disaster Recovery - Incident Response

{{< figure src="/_img/bcdr.png" >}}

Business continuity.
	Critical Business functions, plans to get them back online fast enough.

Disaster recovery
	When an incident is SO BAD that you had to 'move'

Incident Response


What's considered critical?
	Whatever senior management says is critical
	Whatever keeps the cash register ringing

What's considered not critical
	Anything that doesn’t stop the cash register from ringing.


Business  Continuity Plan
	1) Perform "BIA" - business impact assessment
		a. No discussion of probability. Only impact
	2) BIA Plans -> pick an output
	3) Put plans into place

Business Impact Analysis.
	1) Gather Info
		a. What all things do you do?
	2) Identify what's critical
	3) Map relationships between critical items and dependencies
	4) "Doing the math"
		a. Calculate "MTD" Maximum Tolerable Downtime
		b. Calculate "RTO" - recovery time objective
			i. Amount of time required to recover
			a. Can be split into 2 parts.
				1) Part 1 - RTO "amount of time to order a part"
				2) Part 2 -  'WRT' Work Recovery Time "amount of time to install the ordered parts
		c. Calculate "RPO" - Recovery Point objective
			a. If a problem is encountered, how much date/time are you able to lose? i.e. If you backups are every 24 hours, your RPO should say you're willing to lose up to 24 hours of data if you were to restore to the last backup.
		d. Perform Cost/Benefit analysis
	5) Develop continuity plans
		a. Perform cost/benefit analysis

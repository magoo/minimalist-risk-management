# Example scenarios for an organization
The following are scenarios to support a simple approach to risk found [here](README.md)

These can be modified as much as needed to make sense for a specific organization.

Risk scenarios are hierarchal. They are variable based on how specific they are and the area they address. Top level risks set by leadership are usually broad and non-specific scenarios, whereas scenarios managed by a CISO are scoped to technical scenarios, and individually contributing engineers are far more specific. Engineering efforts that focus on these scenarios will influence the probabilities of higher level scenarios occurring.

This is an example of [decomposing risk](https://medium.com/starting-up-security/decomposing-security-risk-into-scenarios-7ecf0979be01).

## Top level leadership risks
Broad, strategic risks typically expressed by a board or C-Suite when asked by a security team.

- A trust issue has threatened investors (_We don't want to hurt stock price_)
- A trust issue has created a press event. (_Keep us out of the press_)
- A trust issue has begun a regulatory / legal event. (_We don't want to get sued_)
- A trust issue has created a loss in customer activity. (_We want to keep customers happy_)
- An executive is removed do to a mishandled trust issue. (_I want to keep my job_)

## Information Security Risk
These are risks that can be decomposed from top level risks voiced by leadership. These would calibrate a whole team toward specific issues.

- A production infrastructure credential has been exposed publicly.
- Confidential information has leaked and is accessible externally.
  - An employee has leaked intentionally.
  - An employee has accidentally leaked.
  - Information was stolen.
  - A system was misconfigured and exposed confidential information.
- An insider has intentionally used their access for personal gain or to cause harm.
- A customer's data has been improperly accessed.
- An application weakness has resulted in an incident.
  - Public security research has gone outside of a proper disclosure process.
  - A security issue was exploited.
  - An application behaved incorrectly and exposed data.
- We poorly handle an incident.
  - An incident occurred that has "log regret" (logs that needed to exist that did not)
  - We have botched crisis communications and a situation is made worse.
- A vendor of ours has had an incident.
- Payment instruments are compromised en route from customer to us.
- Weak authentication is involved with an incident.
- An adversary is aware that they can operate within our network boundary.
- An employee is physically threatened.
- An unencrypted physical storage device is stolen.
- A production cryptographic certificate or key is exposed (Encryption or Signing)
- An unpredicted and uncategorized incident has occurred.
- A competitor is involved with an incident.
- An endpoint is compromised.

## Tasks
With target risks in mind, a team can pursue OKRs to influence the likelihood of information security risks taking place. This is well covered in [better OKR's](https://medium.com/@magoo/how-to-measure-risk-with-a-better-okr-c259bccf359e).
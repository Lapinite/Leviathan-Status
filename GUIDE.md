# Public status guide

[Status overview](README.md)

## Components

No monitored public service components are registered in this repository yet. Do not interpret an empty component list as operational status. Components should use user-facing service names only, without hosts, providers, regions that reveal private deployment details, or internal dependencies.

## Availability

Availability is not currently measured or reported here. Do not publish an uptime percentage without a defined public measurement window, source, and scope. Repository activity is not evidence that a service is available.

## Incidents

Use the [incident template](templates/incident.md) for a confirmed public incident. Describe the affected user action, severity of impact, start time, update time, workaround if safe, and recovery. Use UTC timestamps. Keep causes at a public level and omit credentials, infrastructure details, personal information, and exploit mechanics.

Suggested editorial states are investigating, identified, monitoring, and resolved. These are reporting labels, not claims that an incident is active.

## Maintenance

Use the [maintenance template](templates/maintenance.md) when maintenance affecting a public service is confirmed. Give the UTC time window, expected user impact, affected public components, and completion or postponement updates.

## Historical status

No incident or maintenance history is published here yet. This means no records are available; it does not establish a history of uninterrupted service. Future records should preserve dated updates and correct inaccuracies transparently.

## Publication

Verify an event before publishing it. Separate confirmed facts from investigation. Review every update for privacy, use consistent public component names, and link only to existing public records. Do not expose private monitoring URLs or security architecture.

See [SECURITY.md](SECURITY.md).

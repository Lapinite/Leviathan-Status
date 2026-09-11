<div align="center">

<img width="100%" src="assets/readme-hero.svg" alt="Leviathan Status">

<br>

<img src="https://img.shields.io/badge/status-system%20preparing-06131d?style=flat-square" alt="Status system preparing">
<img src="https://img.shields.io/badge/scope-public%20components%20only-06131d?style=flat-square" alt="Public components only">
<img src="https://img.shields.io/badge/incidents-user%20impact%20focused-06131d?style=flat-square" alt="User impact focused">

**Public service availability, maintenance and incident information for intentionally exposed Leviathan services.**

[Guide](GUIDE.md) · [Launcher](https://github.com/Lapinite/Leviathan-Launcher) · [Docs](https://github.com/Lapinite/Leviathan-Docs) · [API Docs](https://github.com/Lapinite/Leviathan-API-Docs) · [Security](SECURITY.md)

</div>

## Incident lifecycle

<p align="center">
  <img width="100%" src="assets/incident-flow.svg" alt="Animated Leviathan public incident lifecycle">
</p>

Status communication should prioritize affected public components, user impact, current state, mitigation progress, recovery, and any required user action.

## Status model

<table width="100%">
<tr>
<td width="25%" valign="top"><strong>Operational</strong><br><sub>Public component is functioning within expected conditions</sub></td>
<td width="25%" valign="top"><strong>Degraded</strong><br><sub>Service is available but experiencing reduced reliability or performance</sub></td>
<td width="25%" valign="top"><strong>Incident</strong><br><sub>Public user impact is under investigation or mitigation</sub></td>
<td width="25%" valign="top"><strong>Maintenance</strong><br><sub>Planned maintenance with public-facing impact</sub></td>
</tr>
</table>

## Purpose

This repository is intended to provide public information about:

- service availability
- degraded performance
- scheduled maintenance
- public incidents
- recovery updates
- incident history

Only public-facing components should be named here.

## Service boundaries

Public status may eventually cover intentionally exposed Leviathan components such as launcher-facing services, public APIs, authentication-facing integrations, Cast-facing services, developer integrations and other user-visible platform components.

Microsoft, Xbox, Minecraft/Mojang and other third-party services remain external systems. If an external dependency affects Leviathan users, public status can describe the user impact and dependency category without publishing private provider account details, internal infrastructure topology, credentials or sensitive diagnostics.

## Privacy and infrastructure safety

Status information must not expose private hostnames, private IP addresses, credentials, internal topology, administrative endpoints, provider account identifiers, personal information, database details, or security-sensitive implementation information.

Incident reports should explain user impact and resolution at a useful public level without publishing details that create unnecessary security risk.

## Publication principles

A public status update should be:

- accurate
- timestamped
- scoped to user-facing impact
- clear about whether an incident is ongoing or resolved
- free from speculation presented as fact
- safe to publish without exposing private infrastructure

## Current status

The public status system is being prepared as the Leviathan platform develops. Service components will be listed when they are intentionally made available and monitored publicly.

The absence of a listed public component should not be interpreted as proof that an internal system does or does not exist.

## Related repositories

| Repository | Role |
| --- | --- |
| [Leviathan Launcher](https://github.com/Lapinite/Leviathan-Launcher) | Public launcher information |
| [Leviathan Docs](https://github.com/Lapinite/Leviathan-Docs) | Ecosystem documentation |
| [Leviathan API Docs](https://github.com/Lapinite/Leviathan-API-Docs) | Public API documentation |
| [Leviathan Integrations](https://github.com/Lapinite/Leviathan-Integrations) | Supported public integrations |
| [Leviathan Server Tools](https://github.com/Lapinite/Leviathan-Server-Tools) | Public server tooling |

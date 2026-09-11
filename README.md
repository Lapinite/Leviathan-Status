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

<p align="center"><img width="100%" src="assets/incident-flow.svg" alt="Animated Leviathan public incident lifecycle"></p>

<p align="center"><sub>Status communication prioritizes affected public components, user impact, current state, mitigation, recovery and required user action.</sub></p>

## Public state model

<p align="center"><img width="100%" src="assets/state-map.svg" alt="Animated Leviathan public service state model"></p>

<p align="center"><sub>Operational, degraded, incident and maintenance states communicate what users need without publishing private infrastructure detail.</sub></p>

## Service boundaries

Public status may eventually cover intentionally exposed Leviathan components such as launcher-facing services, public APIs, authentication-facing integrations, Cast-facing services, developer integrations and other user-visible platform components.

Microsoft, Xbox, Minecraft/Mojang and other third-party services remain external systems. If an external dependency affects Leviathan users, public status can describe user impact and the dependency category without exposing provider account details or internal topology.

## Privacy and infrastructure safety

Status information must not expose private hostnames, private IP addresses, credentials, internal topology, administrative endpoints, provider account identifiers, personal information, database details or security-sensitive implementation information.

Incident reports should explain user impact and resolution at a useful public level without publishing details that create unnecessary security risk.

## Publication principles

A public status update should be accurate, timestamped, scoped to user-facing impact, clear about whether an incident is ongoing or resolved, free from speculation presented as fact, and safe to publish.

## Current status

The public status system is being prepared as the Leviathan platform develops. Service components will be listed when they are intentionally made available and monitored publicly.

The absence of a listed public component should not be interpreted as proof that an internal system does or does not exist.

## Related repositories

<p align="center">
<a href="https://github.com/Lapinite/Leviathan-Launcher"><strong>Launcher</strong></a> ·
<a href="https://github.com/Lapinite/Leviathan-Docs"><strong>Docs</strong></a> ·
<a href="https://github.com/Lapinite/Leviathan-API-Docs"><strong>API Docs</strong></a> ·
<a href="https://github.com/Lapinite/Leviathan-Integrations"><strong>Integrations</strong></a> ·
<a href="https://github.com/Lapinite/Leviathan-Server-Tools"><strong>Server Tools</strong></a>
</p>

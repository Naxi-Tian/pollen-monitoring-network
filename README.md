# School-Based Pollen Monitoring Network (PollenTree)

PollenTree is a school-based pollen monitoring initiative that deployed four physical monitoring stations across Beijing and connected them to a real-time companion app. The system served more than 6,000 users with current pollen information.

Tenne Tian founded the initiative and worked on measurement accuracy under wind and rain conditions, as well as Wi-Fi connectivity for automatic station updates. The deployment ran from July 2025 through May 2026 and grew out of a broader graphene pollen-sensor research project.

> An existing `Naxi-Tian/PollenTree` repository was identified in the conversation context. Use this package as a README/structure upgrade for that repository rather than creating a confusing duplicate, unless the current repository has a different scope.

## System overview

```text
Four monitoring stations
        ↓
Networked data updates
        ↓
Real-time companion app
        ↓
6,000+ users
```

Replace this overview with an accurate architecture diagram showing the actual station hardware, communications path, backend, data processing, and app.

## Documented impact

- Four monitoring stations deployed across Beijing.
- Real-time pollen data delivered through a companion app.
- More than 6,000 users served.
- Measurement behavior improved for wind and rain conditions.
- Wi-Fi added for automatic updates.

## Suggested repository structure

```text
app/          Shareable companion-app source or links to its repository
assets/       Station photos, screenshots, maps, and demo media
data/         A documented, redistributable sample—not sensitive raw data
docs/         Architecture, station deployment, maintenance, and methods
firmware/     Actual station firmware
hardware/     Approved schematics, enclosure files, and bill of materials
```

## Before this repository is public

- [ ] Audit and improve the existing `PollenTree` repository instead of duplicating it.
- [ ] Add a verified system architecture and hardware inventory.
- [ ] Document the actual measurement and update pipeline.
- [ ] Explain how wind/rain accuracy was evaluated and improved, using real evidence only.
- [ ] Remove Wi-Fi credentials, API keys, precise private locations, and personal data.
- [ ] Confirm permission to share school, station, hospital, and weather-station information.
- [ ] Add app screenshots and station photos with permission.
- [ ] Add deployment and maintenance guidance that matches the real system.
- [ ] Choose a license after confirming ownership of each component.

## Related work

The underlying graphene-based sensor research, characterization, and publication belong in the companion `graphene-pollen-biosensor` repository. Keeping the repositories separate clarifies two different achievements: sensor research and a real-world monitoring network.

## Status

Historical deployment documented for July 2025–May 2026. **TODO:** state the network's current operating status and provide a live or archived app link, if appropriate.


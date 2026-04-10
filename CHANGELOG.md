<!--
SPDX-FileCopyrightText: 2026 Ludwig Hülk <https://github.com/Ludee> © Reiner Lemoine Institut
SPDX-FileCopyrightText: Climate and Energy Policy Ontology <https://github.com/OpenEnergyPlatform/climate-energy-policy-ontology/>
SPDX-License-Identifier: CC0-1.0
-->

# Changelog

All notable changes to this project will be documented in this file. <br>
For each version, important additions, changes and removals are listed here.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]

### Added

### Changed

### Removed


## [0.1.1] Patch Release - 2026-04-10

### Added
- Introduction, description, scope, and logo to `README.rst` [(#2)](https://github.com/OpenEnergyPlatform/climate-energy-policy-ontology/pull/2)
- Move ontology metadata to `cepo.owl` [(#15)](https://github.com/OpenEnergyPlatform/climate-energy-policy-ontology/pull/15)
- Class `moratorium` [(#16)](https://github.com/OpenEnergyPlatform/climate-energy-policy-ontology/pull/16)
- Class `phase-out` [(#16)](https://github.com/OpenEnergyPlatform/climate-energy-policy-ontology/pull/16)
- Class `phase-down` [(#16)](https://github.com/OpenEnergyPlatform/climate-energy-policy-ontology/pull/16)
- Class `auction` [(#16)](https://github.com/OpenEnergyPlatform/climate-energy-policy-ontology/pull/16)
- Class `auction with floating feed-in premium` [(#16)](https://github.com/OpenEnergyPlatform/climate-energy-policy-ontology/pull/16)
- Issue template `issue_template_new_ontology_term.md` [(#21)](https://github.com/OpenEnergyPlatform/climate-energy-policy-ontology/pull/21)

### Changed
- Ontology metadata [(#15)](https://github.com/OpenEnergyPlatform/climate-energy-policy-ontology/pull/15)
- Ontology IRI [(#15)](https://github.com/OpenEnergyPlatform/climate-energy-policy-ontology/pull/15)
- Rename class `moratoria to ban` [(#16)](https://github.com/OpenEnergyPlatform/climate-energy-policy-ontology/pull/16)
- Add note to class `technology standard` [(#16)](https://github.com/OpenEnergyPlatform/climate-energy-policy-ontology/pull/16)
- Add note to class `performance standard` [(#16)](https://github.com/OpenEnergyPlatform/climate-energy-policy-ontology/pull/16)
- Add note to class `institutional creation` [(#16)](https://github.com/OpenEnergyPlatform/climate-energy-policy-ontology/pull/16)
- Adjust hierarchy of `auction` types to all be children of class `auction` [(#16)](https://github.com/OpenEnergyPlatform/climate-energy-policy-ontology/pull/16)
- Add relation `has part` to class `auction` [(#16)](https://github.com/OpenEnergyPlatform/climate-energy-policy-ontology/pull/16)
- Add relation `green certificate trading scheme` complies with `quota` [(#16)](https://github.com/OpenEnergyPlatform/climate-energy-policy-ontology/pull/16)
- Add relation `white certificate trading scheme` complies with `quota` [(#16)](https://github.com/OpenEnergyPlatform/climate-energy-policy-ontology/pull/16)
- Add relation `greenhouse gas emissions trading scheme` complies with `emissions cap` [(#16)](https://github.com/OpenEnergyPlatform/climate-energy-policy-ontology/pull/16)
- Add relation `offsetting scheme` complies with `offsetting rule` [(#16)](https://github.com/OpenEnergyPlatform/climate-energy-policy-ontology/pull/16)
- Add contributors to `CITATION.cff` [(#17)](https://github.com/OpenEnergyPlatform/climate-energy-policy-ontology/pull/17)

### Removed
- File `cepo.ttl` [(#15)](https://github.com/OpenEnergyPlatform/climate-energy-policy-ontology/pull/15)

## [0.0.0] Initial Release - Hello World - 2025-10-10

### Added
- GitHub repository
- .gitignore
- LICENSE (CC0-1.0 License)

..
  SPDX-FileCopyrightText: 2024 Ludwig Hülk <https://github.com/Ludee> © Reiner Lemoine Institut
  SPDX-FileCopyrightText: super-repo v0.5.0 <https://github.com/rl-institut/super-repo>
  SPDX-License-Identifier: MIT

.. figure:: https://github.com/OpenEnergyPlatform/climate-energy-policy-ontology/blob/develop/docs/img/CEPO_banner.png
    :align: left
    :target: https://github.com/OpenEnergyPlatform/climate-energy-policy-ontology/
    :alt: Repo logo

==================================
Climate and Energy Policy Ontology
==================================

**A common ontology to record and structure climate and energy policy data.**

.. list-table::
   :widths: auto

   * - License
     - |badge_license_CC0| |badge_license_MIT|
   * - Documentation
     - 
   * - Tests
     - 
   * - Publication
     - 
   * - Development
     - |badge_issue_open| |badge_issue_closes| |badge_pr_open| |badge_pr_closes|
   * - Community
     - |badge_contributions| |badge_contributors| |badge_repo_counts|

.. contents::
    :depth: 2
    :local:
    :backlinks: top

Introduction
============
The Climate and Energy Policy Ontology (CEPO) is a common set of definitions and
relationships which can be used to structure information about climate and
energy policy instruments.
The CEPO was first developed in 2025 and will be extended and revised according to
the needs of the user community.

Scope
=====
The CEPO is a collaborative effort between different researchers, from academia and
civil society, to map and clearly define different kinds of climate and
energy policy instruments.
Existing ways of categorizing policy instruments in the climate and energy realm were
developed by practitioners like the International Energy Agency (IEA),
Organization for Economic Cooperation and Development (OECD),
`Climate Policy Database (CPDB) <https://climatepolicydatabase.org/>`_
and `Climate Policy Radar (CPR) <https://www.climatepolicyradar.org/>`_.
These actors gather data on which policy documents have been published in certain years
and tag them with potential instruments.
However, their focus is mapping climate policies and their existence on a large scale,
not on the specific instruments and how they relate to each other.
In some cases, the methodology and definitions were not made publicly available.

We therefore propose a climate and energy policy ontology which encompasses instruments
at a sufficient level of detail to code in-depth policy data.
Rather than coding all “tax instruments” together, we differentiate between a
tax reduction, tax deduction, tax credit, tax exemption, and tax rebate
(all of which are types of tax incentives).
This level of granularity is important in being able to compare policies across
jurisdictions and time.
In order to ensure interoperability with other ontologies it makes use of the
Basic Formal Ontology (BFO) and its principles.
It also maps its alignment with the CPDB and CPR policy instrument typologies.

The ontology can be used to code policy documents with information about the
instruments that they contain.
Such policy data can be used to answer questions such as:

- Which countries tend to use the most regulatory instruments vs economic instruments to introduce electric vehicles?
- What are the most common types of tax incentives to promote renewable energy, and how have these changed over time?
- Which policy instruments (or mixes of policy instruments) have been the most effective at promoting decarbonization outcomes (emissions reductions, growth in clean energy generation, etc.)?

Documentation
=============
| The documentation is created with Markdown using `MkDocs <https://www.mkdocs.org/>`_ and `mike <https://github.com/jimporter/mike>`_.
| All files are stored in the ``docs`` folder of the repository.

Collaboration
=============
| Everyone is invited to develop this repository with good intentions.
| Please follow the workflow described in the `CONTRIBUTING.md <https://github.com/OpenEnergyPlatform/climate-energy-policy-ontology/blob/production/CONTRIBUTING.md>`_.

Contributors:

.. figure:: https://contrib.rocks/image?repo=OpenEnergyPlatform/climate-energy-policy-ontology
    :align: left
    :target: https://github.com/OpenEnergyPlatform/climate-energy-policy-ontology/graphs/contributors
    :alt: [contrib.rocks](https://contrib.rocks)

License
=======
| This repository is **dual-licensed** under `Creative Commons Zero v1.0 Universal (CC0-1.0) <https://creativecommons.org/publicdomain/zero/1.0/legalcode>`_ or `MIT License (MIT) <https://opensource.org/license/mit>`_.
| You can choose between one of them if you use this work.
| See `LICENSE-CC0.txt <LICENSE-CC0.txt>`_ and `LICENSE-MIT.txt <LICENSE-MIT.txt>`_ for rights and obligations.
| Copyright: `Climate and Energy Policy Ontology <https://github.com/OpenEnergyPlatform/climate-energy-policy-ontology/>`_ | `CC0-1.0 <http://creativecommons.org/publicdomain/zero/1.0/>`_ OR `MIT <https://opensource.org/license/mit>`_

Citation
========
| For **scientific citation** of this ontology, please refer to the `CITATION.cff <https://github.com/OpenEnergyPlatform/climate-energy-policy-ontology/blob/production/CITATION.cff>`_ file.




.. |badge_license_CC0| image:: https://img.shields.io/badge/License-CC0%201.0-green.svg
    :target: http://creativecommons.org/publicdomain/zero/1.0/
    :alt: License CC0

.. |badge_license_MIT| image:: https://img.shields.io/badge/License-MIT-green.svg
    :target: https://opensource.org/license/mit
    :alt: License MIT

.. |badge_issue_open| image:: https://img.shields.io/github/issues-raw/OpenEnergyPlatform/climate-energy-policy-ontology
    :target: https://github.com/OpenEnergyPlatform/climate-energy-policy-ontology/issues
    :alt: Open Issues

.. |badge_issue_closes| image:: https://img.shields.io/github/issues-closed-raw/OpenEnergyPlatform/climate-energy-policy-ontology
    :target: https://github.com/OpenEnergyPlatform/climate-energy-policy-ontology/issues?q=is%3Aissue+is%3Aclosed
    :alt: Closed Issues

.. |badge_pr_open| image:: https://img.shields.io/github/issues-pr-raw/OpenEnergyPlatform/climate-energy-policy-ontology
    :target: https://github.com/OpenEnergyPlatform/climate-energy-policy-ontology/pulls
    :alt: Open PR

.. |badge_pr_closes| image:: https://img.shields.io/github/issues-pr-closed-raw/OpenEnergyPlatform/climate-energy-policy-ontology
    :target: https://github.com/OpenEnergyPlatform/climate-energy-policy-ontology/pulls?q=is%3Apr+is%3Aclosed
    :alt: Closed PR

.. |badge_contributions| image:: https://img.shields.io/badge/contributions-welcome-brightgreen.svg?style=flat
    :target: https://github.com/OpenEnergyPlatform/climate-energy-policy-ontology/blob/production/CONTRIBUTING.md
    :alt: Contributions

.. |badge_contributors| image:: https://img.shields.io/github/contributors/OpenEnergyPlatform/climate-energy-policy-ontology
    :target: https://github.com/OpenEnergyPlatform/climate-energy-policy-ontology/graphs/contributors
    :alt: Contributors

.. |badge_repo_counts| image:: https://hits.sh/github.com/OpenEnergyPlatform/climate-energy-policy-ontology.svg
    :target: https://hits.sh/github.com/OpenEnergyPlatform/climate-energy-policy-ontology/
    :alt: Hits

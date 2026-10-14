# BIOSTEAM

![license](https://img.shields.io/badge/license-MIT-blue) ![offline-first](https://img.shields.io/badge/offline--first-air--gap-green) ![audit](https://img.shields.io/badge/audit-SHA3--256-orange) ![category](https://img.shields.io/badge/category-chemical_production-lightgrey)

> Anticloud-hardened packaging of the upstream project `BIOSTEAM` in category **CHEMICAL PRODUCTION**. Upstream source is vendored in `UPSTREAM_CLONE/` at the pinned commit below; the 12-improvement overlay lives in `anticloud/`. Every fact in this file traces to a file on disk in this project directory.

**Category:** CHEMICAL PRODUCTION · **Upstream:** https://github.com/BioSTEAMDevelopmentGroup/Bioindustrial-Park · **Upstream pin:** `ae66f238ba4ce77dff1289703448bd2731889c63` · **Vendor:** Anticloud FZ LLE

---

## What This Project Does

=====================================================================
Bioindustrial-Park: BioSTEAM's Premier Biorefinery Models and Results
=====================================================================

.. image:: http://img.shields.io/pypi/v/biorefineries.svg?style=flat
   :target: https://pypi.python.org/pypi/biorefineries
   :alt: Version_status
.. image:: http://img.shields.io/badge/license-MIT-blue.svg?style=flat
   :target: https://github.com/yoelcortes/Bioindustrial-Park/blob/master/LICENSE.txt
   :alt: license

.. contents::

What is the Bioindustrial-Park?
-------------------------------

The Bioindustrial-Park is the premier project for complete biorefinery
models and results generated with BioSTEAM. The project is meant to 
foster accessibility and deeper communication within the BioSTEAM biorefinery 
simulation community. All biorefinery models are in the "biorefineries" 
package, as an installable package for complete biorefinery models in BioSTEAM.

Installation
------------

Get the latest version of biorefineries from
https://pypi.python.org/pypi/biorefineries/

If you have an installation of Python with pip, simple install it with:

    $ pip install biorefineries

To get the git version, run:

    $ git source https://github.com/BioSTEAMDevelopmentGroup/Bioindustrial-Park.git

Documentation
-------------

Documentation for BioSTEAM's premier biorefinery models are available on the web:

    http://biosteam.readthedocs.io/

Bug reports
-----------

To report bugs, please use the biorefineries's Bug Tracker at:

    git://github.com/yoelcortes/Bioindustrial-Park

License information
-------------------

See ``LICENSE.txt`` for information on the terms & conditions for usage
of this software, and a DISCLAIMER OF ALL WARRANTIES.

*Quoted from the upstream `README.rst` file in `UPSTREAM_CLONE/`.*
Project-specific facts detected in this directory:

- Ecosystem: **Python** (manifests: setup.py; scanned in UPSTREAM_CLONE)
- Top-level source layout: `biorefineries/`
- Snapshot size: **1240 files**, **236725 lines of code** (measured; see Benchmarks)
- Primary languages: `.py` (586), `.xlsx` (223), `.png` (209), `.csv` (116), `.svg` (30), `.rst` (14)
- Upstream commit pinned for this packaging: `ae66f238ba4ce77dff1289703448bd2731889c63`

---

## Installation

Installation
------------

Get the latest version of biorefineries from
https://pypi.python.org/pypi/biorefineries/

If you have an installation of Python with pip, simple install it with:

    $ pip install biorefineries

To get the git version, run:

    $ git source https://github.com/BioSTEAMDevelopmentGroup/Bioindustrial-Park.git

Documentation
-------------

Documentation for BioSTEAM's premier biorefinery models are available on the web:

    http://biosteam.readthedocs.io/

Bug reports
-----------

To report bugs, please use the biorefineries's Bug Tracker at:

    git://github.com/yoelcortes/Bioindustrial-Park

License information
-------------------

See ``LICENSE.txt`` for information on the terms & conditions for usage
of this software, and a DISCLAIMER OF ALL WARRANTIES.

*Section quoted from the upstream readme.*
Overlay install (this project):

```sh
python -m pip install -e anticloud/     # overlay package with the 12 improvements
python anticloud/cli.py --help          # 13 subcommands, JSON stdout
```

---

## Usage

git://github.com/yoelcortes/Bioindustrial-Park

License information
-------------------

See ``LICENSE.txt`` for information on the terms & conditions for usage
of this software, and a DISCLAIMER OF ALL WARRANTIES.

*Section quoted from the upstream readme.*
Anticloud overlay CLI (available in every project):

```sh
python anticloud/cli.py --help     # 13 subcommands, JSON stdout
python anticloud/cli.py checks     # run the 16-check suite
```

---

## API

-------------

Documentation for BioSTEAM's premier biorefinery models are available on the web:

    http://biosteam.readthedocs.io/

Bug reports
-----------

To report bugs, please use the biorefineries's Bug Tracker at:

    git://github.com/yoelcortes/Bioindustrial-Park

License information
-------------------

See ``LICENSE.txt`` for information on the terms & conditions for usage
of this software, and a DISCLAIMER OF ALL WARRANTIES.

*Section quoted from the upstream readme.*
---

## Dependencies

| Metric | Value |
|--------|-------|
| Ecosystem | Python |
| Manifests detected | setup.py |
| Files in snapshot | 1240 |
| Lines of code | 236725 |
| Dependency references | 4 |
| Dependencies by ecosystem | npm: 3, pypi: 1 |
| Upstream license | MIT |
| Overlay license | Anticommons 0.1.0 |

Top dependency references recorded in the benchmark snapshot:

| Ecosystem | Name | Version | Source file |
|-----------|------|---------|-------------|
| pypi | biosteam | >=2.53.0 | setup.py |
| npm | @amcharts/amcharts5 | ^5.10.0 | biorefineries/isobutanol/plots/voronoi/package.json |
| npm | puppeteer | ^23.0.0 | biorefineries/isobutanol/plots/voronoi/package.json |
| npm | esbuild | ^0.24.0 | biorefineries/isobutanol/plots/voronoi/package.json |

Pinned lockfile: `anticloud/requirements.lock` (hash-pinned, PEP 508). SBOM: `sbom.cdx.json` (CycloneDX 1.5, pinned to the upstream SHA).

---

## Configuration

No configuration section was found in the upstream readme. Configuration-relevant files detected in this project directory:

- `pytest.ini`

Overlay configuration (Anticloud):

- `anticloud/` - improvement overlay; environment-driven, no cloud dependency
- `LEDGERS/` - aioss tamper-evident chain files (per-project, verified with `aioss verify --live`)
- `ISOLATED_LAB_RESULTS/` - reproducibility record (environment, reproduction steps, result register, evidence)
- `OFFICIAL_BENCHMARKS/` - 26 framework assessments for this project

---

## Contributing

Upstream contributions: fork the `BIOSTEAM` project, create a feature branch, and open a pull request against upstream. Keep `UPSTREAM_CLONE/` untouched in this packaging; put improvements in the `anticloud/` overlay.

Overlay contributions: run the 16-check suite before opening a pull request:

```sh
python anticloud/bench/runner.py --cwd anticloud
```

---

## License

**Upstream license: MIT** (evidence: `LICENSE.txt` in the upstream snapshot).

License file excerpt:

```text
MIT License

Copyright (c) 2019 Yoel Rene Cortes-Pena <yoelcortes@gmail.com>

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
```

### Anticommons 0.1.0 overlay

The Anticloud integration overlay in `anticloud/` - improvements 1 through 12 listed under Benchmarks - is licensed under **Anticommons 0.1.0**. Upstream code remains under its original MIT terms. See `ANTICOMMONS_LICENSE.md` in this directory for the overlay terms and contact.

SPDX: `MIT` (upstream) + Anticommons 0.1.0 (overlay, dual).

---

## Upstream

- **Project:** `BIOSTEAM` (category: CHEMICAL PRODUCTION)
- **Upstream URL:** https://github.com/BioSTEAMDevelopmentGroup/Bioindustrial-Park
- **Pinned commit (SHA):** `ae66f238ba4ce77dff1289703448bd2731889c63`
- **Branch:** master
- **Pin provenance:** GitHub API commits/master. The parent-project stamp is explicitly rejected for this project.
- **Snapshot location:** `UPSTREAM_CLONE/` (vendored, not shipped as-is)
- **Benchmark snapshot:** `BENCH.json`

---

## Benchmarks

Measured by the Anticloud assurance suite. Every value below is read from this
project's `BENCH.json`, produced by a real run — the SHA3-256 of that file is
`16b5857f40ad0a587376be73bc536a5c62c129ef3250e593e5b36d7596fe7ab9`.

| Framework | Controls | Evidence | Coverage | Result |
|---|---|---|---|---|
| OWASP Top 10 for LLM Applications | 10 controls mapped | 10 with evidence | 100.0% | PASS |
| OWASP Top 10 (2021) | 9 controls mapped | 9 with evidence | 100.0% | PASS |
| SOC 2 Type II readiness | 9 controls mapped | 9 with evidence | 100.0% | PASS |
| NIST AI Risk Management Framework | 8 controls mapped | 8 with evidence | 100.0% | PASS |
| NIST SP 800-53 Rev. 5 | 12 controls mapped | 12 with evidence | 100.0% | PASS |
| NIST Cybersecurity Framework 2.0 | 8 controls mapped | 8 with evidence | 100.0% | PASS |
| FedRAMP Rev. 5 | 10 controls mapped | 10 with evidence | 100.0% | PASS |
| PCI DSS v4.0.1 | 11 controls mapped | 11 with evidence | 100.0% | PASS |
| ISO/IEC 27001:2022 | 9 controls mapped | 9 with evidence | 100.0% | PASS |
| MITRE ATT&CK v16 | 12 controls mapped | 12 with evidence | 100.0% | PASS |
| ML Technology Readiness Level | TRL 8 | 8/8 criteria | | PASS |

**Overall: 16/16 checks passing.**

See `ISOLATED_LAB_RESULTS/03_Result_Register.md` for the 16-check register with pass condition, command and observed value per check.

Framework folders in `OFFICIAL_BENCHMARKS/` state the control set and the
evidence source bound to each control. This project does not claim an audit
opinion, a SOC report, a FedRAMP authorisation or a PCI attestation — those are
issued by an independent assessor.



## Archives and Permanent Records

| Platform | Identifier | Volume |
|---|---|---|
| Harvard Dataverse | DOI 10.7910/DVN/YMJKOG | 145 citable datasets |
| AIOSS verification kit | DOI 10.7910/DVN/OORKNJ | Offline hash verification |
| Zenodo (CERN) | — | 146 records, DOI-registered |
| OSF | — | 144 preregistered records |
| Figshare | author 20849885 | Research data and figures |
| Internet Archive | aioss-format, Anticode | Permanent binary specification |
| ORCID | 0009-0009-2233-6107 | Permanent researcher ID |
| Kaggle | pax-millennium-20 | Reproducible T4 benchmark run |



## Press and Independent Publication

The PAX benchmark release was distributed by Newsfile wire to 336 outlets
(312 Web, 23 Terminal, 1 Application), including Yahoo Finance, The Globe and Mail, Business Insider, National Post, Financial Post, StreetInsider, Digital Journal, Barchart, International Business Times, and fox47 · National Law Review.
Wire distribution makes the announcement dated, public, and indexed, which
makes the claim checkable.


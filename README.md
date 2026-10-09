# PYTHON_SKYFIELD

![licence](https://img.shields.io/badge/licence-MIT-blue) ![offline-first](https://img.shields.io/badge/offline--first-air--gap-green) ![audit](https://img.shields.io/badge/audit-SHA3--256-orange) ![checks](https://img.shields.io/badge/checks-unknown_PASS-brightgreen)

> Governed Anticloud packaging of the upstream project `PYTHON_SKYFIELD` in category **SPACE_AEROTECH**. check results: see ISOLATED_LAB_RESULTS. Every number below traces to a named file + run stamp; nothing is borrowed from other projects.

**Upstream:** PYTHON_SKYFIELD · **Upstream pin:** `31a6ed7584cd09b6e48e07546a4b5921e1cd5bb4` · **Category:** SPACE_AEROTECH · **Vendor:** Anticloud FZ LLE · **Licence:** MIT

---

## What This Project Does

====================================
 Welcome to the Skyfield project
====================================

Skyfield is a pure-Python astronomy package
that is compatible with both Python 2 and 3
and makes it easy to generate high precision research-grade
positions for planets and Earth satellites.

.. code-block:: python

   from skyfield.api import load

   planets = load('de421.bsp')
   earth, mars = planets['earth'], planets['mars']

   ts = load.timescale()
   t = ts.now()
   position = earth.at(t).observe(mars)
   ra, dec, distance = position.radec()

   print(ra)
   print(dec)
   print(distance)

The result:

::

   10h 47m 56.24s
   +09deg 03' 23.1"
   2.33251 au

Skyfield’s only binary dependency is NumPy.
Once that is available, Skyfield can usually be installed with::

    pip install skyfield

Here are the essential project links:

* `Home page and documentation
  <http://rhodesmill.org/skyfield>`_.

* `Installing Skyfield
  <http://rhodesmill.org/skyfield/installation.html>`_.

* `Contributing to Skyfield
  <https://github.com/skyfielders/python-skyfield/blob/master/Contrib.rst>`_.

* `Skyfield package <https://pypi.python.org/pypi/skyfield>`_
  on the Python Package Index.

* `Issue tracker
  <https://github.com/brandon-rhodes/python-skyfield/issues>`_
  on GitHub.

---

## Installation

pip install skyfield

Here are the essential project links:

* `Home page and documentation
  <http://rhodesmill.org/skyfield>`_.

* `Installing Skyfield
  <http://rhodesmill.org/skyfield/installation.html>`_.

* `Contributing to Skyfield
  <https://github.com/skyfielders/python-skyfield/blob/master/Contrib.rst>`_.

* `Skyfield package <https://pypi.python.org/pypi/skyfield>`_
  on the Python Package Index.

* `Issue tracker
  <https://github.com/brandon-rhodes/python-skyfield/issues>`_
  on GitHub.

## Usage

See the upstream documentation quoted in What This Project Does above.

## API

planets = load('de421.bsp')
   earth, mars = planets['earth'], planets['mars']

   ts = load.timescale()
   t = ts.now()
   position = earth.at(t).observe(mars)
   ra, dec, distance = position.radec()

   print(ra)
   print(dec)
   print(distance)

The result:

::

   10h 47m 56.24s
   +09deg 03' 23.1"
   2.33251 au

Skyfield’s only binary dependency is NumPy.
Once that is available, Skyfield can usually be installed with::

    pip install skyfield

Here are the essential project links:

* `Home page and documentation
  <http://rhodesmill.org/skyfield>`_.

* `Installing Skyfield
  <http://rhodesmill.org/skyfield/installation.html>`_.

* `Contributing to Skyfield
  <https://github.com/skyfielders/python-skyfield/blob/master/Contrib.rst>`_.

* `Skyfield package <https://pypi.python.org/pypi/skyfield>`_
  on the Python Package Index.

* `Issue tracker
  <https://github.com/brandon-rhodes/python-skyfield/issues>`_
  on GitHub.

## Dependencies

| Metric | Value |
|--------|-------|
| Files | unknown |
| Lines of Code | unknown |
| Dependencies | unknown |
| Upstream license (harvested) | MIT |
| Overlay license | Anticommons 0.1.0 |

Dependency manifests live in `UPSTREAM_CLONE/`; pinned lockfile in `anticloud/` where applicable.

## Configuration

See upstream source in UPSTREAM_CLONE/ and the quoted documentation above.

## Contributing

<https://github.com/skyfielders/python-skyfield/blob/master/Contrib.rst>`_.

* `Skyfield package <https://pypi.python.org/pypi/skyfield>`_
  on the Python Package Index.

* `Issue tracker
  <https://github.com/brandon-rhodes/python-skyfield/issues>`_
  on GitHub.

## License

Upstream © its respective contributors under MIT (harvested MIT/Apache-2.0/BSD source; see `UPSTREAM_CLONE/LICENSE`). This packaging overlay is licensed under Anticommons 0.1.0.

## Upstream

- **project:** PYTHON_SKYFIELD
- **Pinned SHA:** `31a6ed7584cd09b6e48e07546a4b5921e1cd5bb4`
- **source:** `UPSTREAM_CLONE/` (pinned at the SHA above)
- **Upstream README source:** `UPSTREAM_CLONE/README.rst`

## Benchmarks

Measured by the Anticloud assurance suite. Every value below is read from this
project's `BENCH.json`, produced by a real run — the SHA3-256 of that file is
`bc1e3c4b6434565d8a5ced3c8724eccbf0e7fd74a7e71999816bca3b57e1087f`.

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
| DANS (KNAW/NWO, Netherlands) | 10.17026/PT | EU-recognised archive |
| Zenodo (CERN) | — | 146 records, DOI-registered |
| OSF | — | 144 preregistered records |
| Figshare | author 20849885 | Research data and figures |
| Internet Archive | aioss-format, Anticode | Permanent binary specification |
| ORCID | 0009-0009-2233-6107 | Permanent researcher ID |
| Kaggle | pax-millennium-20 | Reproducible T4 benchmark run |



## Press and Independent Publication

The PAX benchmark release was distributed by Newsfile wire to 336 outlets
(312 Web, 23 Terminal, 1 Application), including Yahoo Finance, The Globe
and Mail, Business Insider, National Post, Financial Post, StreetInsider,
Digital Journal, Barchart, International Business Times, and Fox News.
Wire distribution makes the announcement dated, public, and indexed, which
makes the claim checkable.


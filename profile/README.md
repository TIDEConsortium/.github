# TIDE

**Tinnitus Identification and Diagnosis through Electrophysiology**

TIDE is a multicentre, prospective, case–control biomarker study developing and
validating objective neurophysiological markers for chronic constant tinnitus.
It is funded by the Rainwater Charitable Foundation and coordinated at the
Trinity College Dulin.

## The problem

Tinnitus is diagnosed by self-report. There is no objective test, which
constrains clinical trials, obscures whether apparently similar patients share a
mechanism, and makes treatment effects difficult to measure. TIDE asks whether
central auditory processing differences can be measured directly, reliably
enough to distinguish individuals with chronic tinnitus from those without.

## Design

Case–control, seven international recruiting sites, harmonised protocol.

**Measures**
- 64-channel EEG
- Detailed audiological phenotyping
- Standardised clinical and psychometric instruments (ESIT-SQ, TSCHQ, THI, TFI,
  HQ, HADS, PSQI and others)

**Paradigms**
- **cGPIAS** — cortical gap prepulse inhibition of the acoustic startle, testing whether
  the tinnitus percept fills the silent gap
- **Auditory oddball with omission trials** — testing predictive processing and
  deviance detection
- **Resting-state EEG** — spontaneous oscillatory activity

Mechanistic hypotheses are tested directly; the same data feed a multimodal
machine-learning classifier evaluated for generalisation across sites.

## Sites

| Site | Role |
|---|---|
| University of Tübingen | Coordination, recruitment |
| University of Regensburg | Recruitment |
| University of Zürich | Recruitment, resting-state analysis |
| Ghent University | Recruitment |
| Trinity College Dublin | Recruitment, oddball analysis |
| Austin, USA | Recruitment |
| Illinois, USA | Recruitment |
| St. Gallen | Machine-learning analysis |

## Repositories

| Repository | Contents |
|---|---|
| [`TIDE`](https://github.com/TIDEConsortium/TIDE) | Stimulus generation and calibration, paradigm implementation, EEG preprocessing pipelines, questionnaire and audiometric analysis |
| [`Tinnorm`](https://github.com/TIDEConsortium/Tinnorm) | Normative modelling of tinnitus-related EEG measures |

## Data availability

No participant-level data are held in these repositories, by policy.

The consortium intends to release an anonymised dataset following primary
publication, subject to the ethical approvals and consent conditions at each
site. Release follows TIDE-DMS-001, the consortium's de-identification standard,
which requires a documented disclosure-risk assessment before any deposit.

## Funding

Rainwater Charitable Foundation.

## Contact

Christopher Cederroth, Coordinating Investigator
University of Tübingen — [christopher.cederroth[@]uni-tuebingen.de]

## Citation

Vanneste S, Yasoda-Mohan A, Chen F, et alObjective data-driven personalised approach to diagnosis of chronic tinnitus: the Tinnitus Detection (TIDE) project – protocol for the identification and validation of a biomarker for tinnitus. BMJ Open 2026;16:e112788. doi: 10.1136/bmjopen-2025-112788

# TIDE — Tinnitus Detection 

**Protocol and umbrella repository for the Tinnitus Detection (TIDE) project.**

TIDE is a multicentre, prospective, case–control study identifying and validating
neurophysiological biomarkers of chronic constant tinnitus across seven
international sites. This repository holds the study description, measurement
protocol and shared documentation. Paradigm implementations and analysis code
live in separate repositories — see [Components](#components).

> Vanneste S, Yasoda-Mohan A, Chen F, *et al.* Objective data-driven personalised
> approach to diagnosis of chronic tinnitus: the Tinnitus Detection (TIDE)
> project — protocol for the identification and validation of a biomarker for
> tinnitus. *BMJ Open* 2026;16:e112788.
> [doi:10.1136/bmjopen-2025-112788](https://doi.org/10.1136/bmjopen-2025-112788)

**Trial registration:** [NCT06520865](https://clinicaltrials.gov/study/NCT06520865)
**Status:** recruitment from 1 August 2024, scheduled to complete April 2026;
study end 31 December 2029.

---

## Rationale

Tinnitus is diagnosed by patient report. There is no established objective,
quantitative biomarker for diagnosis or for characterising the condition. That
absence sustains a trial-and-error approach to management, complicates
differential diagnosis where psychiatric or non-auditory factors shape symptom
expression, and leaves treatment trials dependent on subjective endpoints with
inconsistent minimal clinically important differences.

TIDE tests two candidate mechanisms drawn from contemporary models of tinnitus,
using standardised paradigms applied identically across sites.

## Objectives

**Primary.** Determine whether EEG/MEG event-related potential markers derived
from (1) a cortical gap prepulse inhibition of the acoustic startle (GPIAS)
paradigm and (2) an omission auditory oddball paradigm can differentiate
individuals with chronic tinnitus from matched controls.

**Secondary.**
- Test whether these markers are associated with tinnitus intensity and severity
  (loudness matching, questionnaire-based severity)
- Assess reliability and reproducibility across sites, and within-site
  repeatability where applicable
- Evaluate the influence of covariates — hearing loss, hyperacusis, age, sex

## Design

Multicentre, prospective, case–control, experimental and patient-oriented.

**560 participants: 280 chronic constant tinnitus cases, 280 non-tinnitus
controls.** Target 40 cases and 40 controls per site. Cases and controls
group-matched for sex, age and hearing loss post-recruitment.

Sample size. Target 40 cases and 40 controls per site across seven sites,
giving 280 per group. The target was set by site-level feasibility rather than
by an a priori power calculation, as no prior effect-size estimates existed for
these paradigms. With 280 per group, a two-group comparison at α = 0.05
(two-sided) has 80% power to detect d ≈ 0.24 (Cohen's f ≈ 0.12). The study is
not longitudinal and no attrition is anticipated. Prespecified confounders:
age, sex, hearing loss and hyperacusis.

## Sites

| Site | Country | Principal Investigator |
|---|---|---|
| University Hospital Regensburg | Germany | Berthold Langguth |
| University Clinic of Tübingen | Germany | Christopher R. Cederroth |
| Brai3n Clinic | Belgium | Dirk de Ridder |
| Trinity College Dublin | Ireland | Sven Vanneste |
| University of Zurich | Switzerland | Patrick K.A. Neff |
| University of Texas at Austin | USA | Julia Campbell |
| University of Illinois Urbana-Champaign | USA | Fatima T. Husain |

Analysis is additionally supported by Winfried Schlee at the Institute of Information and Process
Management, Eastern Switzerland University of Applied Sciences, St Gallen.

## Ethics approvals

Approved by the ethics committee or IRB at each of the seven sites, compliant
with US and European data protection regulation. Informed consent is obtained
from all participants prior to participation, in accordance with the Declaration
of Helsinki.

| Site | Reference |
|---|---|
| Trinity College Dublin | SPREC022020-07 |
| University of Regensburg | 23-3580_2-101 |
| University of Zurich | 2024-00116 |
| University of Illinois Urbana-Champaign | IRB24-1117 |
| University of Tübingen | 079/2024BO2 |
| Brai3n — University Hospital Antwerp | BUN B3002024000114 |
| University of Texas at Austin | STUDY00004651 |

## Eligibility

**Inclusion**

- Cases: chronic tinnitus for at least 6 months by history, constant, subjective,
  non-pulsatile, classified as primary tinnitus
- Controls: no tinnitus experienced for longer than 2 minutes in one instance
- Age 18–70
- Able to understand, consent and participate
- MoCA ≥ 26
- Hyperacusis Questionnaire (HQ) ≤ 27
- Speaks Dutch, English or German (screening instruments are not validated in
  other languages)
- If receiving tinnitus treatment, the regimen must be stable for ≥ 6 months
  (no initiation or major change); treatment history recorded

**Exclusion**

1. Objective tinnitus; heartbeat-synchronous tinnitus as primary concern
2. Otosclerosis; acoustic neuroma or other ear disorders with fluctuating hearing
3. Acute ear, nose and throat infection (otitis media, otitis externa, sinusitis)
4. Ménière's disease or similar syndromes
5. Vestibular migraine
6. Serious internal, neurological or psychiatric conditions
7. Epilepsy or other CNS disorders (brain tumour, encephalitis)
8. Clinically relevant drug, medication or alcohol abuse up to 2 weeks before
   study start
9. Severe hearing loss — PTA ≥ 71 dB HL in the better ear (mean of 0.5, 1, 2, 4 kHz)
10. Inability to communicate properly during the study
11. One deaf ear

Participants with red flags for secondary or retrocochlear pathology (unilateral
tinnitus, focal neurological signs, vestibular symptoms, unexplained asymmetric
sensorineural hearing loss, disproportionate speech discrimination deficits) are
referred for standard-of-care evaluation including MRI of the internal auditory
meati / cerebellopontine angle, and enrolled only if no secondary cause is found.

## Session structure

Total duration approximately 3 hours.

| Stage | Duration |
|---|---|
| Information, consent, enrolment | — |
| Online questionnaires | 30 min |
| Audiometry | 30 min |
| EEG set-up | 30 min |
| Resting state | 10 min |
| GPIAS paradigm | 45 min |
| Pause | 30 min |
| Oddball paradigm | 60 min |

Order of the GPIAS and oddball paradigms is randomised between subjects,
separately for each site.

## Measures

### Questionnaires

Delivered online through REDCap where possible.

| Instrument | Purpose | Cronbach's α |
|---|---|---|
| **MoCA** | Cognitive screening (30-point; ≥26 for inclusion) | — |
| **ESIT-SQ** | Risk factors, demographics, lifestyle, medical and otological history, tinnitus characteristics | — |
| **THI** | Tinnitus handicap — **primary measure of tinnitus severity** | 0.93 |
| **TFI** | Tinnitus functional index | 0.97 |
| **HADS** | Anxiety and depression | 0.83–0.85 |
| **PSQ-30** | Perceived stress | 0.94 |
| **HQ** | Hyperacusis (≤27 for inclusion) | 0.90 |
| **VAS** | Tinnitus loudness (0–100), per cent of waking time aware, annoyance (0–100) | — |

Plus additional items on pain and physical discomfort. Individual sites may
administer further instruments beyond this common battery.

### Audiological

**Pure-tone audiometry.** Air-conduction thresholds in a sound-treated booth on
a clinical audiometer calibrated to site standard, following otoscopy to confirm
a clear ear canal. Thresholds at **0.5, 1, 2, 3, 4, 6, 8, 10 and 12.5 kHz**, with
bone conduction where indicated, per British Society of Audiology procedures
using a standard ascending method (10 dB down / 5 dB up), threshold defined as
the lowest level eliciting responses on at least 50% of ascending trials.
Extended high-frequency audiometry to 16 kHz at sites so equipped. Masking
applied where interaural attenuation or air–bone gap criteria indicate.

**Tinnitus pitch.** Paired-comparison procedure. A 500 Hz then a 4000 Hz pulsed
tone; the participant selects which more closely matches the tinnitus pitch.
Comparison then proceeds to 2000/8000 Hz or 250/1000 Hz accordingly, converging
in half-octave steps. Repeated three times and averaged.

**Loudness matching.** Ascending method of limits from 10 dB above threshold,
comparing tinnitus loudness to a 1000 Hz tone in 2 dB steps until bracketed.
Repeated five times and averaged. Performed in the tinnitus ear, or the ear with
the louder percept; if equal, the right ear. Unilateral tinnitus is analysed
contralaterally to the tinnitus ear; bilateral tinnitus contralaterally to the
worse ear.

**Quality assurance.** All sites follow a harmonised audiology Scope of Practice
covering equipment calibration checks, standardised instructions, threshold
criteria, masking rules and data-entry conventions. Site-specific deviations are
documented; outcome variables and scoring definitions are held constant across
centres.

### Electrophysiology

**64-channel EEG** at all sites. Tübingen additionally attempts simultaneous MEG
using low-interference Etymotic ER2 earbuds; where simultaneous acquisition is
not achievable, EEG only is collected.

Recordings are made in a quiet, dimmed room with the participant seated upright.

**Resting state** — 5 minutes, eyes open.

## Paradigms

### GPIAS — cortical gap prepulse inhibition of the acoustic startle

**Hypothesis.** Individuals with tinnitus show impaired inhibition of cortical
evoked responses to sound pulses when preceded by a silent gap embedded at a
carrier frequency close to the tinnitus percept, relative to non-tinnitus
individuals. Inhibition with a broadband carrier is expected to be similar
between groups.

Unlike classical GPIAS, which indexes the motor startle reflex, this
implementation measures the **cortical** response. GPIAS is regulated at the
level of the auditory cortex, and cortical responses may capture inhibition more
accurately than motor reflex measures.

**Stimuli.** Delivered binaurally through Etymotic ER2 ear inserts; background
SPL below 35 dB(A). Sound is calibrated directly from the ear insert against a
calibration microphone and compared with a high-frequency head calibrator.

- **Pulse:** broadband, 20 ms, 90 dB, no rise or fall time
- **Carriers:** continuous broadband noise (BBN), or Butterworth-filtered 1 kHz-wide
  narrowband noise centred at 3 kHz or 8 kHz (48 dB/octave), all at 60 dB
- **Gap:** 50 ms, 2 ms rise and fall ramp, down to background noise floor,
  preceding the pulse by 240 ms ISI
- **Trial types:** pulse only (PO), gap + pulse (GP), gap only (GO)

**Structure.** PO, GP and GO are presented 100 times in trios of randomised
order within each carrier condition, 50 random trials per block. The three
carrier sessions (BBN, 3 kHz, 8 kHz) are presented in randomised order.

Before and after the carrier sessions, an **input/output block** presents 25 PO
trials at randomised intensities (70, 75, 80, 85, 90 dB) in a 60 dB BBN carrier —
50 trials in total — to characterise the ERP input/output growth function and
habituation to pulses.

**Outcome.** Peak amplitude and latency of the N1 ERP.

Participants fixate a dark `+` on a white background throughout. Total GPIAS
duration approximately 1 hour, with intercom contact after each session.

### Auditory oddball with omissions

**Hypothesis.** Individuals with tinnitus show a stronger electrophysiological
response to mismatch between prediction and perception (MMN), and increased
amplitude with delayed latency of the late positive evoked response (P300),
relative to controls. MMN is proposed as a marker for tinnitus **loudness**,
P300 for tinnitus **presence**.

Procedure follows Wacongne and colleagues.

**Stimuli.** Two five-element sequences of 50 ms elements, 7 ms rise and fall,
250 ms ISI, normalised to equal root-mean-square power:

- **Sequence X** — five 500 Hz tones
- **Sequence Y** — four 500 Hz tones and one white noise burst

**Presentation level.** Set individually to the participant's most comfortable
loudness, established with a 1–7 rating scale in 5 dB steps, followed by a
loudness match between the tones and the noise burst. This controls for the
possibility that ERP differences between standards and deviants reflect
subjective loudness rather than deviance, and accounts for hearing loss in
perceptual rather than physical terms.

**Protocols.** Three, presented in randomised order:

1. **xxxxx** — Sequence X standard, Sequence Y first deviant, omission second deviant
2. **xxxxY** — Sequence Y standard, Sequence X first deviant, omission second deviant
3. **Omission-only** — Sequence Omission, 100% expected

Each protocol comprises **5 blocks of 125 trials**. Each block opens with 25
trials of the standard to establish the global rule; of the following 100 trials,
standards occur with 75% probability, deviants 15% and omission sequences 10%.
Across the five blocks of a protocol: **500 standards, 75 deviants, 50 omission
sequences**. The omission-only protocol presents 125 Sequence Omission trials
separately.

Random intertrial jitter 1300–1500 ms. Participants attend to the stimuli with
eyes fixed on a point ahead, with breaks every two blocks and between protocols.

## Safety and adverse events

EEG and MEG are non-invasive and serious adverse events are not expected.
Anticipated events include transient scalp redness or mild skin irritation from
the cap and electrolyte, transient discomfort from sound stimulation including
startle or hyperacusis-related discomfort, fatigue or mild headache from
prolonged testing, transient dizziness or nausea, and where applicable anxiety
or claustrophobia during MEG.

Mitigations: skin-friendly procedures with minimal abrasion, disinfected
electrodes, hypoallergenic electrolyte where needed, monitoring throughout,
calibrated and conservative sound levels that can be reduced or the session
paused or terminated at the participant's request, and regular breaks. Testing
stops immediately if a participant reports unacceptable discomfort. All adverse
events are recorded with severity and relatedness and reported per local
ethics/IRB procedures.

Pilot cGPIAS testing indicated that 90 dB pulses are tolerated by individuals with and
without tinnitus (~n=20), giving ERP amplitudes similar to 95 dB pulses, and that
60 dB carriers are as effective as 65 dB and more comfortable
(Shabestari et al., JARO. 2025. 26(5):515–529. doi: 10.1007/s10162-025-00999-w). Hence, TIDE tested 90 dB
pulses in a 60 dB carrier.

## Data management

All data are managed under **unique study codes**. The key associating codes with
participant identities is stored in a protected file with access restricted to
designated members of the research team at each site. Paper documentation is held
in locked cabinets in secured offices; electronic data on a secure,
password-protected server. Participant names are not disclosed; analyses use
de-identified coded data only, and only summary statistics are reported.

Variables collected for analysis:

1. **Demographics** — age, sex/gender, race/ethnicity where available, study site,
   assessment language
2. **Clinical** — case/control status, tinnitus duration and characteristics from
   ESIT-SQ, treatment history and stability, MoCA, HQ, THI, TFI, HADS, PSQ-30,
   VAS ratings
3. **Audiological** — pure-tone thresholds including high frequencies where possible, derived
   hearing-loss indices, tinnitus pitch and loudness matching
4. **Neurophysiological** — outcomes derived from EEG/MEG

### Repository data policy

**No participant-level data are held in any TIDE repository.** Data are read from
paths outside the repository tree; a `.gitignore` and a pre-commit hook enforce
this. Identifier crosswalks linking TIDE study codes to those of any other study
are treated as the most sensitive file class and never enter a repository. See
[`CONTRIBUTING.md`](CONTRIBUTING.md).

Any public release of data follows **TIDE-DMS-001**, the consortium's
de-identification standard, which requires a documented disclosure-risk
assessment before deposit. Removal of an identifier column does not constitute
de-identification.

## Components

| Repository | Contents | Status |
|---|---|---|
| **`TIDE`** (this repository) | Protocol, study description, shared documentation | Public |
| `tide-gpias` | GPIAS stimulus generation, calibration, paradigm, preprocessing | Private until publication |
| `tide-oddball` | Oddball paradigm, loudness matching, sound generation, EEGLAB preprocessing | Private until publication |
| `tide-questionnaires` | Questionnaire and audiometric analysis (R) | Private until publication |
| [`Tinnorm`](https://github.com/TIDEConsortium/Tinnorm) | Normative modelling of tinnitus-related EEG measures | Public |

Paradigm repositories are released as their corresponding manuscripts are
published, each archived with its own DOI.

## Contributing

See [`CONTRIBUTING.md`](CONTRIBUTING.md). Before your first commit:

```
chmod +x .githooks/pre-commit
git config core.hooksPath .githooks
```

## Funding

Rainwater Charitable Foundation (#18340). CRC receives additional funding from
the American Tinnitus Association.

## Citation

If you use material from this repository, please cite the protocol:

```bibtex
@article{Vanneste2026TIDE,
  author  = {Vanneste, Sven and Yasoda-Mohan, Anusha and Chen, Feifan and others},
  title   = {Objective data-driven personalised approach to diagnosis of chronic
             tinnitus: the Tinnitus Detection (TIDE) project — protocol for the
             identification and validation of a biomarker for tinnitus},
  journal = {BMJ Open},
  year    = {2026},
  volume  = {16},
  pages   = {e112788},
  doi     = {10.1136/bmjopen-2025-112788}
}
```

<!-- Add CITATION.cff and, once minted, the Zenodo concept DOI for this repository. -->

## Licence

<!-- Add a LICENSE file. CC-BY-4.0 suits the documentation in this repository;
     MIT or BSD-3-Clause suits the analysis code repositories. Note the protocol
     paper itself is CC BY-NC 4.0. -->

## Contact

Christopher Cederroth, University Clinic of Tübingen — christopher.cederroth[@]uni-tuebingen.de
Sven Vanneste, Trinity College Dublin — sven.vanneste[@]tcd.ie

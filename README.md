# 2026 Sagan Summer Workshop — Roman Exoplanets

## Exoplanets with Roman Surveys: Microlensing and Transits

A public, collaborative, **source-available and non-commercial** learning repository built around the hands-on computational material from the **2026 Sagan Summer Workshop: Exoplanets with Roman Surveys: Microlensing and Transits**.

This repository is designed for two complementary uses:

1. **Try the workshop exercises yourself** using preserved copies of the original workshop notebooks.
2. **Study completed versions** in which the workshop-provided material is preserved and participant code is added only where the notebooks explicitly request learner input. Completed copies will retain executed outputs where practical so readers can inspect plots, fitted parameters, tables, diagnostics, and other results without rerunning every cell.

> This is an independent educational and learning repository. It is not an official NASA, Caltech, NExScI, Nancy Grace Roman Space Telescope, or Sagan Summer Workshop repository.

## What this repository covers

The workshop materials explore computational methods used in Roman exoplanet science, including:

- gravitational microlensing;
- point-source point-lens modelling;
- binary-lens microlensing;
- caustics and finite-source effects;
- model fitting and chi-square minimization;
- Markov Chain Monte Carlo (MCMC);
- simulated Roman-like light curves;
- transit and microlensing events in Galactic context;
- Galactic Center events;
- dark-lens investigations;
- spectral energy distribution (SED) fitting; and
- binary events.

The notebooks use Python/Jupyter workflows and tools such as NumPy, pandas, matplotlib, SciPy, Astropy, MulensModel, emcee, corner, iminuit, VBMicrolensing, and SPISEA where relevant to the individual exercises.

## Repository structure

```text
2026-Sagan-Summer-Workshop-Roman-Exoplanets/
├── README.md
├── LICENSE
├── LICENSE_SCOPE.md
├── NOTICE
├── CONTRIBUTING.md
├── CONTRIBUTOR_AGREEMENT.md
├── THIRD_PARTY_NOTICES.md
├── requirements.txt
│
├── workshop-materials/
│   ├── README.md
│   ├── SSW2026_Google_Colab_Instructions.pdf
│   └── notebooks/
│       ├── session-1/
│       │   ├── SSW2026_HandsOnI_Microlens_Setup.ipynb
│       │   ├── SSW2026_HandsOnI_SingleLens.ipynb
│       │   ├── SSW2026_HandsOnI_Binary_Lens.ipynb
│       │   └── SSW2026_HandsOnI_Group_Project.ipynb
│       └── session-2/
│           ├── SSW2026_HandsOnII_ML_or_Transit_Context.ipynb
│           ├── SSW2026_HandsOnII_Group_Project_GC_Event.ipynb
│           ├── SSW2026_HandsOnII_Group_Project_Dark_Lens.ipynb
│           ├── SSW2026_HandsOnII_Group_Project_SED_Fitting.ipynb
│           └── SSW2026_HandsOnII_Group_Project_Binary_Event.ipynb
│
├── completed-notebooks/
│   ├── README.md
│   ├── session-1/
│   └── session-2/
│
├── notes/
│   └── README.md
├── results/
│   └── README.md
└── participation/
    └── README.md
```

The `workshop-materials/` directory preserves the **default workshop files** for learners who want to attempt the exercises independently. The `completed-notebooks/` directory is kept separate and will contain participant-completed copies with answers added only at the intended exercise locations and executed outputs retained where practical.

## Suggested learning workflow

```text
Read the concept
      ↓
Open the original workshop exercise
      ↓
Attempt the incomplete cells yourself
      ↓
Run and inspect the analysis
      ↓
Compare with the completed notebook
      ↓
Read the accompanying notes and interpretation
```

The completed notebooks will preserve existing workshop content as closely as possible. Participant additions are limited to cells or placeholders where the workshop explicitly asks the learner to provide code, values, parameters, plots, or analysis.

## Hands-On Session I — Microlensing Fits of Single and Binary Lenses

Coverage includes:

- microlensing environment/setup;
- single-lens microlensing;
- binary-lens microlensing;
- group-project analysis;
- parameter estimation;
- optimization and MCMC; and
- finite-source and higher-order modelling where included in the exercises.

## Hands-On Session II — Placing Transit or Microlensing Events in a Galactic Context

Coverage includes:

- transit or microlensing events in Galactic context;
- Galactic Center events;
- dark-lens analysis;
- SED fitting; and
- binary-event exploration.

## Workshop materials and permission

The source notebooks and instructional PDF were created by the workshop organizers and contributors. They are **not authored or owned by this repository owner merely because they appear here**.

Direct permission to include and redistribute the workshop-provided notebooks and instructional PDF in this public educational repository was confirmed by a workshop organizer in August 2026. The original workshop files are therefore preserved separately from participant-created material and retain their original authorship and attribution.

The repository distinguishes between:

- workshop-authored notebooks and documents;
- participant-added solutions and executed outputs;
- independently written notes, explanations, documentation, and repository structure; and
- participation evidence.

See [`THIRD_PARTY_NOTICES.md`](THIRD_PARTY_NOTICES.md) for provenance and attribution details.

## Running the notebooks

The workshop notebooks were designed primarily for **Google Colab**, although many can also be run as standard Jupyter notebooks with the appropriate Python environment and dependencies.

Start with [`workshop-materials/SSW2026_Google_Colab_Instructions.pdf`](workshop-materials/SSW2026_Google_Colab_Instructions.pdf). Session I begins with the microlensing setup notebook; Session II relies on workshop-provided shared data resources described in the original instructions.

The repository-level [`requirements.txt`](requirements.txt) provides an overview of the main Python dependencies observed across the notebooks. Individual exercises may require additional setup or specific versions.

## Results and notes

The repository will include selected plots, modelling outputs, explanations, and concise technical notes so that the work is useful even to readers who do not run every notebook themselves.

For each completed exercise, the documentation will aim to explain:

- what problem is being solved;
- what model or method is being used;
- what the important parameters mean;
- what was added to the workshop template;
- what output was produced;
- how the result is interpreted; and
- what was learned from the exercise.

## Participation

This repository also serves as a record of participation and continued work through the 2026 Sagan Summer Workshop material. Selected screenshots and formal attendance documentation may be added under [`participation/`](participation/) when appropriate.

Participation evidence is intentionally secondary to the scientific and computational content of the repository.

## Ownership and contribution model

Repository-original material is controlled by the repository owner. Contributors are welcome to propose improvements through issues and pull requests, but contributions will only be accepted under the terms in [`CONTRIBUTING.md`](CONTRIBUTING.md) and [`CONTRIBUTOR_AGREEMENT.md`](CONTRIBUTOR_AGREEMENT.md).

The contribution policy is designed so that accepted contributor-authored material can be centrally maintained, relicensed, and enforced by the repository owner. Third-party workshop material is excluded from any claim of ownership by the repository owner.

## License — non-commercial use only

Repository-original software and code made available by the repository owner are licensed under the **PolyForm Noncommercial License 1.0.0**, subject to the scope and third-party exclusions described in [`LICENSE_SCOPE.md`](LICENSE_SCOPE.md), [`NOTICE`](NOTICE), and [`THIRD_PARTY_NOTICES.md`](THIRD_PARTY_NOTICES.md).

**Commercial use of repository-original licensed software is not permitted under that license** unless separate written permission is granted by the applicable copyright holder.

This project is therefore described as **source-available**, not OSI-approved open source. The source is public and collaboration is welcome, but commercial use is intentionally restricted.

The repository license does **not** transfer ownership of or override rights in workshop-provided notebooks, PDFs, datasets, or other third-party material.

## Status

**In progress.** The original workshop materials and repository governance are now in place. The next phase is to complete the exercise notebooks systematically, retain reproducible outputs, and add concise technical notes and result explanations.

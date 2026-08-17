# Completion Roadmap

This roadmap tracks the transition from the preserved workshop source material to reproducible participant-completed notebooks.

The source notebooks under `workshop-materials/` are treated as reference copies and are not edited for participant solutions. Completed work is created separately under `completed-notebooks/`.

## Completion standard

A notebook is marked complete only when:

- all intended learner-input cells have been addressed;
- workshop-authored instructional content and starter code have been preserved as closely as possible;
- the notebook executes successfully in its intended environment, where the required workshop data and dependencies remain available;
- meaningful outputs such as figures, fitted values, tables, chains, or diagnostics have been retained where practical;
- obvious runtime errors have been resolved without silently rewriting the scientific exercise;
- participant additions can be distinguished from the underlying workshop-authored material through repository provenance and documentation;
- a concise exercise note explains the objective, approach, important outputs, and interpretation.

## Hands-On Session I — Microlensing Fits of Single and Binary Lenses

- [ ] **Environment/setup** — `SSW2026_HandsOnI_Microlens_Setup.ipynb`
  - Verify the workshop environment and data download process.
  - Preserve a reproducible record of the setup used for the completed exercises.

- [ ] **Single-lens microlensing** — `SSW2026_HandsOnI_SingleLens.ipynb`
  - Complete all designated learner-input cells.
  - Fit the single-lens event.
  - Retain model/data visualizations and fitting diagnostics.
  - Document parameter interpretation and fitting workflow.

- [ ] **Binary-lens microlensing** — `SSW2026_HandsOnI_Binary_Lens.ipynb`
  - Complete designated learner-input cells.
  - Explore binary-lens geometry, caustics, finite-source effects, and fitting steps requested by the notebook.
  - Retain meaningful plots and diagnostics.

- [ ] **Session I group project** — `SSW2026_HandsOnI_Group_Project.ipynb`
  - Complete the independent analysis requested by the notebook.
  - Preserve optimization/MCMC results and comparison of models where requested.
  - Document assumptions and interpretation.

## Hands-On Session II — Placing Transit or Microlensing Events in a Galactic Context

- [ ] **Main Galactic-context exercise** — `SSW2026_HandsOnII_ML_or_Transit_Context.ipynb`
  - Complete requested analysis using the workshop catalog resources.
  - Retain CMD/kinematic/context plots and relevant outputs.

- [ ] **Galactic Center event** — `SSW2026_HandsOnII_Group_Project_GC_Event.ipynb`
  - Complete the selected event analysis.
  - Document the Galactic Center context and conclusions supported by the exercise.

- [ ] **Dark-lens project** — `SSW2026_HandsOnII_Group_Project_Dark_Lens.ipynb`
  - Select/use an appropriate event as requested by the notebook.
  - Complete CMD and kinematic-context analysis.
  - Document what can and cannot be inferred about source/lens properties.

- [ ] **SED fitting** — `SSW2026_HandsOnII_Group_Project_SED_Fitting.ipynb`
  - Establish the recommended SPISEA environment.
  - Generate and compare isochrones/SEDs as requested.
  - Retain results and document the multidimensional fitting challenges identified in the exercise.

- [ ] **Binary-event project** — `SSW2026_HandsOnII_Group_Project_Binary_Event.ipynb`
  - Inspect provided light curves.
  - Identify and visualize binary-event signatures as requested.
  - Compare unusual events in the relevant parameter spaces and document interpretation limits.

## Supporting documentation

- [ ] Add concise technical notes for microlensing fundamentals.
- [ ] Add a glossary of important parameters and astronomy terms used in the notebooks.
- [ ] Add selected result figures under `results/` where standalone figures improve navigation.
- [ ] Add workshop participation screenshots with descriptive captions.
- [ ] Add formal attendance documentation when available.
- [ ] Perform a final reproducibility and attribution review before the first stable release.

## Versioning approach

The repository will keep two distinct layers:

```text
workshop-materials/       unchanged/default workshop source copies
completed-notebooks/      participant-completed copies with saved outputs
```

This separation is intentional: readers can attempt the workshop exercises first and then compare their work with the completed versions.

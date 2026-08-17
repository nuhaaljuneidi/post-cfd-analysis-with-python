# Post-CFD Analysis with Python

A six-session, application-driven course by **Dr. Nuha Aljuneidi** for students, researchers, and practicing engineers who want to turn CFD results into trustworthy engineering evidence.

The course begins after a CFD solver has produced results. It focuses on validation, automation, interpretation, and communication—not on building meshes or running a particular solver. Every notebook runs directly in Google Colab and includes synthetic data, so no commercial CFD license is required. The import patterns are designed for generic CSV files and ANSYS Fluent exports.

## Course roadmap

| Session | Topic | Start |
|---|---|---|
| 1 | From CFD Export to Trustworthy Data | [Open in Colab](https://colab.research.google.com/github/nuhaaljuneidi/post-cfd-analysis-with-python/blob/main/session-01/session-01-student.ipynb) |
| 2 | Field Maps, Profiles, and Publication-Quality Figures | [Open in Colab](https://colab.research.google.com/github/nuhaaljuneidi/post-cfd-analysis-with-python/blob/main/session-02/session-02-student.ipynb) |
| 3 | Surface Data, Pressure Coefficient, and Aerodynamic Loads | [Open in Colab](https://colab.research.google.com/github/nuhaaljuneidi/post-cfd-analysis-with-python/blob/main/session-03/session-03-student.ipynb) |
| 4 | Transient CFD and Spectral Analysis | [Open in Colab](https://colab.research.google.com/github/nuhaaljuneidi/post-cfd-analysis-with-python/blob/main/session-04/session-04-student.ipynb) |
| 5 | Turbulence, Wakes, and Engineering Diagnostics | [Open in Colab](https://colab.research.google.com/github/nuhaaljuneidi/post-cfd-analysis-with-python/blob/main/session-05/session-05-student.ipynb) |
| 6 | Multi-Case Automation and Reproducible CFD Reports | [Open in Colab](https://colab.research.google.com/github/nuhaaljuneidi/post-cfd-analysis-with-python/blob/main/session-06/session-06-student.ipynb) |

## What participants will learn

1. Import and standardize CFD exports without losing units or conventions.
2. Distinguish solver convergence from engineering validation.
3. Create defensible field maps, profiles, force coefficients, and spectral results.
4. Analyze transient signals, wakes, turbulence statistics, and multi-case studies.
5. Automate quality checks and create reproducible CFD reports.

## Recommended background

Introductory fluid mechanics and basic familiarity with CFD terminology are expected. Prior Python experience is helpful but not required.

## Software

Google Colab, Python, NumPy, pandas, Matplotlib, and SciPy.

## Using your own Fluent data

Export tables or solution data as CSV. Include coordinates, variable names, units, operating conditions, reference values, and case identifiers. Begin by replacing the synthetic-data cell in a notebook with `pd.read_csv(...)`, then map your solver's column names to those used in the exercise.

## Engineering standard

Every reported result should include a value, unit, reference convention, numerical-quality check, physical interpretation, and limitation.

## Instructor

**Dr. Nuha Aljuneidi**  
Assistant Professor of Mechanical Engineering, Embry-Riddle Aeronautical University.

# Portfolio development notes

The PPG repositories are based on Kiana Pilevar Abrisham's research and link the related publications. The SVM, Naive Bayes, K-means, tabular MLP, stroke-pipeline, and MobileNet projects are separate learning or applied-workflow examples.

## Research and subsequent engineering

The original PPG notebooks provide research provenance. Later repository work used AI coding assistance for implementation and refactoring, input checks, tests, documentation, public-data preparation, and execution of validation runs. The current modular packages and recorded reevaluations should be understood in that context. Repository ownership and a commit author name do not imply that every current line was written without assistance.

The research notes describe changes from the notebooks. Source hashes and commit references identify the implementations used for recorded evaluations. A fresh evaluation of a revised implementation is distinct from reconstructing every original experiment.

## Execution records

The September 2026 portfolio checks and public-PWDB runs were executed in a hosted Linux CPU environment. Historical notebook outputs and run metadata can therefore contain absolute paths beginning with `/workspace/scratch/`. These paths identify that execution environment; they are not installation instructions or a requirement to use the same filesystem.

Use each repository's commands from its root directory and choose a new output directory for each run. The saved records retain their original paths, configurations, results, and limitations. Their presence does not claim that the runs were performed on the maintainer's personal computer.

## Maintenance history

Several projects were packaged and revised together in September 2026. Their commit dates record those repository updates; they should not be used as the dates on which the underlying research was conducted. Shared PPG utilities and similar setup instructions reflect related pipelines.

The subsequent Python formatting pass preserves program syntax-tree structure. It changes readability without changing model definitions, split logic, or training settings. Existing numerical reports retain the source commit used for their evaluations.

## Reading the evidence

- Public-PWDB results cover six age-classification model/site experiments and one radial XGBoost evaluation, with 35 saved fold models.
- Attention, ResNet-18, and VGG16 have software checks but no completed full public-data evaluation in the current records.
- The other projects state their own small-dataset or synthetic-example scope. An executed notebook or passing test verifies only the checks described with it.

Results and limitations are documented at project level so that each claim can be traced to its input data, configuration, and outputs.

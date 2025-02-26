# Brainstorm-Tool-Additional-Files
This repository contains datasets and files to test the tool and the documentation to manually build a pipeline.

## Testing
To test the tool, execute the pipeline on the correspondong dataset and compare the output report to the report of the expected output.
| Dataset | Pipeline | Expected Output |
| -------- | ------- | ------- |
| [Face13_S01_S02*](https://drive.google.com/file/d/1aa7S7_9JyNxn00QL75GLCeul6eHWB7hb/view?usp=drive_link) | [test pipeline](./pipeline/example/pipeline_eeg_test.json) | [Face13_S01_S02_output](https://drive.google.com/file/d/1ns2XUlvlCfoFqnyGndz7hQCq9fpPsiRk/view?usp=drive_link) |

\* The Face13_S01_S02 dataset contains only the subject 1 and subject 2 of the Face13 dataset.


## How To a Create Pipeline

An [example of a pipeline](./example/pipeline_eeg_test.json) can be used as a starting point (before adding or removing processes). A [list of process](./process_documentation.md) and a [template for each process](./process_json_templates.md) (including the Brainstorm plugins) is avaible on this repo.

Pipelines are saved as `JSON`. The only required field is `Processes`, which contains a list of processes that will be executed one after the other.

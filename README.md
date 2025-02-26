# Brainstorm-Tool-Additional-Files
This repository contains datasets and files to test the tool and the documentation to manually build a pipeline.

## How To a Create Pipeline
The easiest way to create a pipeline is using the [Brainstorm interface](https://github.com/CorentinLabelle/Brainstorm-Tool?tab=readme-ov-file#pipelines). Another is to create a `JSON` file. An [example of a pipeline](./example/pipeline_eeg_test.json) can be used as a starting point (before adding or removing processes). A [list of process](./process_documentation.md) and a [template for each process](./process_json_templates.md) (including the Brainstorm plugins) is avaible on this repo.

Pipelines are saved as `JSON`. The only required field is `Processes`, which contains a list of processes that will be executed one after the other.

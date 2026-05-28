
# LLM-BPMInterviewer Benchmark Repository

This repository contains the complete experimental benchmark used in the paper:

**"LLM-based Interviewer for Process Control-Flow Elicitation"**

The repository provides all artifacts required to reproduce, inspect, and evaluate the experiments conducted with the SBMN-based LLM interviewer proposed in the study.

The benchmark contains **33 business process scenarios** organized into two independent interview executions:

* `SUBJECT1`
* `SUBJECT2`

Each subject represents an independent execution set performed by a different participant during the experimental evaluation described in the paper.

---

# Repository Structure

Each scenario (`SC001` ... `SC033`) follows the same artifact organization:

```text
SCXXX/
│
├── description/
│   └── process_description.txt
│
├── GROUND_TRUTH/
│   ├── reference_model.bpmn
│   ├── expected_sbmn.json
│   
│
├── interview/
│   ├── interview_transcript.txt
│   ├── obtained_sbmn.json
│   └── interview_metadata.json
│
├── solutions/
│   ├── solution_01.bpmn
│   ├── solution_02.bpmn
│   └── ...
│
├── evaluation/
│   ├── evaluation_metrics.csv
│   ├── evaluation_summary.json
│   └── confusion_analysis.csv
│
└── metadata/
    └── scenario_metadata.json
```

---

# Artifact Description

## description/

Contains the natural language process description used as the source for the elicitation interview.

## GROUND_TRUTH/

Contains the reference artifacts used as ground truth during evaluation:

* Reference BPMN model
* Expected SBMN model

## interview/

Contains the complete elicitation interview execution:

* Full interview transcript
* SBMN model obtained during the interview
* Metadata regarding the interview execution

## solutions/

Contains BPMN models automatically generated from the elicited SBMN model.

## evaluation/

Contains evaluation results and metrics computed for the generated BPMN solutions.

## metadata/

Contains additional scenario-level metadata and benchmark characterization information.

---

# Benchmark Characteristics

The benchmark includes process models with different:

* complexity levels,
* control-flow structures,
* behavioral patterns,
* semantic densities,
* interleaving characteristics,
* and workflow control-flow patterns.

The dataset was designed to support:

* reproducibility,
* benchmarking,
* evaluation of LLM-based process elicitation approaches,
* and comparative analysis of process modeling techniques.

---

# Relation to the Paper

This repository accompanies the paper:

**LLM-based Interviewer for Process Control-Flow Elicitation**

submitted to EDOC/CBI 2026.

The benchmark was used to evaluate the behavior of a structured SBMN-guided LLM interviewer capable of eliciting declarative control-flow knowledge and generating BPMN-compatible process models.

---

# Reproducibility

All experimental artifacts required for inspection and partial reproduction are included:

* process descriptions,
* reference BPMN models,
* expected SBMN specifications,
* interview traces,
* elicited SBMN models,
* generated BPMN solutions,
* and evaluation metrics.

---

# License

This repository is intended for academic and research purposes.

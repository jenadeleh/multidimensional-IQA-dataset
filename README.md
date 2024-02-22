# Example Dataset README

## Description
This dataset contains information about trap correctness from a study conducted. The dataset is provided in a CSV  format.

## Contents
- `MD_IQA_Crowdsourcing_results_all_assignments.csv`: A CSV file containing the dataset in table format (anonymized).

## Dataset Information
The dataset consists of the following columns for each question (triplet):
- `HIT_ID`: Identifier for each Human Intelligence Task (HIT).
- `assignment_ID`: Identifier for each assignment.
- `worker_ID`: Identifier for each worker (from MTurk).%removed to anonymize the dataset
- `worker_index`: Index assigned to each unique worker.
- `question_type`: Type of question.
- `source`: Source image name (ID).
- `left_dist`: Type of the distortion of the left image.
- `left_dist_level`: Level of the distortion of the left image.
- `anchor_dist`: Type of the distortion of the anchor image.
- `anchor_dist_level`: Level of the distortion of the anchor image.
- `right_dist`: Type of the distortion of the right image.
- `right_dist_level`: Level of the distortion of the right image.
- `decision`: participant's decision
- `decision_time`: Time taken form image display until the participant decision.
- `trap_correct`: Number of correct questions per assignment (there are 2 trap questions per assignment).
- `uum_undecided`: Number of undecided question per assignment.


## Usage
The dataset can be used for various purposes such as:
- ...

## Citation
If you use this dataset in your research, please cite it as follows:



## License
This dataset is licensed under the [Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License](https://creativecommons.org/licenses/by-nc-sa/4.0/).
 

# Dataset README

## Description
This dataset contains information about trap correctness from a study conducted. The dataset is provided in a CSV  format.

## Subjective data before filtering

- **File name:** MD_IQA_Crowdsourcing_results_all_assignments.csv
- **Details:** This dataset includes results from 368 HITs, each with 20 questions (triplet comparisons), and one HIT with 8 questions. Each HIT was published with nine unique assignments, resulting in a total of 3,321 assignments.
- **Responses:** A total of 66,312 responses were collected via a crowdsourcing experiment from 264 unique workers. The dataset covers 6,630 study questions and 738 trap questions, with each question receiving 9 responses.

## Data cleansing

- **Cleaned data file names:**
  - MD_IQA_Crowdsourcing_results_rejected_818_assignments.csv
- **Cleansing details:** We excluded 818 assignments due to either the failure of workers to correctly answer a trap question or not answering three or more questions within the 8-second response time. 
- **Remaining data:** After data cleansing, 49,952 responses remain, covering 6,252 study questions and 696 trap questions, totaling 6,948 unique triplets.
- **Note:** We also removed 259 triplets with 'no decision' (workers didn't answer them within 8 seconds response time) before the data analysis. The remaining 49,693 responses to 6,948 unique triplets were used for data analysis.

## CSV file columns 
The CSV file consists of the following columns for each question (triplet):
- `HIT_ID`: Identifier for each Human Intelligence Task (HIT).
- `assignment_ID`: Identifier for each assignment.
- `worker_ID`: Identifier for each worker (from MTurk). [Removed to anonymize the dataset]
- `worker_index`: Unique index assigned to each unique worker_ID.
- `question_type`: Type of question.
- `source`: Source image name (ID).
- `left_dist`: Type of the distortion of the left image.
- `left_dist_level`: Level of the distortion of the left image.
- `anchor_dist`: Type of the distortion of the anchor image.
- `anchor_dist_level`: Level of the distortion of the anchor image.
- `right_dist`: Type of the distortion of the right image.
- `right_dist_level`: Level of the distortion of the right image.
- `decision`: participant's decision ('no decision' is recorded in case the worker didn't response within 8 seconds)
- `decision_time`: Time taken from image display until the participant decision.
- `trap_correct`: Number of correct questions per assignment (there are 2 trap questions per assignment).
- `num_undecided`: Number of undecided question per assignment.

## Usage
- ...

## Citation
If you use this dataset in your research, please cite it as follows:



## License
This dataset is licensed under the [Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License](https://creativecommons.org/licenses/by-nc-sa/4.0/).
 

# Appendix A: Data Dictionary (Codebook)

This file provides the definitions for the variables used in the dataset file: `AI_L2_Writing_Study_Dataset.xlsx`.

| Variable Name | Type | Description |
| :--- | :--- | :--- |
| `Participant_ID` | String | Unique identifier for each L2 writer. |
| `V1_MTLD` | Numeric | MTLD score for the first draft (Baseline). |
| `V2_MTLD` | Numeric | MTLD score for the second draft. |
| `V3_MTLD` | Numeric | MTLD score for the final draft. |
| `Mean_Sentence_Length` | Numeric | Average sentence length across drafts. |
| `LSA_Overlap` | Numeric | Latent Semantic Analysis overlap between AI feedback and writer revision. |
| `Human_Rating` | Numeric | Holistic writing score assigned by blinded raters (Scale 1-10). |

*Note: All linguistic indices were calculated using Python's NLTK and SpaCy libraries.*

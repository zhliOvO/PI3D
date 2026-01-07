# PI3D

This repository contains a **small portion** of our complete dataset. Due to file size constraints, we cannot upload every single image from our study. The included samples are representative of the full dataset and sufficient for understanding our experimental methodology and results.

## Dataset Overview

This dataset contains samples from different object placement strategies across multiple scene types. The data includes:

- **Three Experimental Combinations** :
  - `Comb1`: Gemini-2.0-Flash (crit.) with GPT-4o-mini (eval.)
  - `Comb2`: GPT-4o-mini (crit.) with Gemini-2.0-Flash (eval.)
  - `Comb3`: GPT-5 (crit.) with Gemini-2.5-Flash (eval.)
- **Three Scene Types**: Home (note), Office (whiteboard), and Outdoors (billboard)
- **Three Placement Methods**:
  - `experience_guided`: Our proposed experience-guided approach
  - `iterative_plausibility`: Iterative-plausibility baseline method
  - `single_placement`: Single-placement baseline method

Each combination includes:
- CSV files with results (positions, rotations, physics scores, attack success rates)
- Representative images showing object placements
- Metadata for each experimental condition

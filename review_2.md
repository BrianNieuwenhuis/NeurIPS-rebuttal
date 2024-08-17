**Response to Reviewer Ye65:**

Thank you for your thorough and constructive review of our paper. We greatly appreciate the time and effort you invested in providing feedback. Your comments have helped us identify several areas for improvement, and we have made significant revisions to the manuscript to address your concerns. Below, we provide a detailed response to each of the points you raised.

1.**Title Inconsistency:** Thank you for pointing out the inconsistency in the title. The title discrepancy was an oversight, and the final version of the paper now has a consistent title throughout. The correct title is: "ReefNet: A Large-scale, Taxonomically Enriched Dataset and Benchmark for Coral Reef Classification."

2.**Use of 'Identification':** We understand your concern about the use of the term "identification" in the context of the taxonomic labels. The paper has been revised to use the term "classification" consistently to better reflect the nature of the work.

3.**GitHub Repository Issues:** We acknowledge that the GitHub repository was prematurely linked in the draft. The repository was intended to host code and scripts to assist users in interacting with the dataset, but it was initially under development. The repository is now fully populated with the necessary resources. The links to the dataset on Hugging Face have also been verified and corrected.


4.**Clarification of Terms 'High, Medium, Low':** We agree that these qualitative terms should be better defined. In the revised paper, Table 1 has been reworked using better-defined terminology and, where possible, numeric statistics have been provided, allowing readers to make informed interpretations.

5.**Introduction and Definition of Terms (WoRMS, CoralNet, Red Sea):** We have added detailed explanations of WoRMS (World Register of Marine Species), CoralNet, and the geographic regions mentioned (e.g., the Red Sea) early in the paper. These explanations will be accompanied by citations and references to ensure clarity for readers unfamiliar with these terms.

6.**Data Source Clarification:** The data in our dataset is sourced from CoralNet, which provides point annotations across various coral reef sites. These annotations are then organized following the WoRMS taxonomic framework. We will make this data lineage clearer in the manuscript.

7.**Related Works Section:** Thank you for the suggestion to add a related works section. While we appreciate the value of a dedicated section, due to space constraints, we will integrate the discussion of related datasets directly into the introduction. In this revised introduction, we have included a comparison with the datasets you mentioned, such as BIOSCAN-1M, and BenthicNet (which includes FathomNet, iNaturalist, and SQUIDLE+). This will ensure that the context and relevance of ReefNet within the broader landscape of biological datasets are adequately addressed while maintaining a focused and concise paper structure.

8.**Table 2 Clarifications:** Thank you for your feedback on Table 2. We have revised the table to present taxonomic statistics for both hard and non-hard corals clearly. We will also clarify that taxonomic labels refer to the number of categories under each taxonomic rank and provide information on the percentage of data labeled for each rank.

9.**Presentation of Results:** We agree that the results presented in the paper were limited. The results section has been expanded to include performance metrics for the other state-of-the-art models mentioned (EfficientNet, ConvNext, ResNet, BEiT). A detailed explanation of the classes used in the experiments has been provided, and the results for taxonomic classification and coral conditions have been separated to avoid confusion.

The table below presents the performance metrics (in terms of F1-scores) for various models across different biogeographical regions. These results demonstrate the effectiveness of different state-of-the-art models in classifying coral reef images within the specified regions.


| Model         | Tropical Atlantic | Eastern Indo-Pacific | Central Indo-Pacific | Western Indo-Pacific |
| ------------- |:-----------------:|:--------------------:|:--------------------:|:--------------------:|
| ResNet        | 29.72%            | 38.04%               | 34.65%               | 38.41%               |
| EfficientNet  | 53.76%            | 61.34%               | 58.86%               | 61.68%               |
| BeiT          | 64.14%            | 71.62%               | 71.95%               | 77.69%               |
| ConvNext      | 47.06%            | 54.38%               | 48.70%               | 55.23%               |
| ViT           | 62.31%            | 70.70%               | 68.90%               | 73.30%               |
| ViT + SSL     | 62.53%            | 68.18%               | 66.48%               | 71.25%               |


**Note:** The F1-scores are indicative of the model's ability to generalize across the different regions, highlighting the variability in performance depending on the region and model used.


10.**Generalization Claims:** We appreciate the need for clarity regarding our generalization claims. The detailed performance results that demonstrate robust generalization from non-Red Sea data to unseen Red Sea data, as claimed in the abstract, have been included. This includes specific F1-scores for selected coral genera.

11.**Dataset Description Section:** A dedicated section titled "Dataset" has been added, providing detailed descriptions of all technical terms, data sources, and metadata files. This section guides readers on how to access, interpret, and utilize the dataset effectively.

12.**Metadata File Documentation:** A detailed description of the metadata file has been included in the revised manuscript, outlining its format, contents, and how users can access and interpret the data.

13.**Addressing Correctness and Documentation Issues:** All links on the GitHub page have been corrected, ensuring that it contains relevant and functional resources, including access to the dataset. Additionally, the title inconsistency has been resolved, and the paper's content has been thoroughly reviewed for clarity and correctness.

14.**Presentation Improvements:** We agree that the paper's presentation could be improved. All figures and tables have been clearly labeled and referenced appropriately within the text. The first image has been moved to follow the abstract to maintain a clean and professional layout.

15.**Additional Revisions:** Other minor revisions have been made throughout the manuscript to address the clarity and presentation issues you raised, ensuring that the final submission is clear, accurate, and comprehensive.

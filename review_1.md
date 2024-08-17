**Response to Reviewer JG9Q:**

Thank you for your detailed and constructive feedback on our paper. We greatly appreciate the time and effort you invested in reviewing our work. Your comments have been instrumental in refining the manuscript, and we have made several revisions to address the points you raised. Below is a detailed response to each of your comments.

1.**Permission to Relicense Data:** We have obtained explicit permission from the managers of CoralNet to redistribute the data as part of our dataset. This permission was granted after a thorough discussion, and we have email exchanges documenting this approval. Appropriate credit has been given to the individual data sources used, as requested by CoralNet. A list of sources has been compiled, and the respective organizations/names are credited in the attached supplementary materials, along with links to the original data locations on CoralNet. This ensures compliance with ethical and legal standards while maintaining transparency about data provenance.

2.**Test Partition for the Full Dataset:** We acknowledge the concern regarding the lack of a test partition for the full dataset. The revised manuscript includes a detailed description of the partitioning methodology, ensuring that it meets the standards for creating a consistent and robust benchmark. Experiments were conducted using a geo-location-based partitioning strategy that selects part of the CoralNet sources as the training set while using others as the test set. Both the training and test sets cover data from different oceans worldwide, reducing the risk of overfitting and providing a more practical evaluation.

3.**Spatial Distribution of Samples:** We appreciate the suggestion to include more detailed information on the spatial distribution of samples. A figure showing the geographic distribution of the dataset has been added. The supplementary materials include latitude and longitude labels as well as a classification of the sources into the marine ecoregions of the world. This helps readers understand the scope and coverage of the dataset and facilitates customized data extraction.

4.**Utility for the Machine Learning Community:** While the primary focus of the dataset is on coral reef biodiversity, its utility for machine learning researchers has been explicitly stated. The manuscript has been revised to emphasize the unique properties of the dataset that make it suitable for advancing machine learning techniques, such as the challenges posed by fine-grained classification, the multi-source nature of the data, the hierarchical structure of the labels, and the potential for transfer learning in environmental and biological datasets.

5.**Number of Images in the Dataset:** Thank you for highlighting the omission regarding the total number of images in the dataset. This has been corrected by specifying the total number of images alongside the number of annotations and sources. Additionally, the filtering criteria used to reduce the number of sources from 1,033 to 98 have been clarified, ensuring transparency in the data selection process.

6.**Clarification of F1-Score in the Abstract:** We acknowledge the potential confusion caused by the abstract's claim of achieving an F1-score of over 90% for selected coral genera. The abstract has been revised to provide a more accurate representation of the results, ensuring consistency with the main results presented in the paper.

7.**Additional Experiments and Analysis:** The experimental section of the paper has been strengthened. Additional experiments have been included that compare training from scratch with using existing pretrained networks (e.g., pretrained on ImageNet with SSL). A thorough analysis of the results has been provided, particularly focusing on the lack of performance improvement with SSL pretraining on Hard Coral labels. These additional experiments and analyses have been moved from the supplement to the main body of the paper to ensure they are given the appropriate level of importance.

8.**Clarifications for Figures and Tables:**  

- **Figures 3 and 4:** These figures have been revised to improve readability, using a log-scale y-axis where appropriate and separating bar plots for better interpretation. Individual F1 scores are clearly labeled above the bars.

- **Table 4:** The F1 score shown has been clarified as either the micro or macro average, with an explanation provided in the context of the dataset's intended use case. This clarification helps readers understand the relevance of the evaluation metrics to different applications of the dataset.

9.**Typographical Errors:** Thank you for pointing out the typographical errors. The specific issues you mentioned (e.g., "listed grow forms" to "listed growth forms," STOA to SOTA, incorrect quotation marks) have been corrected, and the entire manuscript has been reviewed for similar errors.

10.**Incomplete and Incorrect References:** The references have been updated to ensure they are complete, correctly formatted, and consistent with citation standards. This includes correcting the casing for terms like SGD, ImageNet, and others, as well as ensuring all references contain the necessary details.

11.**Limitations in the Main Text:** The limitations related to spatial sampling biases, camera depth effects, and the dynamic nature of oceanographic taxonomies have been addressed more prominently in the main text, not just the supplement. This provides a clearer understanding of the potential challenges and considerations when using the dataset.

12.**Correctness and Dataset Partitioning:** The partitioning methodology used for the Red Sea Global data has been elaborated on and extended to the full dataset. This includes a well-structured test partition designed to evaluate model performance on unseen data collected at new sites. A spatial-blocking approach has also been considered to account for the correlation of images taken in close proximity.

13.**Relation to Prior Work:** The related work section has been expanded to include mentions and citations of other platforms like SQUIDLE+ and FathomNet, as well as datasets like BenthicNet. This provides a more comprehensive context for our work and demonstrates how our dataset fits within the broader ecosystem of coral reef imagery datasets.

14.**Metadata Documentation:** The documentation of the dataset's metadata has been improved, specifying details such as the source dataset, original image information, and geographic labels (latitude and longitude). This ensures that users have access to all necessary information to effectively utilize the dataset.

15.**Ethical Considerations and Copyright Issues:** We appreciate the reviewer's concern regarding the licensing and redistribution of the data. Proactive steps have been taken to ensure full compliance with ethical and legal standards. Specifically, we contacted the managers of CoralNet, the original source of the data, and received explicit permission to redistribute the data as part of our dataset. The approval was documented through email exchanges, where the managers of CoralNet confirmed that the data could be published, provided that appropriate credit is given to the individual data sources. An overview of the sources and their contributors is provided in the supplementary materials, including links to the original sources.

This approach ensures that the rights of the original data contributors are respected while allowing the broader research community to benefit from the dataset.

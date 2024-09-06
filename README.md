# Daberta-ELL881

Code repository for the paper titled:

Empowering the Fact-checkers! Automatic Identification of Claim Spans on Twitter. Megha Sundriyal, Atharva Kulkarni, Vaibhav Pulastya, Md Shad Akhtar, Tanmoy Chakraborty

Accepted at the 2022 Conference on Empirical Methods in Natural Language Processing (EMNLP'22), Abu Dhabi, December 7–11, 2022.

Changes Made:
- Mitigated the overfitting problem in the SOTA DABERTA model for CSI by focusing on the fully connected layers
-  Developed a heuristic post-processing algorithm based on EDA-derived claim span properties
-  The modifcations improved the Model’s F1 score from 0.834 to 0.842 and also decreased the training time

Directions to implement the code:

- Create and activate a virtual environment.
- Install all the dependencies from the requirements.txt file: pip install -r requirements.txt
- Add all datasets in the dataset folder (train, test, and validation). The dataset folder already contains the claim descriptions embeddings from RoBERTa.
- Run python daberta.py to run the code: python daberta.py
- The model for each epoch will get saved in the models folder.

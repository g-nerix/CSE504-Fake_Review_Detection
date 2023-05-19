# CSE504-Fake_Review_Detection
This project is a part of the Information Retrieval course at IIIT Delhi and focuses on detecting fake reviews on online platforms. The objective is to identify and remove fake reviews to ensure fair competition and maintain user trust.
To achieve fruitful results, we have utilized LSTM and BERT models, achieving an accuracy of 87% and 90%, respectively.

## Features
 - Machine Learning Approach: Develop a machine learning-based solution to detect fake reviews using a dataset of reviews collected from online platforms.

 - Feature Extraction: Preprocess the reviews to extract relevant features that will be used to train a classifier.

 - Classifier Evaluation: Explore various machine learning algorithms and techniques to achieve optimal performance in detecting fake reviews. Evaluate the classifier using standard metrics such as precision, recall, and F1 score.

 - Python and ML Libraries: Implement the project using Python and utilize machine learning libraries such as Scikit-Learn and TensorFlow.

## Setup and Usage
 1. Move into the data folder using the command cd data.

 2. Run the code using the Streamlit command: streamlit run <File_Name>.py. The UI is built with Streamlit, which connects with the backend Python code and displays the results.

 3. The frontend.py file contains graphs and results obtained from the dataset using SVM, Random Forest, Decision Trees, CNN Model, and ANN Model.

 4. Move the lstm.h5 and bert.h5 files to the data folder, along with frontend.py and changes.py.

### Run the following commands:
    cd data
    streamlit run changes.py
    streamlit run frontend.py
    
## Contributions
We welcome contributions from the community to enhance the fake review detection system. If you have any ideas, bug fixes, or feature enhancements, please feel free to submit a pull request.

## License
This project is licensed under the MIT License. You are free to use, modify, and distribute the code as per the terms of the license.

## Contact
If you have any questions or suggestions regarding the project, please contact us at shashank20119@iiitd.ac.in 

Thank you for your interest in the Fake Review Detection project!


Lung Cancer Detection using Machine Learning
If lung cancer is found at an earlier stage, when it is small and before it has spread, it is more likely to be treated successfully. Lung cancer screening is recommended for certain people who smoke or used to smoke, but who don't have any signs or symptoms. If a person has lung cancer but doesn't have any symptoms, this usually means there's a chance to detect the disease early.

Lung Cancer Detection using Machine Learning and Computer Vision is a project that aims to develop a system that can automatically detect the presence of lung cancer in medical images of the lungs, such as X-rays or CT scans, using advanced algorithms and techniques from the fields of machine learning and computer vision. The system will be trained on a large dataset of annotated medical images and will use various image processing techniques to extract relevant features and patterns from the images.

The output of the system will be a prediction of whether or not lung cancer is present in the image, which can be used to assist medical professionals in making accurate and timely diagnoses. The project involves the use of state-of-the-art machine learning algorithms, such as convolutional neural networks (CNNs), and advanced image processing techniques, such as edge detection, segmentation, and feature extraction.

Check out the live Deployment at - Streamlit Deployment

How to Run this Project
Tech Stacks Used
Python
Streamlit API
Tensorflow , Keras API
Numpy , Pandas , Seaborn
How to run this Project
git clone URL
cd LungCancerDetection
Install modules if not available using following commands
pip install -r requirements.txt
Run the app.py file
streamlit run app.py
Note- Sometimes models as well as csv file might not be detected due to environment related issue it is recommended that you install Anaconda and create a seperate environment by the name 'tf' install required modules. Then run the following commands-
activate conda tf
cd LungCancerDetection
streamlit run app.py

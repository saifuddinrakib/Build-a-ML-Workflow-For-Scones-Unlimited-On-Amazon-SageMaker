Scones Unlimited Image Classification Project On Amazon SageMaker
This project is a part of the assessment in the Udacity's AWS Machine Learning Engineer Nanodegree Program.

Project Overview:
In this project, I've used AWS Sagemaker to build an image classification model that can tell bicycles apart from motorcycles. And I've deployed the model, using AWS Lambda functions to build supporting services, and AWS Step Functions to compose the model and services into an event-driven application.

AWS Sagemaker: Building and deploying the image classification model
AWS Lambda: Creating supporting services
AWS Step Functions: Composing an event-driven application
Python: Scripting and model development
Jupyter Notebooks: Data exploration and model training

Project Steps Overview:
Step 1: Data staging
Step 2: Model training and deployment
Step 3: Lambdas and step function workflow
Step 4: Testing and evaluation
Step 5: Optional challenge
Step 6: Cleanup cloud resources

Prerequisites
AWS Account
Python 3.7+
AWS CLI
Git
Installation

Clone the repository:
git clone https://github.com/yourusername/scones-unlimited-image-classification.git
cd scones-unlimited-image-classification
Install dependencies:
pip install -r requirements.txt
Configure AWS CLI:
aws configure

Project Structure
data/: Contains training and testing datasets
notebooks/: Jupyter notebooks for data exploration and model training
src/: Lambda functions and Step Function workflow definitions
models/: Trained model files
README.md: Project documentation
requirements.txt: Project dependencies

Results
The image classification model successfully distinguishes between bicycles and motorcycles, aiding Scones Unlimited in optimizing delivery operations by routing drivers based on their vehicle type.

Contributing
Contributions are welcome! Please open an issue or submit a pull request for any changes or improvements.

License
This project is licensed under the MIT License - see the LICENSE file for details.

Acknowledgements
The team at Scones Unlimited
AWS for providing the cloud infrastructure
The open-source community for various tools and libraries

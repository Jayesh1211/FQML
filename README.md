**QF Hackathon 2024**
# :space_invader: Quantum Federated machine learning - Team Feynman Prodigies 

  - [Project Description](#Projectdescription)
- [ Setup Instructions](#SetupInstructions)
-  [Team Introduction](#team-introduction)
- [Acknowledgement](#Acknowledgement)


Updated on 18 July 2024-   We have updated the repository for more clarity and explanation on the steps with the given PDF [PDF](https://github.com/Jayesh1211/FQML/blob/main/Explanation.pdf) Here 





## Project Description 
 Quantum Machine Learning for Brain Tumor Classification
Problem Statement
Brain tumor classification is a critical problem in medical diagnosis, where timely and accurate identification of tumor types can significantly impact patient treatment outcomes. Traditional machine learning algorithms have been used to tackle this problem, but quantum machine learning (QML) offers the potential for improved accuracy and efficiency due to the unique computational capabilities of quantum systems.

Objectives
- Accurate Classification: Develop a quantum machine learning model to classify different types of brain tumors from MRI images.
- Efficient Data Processing: Implement efficient data processing techniques to handle and preprocess medical imaging data.
- Federated Learning: Utilize federated learning (FL) techniques to train the model across multiple clients while preserving data privacy.
- Quantum Model Training: Leverage quantum algorithms, specifically Variational Quantum Classifiers (VQC), for training and inference.


## Setup Instructions

#### 1. **Clone the Repository**

   Open your terminal or command prompt and run the following command to clone the repository:

   ```bash
   git clone https://github.com/Jayesh1211/FQML.git
```
Navigate into the project directory:
```bash
cd FQML
```
#### 2. **Create a Python Virtual Environment**
Create a virtual environment to manage dependencies:

```bash
python -m venv venv
```
#### 3. **Activate the Virtual Environment**
On Windows:
```bash
venv\Scripts\activate
```
On macOS and Linux:
```bash
source venv/bin/activate
```
#### 4. **Install Dependencies**
Install the required dependencies listed in the ['requirements.txt'](requirements.txt) file:

#### 5. **Download the Dataset**
Download the Brain Tumor dataset (data.zip) from (https://figshare.com/articles/dataset/brain_tumor_dataset/1512427/5)
Or 
Directly use a processed data file from the directory.
## Usage of the Project
- `MRI.ipynb` - Contains notebook for Training MRI Dataset.
-  `PULSAR_FQML.ipynb` - Contains notebook for training pulsar dataset.
 - `processed_data.npz` - contains processed MRI Data
 - `pulsar.csv` - Contains Pulsar data
 - `Zaiku_Hackathon (1)`- The slide PDF Explaining the work


## Team Introduction
**Team Name:** Feynman Prodigies 

|   **Member Names**| **Abdullah Kazi**                      | **Jayesh Hire** |
|----------------|-----------------------------------|----------------------------|
| **GitHub ID**  | AbdullahKazi500                   | Jayesh1211      |  
|Role            | Idea formulation and preparing documentation                 | Code and development |

----------------------

## Acknowledgement
We would like to extend our heartfelt gratitude to Zaiku and Quantum Formalism for organizing and hosting the Zaiku QF Hackathon 2024. This event provided a remarkable platform for innovation, collaboration, and the exchange of ideas in the quantum computing community.

Thank you for the opportunity to participate in this event, which has not only enriched our knowledge and skills but also connected us with a network of like-minded professionals and enthusiasts.

# EEG-Motor-Imagery-Classification-System

## Table of Contents
- [Introduction](##introduction)
- [Setup Instructions](#setup-instructions)
  - [Prerequisites](#prerequisites)
- [Usage Guide](#usage-guide)
  - [Data Input](#data-input)
- [Additional Information](#additional-information)
  - [Model Details](#model-details)
  - [Dataset](#dataset)


## Introduction

Motor imagery based Brain Computer Interfaces (BCIs) allow users to control systems using only their thoughts by imagining specific movements. This project focuses on building a machine learning model that can classify a user’s imagined movements—such as left hand, right hand, feet, or tongue based on EEG (electroencephalography) signals.

Accurate classification of motor imagery is a critical step toward developing real-time BCIs used in neurorehabilitation, prosthetic control, assistive technologies, and neural research.

### About Motor Imagery

Motor imagery is the mental simulation of movement without performing any physical action. When a person imagines moving a limb, the brain produces distinct electrical patterns similar to actual movement. These signals can be recorded using EEG sensors placed on the scalp.

![banner](https://www.googleapis.com/download/storage/v1/b/kaggle-user-content/o/inbox%2F11352499%2Ff95e168febc6d07008b8d4adf1991131%2FScreenshot%202023-09-17%20155842.png?generation=1694946583070778&alt=media)

### Purpose of the Project

The purpose of this project is to develop a machine learning model capable of classifying four motor imagery tasks using multichannel EEG signals. By training on labeled and modified data from the BCI Competition IV_2a

### Potential Impact

This EEG Motor Imagery Classification System has strong potential to support motor recovery in stroke and spinal-injury patients. In neurorehabilitation, patients often struggle to move affected limbs, but the brain may still generate motor-related activity when they imagine the movement. Our model can detect these motor-imagery signals and translate them into actionable feedback

## Setup Instructions

(Ignore if you do not want to run the project locally)

### Prerequisites

Make sure you have the following installed:

- Python (>= 3.8)

- pip (Python package installer)

### Installation

Clone the repository:
  ```bash
    git clone https://github.com/aeonioo/EEG-Motor-Imagery-Classification-System.git
    cd EEG-Motor-Imagery-Classification-System
  ```

Create a virtual environment:

   ```bash
   python3 -m venv venv
   source venv/bin/activate
   ```


Install dependencies:

  ```bash
   pip install -r requirements.txt
   ```

## Usage Guide
### Data Input

1. Go to the [web application](link) and navigate to the Motor Imagery Prediction section.
2. Load the EEG dataset or upload your own preprocessed EEG samples.
3. The system will process the multichannel EEG signals and generate predictions for the imagined movement class (Left Hand, Right Hand, Foot, or Tongue)

## Additional Information

### Model Details

- **Algorithm:** (model) (Accuracy≈xyz)
- **Purpose:** To classify EEG signals into four motor imagery tasks (Left Hand, Right Hand, Foot, Tongue)
- **Input Features:** Multichannel EEG signals from 22 scalp electrodes

### Dataset

This project uses a subset of the [BCI Competition IV-2a EEG Motor Imagery dataset (Kaggle mirror)](https://www.kaggle.com/datasets/aymanmostafa11/eeg-motor-imagery-bciciv-2a). The dataset includes EEG recordings from 9 subjects performing motor imagery tasks such as left hand, right hand, feet, and tongue. The data is structured in terms of individual trials, with each trial containing time-stamped EEG signals from 22 scalp electrodes, organized under columns like EEG-Fz, EEG-C3, EEG-Cz, EEG-C4, EEG-Pz, and intermediary channels labeled numerically (EEG-0 through EEG-16). Each record also contains metadata including patient, time, label, and epoch. This structured format provides a clean, well-annotated foundation for training and evaluating multi-class motor imagery classification models.

### Deployment
The final EEG Motor Imagery Classification System is deployed on:
- Streamlit Share : [Visit Site](link)

### Author

Shaunak Pathak
Feel free to reach out for questions or collaboration:
shaupathak41@gmail.com


# Projects

## 1. Fake News Detection

**GitHub:** https://github.com/nishitpatel01/Fake_News_Detection

**Number of Stars:**  **638**  
**Number of Contributors:**  **5**

## **Project Description**

This project uses Natural Language Processing (NLP) and machine learning techniques in Python to classify news articles as fake or genuine. It leverages the scikit-learn library for text preprocessing, feature extraction, model training, and performance evaluation.

### Dataset
**LIAR: A Benchmark Dataset for Fake News Detection**

The original dataset contains 13 features across the training, validation, and test sets. For simplicity, this project uses the following two features:
- **Statement:** News headline or article text
- **Label:** True / False

### Python Libraries
- NumPy
- SciPy
- scikit-learn

### Main Files
- **DataPrep.py:** Cleans and preprocesses the dataset by tokenizing, stemming, and preparing the training and testing data.
- **FeatureSelection.py:** Extracts text features using feature extraction techniques.
- **classifier.py:** Trains, evaluates, and selects the best-performing machine learning classifier.
- **prediction.py:** Loads the trained model and predicts whether a news article is fake or real along with its confidence score.

### Improvements I can add to the project :
1. Use more variables to improve project's accuracy
2. We can provide prediction probability e.g 90% fake 10% real
3. We can use SHAP to traceback to words which helped our prediction
   


## 2. Vulnerability Scanner using Nuclei

**GitHub:** https://github.com/projectdiscovery/nuclei

**Number of Stars:** **29.9k**  
**Number of Contributors:**  **246**

## **Project Description**

Nuclei is an open-source vulnerability scanner that rapidly detects security issues in **web applications, networks, cloud environments, and APIs**. Instead of relying on a fixed set of checks, it uses customizable **YAML templates** that define how vulnerabilities are identified. This allows security researchers and developers to efficiently scan systems for **known vulnerabilities, misconfigurations, exposed secrets, weak credentials, and other security risks**.

## Dataset Used

There is no specific dataset used in this project. Instead, Nuclei relies on:

- **Publicly disclosed software vulnerabilities (CVEs)**
- **Community-maintained YAML vulnerability templates**
- **User-provided targets** such as websites, APIs, IP addresses, domains, and networks

## **Technologies Used**

- **Go (Golang)**
- **YAML**
- **HTTP/HTTPS Protocols**
- **REST APIs**

## **Main Components**

- **Scanning Engine:** Executes vulnerability scans against target systems.
- **Template Engine:** Processes YAML templates that define vulnerability detection logic.
- **Target Manager:** Manages and scans single or multiple targets.
- **Reporting Module:** Generates detailed vulnerability reports with severity levels and scan results.
- **Cloud Dashboard Integration:** Uploads and visualizes scan results on the ProjectDiscovery platform.






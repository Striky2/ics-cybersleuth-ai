# ics-cybersleuth-ai

A machine learning project focused on detecting cyber incidents within critical industrial systems using data from various real-world and simulated datasets. This repository includes exploratory data analysis (EDA), feature engineering, and model training to distinguish between normal operations and potential cyber threats in industrial control systems (ICS). The datasets used in this project include contributions from iTrust, Centre for Research in Cyber Security, Singapore University of Technology and Design (SUTD), specifically the BATtle of Attack Detection Algorithms (BATADAL) dataset. This dataset was part of a competition aimed at benchmarking algorithms for detecting cyber attacks on water distribution systems. For further details on the datasets, visit iTrust Labs Datasets (https://itrust.sutd.edu.sg/itrust-labs_datasets/).

---

## Repository Structure

### Files and their Purpose

- ** Report_4Pages.pdf**: A concise 4-page version of the report summarizing the project's objectives, methodology, results, and conclusions.
- **Notebooks**:
    - **batadal-v1.ipynb**: "School project" version of the notebook, focused on basic EDA and understanding the BATADAL dataset.
    - **batadal-v2.ipynb**: "Personal work", Improved version with feature engineering and anomaly detection algorithms.
    - **batadal-v3.ipynb**: "Personal work", New approach including all experiments and optimized models, focusing on unsupervised learning methods like Isolation Forest.

---

## How to Use This Repository

1. **Install dependencies**:
   Ensure you have Python 3.10+ installed. Then, install the required packages:
   ```bash
   pip install -r requirements.txt
   ```

2. **Run the notebooks**:
   Open and execute the `main-v3.ipynb` notebook to reproduce the final results. Previous versions (`main-v1.ipynb` and `main-v2.ipynb`) can be used to track project evolution and exploratory steps.

3. **Explore the datasets**:
   The `data/` folder contains the operational and attack datasets used in this project. Details on their structure and simplifications applied are available in the `Report_4Pages.pdf`.

---

## Methodology

This project employs a combination of supervised and unsupervised learning techniques, with a strong focus on:
1. **Exploratory Data Analysis (EDA)** to understand the BATADAL dataset and its challenges.
2. **Feature Engineering** to enhance model performance, including time-series transformations.
3. **Classification Models** such as Random Forests, and **Unsupervised Anomaly Detection** using Isolation Forest to identify cyber-physical anomalies.

---

**Reference**  
Riccardo Taormina and Stefano Galelli and Nils Ole Tippenhauer and Elad Salomons and Avi Ostfeld and Demetrios G. Eliades and Mohsen Aghashahi and Raanju Sundararajan and Mohsen Pourahmadi and M. Katherine Banks and B. M. Brentan and Enrique Campbell and G. Lima and D. Manzi and D. Ayala-Cabrera and M. Herrera and I. Montalvo and J. Izquierdo and E. Luvizotto and Sarin E. Chandy and Amin Rasekh and Zachary A. Barker and Bruce Campbell and M. Ehsan Shafiee and Marcio Giacomoni and Nikolaos Gatsis and Ahmad Taha and Ahmed A. Abokifa and Kelsey Haddad and Cynthia S. Lo and Pratim Biswas and M. Fayzul K. Pasha and Bijay Kc and Saravanakumar Lakshmanan Somasundaram and Mashor Housh and Ziv Ohar; “The Battle Of The Attack Detection Algorithms: Disclosing Cyber Attacks On Water Distribution Networks.” Journal of Water Resources Planning and Management, 144 (8), August 2018. (doi link, bib)

---

## Acknowledgments

Special thanks to the BATADAL competition organizers for providing an excellent benchmark dataset for research in ICS cybersecurity.

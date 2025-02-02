# ML Team B - Predicting Laid-Up Time of Vehicles 

## Project Overview
This project aims to predict the **laid-up time (LAID_UP_TIME)** of vehicles at dealerships using machine learning techniques. 
By leveraging historical sales data, we develop predictive models to estimate how long a vehicle will remain in inventory before being sold.

### Workflow:
✔ **Data Preprocessing** – Cleaning and transforming raw data for training.  
✔ **Model Training & Evaluation** – Testing multiple regression models.  
✔ **Feature Importance Analysis** – Identifying key factors influencing laid-up time.  
✔ **Vehicle Prioritization** – Recommending optimal vehicle types for dealerships.  

## Model Availability 
⚠ **Important:** Due to GitHub's file size limits, trained models are **not stored in this repository**.  

### **How to Use the Models?**
 **Option 1: Download Pretrained Models**  
   - The models are available on **[Google Drive (https://drive.google.com/drive/folders/16Kdsq_w1Mo4xPmSNiN0BEusoVnh080Fj)]()**.  
   - Download and place them in the `/models` directory.  

 **Option 2: Retrain the Models**  
   - If you cannot access the pretrained models, run the following script to train them:  
     ```bash
     python code/model_eval.ipynb
     ```
   - This will generate new models and save them in `/models`.  

## Getting Started 🚀

### Clone the Repository
```bash
git clone https://github.com/JONICK277/ML.git
cd ML

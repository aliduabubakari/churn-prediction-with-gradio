# 📁 Churn Prediction Model and Deployment with Gradio

![Alt text](images/banner.png)

This repository includes code and resources for:

- Building a churn prediction model using machine learning techniques 🤖📊

- Code for building and training the churn prediction model 📝🔬

- Preprocessed dataset for model training and evaluation 📊🔢

- Instructions for setting up the development environment and dependencies 🛠️📦

- Deploying the model with Gradio for a user-friendly interface 🚀🌐

- Allowing users to input customer data and receive churn predictions 📈💡




## Summary
| Code      | Name        | Published Article |  Deployed App |
|-----------|-------------|:-------------:|------:|
| LP4 | Churn Prediction with Gradio |  [Churn Prediction article](https://medium.com/@alidu143/building-a-customer-churn-prediction-web-app-with-gradio-a-step-by-step-guide-5d7d77ede323) | [Churn Preiction App](https://huggingface.co/spaces/Abubakari/churn_prediction_App) |



## Project Description


### 🔧 Tools and Technologies Used:

- Machine learning techniques for model development 🧠💻

- Gradio for creating the web interface 🌐🖥️


## Setup

## Installation

### Manual Setup

For manual installation, you need to have `Python 3` on your system. Then you can clone this repo and be at the repo's root `https://github.com/aliduabubakari/churn-prediction-with-gradio.git` to follow the steps as outlined below; 

## Setting up the Environment

To run the evaluation locally, follow these steps:

1. Create a Python virtual environment to isolate the project's required libraries and avoid conflicts. Execute the following command in your terminal:

    ```bash
    python -m venv venv
    ```
   
2. Activate the Python virtual environment to use the isolated Python kernel and libraries. Run the appropriate command based on your operating system:

    - For Windows:

    ```bash
    venv\Scripts\activate
    ```
    - For Linux and MacOS:

    ```bash
    source venv/bin/activate
    ```

3. Upgrade Pip, the package manager, to ensure you have the latest version. Use the following command:

    ```bash
    python -m pip install --upgrade pip
    ```

4. Install the required libraries listed in the `requirements.txt` file. Run the command:

    ```bash
    python -m pip install -r requirements.txt
    ```

*Note: If you encounter any issues on MacOS, please make sure Xcode is installed.*

By following these steps, you will set up the necessary environment and install all the required packages to run the evaluation on your local machine.

## Running the Execution 

To run the demo app (being at the repository root), use the following command:

```bash
streamlit run churnProject3.py
```

## Deployed App on Huggingface: 

Alternatively, you can visit: click here ⬇️

[![Gradio app](images/Gradio.jpg)](https://huggingface.co/spaces/Abubakari/churn_prediction_App)

By clicking on the image, you will be redirected to the Churn Prediction App.


## App Execution



![Alt text](images/1.png)

First step select the gender and the select whether he/she is a senior Citizen. The key is prpvided that indicates 0 is for NO and 1 is for a YES. Also choose if the customer has a partner. 



![Alt text](images/3.png)

Select if the customer has any dependents. 


![Alt text](images/4.png)


Next, input the length of the tenure in months, slect if the customer has the following; Phoneservice, multiple lines, Internetservice, Onlinesecurity and onlinebackup.



![Alt text](images/5.png)

Next, choose if the customer has the following; Deviceprotection, Techsupport, StreamingTV and streamingMovies. 

 

![Alt text](images/6.png)

Select if the cutomer prefers paperlessbilling. Also select the Paymentmethod, and enter the Monthly charges together with the Total charges. 


![Alt text](images/7.png)

Lastly submit the values and click on the predict button to the prediction.

![Alt text](images/8.png)


🌟 Key Features and Benefits:

1. Accurate churn prediction to identify customers at risk of leaving 🎯🔍

2. User-friendly interface for easy input and prediction retrieval 🌐💡

3. Potential for data-driven decision-making and customer retention strategies 💼📉

✨ Conclusion:

The churn prediction model and deployment with Gradio offer a powerful solution for predicting customer churn and improving customer retention efforts. By leveraging machine learning techniques and a user-friendly interface, businesses can make data-driven decisions to identify at-risk customers and implement effective retention strategies. Explore the repository and start building your own churn prediction application! 🚀💪



## Author

Alidu Abubakari

Data Analyst

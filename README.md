# StudentPerformancePredictionML
This end-to-end Data Science project aims to predict the test scores of students based on the number of hours they studied. The project takes into consideration other variables such as `Gender`, `Ethnicity`, `Parental level of education`, `Lunch`, and `Test preparation course` that may affect a student's performance. The project includes all the necessary steps involved in a typical Data Science project, such as **data cleaning**, **exploratory data analysis**, **feature engineering**, **model building**, and **evaluation**.

## Installation
To run this project, you will need to have Python 3 installed on your machine. You can install the required packages by running the following command:

```bash
pip install -r requirements.txt
```

## SETUP

1. Go to ***VS CODE*** and open project folder.

2. Create New environment

    ```
    conda create -p venv python==3.7 -y
    ``` 

3. Activate Environment
    ```
    conda activate venv/
    ```

4. Install Required libraries from [Requirements.txt](/requirements.txt)
    ```
    pip install -r requirements.txt
    ```

5. Cofigure username in git cli
    ```
    git config --global user.name "Ninad Karlekar"
    ```

6. Cofigure email in git cli
    ```
    git config --global user.email "< Write your github account email here >"
    ```

7. Commit and push

    <details>
    <summary>Steps</summary>
    <br>

    1. Add File
        1. Add a **single** file

            ``` 
            git add requirements.txt
            ```

        2. Add **all** files

            ```
            git add .
            ```

    2. To see **status**
        ```
        git status
        ```

    3. To **commit** with message
        ```
        git commit -m "Write message here"
        ```

    4. To **push** changes
        ```
        git push origin main
        ```

    </details>
    <br>
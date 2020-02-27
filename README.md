# MVP tracker

Predicting the MVP of Polish Basketball League (PLK) using machine learning and data science methods

## Methodology

Data is scraped from plk.pl/archiwum and plk.pl websites with requests and BeautifulSoup. Then the data is cleaned and prepared. I decided to use Logistic Regression, as it gave the most probable and viable results. Moreover it allowed me to see the percentages of the chances of each player belonging to the mvp group.

### Requirements

pandas  
numpy  
matplotlib  
sklearn  
jupyter  
BeautifulSoup
requests

### Running the app

    # Change into project directory
    cd PLK_MVP_predictor

    # Make virtual enviornment
    python3 -m venv <env_name>

    # Activate virtual env
    source golem_env/bin/activate

    # Install requirements
    pip install -r requirements.txt

    # open jupyter notebook and open the MVP_PLK_predictor notebook
    jupyter notebook

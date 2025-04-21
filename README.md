
# Scout API Test #

Streamlit application for testing Scout API model performance across multiple configurations and scenarios.

### What is this repository for? ###

* Visual testing tool for ShotTracker Scout APIs  
* Allows manual testing of extrac analyze, dispatch and aliases APIs  
* Compares results across models and temperature settings  

* Quick summary
* Version
* [Learn Markdown](https://bitbucket.org/tutorials/markdowndemo)

### How do I get set up? ###

* Clone the repository to your local machine
* Install dependencies listed in `requirements.txt`
* Run the application using Streamlit:
  ```bash
  streamlit run main.py

### Contribution guidelines ###

* Writing tests
* Code review
* Other guidelines


### API Accuracy ###

| API Name       | Accuracy     | Description                                                                 |
|----------------|--------------|-----------------------------------------------------------------------------|
| Analyze API    | 92.4%        | Accuracy of analysis and breakdown responses from annotated queries.        |
| Extract API    | 90.1%        | Measures correct extraction of structured data from user questions.         |
| Aliases API    | 95.6%        | Accuracy of alias detection and replacement in queries.                     |
| Dispatch API   | 88.3%        | Correctness of category routing based on user query intent.                 |

**View full annotation and API status tracking sheet here:**  
[API Annotation & Progress Sheet (Google Sheets)](https://docs.google.com/spreadsheets/d/1jCVYNRsSnEeIhIHQ7Nx6vBhfxAVlzIX9zG-754C67cM/edit?usp=sharing)

### Who do I talk to? ###

* Repo owner or admin
* Other community or team contact

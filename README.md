# Functional Dependency Analyzer
Functional Dependency Analyzer is a python project that helps in finding the canonical cover of a set of functional dependencies (FDs) and identifies extraneous attributes in the given set of FDs. 
It provides a user-friendly GUI through Streamlit library.

### Installation
To run the project, you need to install the required libraries mentioned in the requirements.txt file. You can do this by running the following command in your terminal:

Copy code:   pip install -r requirements.txt

### HOW TO RUN
To use the Functional Dependency Analyzer, you can simply run the app.py file and it will open the Streamlit app in your browser.

Copy code:   streamlit run CANONICAL_COVER_20BCE032_046_073.py

The app has a simple and intuitive interface that allows you to input your set of FDs and find the canonical cover and identify extraneous attributes.

## Functions
The project contains separate functions for each step involved in finding the canonical cover of the given set of FDs. These functions are:

* Decomposition
* Closure
* RemoveExtraFD
* RemoveExtraAttribute
* Composition

![image](https://github.com/RAJDEEPBODAR7/Canonical-Cover/assets/119515262/6eb12d8b-0fbe-4764-a510-426ef56ba804)

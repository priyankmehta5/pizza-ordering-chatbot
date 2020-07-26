# Pizza Ordering Chatbot
Pizza Ordering Chatbot developed using RASA.

After successful testing of this chatbot in the shell & RASA X UI environment,\
I also implemented it into a basic HTML website to display its functionality in practicality.


## Prerequisites
- RASA X
- spaCy
- Python v3.6 (preferably, as RASA tends to give errors with newer versions)

## Steps
Clone the repo.

1. Install PyCharm IDE.
2. Create Virtual Environment.
3. Install all the requirements given in **requirements.txt** and activate the environment.
4. Initialize RASA and train the model.
```
rasa init --no-prompt
```
5. Next, load the chatbot using the below command:
```
rasa run -m models --enable-api --cors "*" --debug
```
6. Launch the index.html file in the **Website** folder.

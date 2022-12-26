# Question-Answering-Models-QA-.

## There are 2 different categories of QA Modeling

* Domain - systems that are constrained by the input data; we have open and closed systems
    - Open domain systems are for broad questions, not specific to what category of discussion (Wikipedia, World wide web, Alexa, etc...)
    - Closed domain systems are more narrow in its vocabulary and focus on a specific industry or topic (Football, Finance, Tech, Law etc..)
* Question Type - Open ended questions, Yes/No questions, inference questions etc...)
    - Once you determine what type of system you want to establish, you then need to figure out which question type you want your model to focus on


## Types of Question Answering Models
   - Extractive Question Answering is a deep learning model that can provide an answer when given a corpus of text (i.e context). So, when you provide a question to the       model, the model then "searches" the documents to pinpoint the best answer to the question. It's essentially a searching tool in many ways...
   - Open Generative Question Answering is a deep learning model that generates text based on context. So, unlike the extractive question answering model, the answer          does not literally have to be in the text.
   - Closed Generative Question Answering is a deep learning model where no context is provided and the answer is generated by the model.

** We Make a Extractive question system **

# Dataset
It is some articles from BBC which talking about different topics. 
- We try to answer 4 questions which are ==> 'Where it happened?', 'who is the subject and object of this article?', 'what happened exactly?', 'when it happened?'

# Model
- We use ROBERT

# MedReceipt
Your goto AI computer for diagnosis! It is accurate, reliable, and fast!
Try it out here: https://medreceipt.arnavpandey722.repl.co/

# Inspiration
Our inspiration for the project was based on the challenge that is involved with going to the doctor just for them to tell you that you have the Common Cold and there was nothing they could do to help you, or if you are going online to check your symptoms and you get nonsensical results compared to what you actually have (you put in symptoms for common cold and you get brain cancer). With MedReceipt you can simply put in your symptoms and receive a accurate and fast diagnosis and suggested actions without even leaving your house, saving valuable time and money!

# What it does
MedReceipt analyses the symptoms reported by the user and presents the most likely illness based on those symptoms using a custom-built, advanced AI. MedReceipt allows the user to receive a text showing basic information about their illness, as well as a more advanced invoice, which gives the user information such as the time of diagnosis and suggested actions.

# How we built it
MedReceipt was built using Python's Flask Framework as the server, and HTML5 (with Jinja2), JavaScript, and CSS. MedReceipt uses the python-docx and aspose-words module to generate the Invoice, the twilio module to text the user, and the boto3 module to interact with the AI model. datetime, os, and pandas were used for miscellaneous security and data management tasks. MedReceipt's custom AI Model was built on AWS SageMaker Studio and was trained with over 5,000 rows of modified open-source data to ensure accuracy and responsiveness. MedReceipt uses HTML5, CSS3, and JavaScript in the frontend along with Jinja2 interacting with Flask to ensure a smooth, fast, and good-looking frontend.

# Challenges we ran into
We ran into a multitude of challenges, especially in the backend. Get a SageMaker AI endpoint to successfully interact with the boto3 module. [FIXED] Get the python-docx module to reliably display information without changing font or font size. [FIXED] Get the Twilio API to show information preview with the correct format [FIXED] Fix latency from 1 second to ~0.1 seconds [FIXED].

# Accomplishments that we're proud of
The custom AI Model was a real achievement for us, it's the first time either of us has used AI for any project outside of a basic "hello world" type project. The invoice, it was the first time that either of us had done any sort of modifying non-plain text or image files.

# What we learned
We learned how to use more advanced AI models with a higher amount of data. We learned how to use Jinja2 in a more advanced fashion using for loops and conditionals.

# What's next for MedReceipt
In the future, we plan to expand MedReceipt into being able to determine more illnesses and improve the AI model to make MedReceipt more accurate and fast. We also plan to switch to a local model instead of calling AWS.

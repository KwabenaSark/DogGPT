# DogGPT
 A parady of chatGPT made for Dogs
 
I've encountered some difficulties while attempting to host this project, and I've decided to stop trying for now. However, I can guide you through the steps to run it on your own computer. If anyone has experience hosting Flask apps or Python APIs, I would appreciate their assistance. Until I find a solution for hosting, the instructions below will help you get the project up and running locally:
To get started with the DogGPT project, follow these steps:

Clone the repository and create a virtual environment:

Copy code
$ git clone https://github.com/KwabenaSark/DogGPT.git
$ cd DogGPT
$ python3 -m venv venv
$ . venv/bin/activate
Install the required dependencies:

Copy code
$ (venv) pip install Flask torch torchvision nltk
Install the nltk package:
python
Copy code
$ (venv) python
>>> import nltk
>>> nltk.download('punkt')
Train the model:

Copy code
quit()
$ (venv) python train.py
This will generate the data.pth file.

Test the model in the console:
ruby
Copy code
$ (venv) python chat.py
This will allow you to interact with the model in the terminal.

To use the frontend, follow these additional steps:

Open the frontend files path.

Run the Flask application:

ruby
Copy code
$ (venv) python app.py
Launch the index.html file in your web browser.
By following these steps, you will have the DogGPT project set up and running. You can chat with the model in the console and also interact with it through the provided frontend by opening the index.html file.

# BERT-QnA-English

## Instructions to set up the Bert QNA English Demo on Local system

1. Clone the repository in your system.
2. Download the model files from  and unzip it in /bert directory.
3. Install and create a virtual environment by the following step. You'll need python <= 3.6 to set it up.
```shell
sudo apt install virtualenv
virtualenv venv --python=python3.6
source venv/bin/activate
```
4. Install the dependencies from requirement.txt file (it will install all the required packages)
```shell
pip install -r requirement.txt
```
5. Run the flask app by the following command (by default the app is running on port 5000)
```shell
python main_app.py 
```
6. You can access the Bert QNA at http://127.0.0.1:5000/ 

7. We have also included API to enable access of the QnA from third-party application. You can make call to http://127.0.0.1:5000/submitted_api with paragraph and questions from HTML form.

If you have any other questions or face issues in setting the demo up then kindly reach out to us at letstalk@pragnakalp.com 
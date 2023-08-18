echo "# llama2-faiss-chatbot" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/jjasmin123/llama2-faiss-chatbot.git
git push -u origin main

conda activate C:\Users\jjasm\OneDrive\Chatbot-QA-FAISS-LLAMA2\env_Llama2Faiss

### How to use google colab in VS codes. Use below link for reference.
https://www.freecodecamp.org/news/how-to-use-google-colab-with-vs-code/ OR
##########################################

follow below instructions.

Create a Colab Notebook: Start by creating a new Colab notebook and give it a name.

Install colabcode Package: In a code cell within the Colab notebook, run the following command to install the colabcode package:

python
Copy code
!pip install colabcode
Import ColabCode: In another code cell, import the ColabCode class:

python
Copy code
from colabcode import ColabCode
Start the Code Server: Create an instance of ColabCode and start the code server on a specified port:

python
Copy code
ColabCode(port=10000)
Replace 10000 with the desired port number.

Copy the URL: Once you start the code server, it will display a URL in the output. Copy this URL.

Configure Visual Studio Code: Open Visual Studio Code and ensure you have the Jupyter extension installed. Use the "Specify Jupyter server for connections" option and paste the URL you copied earlier. This connects your Visual Studio Code to the Colab notebook running on Google Colab.
#########################################################




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_#345tttttdssggsssdsfsdfdfd

use below link for opening
  Local URL: http://localhost:8501
  Network URL: http://192.168.1.4:8501


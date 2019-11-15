# Run on Google Colab
1. Open https://colab.research.google.com/ and login with your Google account
2. Go to the GitHub tab and enter <em>https://github.com/jhagelback/ml-workshop</em>
3. Click <em>Authorize</em> and login to your GitHub account
4. If not already selected, select the <em>ml-workshop</em> repository in the dropdown list
5. Start by opening the <em>Iris Sklearn</em> notebook
6. Click <em>Copy to drive</em> to make a local copy
7. Now you are ready to start hacking!

# Run using Docker
1. Clone the GitHub repository to your computer
2. Run the Jupyter TensorFlow notebook and attach the notebooks directory by running the following command in a terminal:
<code>
docker run -p 8888:8888 -v ~/[change to your local path here]/ml-workshop:/home/jovyan jupyter/tensorflow-notebook  
</code>
3. Copy the URL you see in the terminal (<em>http://127.0.0.1:8888/?token=...</em>) and paste it in a web browser
4. Now you are ready to start hacking!

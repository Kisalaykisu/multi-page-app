# multi-page-app(Streamlit)

# Reproducing this web app
To recreate this web app on your own computer, do the following.

# Create conda environment
   Firstly, we will create a conda environment called multipage

    conda create -n multipage python=3.7.9

   Secondly, we will login to the multipage environement

    conda activate multipage

Install prerequisite libraries

Download requirements.txt file

wget https://github.com/Kisalaykisu/multi-page-app/blob/main/requirements.txt

Pip install libraries

     pip install -r requirements.txt

Download and unzip contents from GitHub repo

Download and unzip contents from https://github.com/Kisalaykisu/multi-page-app

Launch the app

    streamlit run app.py

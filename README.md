
![download1](https://github.com/Parikshitnh72/Phonepe_/assets/153513327/900c5ba7-4dea-4689-bd8e-34d2bc99bbfe)

# Phonepe_Pulse Data Visualisation 
To deploy this project run
  import streamlit as st
  from PIL import Image
  import os
  import json
  from streamlit_option_menu import option_menu
  import subprocess
  import plotly.express as px
  import pandas as pd
  import sqlite3
  import requests

  # Cloning phonepe pulse Repository
    response = requests.get('https://api.github.com/repos/PhonePe/pulse')
  repo = response.json()
  clone_url = repo['clone_url']

  repo_name = "pulse"
  clone_dir = os.path.join(os.getcwd(), repo_name)

  # Pandas - DataFrames
  After Cloning Git-hub create a corresponding DataFrame of given pulse data's and insert it into SQL database and create diffrent tables for diffrent aggregated data's
  ![image](https://github.com/Parikshitnh72/Phonepe_/assets/153513327/0d412d68-5476-465f-a73a-842399fe70e6)

  #  Streamlit - webpage
  HOME
  ![image](https://github.com/Parikshitnh72/Phonepe_/assets/153513327/5a7c5b19-3ff6-49af-b1b2-543f482db3cd)

# About Pulse
![image](https://github.com/Parikshitnh72/Phonepe_/assets/153513327/02a10a3d-90c9-4808-9d5c-869f59937ecd)


# Basic insights
![image](https://github.com/Parikshitnh72/Phonepe_/assets/153513327/13f1696a-58ee-489a-8e80-1335ebe5b8cb)

# Contact
![image](https://github.com/Parikshitnh72/Phonepe_/assets/153513327/1e6c9c3d-17c5-49d2-aa5e-2ebf518fe720)


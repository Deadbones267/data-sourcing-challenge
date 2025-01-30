# data-sourcing-challenge
#description
the pourpose of this project was to make a dataset for a prediction system used by "NOOA" to better predict solar storms from  Coronal Mass Ejections.
I used NASA's pulicly aviable API's to get data on "CME's" and "GST's" , cleaned the data, formated it, and combined the dataframes. Then i added a colum to show the time between a CME and a GST.

in order to use this you will need these packages: 
import requests
import time
from dotenv import load_dotenv
import os
import pandas as pd
import json
import os
from datetime import datetime

and you will need an api key from NASA's link:https://api.nasa.gov/

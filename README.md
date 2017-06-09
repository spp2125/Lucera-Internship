# Lucera-Internship
import requests
import json
from bs4 import BeautifulSoup
sectors=list()
url = "http://www.google.com/finance"
response=requests.get(url)
response_soup=BeautifulSoup(response.content,'lxml')

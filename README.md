# CV_automation_sender

Python language is used

to fully access code you have to install those libraries: 
  import smtplib
  import time
  import requests
  from bs4 import BeautifulSoup as bs
  import re
  import csv
  from email.message import EmailMessage

short description:
  code parses the jobs.ge web page and sends automatically provided resume on companies emails with the subject, with texts content.
  
long description:
  you have to fill some information to work with code. GMAIL_SMPT, GMAIL_PORT, EMAIL_ADDRESS = "your EMAIL",  EMAIL_PASS = "your email password", MSG_CONTENT = "what text message you want to send", good_tittle= "here writes shat kind of vacancies you want to access if it is empty code will send on all of the vacancies", MY_CV = "your resume", when code will parse jobs.ge web page will search company emails. when mails will found code will automatically send to it. (remember code automatically provides the subject of email it is vacancy name) , if mail would be sent it will append on sended_mail_list, if mail will not be sent it appears on bad_mail_list,  if the company is not providing email it will be uploaded on empty_mail_list

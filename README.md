# Powerschool API
This script logs into powerschool using your username and hashed password. From there, it gets your grades. It requires the import requests, re, html, BeautifulSoup, and urllib.request libraries. 

To extract overall grades for all classes, use class_grades(<"username">,<"password">). These grades are formated as a dictionary with the teacher name and grade. To extract assignment grades for one class, use assignment_grades(<"username">,<"password">,<"period_number">). These grades are formated as a list of lists with the due date, category, assignment name, score, and grade.

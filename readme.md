#Authenticate With Google Outh 2.0

#Steps:
1) Go to Google developers dashboard from here https://console.developers.google.com/
2) Create a new project
3) Select the project and click credentials in the sidebar.
4) Select OAuth client ID from the dropdown menu.
5) Select Web Application in application type. The name could be whatever you want.
6) In Authorized JavaScript origins add this line :
    http://localhost:5000
7) In Authorized redirect URIs field add this line :
    http://localhost:5000/auth/google/callback
6) Download the credentials JSON file by clicking on the tiny download button.
7) Save it to google_key.json file in the project
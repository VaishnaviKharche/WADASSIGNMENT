# WADASSIGNMENT
app.yml

runtime: python27
threadsafe: true

handlers:
- url: /
  script: main.app


test.py

import webapp2

class MainPage(webapp2.RequestHandler):
    def get(self):
        self.response.write("Hello World")

app = webapp2.WSGIApplication([('/',MainPage)],debug=True)        

angular
npm install -g @angular/cli@latest
Get-ExecutionPolicy -list
Set-ExecutionPolicy RemoteSigned -scope CurentUser
Get-ExecutionPolicy -list

ny new appname
y 
enter
components- ng g c login
 cd appname
ng serve


nodejs
npm init
create index.js 
copy code 
create public folder in this index.html

nodes index.js
localhost:3000

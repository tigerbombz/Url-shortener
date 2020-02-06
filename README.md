# Url-shortener
Url shortener backend in Node
Steps:
1) Open up my folder in a code editor of your choice
2) Run an `npm install` to install all the packages and dependancies ive added
3) Run `npm run dev` to have the server spin locally at 5000 with nodemon
4) Open up Postman and do a post request to http://localhost:5000/api/url/shorten
5) In the body put in a json format: {	"longUrl" : "https://cloud.mongodb.com/v2/5e3afbdb014b76c51013790a#clusters/connect?clusterId=Cluster0" 
}
6) Check for a response 200 and the payload results
7) Ive attached a screenshot in this zip for your reference
8) The shorten link will then redirect to the long/original url. 

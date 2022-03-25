## Timestamp Microservice App
Node.js Timestamp Microservice App

## created with
nodejs | html | css

## User Stories:
The API endpoint is "GET [project_url]/api/timestamp/:date_string"
      
## If the date string is # empty it should be equivalent to trigger "new Date()", 
  i.e. the service uses the current timestamp.
  
## If the date string is # valid the api returns a JSON having the structure

##      {"unix": &lt;date.getTime()&gt;, "utc" : &lt;date.toUTCString()&gt; }

##       e.g. <code>{"unix": 1479663089000 ,"utc": "Sun, 20 Nov 2016 17:31:29 GMT"}

## If the date string is invalid the api returns a JSON having the structure

## {"error" : "Invalid Date" }

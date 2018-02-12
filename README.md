# D3jsTemplate
if using d3.csv(),d3.json() method in local, it have a problem 

"Failed to load file:///D:/sales.csv: Cross origin requests are only supported for protocol schemes: http, data, chrome, chrome-extension, https." Cross Origin....

so I solve problem using webpack server.

1. npm install 

2. npm run-script build

3. npm start

then execute d3js webpack


if you make d3js using json,csv file, using this template

#Edit that file  
src/index.html
src/index.js

if you add data(csv,json), save in 'data' directory. 

A details analysis that explores Node.js's capabilities in biulding Scalable with application and also looking at benefits and chalenges of using Node.js
example of Node.js Express Framework
var express = require {'express'};
var app = express();

app.get('/', function(req, res) {
res.send ("Hello Word");

var server = app.listen (8081, function() {
var host = server.address().address
var port = server.address().port

console.log("Example app listening at http //%5:%5, host, port);
};
};

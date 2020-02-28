### api

- anything in the "api" folder will get deployed as a "zeit serverless function" in the cloud. 
You can use any programming language.

- "api/index.js" -> `fetch('/api')`
- "api/weather.js" -> `fetch('/api/weather')`

- the syntax for favascript serverless functions:

module.exports = async function(req, res) {
    try {
        // do something
        // req.body = body of the request
        // req.query = qeury parameters (?lat=1.234)
        req.status(200).send(message)
    } catch(e) {
        res.status(500).send(e.message)
    }
}

fetch(`url`,{
    method:'POST'
    body: JSON.stringly
})
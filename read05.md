# Read: 05 - Heroku Deployment

## Heroku Deployment

- [Getting Started](https://devcenter.heroku.com/articles/getting-started-with-nodejs)
- [Deploying a Simple Blog to Heroku](https://howtonode.org/deploy-blog-to-heroku)

### Node.js For Beginners. Deploy Your Blog to Heroku

Error pages are not what typically appear on your screen when you're surfing the web, but when it happens it's so annoying! To see how servers work from within, we will build a simple web server by ourselves. We will use Node.js as a server part technology for that task. Then we'll use Heroku cloud application platform to turn this local server into a world wide server.

Node.js is an open source, cross-platform runtime environment, which allows you to build server-side and networking applications. It's written in JavaScript and can be run within the Node.js runtime on any platform. 

- First of all, we need to create a JavaScript file. Let's name it server.js:

```
var http = require("http");

http.createServer(function(request, response) {
  response.writeHead(200, {"Content-Type": "text/plain"});
  response.write("It's alive!");
  response.end();
}).listen(3000);
```

- It's simple. It's tiny. But it's a server! Let's make sure it's working. Run at your terminal:

```
node server.js
```


# keylogger-server
Keylogger that send data to server.

1. To run this code use `git clone https://github.com/kubixpankejk/keylogger-server`
2. Run the command `cd keylogger-server`
3. Run the command `python3 setup.py`. This will do the basic setup on the Ubuntu server. It will install NodeJS, Node Package Manager (NPM) and also install all the modules required such as the Express web framework, the body-parser middleware used by Express.
4. Run the command `node server.js` to start the server on port ***8080***

You can use the GET and POST methods on the "/" endpoint.
- GET will show the keylogger data written to the server, with every page refresh.
- POST will write the data with the body
  `{
      keyboardData: <what user entered>

Default server is listening on port 8080.

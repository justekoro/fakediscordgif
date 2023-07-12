<div align="center">
    <h1>fakediscordgif</h1>
    <h3>Discord gets a gif, the user gets redirected.</h3>
    <img src="https://img.shields.io/badge/Made%20with-Fastify-green?logo=fastify" alt="Made with Fastify">
    <img src="https://img.shields.io/badge/Made%20with-NodeJS-blue?logo=node.js" alt="Made with NodeJS">
    <img src="https://img.shields.io/badge/Made%20with-Javascript-yellow?logo=javascript" alt="Made with Javascript">
<hr/>
</div>

## What is this?
This project is a simple webserver that shows the user a gif, but redirects them to a webpage when they middle-click on the gif, or click "open browser". See [this video](https://www.youtube.com/watch?v=tujgR1stxIM) for a demo.

## How does it work?
The webserver checks the user agent. If it matches the discord bot user agents, it shows the gif. Else, it redirects to a chosen webpage.

## How do I use it?
### Prerequisites
- NodeJS
- NPM

### Installation
1. Clone the repository
```bash
$ git clone git@github.com:justekoro/fakediscordgif.git
```
2. Install dependencies
```bash
$ cd fakediscordgif
$ npm install # If you use yarn, just type yarn.
```
3. Start the server
```bash
$ node index.js
```

## Configuration
Use environment variables. To disable logger, just set environment variable NODE_ENV to "prod". There is also the `PORT` environment variable, which is the port the server will listen on. The default is 3000.

## License
This project is licensed under the CC BY-NC 3.0 License. See [LICENSE](LICENSE) for more details.

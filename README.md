# amazon-transcribe-websocket-static

A static site demonstrating real-time audio transcription via Amazon Transcribe over a WebSocket.

## Project Overview

This project appears to be a **JavaScript Application**. It is primarily written in None and was last updated on 2020-09-30 20:22:25+00:00.

## Repository Statistics
- Stars: 0
- Forks: 0

## Key Features
- No automated tests detected
- No CI/CD configuration detected
- No Dockerfile detected
- Includes a license

## File Structure
```
.gitignore
AWS_logo_RGB.png
CODE_OF_CONDUCT.md
CONTRIBUTING.md
LICENSE
NOTICE
README.md
index.html
package-lock.json
package.json...
```

## Main Technologies
- .md: 4 file(s)
- : 3 file(s)
- .json: 3 file(s)
- .js: 3 file(s)
- .png: 1 file(s)

## Dependencies


## Existing README Content

## Amazon Transcribe Websocket Static

[Try it out](https://transcribe-websockets.go-aws.com/)

A static site demonstrating real-time audio transcription via Amazon Transcribe over a WebSocket.

This demo app uses browser microphone input and client-side JavaScript to demonstrate the real-time streaming audio transcription capability of [Amazon Transcribe](https://aws.amazon.com/transcribe/) using WebSockets.

Check out the [Amazon Transcribe WebSocket docs](https://docs.aws.amazon.com/transcribe/latest/dg/websocket.html).

## Building and Deploying

[![amplifybutton](https://oneclick.amplifyapp.com/button.svg)](https://console.aws.amazon.com/amplify/home#/deploy?repo=https://github.com/aws-samples/amazon-transcribe-websocket-static)

Even though this is a static site consisting only of HTML, CSS, and client-side JavaScript, there is a build step required. Some of the modules used were originally made for server-side code and do not work natively in the browser.

We use [browserify](https://github.com/browserify/browserify) to enable browser support for the JavaScript modules we `require()`.

1. Clone the repo
2. run `npm install`
3. run `npm run-script build` to generate `dist/main.js`.

Once you've bundled the JavaScript, all you need is a webserver. For example, from your project directory: 

```
npm install --global local-web-server
ws
```

### Credits

This project is based on code written by Karan Grover from the Amazon Transcribe team, who did the hard work (audio encoding, event stream marshalling).

## License

This library is licensed under the Apache 2.0 License. 


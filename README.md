
     ,-----.,--.                  ,--. ,---.   ,--.,------.  ,------.
    '  .--./|  | ,---. ,--.,--. ,-|  || o   \  |  ||  .-.  \ |  .---'
    |  |    |  || .-. ||  ||  |' .-. |`..'  |  |  ||  |  \  :|  `--, 
    '  '--'\|  |' '-' ''  ''  '\ `-' | .'  /   |  ||  '--'  /|  `---.
     `-----'`--' `---'  `----'  `---'  `--'    `--'`-------' `------'
    ----------------------------------------------------------------- 


Welcome to your Node.js project on Cloud9 IDE!

This chat example showcases how to use `socket.io` with a static `express` server.

## Running the server

1) Open `server.js` and start the app by clicking on the "Run" button in the top menu.

2) Alternatively you can launch the app from the Terminal:

    $ node server.js

Once the server is running, open the project in the shape of 'https://projectname-username.c9users.io/'. As you enter your name, watch the Users list (on the left) update. Once you press Enter or Send, the message is shared with all connected clients.


    ----------------------------------------------------------------- 
This is the error I'm getting when I try to run your code:


Benji:live-poets-society benjifriedman$ npm start

> meanfirst@1.0.0 start /Users/benjifriedman/Websites/live-poets-society
> node server.js

Begin set up router
Begin poemrouter
End poemrouter
End set up router
internal/net.js:17
    throw new RangeError('"port" argument must be >= 0 and < 65536');
    ^

RangeError: "port" argument must be >= 0 and < 65536
    at assertPort (internal/net.js:17:11)
    at Server.listen (net.js:1390:5)
    at EventEmitter.listen (/Users/benjifriedman/Websites/live-poets-society/node_modules/express/lib/application.js:618:24)
    at Object.<anonymous> (/Users/benjifriedman/Websites/live-poets-society/server.js:43:5)
    at Module._compile (module.js:570:32)
    at Object.Module._extensions..js (module.js:579:10)
    at Module.load (module.js:487:32)
    at tryModuleLoad (module.js:446:12)
    at Function.Module._load (module.js:438:3)
    at Module.runMain (module.js:604:10)
    at run (bootstrap_node.js:394:7)
    at startup (bootstrap_node.js:149:9)
    at bootstrap_node.js:509:3

npm ERR! Darwin 16.4.0
npm ERR! argv "/usr/local/bin/node" "/usr/local/bin/npm" "start"
npm ERR! node v6.9.5
npm ERR! npm  v3.10.10
npm ERR! code ELIFECYCLE
npm ERR! meanfirst@1.0.0 start: `node server.js`
npm ERR! Exit status 1
npm ERR! 
npm ERR! Failed at the meanfirst@1.0.0 start script 'node server.js'.
npm ERR! Make sure you have the latest version of node.js and npm installed.
npm ERR! If you do, this is most likely a problem with the meanfirst package,
npm ERR! not with npm itself.
npm ERR! Tell the author that this fails on your system:
npm ERR!     node server.js
npm ERR! You can get information on how to open an issue for this project with:
npm ERR!     npm bugs meanfirst
npm ERR! Or if that isn't available, you can get their info via:
npm ERR!     npm owner ls meanfirst
npm ERR! There is likely additional logging output above.

npm ERR! Please include the following file with any support request:
npm ERR!     /Users/benjifriedman/Websites/live-poets-society/npm-debug.log
Benji:live-poets-society benjifriedman$ node --version
v6.9.5

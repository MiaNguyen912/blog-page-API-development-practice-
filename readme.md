How to run the blogs app:
1. in CLI run `npm i`
2. Open 2 terminals and run node on both server.js and index.js
    - index.js will handle api requests from server.js, returning json object
    - server.js uses axios to send server-side api request to the localhost port that index.js is hosted on, then render out the returning json
3. Go to localhost:3000 to see the blogs
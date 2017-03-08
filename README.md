Digital currency exchange
================================



**Required components for running the application in development mode**
```
node v6.9.4
nodemon
redis
modern browser with cors support
```

**Install**
```
npm install
```

**Start the internal application in development mode**
```
open a terminal
npm run dev_client
open another terminal
npm run dev_server
Open http://localhost:8080 in your browser.
```

**Start the internal application in prod mode**
```
open a terminal
npm run prod
npm start
Open http://localhost:3000 in your browser.
```



**Informational**
```
Enter a bitcoin amount and click calculate
The exchanged amount for three currencies will be displayed below
The app store requested exchange rates in redis keyed by time 
The app integrates with Bittrex and Poloniex
```
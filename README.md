# Reach Blackjack DApp

This is a classic blackjack game implemented using Reach and runs on the Algorand blockchain which was created for the **Reach Umoja Bounty Hack**


## Instructions
* Node.js, docker, docker-compose must be installed first.
* Run the Algorand devnet using `$ REACH_CONNECTOR_MODE=ALGO`.

* Start the web-app with either
`$ ./reach react`
or 
`$ npm run start`

* Open the **http://localhost:3000** on your browser, ports might differ in your computer. Check the server terminal in case you can't see the server.

## Problems you may face

* If your docker container gets stuck in contract deployment, use `$ ./reach docker-reset` then restart the web-app and the devnet manually.

* In case you get a contract length error, `$ ./reach update` and  `$ ./reach compile`. Then start the servers again.

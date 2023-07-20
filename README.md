# Decentralized-voting-app
Decentralized voting app based on Ethereum Blockchain. Using Truffle React box, to get up and running so quickly with development process, by using Truffle.
Step 1:
 Install dependencies
$ cd election
$ npm install

Step 2:
Start Ganache
Open the Ganache GUI client that you downloaded and installed. This will start your local blockchain instance. 

Step 3: Compile & Deploy Election Smart Contract
$ truffle migrate --reset You must migrate the election smart contract each time your restart ganache.

Step 4: Configure Metamask
Unlock Metamask
Connect metamask to your local Etherum blockchain provided by Ganache.
Import an account provided by ganache.

Step 5: Run the Front End Application
$ npm run dev Visit this URL in your browser: http://localhost:3000

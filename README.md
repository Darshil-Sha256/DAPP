
Dependencies Install these prerequisites.
A) NPM: https://nodejs.org 
B) Truffle: https://github.com/trufflesuite/truffle 
C) Ganache: http://truffleframework.com/ganache/ 
D) Metamask: https://metamask.io/

Step 1. Clone the project git clone https://github.com/Darshil-Sha256/DAPP

Step 2. Install dependencies $ cd election $ npm install

Step 3. Start Ganache Open the Ganache GUI client that you downloaded and installed. This will start your local blockchain instance.

Step 4. Compile & Deploy Election Smart Contract $ truffle migrate --reset You must migrate the election smart contract each time your restart ganache.

Step 5. Configure Metamask Unlock Metamask Connect metamask to your local Etherum blockchain provided by Ganache. Import an account provided by ganache.

Step 6. Run the Front End Application $ npm run dev Visit this URL in your browser: http://localhost:3000

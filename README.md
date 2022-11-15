# Steps to install and run
1. Requires python3, if you don't have it there are multiple resources online on how to install it according to your platform.
2. Set a virtual environment with `Python3 -m venv venv`
3. Initialize your virtual environment with `source venv/bin/activate` (For Mac and Linux).
4. Intall the dependencies with `pip install -r requirements.txt`
5. Play with it

# Process of implementing on my local workspace
The first and major step was to Configure Morlais Server to run locally
Because moralis v2 no longer supports local web3 servers, we will have to set up a local web3 moralis server. I followed the official documentation to accomplish this. How to Install a Self-Hosted Web3 Server.
I have created a github repository with the files for my dapp along with a screenshot of my localhost.
https://github.com/jpriyam/dapp
Post that I cloned the github repository provided in the youtube video desccription.
The I speccified the 
- Moralis Secret

- Web3 Api Key

in the code in order to authenticate.
I installed the required dependencies and then ran the build.
In the code directory, run the following command to install dependencies and build the code.

npm install npm run build Step 5: Launched the app and logged in to Moralis
I ran the app with the npm run dev command, filled out the form, and clicked the Connect Metamask button.

I was getting an error while logging in due to a mismatch between moralis versions and javascript versions as a result I could not entirely complete the experiment.

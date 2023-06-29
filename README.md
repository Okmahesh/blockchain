# here are the folowing steps to create a token/deploy ERC20

# metamask
1. create an account on metamask wallet 
2. connect to goerli testnetwork from settings
3. mine goerliETH from(https://goerli-faucet.pk910.de/)
4. mine more than 0.01 goerliETH from there
![Screenshot (2)](https://github.com/Okmahesh/blockchain/assets/118921585/419cebb2-29be-4b0d-8dc7-2febdbd32454)


# 20lab
1. Go to given link: https://20lab.app/ (20lab is an ERC-20 token generator tool)
2. Click on open app>Start
3. Connect your wallet using connect wallet button and select metamask then once you see your account click on connect.
4. Choose blockchain Goreli(Testnet), then enter your Token name, Token symbol, Initial supply (take very large number), 18 Decimals.
5. Select your desired options and click validate & compile, it will open metamask and ask for gas fee for deploying your token
6. View your token name and address in dashboard


# HYPERLEDGER-FABRIC
TO INITIATE THE FIRST HYPERLEDGER FABRIC NETWORK, WE WILL UTILIZE THE FABRIC-SAMPLES REPOSITORY. THIS REPOSITORY CONSISTS OF CLI TOOL BINARIES AND FABRIC DOCKER IMAGES, WHICH ARE ESSENTIAL FOR COMPREHENDING AND UTILIZING THE FUNDAMENTALS OF FABRIC. BEFORE COMMENCING THE PROJECT, IT IS NECESSARY TO INSTALL THE FOLLOWING DEPENDENCIES:
## 1. INSTALL DOCKER


```bash
   sudo apt-get -y install docker-compose
```
## 2. INSTALL GOLANG-GO
```bash
sudo apt install golang-go
```
## 3. INSTALL JQ  
```bash
sudo apt install jq
```  
## 4. INSTALL NODE/JAVA  
```bash
sudo apt install npm
npm install node
```
## 5. INSTALLING FABRIC-SAMPLES REPOSITORY  
```bash
curl -sSLO https://raw.githubusercontent.com/hyperledger/fabric/main/scripts/install-fabric.sh && chmod +x install-fabric.sh
```  
THEN YOU CAN PULL DOCKER CONTAINERS BY RUNNING ONE OF THESE COMMANDS:  
```bash
./install-fabric.sh docker samples
./install-fabric.sh d s
```  
TO INSTALL BINARIES FOR FABRIC SAMPLES YOU CAN USE THE COMMAND BELOW:  
```bash
./install-fabric.sh binary
```
## BUILDING FIRST NETWORK 
1. NAVIGATE THROUGH THE FABRIC-SAMPLES FOLDER AND THEN THROUGH THE TEST NETWORK FOLDER WHERE YOU CAN FIND SCRIPT FILES USING THESE WE CAN RUN OUR NETWORK.  
```bash
cd fabric-samples/test-network
```
2. WE WOULD BE RUNNING ./NETWORK.SH DOWN COMMAND TO REMOVE ANY PREVIOUS NETWORK CONTAINERS OR ARTIFACTS THAT STILL EXIST.
```bash
./network.sh down
```
3. WE CAN BRING UP A NETWORK USING THE FOLLOWING COMMAND. THIS COMMAND CREATES A FABRIC NETWORK THAT CONSISTS OF TWO PEER NODES AND ONE ORDERING NODE.
```bash
 ./network.sh up
 ```
 NOW OUR FIRST HYPERLEDGER FABRIC NETWORK IS SUCCESSFULLY RUNNING.

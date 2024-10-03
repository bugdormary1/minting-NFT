# ![image](https://github.com/user-attachments/assets/f8e3e39f-d0d0-4bf4-9b9c-078704af970e)



# User-manual-on-how-to-mint-NFT-using-Helios-by-Lawrence-

# Introduction 

This manual is prepared by Coxygen Global a Cardano Smart Contract development live support platform where you learn, build, and develop with various tools of Cardano Blockchain systems.

This manual is one of our many guide that will explain to you how to get into various Smart Contracts developments with ease. 

This user manual will explain to you how to mint NFT using Helios smart contract an example from Lawrence.

### About Lawrence 

https://www.amazon.com/Ultimate-Cardano-Smart-Contracts-Development/dp/8197396531#:~:text=This%20book%20takes%20you%20on,of%20transactions%20and%20smart%20contracts

### About NFT's

NFTs (Non-Fungible-Tokens) are digital assets that represent ownership of unique items or content on the blockchain. Unlike fungible assets like cryptocurrencies, each NFT is distinct and carries specific value and attributes .

NFTs offers a way to verify the authenticity and ownership of digital items , revolutionizing the digital asset landscape.

### About Helios

Helios is a powerful framework for developing smart contracts on the Cardano blockchain. It simplifies the process of creating, testing, and deploying smart contracts, offering a developer-friendly environment. 

Helios makes NFT minting and management efficient and effective, making it the ideal choice for developers looking to harness Cardano’s potential.

# Must Access Repositories

In minting NFTs there are some repositories examples that one has to access to understand the basics of minting NFT with Helios.

### How to access Helios Examples 

1. Open your web browser and navigate to the Helios Examples GitHub Repository.
   
NOTE: GitHub is a platform for hosting and sharing code, and this repository contains sample code and examples for Helios smart contracts.

2. Clone the Repository Locally
   
To work with the examples on your local machine:

a. Install Git: If you don’t have Git installed, download and install it from git-scm.com.

b. Open Terminal or Command Prompt: Run the following command:git clone https://github.com/lley154/helios-examples.git

3. Navigate to the Repository Folder
   
After cloning, change your directory to the repository folder: cd helios-examples

### How to Access NFT Examples 

1. Find the NFT Example Folder
   
Look for a folder named nft. This folder contains files related to minting an NFT on Cardano using Helios. To switch to this directory, open your terminal and run the following command: cd nft

Inside the folder, you will find Helios script files (.helios or .hs) that demonstrate the logic for NFT minting.

2. Open the Project in Visual Studio Code
   
For easier viewing and editing, open the mint-nft folder in Visual Studio Code. In the terminal, run the following command: code .

This will open the folder in Visual Studio Code for easier file browsing and modifications.

### How to Run and Test Examples 

Running and Testing the Example
Follow the instructions in the README.md file or comments in the code to test the NFT minting example. You might need to run Helios from the command line or interact with the Cardano blockchain to mint NFTs.

### How to Run NFT minting Example 

To run the NFT minting example, you'll need to set up your project environment by installing dependencies and starting the development server. Follow these steps to ensure everything is configured correctly.

1. Install Dependencies:

   Run npm install to install all required libraries and modules.
   
2. Start Development Server:

    Use npm run dev to initiate the development environment.
   
These steps ensure that your project is set up correctly, allowing you to focus on building and testing your NFT minting functionality.

# Connecting and Minting an NFT

In this chapter, we will guide you through the process of connecting your Nami wallet and minting an NFT using a local server. Follow these detailed instructions to complete the minting process successfully.

#### 1. Access the Application
   
To begin, open your web browser and navigate to the following URL:

http://localhost:3000

This address should point to your local server where the NFT minting application is running. Ensure that your server is active before attempting to access this link.

local host 

![image](https://github.com/user-attachments/assets/0595f6b1-f678-4f74-bd15-57c838bd70fd)

#### 2. Ensure Nami Wallet Installation
   
Before you can mint an NFT, you must have the Nami wallet installed in your browser. This wallet is essential for interacting with the Cardano blockchain.

a. Installation:

Download and install the Nami wallet extension from the Nami Wallet website or your browser’s extension store.

b. Setup: 

Follow the setup instructions provided by Nami to configure your wallet.

#### 3. Allow Access to Wallet Balance
   
Upon accessing the application, you will be prompted to allow it to access your Nami wallet’s balance. This permission is crucial for the application to interact with your wallet and facilitate the minting process.

![image](https://github.com/user-attachments/assets/10e39365-87f8-4fd7-8f3c-c0623653972f)

Action: Click the button to grant access when prompted in your browser.
This usually involves approving a request from the Nami wallet extension.

#### 4. Enter NFT Details
   
On the application page, you will find a form that requires several details about the NFT you wish to mint. Fill in the following fields:

a. Destination Wallet Address: Input the Cardano wallet address where the minted NFT will be sent.

b. NFT Token Name: Specify a unique name for your NFT.

c. NFT Description: Provide a description that details the NFT’s attributes and purpose.

d. NFT Image: Upload or link to an image that represents your NFT.

#### 5. Initiate the Minting Process
   
After filling out the form with the necessary information, click the “Mint NFT” button to start the minting process.

![image](https://github.com/user-attachments/assets/0fb50333-9e58-40c2-abf2-e6a5f96186c8)

Action: This will submit your request to mint the NFT and initiate the transaction.

#### 6. Confirm the Transaction
   
Following the initiation of the minting process, a confirmation prompt will appear in your Nami wallet. You must sign this transaction to finalize the minting process.

Action: Click the “Sign” button in the Nami wallet to confirm and complete the transaction.

# Summary

To successfully connect your wallet and mint an NFT:

1. Open Local Server: Navigate to http://localhost:3000.

2. Install Nami Wallet: Ensure you have the Nami wallet installed and configured.
   
3. Allow Wallet Access: Approve the request for wallet balance access.
   
4. Fill in NFT Details: Enter the necessary information for the NFT.
   
5. Mint NFT: Click the “Mint NFT” button.
Confirm Transaction: Sign the transaction in the Nami wallet.



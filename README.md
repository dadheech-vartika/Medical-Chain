# Medical-Chain

## Problem Statement
Over decades, medical facilities have evolved elegantly. Still we are the witness of the fact that whenever we visit a doctor, we need to present our medical file manually containing our medical history, previous prescriptions, medical reports, etc. It is a tedious task to maintain these records. 

# Proposed Solution
With Medical-Chain we aim to provide a digital solution to this problem such that, next time when you visit your doctor, you need not carry your medical file manually. We have developed Web portal to allow the doctor to view the past records of any patient with the patient’s consent.
We will be using Blockchain technology to store the patient records. This will ensure that the information remains cryptographically stored, immutable(can't be tampered) & transparent while being decentralised across different peers. 

## Design & Test Cases

1. If meta-mask extension is not connected or not having access to application it will throw exception

2. Entered Data must be valid. If it is not valid, information will not get stored. Smart contract will check entered values.

3. User does not have sufficient ether for transaction

4. Fetch patient’s data from blockchain; Response time- 380ms (subject to network speed)

5. Fetching Doctor’s Data; Response time- 240ms (Subject to network speed)



## Features:
1. Anyone can register on the Blockchain network as a doctor or a patient.
2. Whenever a patient visits a doctor, the doctor will have the required permissions to store the diagnosis and medical logs in the patient’s record which would be stored in distributed ledgers across the Blockchain network.
3. The doctor would require to sign in the transaction (which would be cryptographically encrypted with his private key) to create and modify the records of a patient (who would be uniquely identified by a patient ID).
4. The medical records of a patient will be accessible from any hospital.

## Advantages:
1. Provides a secure way of managing records.
2. Regulatory bodies can create a shared stream of de-identified patient information
3. Patients can specifically authorise any individual to access their medical  information.
4. Blockchain technology simplifies the complex medical billing process by eliminating the series of validations and multiple third parties acting on behalf of other entities.
5. Patients will be able to easily upload and securely store their records

### To run this project install the following:
1. "Truffle" v5.1.20
2. "Node" v12.16.1 

Install the following with npm

* "antd": "^3.9.0",
* "axios": "^0.19.2",
* "bootstrap": "^4.4.1",
* "bs58": "^4.0.1",
* "ipfs-api": "^26.1.2",
* "react": "16.11.0",
* "react-bootstrap": "^1.0.0",
* "react-dom": "16.11.0",
* "react-scripts": "3.2.0",
* "web3": "1.2.2"

3. Metamask as Google Chrome extension.
4. Ganache for deployement of Contracts

### Steps to run project :
1. Add truffle-config.js file in Ganache.
2. Create new network in metamask with port number same as in truffle-config.js
3. Configure Ganache with same port number.
4. Goto Project Directory and run "truffle migrate" on command prompt.
5. Goto Client directory and run "npm start" to start react server.
6. Project will be open in your browser.
7. Execution will start from _**App.js**_ file in client directory.

 

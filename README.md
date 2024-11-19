Here's a more polished and professional version of your documentation for **EHR 2.0**:

---

# EHR 2.0


## Full Features of the Project
- **Appointments Management**  
- **PDF Upload Capability**  
- **Additional Functionalities and Features**  

---

### Contact Information
For inquiries, please contact:  
**Email**: saqlain.patel.md@gmail.com

---

## System Requirements & Setup Instructions

### 1. Prerequisites
- **Node.js**  
  Download and install Node.js: [Node.js Download](https://nodejs.org/en/download/)

- **Ganache**  
  Install Ganache for blockchain testing: [Download Ganache](https://www.trufflesuite.com/ganache)

- **IPFS (Kubo)**  
  Download and configure IPFS: [IPFS Kubo Download](https://dist.ipfs.tech/#go-ipfs)  
  Configuration guide: [IPFS Configuration Reference](https://github.com/shamil-t/ehr-blockchain/issues/15#issuecomment-1333342345)

- **Metamask Browser Extension**  
  Add the Metamask extension for your browser: [Metamask for Chrome](https://chrome.google.com/webstore/detail/metamask/nkbihfbeogaeaoehlefnkodbefgpgknn?hl=en-US)

### 2. Installation and Setup

#### Step 1: Install Project Dependencies
Open a command prompt (CMD) in the project directory and run:
```bash
npm install --force
```

#### Step 2: Install Truffle Globally
Run the following command as an administrator:
```bash
npm install -g truffle
```

#### Step 3: Open Ganache
- Create a new workspace in Ganache.
- Add the project by selecting `truffle-config.js` from your project directory.
- Save the workspace.

#### Step 4: Compile and Migrate Smart Contracts
Run the following command to compile and deploy contracts:
```bash
truffle migrate
```

#### Step 5: Start the Development Server
Run the following command to start the server:
```bash
npm start
```

---

### Known Issues
For information on known issues and their resolutions, refer to: [GitHub Issue #15](https://github.com/shamil-t/ehr-blockchain/issues/15)

---

This polished version aims to improve clarity and professionalism, enhancing user understanding and providing a structured setup guide. Let me know if you need any further adjustments!

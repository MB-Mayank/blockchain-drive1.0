
# Decentralized Image Upload

## Features
- **Decentralized Storage**: Images on IPFS
- **Smart Contract**: Ethereum-based access control
- **Access Control**: Grant/revoke image access via smart contract

## Technologies
- **Solidity**
- **React**
- **IPFS**

## Installation

### Clone and Navigate
```sh
git clone https://github.com/your-username/decentralized-image-upload.git
cd Dgdrive3.0
```

### Install Dependencies
```sh
npm install
```

### Compile and Deploy Smart Contract
```sh
npx hardhat compile
npx hardhat run scripts/deploy.js --network <network-name>
```

### React Dependencies
```sh
cd client
npm install
npm start
```

## Configuration

### Environment Variables
- Set Pinata API keys in `FileUpload.js`.

### Update Contract Address
Update in `App.js`:
```jsx
const contractAddress = "YOUR_DEPLOYED_CONTRACT_ADDRESS";
```

## Usage

1. **Install Metamask**: Ensure Metamask is configured.
2. **Upload Image**: Use the React app to upload.
3. **Get Data**: Click "Get Data" after uploading to view images.
4. **Access Control**: Enter another user's address to access their images if permission is granted.

### Note
Upload an image before clicking "Get Data" to avoid errors.

## License
This project is licensed under the MIT License.
```

This concise README provides an overview of the project, installation steps, configuration, and usage instructions in a format suitable for a GitHub repository.

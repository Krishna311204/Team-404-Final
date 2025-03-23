# AI-Powered Social Media Trend Prediction  
This project predicts trends on Instagram, GitHub, and Twitter using Machine Learning and Blockchain (EduChain & Sepolia). It provides real-time insights into social media trends while ensuring secure and immutable trend data storage.  

## Features  
- Predict social media trends using AI  
- Store trend predictions on blockchain for transparency  
- Low-cost smart contract integration with EduChain  
- Interactive web interface  
![alt text](Screenshot_2025-03-23_110542[1].png)
## Project Structure  
```
team404-main/
│-- .env
│-- .gitignore
│-- README.md
│-- package.json
│
├── contracts/
│   ├── TrendPrediction.sol
│
├── scripts/
│   ├── deploy.js
│
├── hardhat.config.js
│
├── Models/
│   ├── arima_model.h5
│   ├── github_trends_rf_model.joblib
│   ├── instagram_trend_model.h5
│
├── src/
```

## Getting Started  

### Clone the Repository  
```sh
git clone https://github.com/yourusername/team404-main.git
cd team404-main
```

### Install Dependencies  
```sh
npm install
```

### Set Up Environment Variables  
Create a `.env` file in the root directory and add:  
```
EDUCHAIN_RPC_URL=your_educhain_rpc_url
PRIVATE_KEY=your_wallet_private_key
```

### Compile & Deploy Smart Contract  
Compile:  
```sh
npx hardhat compile
```
Deploy to **Sepolia**:  
```sh
npx hardhat run scripts/deploy.js --network sepolia
```
Deploy to **EduChain**:  
```sh
npx hardhat run scripts/deploy.js --network educhain
```

## Smart Contract Details  
- **Deployed on:** EduChain (Sepolia Testnet)  
- **Contract Address:** To be added after deployment  

## Screenshots  
(Add UI screenshots and blockchain transactions here.)  

## License  
This project is licensed under the MIT License.  

## Contact & Support  
- **Project Maintainer:** Your Name  
- **Email:** your.email@example.com  
- **GitHub:** [Your GitHub](https://github.com/yourusername)  

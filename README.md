🚑 MediCrypt — Decentralized Medical Records on Blockchain
![Doctor Dashboard - MediCrypt]

🌍 Vision
MediCrypt is a decentralized platform that transforms medical record management using:

🔐 IPFS for secure off-chain storage

⛓️ Ethereum Smart Contracts for access control

👛 MetaMask for secure, password-less authentication

Patients have complete control over who accesses their data, ensuring privacy, transparency, and security.

✅ Core Features
🔑 MetaMask-Based Authentication
Ethereum wallet login with digital signature.

No password storage — fully decentralized.

⚙️ Smart Contract Access Control
Deployed on Sepolia Testnet.

Patients manage record access directly via smart contracts.

🗂️ IPFS Integration (via Pinata)
Medical records uploaded securely to IPFS.

Returned CIDs are saved on the blockchain.

👥 Role-Based Permissions
Patients: Upload & manage records

Doctors: Request & access approved data

Researchers: View anonymized records (with consent)

🔁 Blockchain-Powered Workflow
Only file references (CIDs) are stored on-chain — low gas usage.

Full transparency and traceability.

🌐 RESTful API Backend
Auth via MetaMask + JWT

CRUD for records and access requests

💻 React Frontend
Dashboards for each user type

Record uploads, approvals, and access viewing

👨‍⚕️ Beneficiaries
Patients: Control and audit access to personal records

Doctors: Instant access to critical records

Researchers: Analyze anonymized data for research

Hospitals: Streamlined patient data sharing

Innovators: Enable secure third-party health services

🔁 Complete Workflow
1. 👛 Connect Wallet
User signs in using MetaMask → gets authenticated using JWT.

2. 📤 Upload Records
Patients upload files → stored on IPFS → CID saved in smart contract.

3. 🔓 Request Access
Doctors request records → patients approve/deny via dashboard.

4. 🧠 Research Mode
Researchers access anonymized data only after consent.

🧪 Tech Stack
Frontend
React + Vite

MetaMask

Axios

Framer Motion

Backend
Node.js + Express

Prisma (PostgreSQL)

Ethers.js

JWT for auth

Decentralization
IPFS via Pinata for file storage

Ethereum Sepolia Testnet

Solidity Smart Contracts

⚙️ Setup Guide
📦 Prerequisites
Node.js & npm

MetaMask (Browser Extension)

🛠️ Backend
bash
Copy
Edit
git clone <repo-url>
cd medicrypt-backend
npm install

Create a .env file:
PORT=5002
DATABASE_URL="postgresql://user:password@localhost:5432/medicrypt"
JWT_SECRET="your-secret-key"
IPFS_PROJECT_ID="your-ipfs-project-id"
IPFS_PROJECT_SECRET="your-ipfs-project-secret"
CHAIN_RPC_URL="http://localhost:8545"
Then run:
npm run dev


💻 Frontend
cd medicrypt-frontend
npm install
npm run dev
Open in browser: http://localhost:5173

📈 Future Enhancements
🔔 Real-time notifications

🔐 IPFS file-level encryption

🧠 AI-based anonymized health insights

🧑‍🔬 Advanced roles for research users

🎨 Improved UI/UX for all stakeholders
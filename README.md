# Swisstronik Tesnet Techinal Task 6 (Deploy Proxy)

## Steps

### 1. Clone Repository

```bash
git clone https://github.com/Mnuralim/swisstronik-deploy-proxy.git
```

```bash
cd swisstronik-deploy-proxy
```

### 2. Install Dependency

```bash
npm install
```

### 3. Set .env File

create .env file in root project

```bash
touch .env
```

add this to your .env file

```bash
PRIVATE_KEY="your private key"
```

### 4. Compile Smart Contract

```bash
npm run compile
```

### 5. Deploy Smart Contract

```bash
npm run deploy
```

### 6. Initialize Owner

```bash
npm run initialize
```

### 7. Add Issuer

```bash
npm run add-issuers
```

### 8. Get Issuers list

```bash
npm run list-issuers
```

### 9. Upgrade Smart Contract

```bash
npm run upgrade
```

### 10. Finsihed

- Open the deployed-adddress.ts file (location in utils folder)
- Select SWTRProxy
- Copy the address and paste the address into testnet dashboard(Point1)
- Open address-with-explorer.txt file (location in utils folder)
- Copy the address explorer and paste the address into testnet dashboard(Point2)
- Open tx-hash.txt file (location in utils folder)
- Copy the transaction hash link and paste the address into testnet dashboard(Point3)
- No need push to github

SWTRProxy = 0x8C98664c3fae5CEb926C51b0411218ceD4C86dbC
ProxyAdmin = 0xaB41f6622CA48f3dAf3Fc4C4d1E0f7B017157CC9
SWTRImplementation = 0x8401F8aE61901d7ea1c726983A0bA857cDeF2F26
    

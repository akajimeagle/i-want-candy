# gimme-my-candy
#### Better instructions / README coming soon.

---

## Features:
- Generates configuration file for candy machine.
- Uploads Assets to ARWeave
- Deploys Candy Machine to CMv2
- Generates Configuration for Frontend Website

### Special Notes:
- I'll clean this up - this is my first time writing typescript code.
- Used: https://github.com/Fulgurus/candy-machine-v2-responsive-ui for frontend
  - Will replace soon with custom tailwind stuffs
- Please email me suggestions for how I could improve the organization of this project, constructive feedback is always welcome 
  `akajimeagle@protonmail.com` 

### Frontend Config:
- Change background image in `frontend/src/img`
- Change logo & mint image in `frontend/public/`

### Requires:
- Sugar CLI Installed
  - https://docs.metaplex.com/tools/sugar/installation
- Configured Solana CLI
- Connected to Correct Cluster in Solana CLI
- Solana in Wallet (~.3 SOL per 100 NFTs)
- Assets folder in `cmv2-nft-launch` directory with `collection.png / collection.json` files
  - https://docs.metaplex.com/tools/sugar/preparing-assets

### How To Use:
1. Clone Repo `git clone https://github.com/akajimeagle/i-want-candy`
2. CD Into i-want-candy/cmv2-nft-launch `cd i-want-candy/cmv2-nft-launch`
3. Install Dependencies `npm i`
4. `npm run config `
5. `npm run deploy`


### To Start Frontend Again:
1. cd into Frontend `cd {parent_path}/i-want-candy/frontend`
2. `npm run start`

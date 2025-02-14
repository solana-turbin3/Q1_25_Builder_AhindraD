![Screenshot 2025-01-08 153657](https://github.com/user-attachments/assets/6f0556bf-1fc9-45bd-8634-17f686b1bd7e)

# Q1_25_Builder_AhindraD

Proof Of Work During My Time In TURBIN3 Builders Cohort Q1 2025 🦀

- # CAPSTONE: PrismPapers - Decentralized Research Platform
  ## Architecture Diagram:
![image](https://github.com/user-attachments/assets/5e45d06d-9046-48b8-8eac-fdd0d009ef4d)




[View on Eraser](https://app.eraser.io/workspace/srtYuk9xciXjH6IUKwJs)

- # WEEK2: Task 02 - Minted OG NFT

  ![Screenshot 2025-01-17 050131](https://github.com/user-attachments/assets/031e33c8-4e17-49bf-85d4-d7ed2e2be941)

  ## Transaction Hash: https://explorer.solana.com/address/6X1EaiVhcn8z3GNb2nmtBDvoA33sr87AMfcp5rNkiuMf/metadata?cluster=devnet


  <br>

- # WEEK1: Task 02 - RUST : Interaction with the WBA Prereq Program:

  ## Transaction Hash: https://explorer.solana.com/tx/5WYcvZjpouBusi3D8zjWjQJqUtaEJjSTMjRKAFu2pMkcZTa3mkqT2f32EP1CFcFnahJ9a3M1zy1UEWz3hUjZ6jV8?cluster=devnet

  <br>

- # WEEK1: Task 01 - Interaction with the Prereq Program:

  ## Transaction Hash: https://explorer.solana.com/tx/22STvcPPZx8FtvxtyeqJEhWKEXuRAiiDzQqmAqR3mEkzqmH4jKKMEoZYt6NhDi3LsmwA3roENDWt1cqK55FQdpMN?cluster=devnet

  <br>
  <br>
  <br>

# NoteSols - Decentralized Note Taker

### Store your notes on the chain! Take the first step towards a decentralized world.

### NoteSols is a decentralized note-taker that allows users to create, read, update, and delete notes. It is built using the Anchor framework and the Solana blockchain Devnet.

- ## NoteSols Program Address - DEVNET

  https://explorer.solana.com/address/7MZAQw52ZgKMzVhE8VZdZCxxcR9XQfdCcmQSEmu93xjh?cluster=devnet

- ## Frontend Deployed:
  ## https://notesols-dapp.vercel.app/notesols

## Snapshots:

<img src="https://github.com/user-attachments/assets/895f7dc7-096d-44e2-a350-75976a5b9c26" alt="notes_snap" width="400"/>
<img src="https://github.com/user-attachments/assets/de19e316-3dd5-40d2-b2eb-1b1216de0ca7" alt="connect-wallet" width="400"/>
<img src="https://github.com/user-attachments/assets/65b0aae2-0ce8-45c2-8e74-6fc010a2eaa6" alt="account_details" width="400"/>
<img src="https://github.com/user-attachments/assets/5712ddd5-cc75-42e2-8f71-ad2550ff2d76" alt="cluster_selection" width="400"/>

## Project Setup

### Environment Setup

For this Task you need:

- [Rust installed](https://www.rust-lang.org/tools/install)
  - Make sure to use a stable version:
  ```bash
  rustup default stable
  ```
- [Solana installed](https://docs.solana.com/cli/install-solana-cli-tools)

  - Use v1.18.18
  - After you have Solana-CLI installed, you can switch between versions using:

  ```bash
  solana-install init 1.18.18
  ```

- [Anchor installed](https://www.anchor-lang.com/docs/installation)

  - Use v0.30.1
  - After you have Anchor installed, you can switch between versions using:

  ```bash
  avm use 0.30.1
  ```

  <br>
  <br>
  <br>

### 01. Anchor Program with Tests

1. Clone the repository:

```bash
git clone https://github.com/AhindraD/notesols
```

2. Change the directory to the "notesols" folder of the cloned repository:

```bash
cd notesols
```

3. Install dependencies:

```bash
npm install
```

4. Change the directory to the anchor folder:

```bash
cd anchor
```

5. Build the program:

```bash
anchor build
```

6. Test the program:

```bash
 anchor test
```

  <br>
  <br>
  <br>

### 02. Web App - Frontend

1. Go to the deployed frontend at https://notesols-dapp.vercel.app/notesols

Or,

2. Run the development server at the root directory:

```bash
npm run dev
```

5. Open http://localhost:3000/notesols in your browser to see the result, and ineteract with the program.

# CWM: Secure Solana Address Generator

## 🔒 Why This Is Safe

This project is designed with **security and transparency** in mind to ensure that users can generate Solana wallet addresses safely. Here’s how we ensure security:

- **No Private Key Storage**: The application **never** stores or transmits private keys. They are generated client-side and remain with the user.
- **Open-Source Code**: Anyone can inspect the source code to verify that there are no hidden vulnerabilities or backdoors.
- **No External API Calls**: The generator runs entirely within your browser, meaning private keys are never sent over the internet.
- **Minimal Dependencies**: We use only trusted, well-maintained libraries to reduce the risk of third-party exploits.

## ⚙️ How It Works

1. **Client-Side Key Generation**: Using a secure cryptographic library, the app generates a **Solana key pair** directly in your browser.
2. **Instant Wallet Address Display**: The public address is displayed immediately for user convenience.
3. **Download & Save**: Users can securely copy or download their generated key pairs.

## 🚀 Features

- **Generate Solana Wallets** instantly
- **Export & Save** key pairs securely
- **Lightweight & Fast** with no backend processing
- **Completely Open-Source** for full transparency

## 🔧 Installation & Usage

To run the project locally:

```sh
# Clone the repository
git clone https://github.com/CustomWalletMaker/cwm
cd cwm

# Install dependencies
npm install

# Start the development server
npm run dev
```

To build for production:

```sh
npm run build
```

Then, upload the `build/` folder to your hosting service.

## 🛡️ Security Best Practices

- Always generate your keys on a **trusted** device.
- Store private keys in a **safe place**, such as a hardware wallet.
- **Never** share your private key with anyone.

## 🤝 Contributing

We welcome contributions! To contribute:

1. Fork the repository
2. Create a new branch (`git checkout -b feature-branch`)
3. Commit changes (`git commit -m "Add new feature"`)
4. Push to GitHub (`git push origin feature-branch`)
5. Open a Pull Request

## 📜 License

This project is licensed under the **MIT License**, meaning you can use, modify, and distribute it freely.


<!-- TITLE -->
<p align="center">
  <img width="100px" src="https://github.com/celo-org/celo-composer/blob/main/images/readme/celo_isotype.svg" align="center" alt="Celo" />
 <h2 align="center">Celo Composer - Farcaster Frame Template</h2>
 <p align="center">Build, deploy, and iterate quickly on Farcaster Frames with integrated Celo blockchain functionality.</p>
</p>
  <p align="center">
    <a href="https://github.com/celo-org/celo-composer/graphs/stars">
      <img alt="GitHub Contributors" src="https://img.shields.io/github/stars/celo-org/celo-composer?color=FCFF52" />
    </a>
    <a href="https://github.com/celo-org/celo-composer/graphs/contributors">
      <img alt="GitHub Contributors" src="https://img.shields.io/github/contributors/celo-org/celo-composer?color=E7E3D4" />
    </a>
    <a href="https://github.com/celo-org/celo-composer/issues">
      <img alt="Issues" src="https://img.shields.io/github/issues/celo-org/celo-composer?color=E7E3D4" />
    </a>
    <a href="https://github.com/celo-org/celo-composer/pulls">
      <img alt="GitHub pull requests" src="https://img.shields.io/github/issues-pr/celo-org/celo-composer?color=E7E3D4" />
    </a>
    <a href="https://opensource.org/license/mit/">
      <img alt="MIT License" src="https://img.shields.io/badge/License-MIT-yellow.svg" />
    </a>
  </p>
</p>

<!-- TABLE OF CONTENTS -->

<div>
  <summary>Table of Contents</summary>
  <ol>
    <li><a href="#about-the-project">About The Project</a></li>
      <ol>
        <li><a href="#built-with">Built With</a></li>
        <li><a href="#prerequisites">Prerequisites</a></li>
        <li><a href="#farcaster-frames">Farcaster Frames</a></li>
     </ol>
    <li><a href="#how-to-use-celo-composer">How to use Celo Composer</a></li>
        <ol>
          <li><a href="#install-dependencies">Install Dependencies</a></li>
          <li><a href="#deploy-a-smart-contract">Deploy a Smart Contract</a></li>
          <li><a href="#develop-your-frame-locally">Develop your Frame Locally</a></li>
          <li><a href="#add-frame-components">Add Frame Components</a></li>
          <li><a href="#deploy-with-vercel">Deploy with Vercel</a></li>
          <li><a href="#supported-frameworks">Supported Frameworks</a></li>
        </ol>
    <li><a href="#frame-development">Frame Development</a></li>
    <li><a href="#usage">Usage</a></li>
    <li><a href="#support">Support</a></li>
    <li><a href="#roadmap">Roadmap</a></li>
    <li><a href="#contributing">Contributing</a></li>
    <li><a href="#license">License</a></li>
    <li><a href="#contact">Contact</a></li>
  </ol>
</div>

<!-- ABOUT THE PROJECT -->

## About The Project

Celo Composer allows you to quickly build, deploy, and iterate on decentralized applications using Celo. This **Farcaster Frame template** specifically enables you to create interactive social experiences that run directly in Farcaster feeds, combining the power of Celo blockchain with Farcaster's decentralized social protocol.

This template provides everything you need to build Farcaster Frames with:

- 🖼️ **Frame Infrastructure**: Complete frame handling, meta tags, and interaction system
- ⛓️ **Celo Integration**: Pre-configured Web3 setup for Celo blockchain interactions
- 🎨 **Dynamic Images**: Server-side image generation for frame visuals
- 🔐 **Authentication**: Farcaster user verification and signature handling
- 📱 **Responsive Design**: Works both as frames and standalone web applications

It is the perfect lightweight starter-kit for any hackathon and for quickly testing out Farcaster integrations and deployments on Celo.

<p align="right">(<a href="#top">back to top</a>)</p>

## Built With

Celo Composer is built on Celo to make it simple to build Farcaster Frames using a variety of front-end frameworks and libraries.

- [Celo](https://celo.org/)
- [Farcaster](https://farcaster.xyz/)
- [Solidity](https://docs.soliditylang.org/en/v0.8.19/)
- [Hardhat](https://hardhat.org/)
- [React.js](https://reactjs.org/)
- [Next.js](https://nextjs.org/)
- [viem](https://viem.sh/)
- [Tailwind](https://tailwindcss.com/)

<p align="right">(<a href="#top">back to top</a>)</p>

<!-- GETTING STARTED -->

## Prerequisites

- Node (v20.9.0 or higher, required by sharp)
- Git (v2.38 or higher)

## Farcaster Miniapps

Welcome to the [Farcaster](https://docs.farcaster.xyz/) miniapp development guide. Farcaster Miniapps are full-featured web applications that integrate seamlessly with the Farcaster ecosystem, providing rich interactive experiences that go beyond simple social posts.

This template provides a complete foundation for building miniapps that integrate with the Celo blockchain, enabling you to create comprehensive social dApps featuring:

- 🪙 **Token interactions** (transfers, swaps, staking)
- 🎨 **NFT creation and trading**
- 🗳️ **Governance and voting**
- 🎮 **Social games and competitions**
- 💰 **DeFi protocols and yield farming**
- 👥 **Social features** powered by Farcaster's social graph

:::info
Learn more about Farcaster development in the [official documentation](https://docs.farcaster.xyz/) 📚
:::

## How to use Celo Composer - Farcaster Miniapp template

The easiest way to start with Celo Composer is using `@celo/celo-composer`. This CLI tool lets you quickly start building Farcaster Miniapps on Celo. To get started, just run the following command, and follow the steps:

- Step 1

```bash
npx @celo/celo-composer@latest create
```

- Step 2: Provide the Project Name: You will be prompted to enter the name of your project.

```text
What is your project name:
```

- Step 3: Choose to Use Hardhat: You will be asked if you want to use Hardhat. Select Yes or No.

```text
Do you want to use Hardhat? (Y/n)
```

- Step 4: Choose to Use a Template: You will be asked if you want to use a template. Select `Yes` .

```text
Do you want to use a template?
```

- Step 5: Select a Template: If you chose to use a template, you will be prompted to select `Farcaster` from the list provided.

- Step 6: Provide the Project Owner's Name: You will be asked to enter the project owner's name.

```text
Project Owner name:
```

- Step 7: Wait for Project Creation: The CLI will now create the project based on your inputs. This may take a few minutes.

- Step 8: Follow the instructions to start the project. The same will be displayed on the console after the project is created.

```text
🚀 Your Farcaster Frame project has been successfully created!
```

## Install Dependencies

Once your custom Frame has been created, just install dependencies, either with yarn:

```bash
   yarn
```

If you prefer npm, you can run:

```bash
   npm install
```

## Deploy a Smart Contract

Find the detailed instructions on how to run your smart contract in [packages/hardhat/README.md](./packages/hardhat/README.md).

For quick development follow these three steps:

1. Change `packages/hardhat/env.template` to `packages/hardhat/env` and add your `PRIVATE_KEY` into the `.env` file.
2. Make sure your wallet is funded when deploying to testnet or mainnet. You can get test tokens for deploying it on Alfajores from the [Celo Faucet](https://faucet.celo.org/alfajores).
3. Run the following commands from the `packages/hardhat` folder to deploy your smart contract to the Celo Testnet Alfajores:

```bash
npx hardhat ignition deploy ./ignition/modules/FarcasterNFT.ts --network alfajores
```

## Develop your Miniapp Locally

Find the detailed instructions on how to run your miniapp in the [`react-app` README.md](./packages/react-app/README.md).

Before you start the project, please follow these steps:

1. Rename the file:
   packages/react-app/.env.template
   to
   packages/react-app/.env

2. Open the newly renamed .env file and add your environment variables:

```env
NEXT_PUBLIC_WC_PROJECT_ID=your_walletconnect_project_id
NEXT_PUBLIC_BASE_URL=http://localhost:3000
NEXT_PUBLIC_CELO_NETWORK=alfajores
```

3. Get your WalletConnect Cloud Project ID from [WalletConnect Cloud](https://cloud.walletconnect.com/)

Once you've done that, you're all set to start your project!

Run the following commands from the `packages/react-app` folder to start the project:

```bash
   yarn dev
```

If you prefer npm, you can run:

```bash
   npm run dev
```

## Miniapp Development

### Local Testing

1. **Development Server**: Your miniapp will be available at `http://localhost:3000`
2. **Mobile Testing**: Test on mobile devices by accessing your local IP address
3. **Responsive Design**: The app is optimized for mobile-first design with responsive layouts

### Miniapp Features

This template includes comprehensive miniapp functionality:

- **Responsive Design**: Mobile-optimized UI with touch-friendly components
- **Wallet Integration**: Connect with various Celo-compatible wallets
- **NFT Management**: Mint, view, and manage NFT collections
- **Token Operations**: Send and receive Celo stablecoins
- **Social Integration**: Built for Farcaster ecosystem integration

### Architecture

- **Next.js App Router**: Modern React framework with server components
- **Tailwind CSS**: Utility-first CSS framework for rapid development
- **ShadCN Components**: High-quality, accessible UI component library
- **Celo Integration**: Built-in Web3 functionality for Celo blockchain
- **TypeScript**: Full type safety throughout the application

### Adding Custom Features

1. **New Pages**: Add new routes in the `app/` directory
2. **Custom Components**: Create reusable components in `components/`
3. **Smart Contract Integration**: Extend `useWeb3` hook for new contract interactions
4. **Styling**: Customize themes and styles using Tailwind CSS

### Deployment

Deploy your miniapp to platforms like:

- **Vercel** (recommended for Next.js)
- **Netlify**
- **Railway**
- **Custom hosting**

See the [Deployment Guide](./packages/docs/DEPLOYMENT_GUIDE.md) for detailed instructions.

Thank you for using Celo Composer! If you have any questions or need further assistance, please refer to the README or reach out to our team.

**_🚀 Voila, you have a Farcaster Miniapp ready to go. Start building your social dApp on Celo! 🎨_**

## Usage

## Support

Join the Celo Discord server at <https://chat.celo.org>. Reach out on the dedicated repo channel [here](https://discord.com/channels/600834479145353243/941003424298856448).

<!-- ROADMAP -->

## Roadmap

See the [open issues](https://github.com/celo-org/celo-composer/issues) for a full list of proposed features (and known issues).

<p align="right">(<a href="#top">back to top</a>)</p>

<!-- CONTRIBUTING -->

## Contributing

We welcome contributions from the community.

<p align="right">(<a href="#top">back to top</a>)</p>

## License

Distributed under the MIT License. See `LICENSE.txt` for more information.

<!-- CONTACT -->

## Contact

- [@CeloDevs](https://twitter.com/CeloDevs)
- [Discord](https://discord.com/invite/celo)

<p align="right">(<a href="#top">back to top</a>)</p>

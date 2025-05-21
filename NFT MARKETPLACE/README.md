# NFT Marketplace Setup Guide

This guide will help you set up and run the NFT Marketplace project locally.

---

## Folder Structure

```
NFT MARKETPLACE/
├── AccountPage/
│   └── Form/
│       ├── Form.jsx
│       └── Form.module.css
├── authorPage/
│   ├── componentIndex.js
│   ├── AuthorNFTCardBox/
│   │   ├── AuthorNFTCardBox.jsx
│   │   └── AuthorNFTCardBox.module.css
│   ├── AuthorProfileCard/
│   │   ├── AuthorProfileCard.jsx
│   │   └── AuthorProfileCard.module.css
│   └── AuthorTaps/
│       ├── AuthorTaps.jsx
│       └── AuthorTaps.module.css
├── collectionPage/
│   ├── collectionIndex.js
│   ├── Banner/
│   │   ├── Banner.jsx
│   │   └── Banner.module.css
│   ├── collectionProfile/
│   │   ├── collectionProfile.jsx
│   │   └── collectionProfile.module.css
│   └── NFTCardTwo/
│       ├── NFTCardTwo.jsx
│       └── NFTCardTwo.module.css
├── components/
│   ├── componentsindex.js
│   ├── AudioLive/
│   │   ├── AudioLive.jsx
│   │   ├── AudioLive.module.css
│   │   ├── AudioCard/
│   │   │   ├── AudioCard.jsx
│   │   │   └── AudioCard.module.css
│   │   └── AudioCardSmall/
│   │       ├── AudioCardSmall.jsx
│   │       └── AudioCardSmall.module.css
│   ├── BigNFTSilder/
│   ├── Brand/
│   │   ├── Brand.jsx
│   │   └── Brand.module.css
│   ├── Button/
│   │   ├── Button.jsx
│   │   └── Button.module.css
│   ├── Category/
│   │   ├── Category.jsx
│   │   └── Category.module.css
│   ├── Collection/
│   │   ├── Collection.jsx
│   │   ├── Collection.module.css
│   │   └── DaysComponents/
│   │       ├── DaysComponents.jsx
│   │       └── DaysComponents.module.css
│   ├── Filter/
│   │   ├── Filter.jsx
│   │   └── Filter.module.css
│   ├── FollowerTab/
│   │   ├── FollowerTab.jsx
│   │   ├── FollowerTab.module.css
│   │   └── FollowerTabCard/
│   │       ├── FollowerTabCard.jsx
│   │       └── FollowerTabCard.module.css
│   ├── Footer/
│   │   ├── Footer.jsx
│   │   └── Footer.module.css
│   ├── HeroSection/
│   │   ├── HeroSection.jsx
│   │   └── HeroSection.module.css
│   ├── LikeProfile/
│   │   ├── LikeProfile.jsx
│   │   └── LikeProfile.module.css
│   ├── NavBar/
│   │   ├── index.js
│   │   ├── NavBar.jsx
│   │   ├── NavBar.module.css
│   │   ├── Discover/
│   │   │   ├── Discover.jsx
│   │   │   └── Discover.module.css
│   │   ├── HelpCenter/
│   │   │   ├── HelpCenter.jsx
│   │   │   └── HelpCenter.module.css
│   │   ├── Notification/
│   │   │   ├── Notification.jsx
│   │   │   └── Notification.module.css
│   │   ├── Profile/
│   │   │   ├── Profile.jsx
│   │   │   └── Profile.module.css
│   │   └── SideBar/
│   │       ├── SideBar.jsx
│   │       └── SideBar.module.css
│   ├── NavBar2/
│   │   ├── index.js
│   │   ├── NavBar.jsx
│   │   ├── NavBar.module.css
│   │   ├── Discover/
│   │   │   ├── Discover.jsx
│   │   │   └── Discover.module.css
│   │   ├── HelpCenter/
│   │   │   ├── HelpCenter.jsx
│   │   │   └── HelpCenter.module.css
│   │   ├── Notification/
│   │   │   ├── Notification.jsx
│   │   │   └── Notification.module.css
│   │   ├── Profile/
│   │   │   ├── Profile.jsx
│   │   │   └── Profile.module.css
│   │   └── SideBar/
│   │       ├── SideBar.jsx
│   │       └── SideBar.module.css
│   ├── NFTCard/
│   │   ├── NFTCard.jsx
│   │   └── NFTCard.module.css
│   ├── Service/
│   │   ├── Service.jsx
│   │   └── Service.module.css
│   ├── Slider/
│   │   ├── Slider.jsx
│   │   ├── Slider.module.css
│   │   └── SliderCard/
│   │       ├── SliderCard.jsx
│   │       └── SliderCard.module.css
│   ├── Subscribe/
│   │   ├── Subscribe.jsx
│   │   └── Subscribe.module.css
│   ├── Title/
│   │   ├── Title.jsx
│   │   └── Title.module.css
│   └── Video/
│       ├── Video.jsx
│       └── Video.module.css
├── contracts/
│   └── Lock.sol
├── ignition/
│   └── modules/
│       └── Lock.js
├── img/
│   ├── collection.png
│   ├── creatorbackground-1.jpeg
│   ├── creatorbackground-10.jpg
│   ├── creatorbackground-11.jpg
│   ├── creatorbackground-2.jpeg
│   ├── creatorbackground-3.jpeg
│   ├── creatorbackground-4.jpg
│   ├── creatorbackground-5.jpg
│   ├── creatorbackground-6.jpg
│   ├── creatorbackground-7.jpg
│   ├── creatorbackground-8.jpg
│   ├── creatorbackground-9.jpg
│   ├── earn.png
│   ├── eran.png
│   ├── facebook.svg
│   ├── founder1.jpg
│   ├── founder2.jpg
│   ├── founder3.jpg
│   ├── founder4.jpg
│   ├── getable.png
│   ├── hero.png
│   ├── hero2.png
│   ├── index.js
│   ├── logo-light.svg
│   ├── logo.svg
│   ├── musicwave.png
│   ├── nft_1.png
│   ├── nft-image-1.png
│   ├── nft-image-2.png
│   ├── nft-image-3.png
│   ├── nftvideo.png
│   ├── provider-1.png
│   ├── provider-2.png
│   ├── provider-3.png
│   ├── provider-4.png
│   ├── service-1.png
│   ├── service-2.png
│   ├── service-3.png
│   ├── service-4.png
│   ├── telegram.svg
│   ├── twitter.svg
│   ├── update.png
│   ├── upload.png
│   ├── user-1.png
│   ├── user-10.png
│   ├── user-2.png
│   ├── user-3.png
│   ├── user-4.png
│   ├── user-5.png
│   ├── user-6.png
│   ├── user-7.png
│   ├── user-8.png
│   ├── user-9.png
│   ├── VectorHIW.svg
│   ├── vimeo.svg
│   ├── warzone.mp3
│   ├── youtube.svg
│   └── zgcmq.svg
├── loginAndSignUp/
│   ├── loginAndSignUp.jsx
│   └── loginAndSignUp.module.css
├── NFTDetailsPage/
│   ├── NFTDescription/
│   │   ├── NFTDescription.jsx
│   │   └── NFTDescription.module.css
│   ├── NFTDetailsImg/
│   │   ├── NFTDetailsImg.jsx
│   │   └── NFTDetailsImg.module.css
│   ├── NFTDetailsIndex.js
│   ├── NFTDetailsPage.jsx
│   ├── NFTDetailsPage.module.css
│   └── NFTTabs/
│       ├── NFTTabs.jsx
│       └── NFTTabs.module.css
├── pages/
│   ├── aboutus.js
│   ├── account.js
│   ├── author.js
│   ├── collection.js
│   ├── connectWallet.js
│   ├── contactus.js
│   ├── index.js
│   ├── login.js
│   ├── NFT-details.js
│   ├── searchPage.js
│   ├── signUp.js
│   ├── subscription.js
│   ├── uploadNFT.js
│   └── _app.js
├── public/
│   ├── favicon.ico
│   └── vercel.svg
├── sampleNFTData/
├── SearchPage/
│   ├── SearchBar/
│   │   ├── SearchBar.jsx
│   │   └── SearchBar.module.css
│   └── searchBarIndex.js
├── styles/
│   ├── aboutus.module.css
│   ├── account.module.css
│   ├── author.module.css
│   ├── collection.module.css
│   ├── connectWallet.module.css
│   ├── contactus.module.css
│   ├── globals.css
│   ├── index.module.css
│   ├── login.module.css
│   ├── searchPage.module.css
│   ├── signUp.module.css
│   ├── subscription.module.css
│   └── upload-nft.module.css
├── Subscription/
│   ├── Subscription.jsx
│   └── Subscription.module.css
├── test/
│   └── Lock.js
├── UploadNFT/
│   ├── DropZone/
│   │   ├── DropZone.jsx
│   │   └── DropZone.module.css
│   ├── UloadNFT.jsx
│   ├── Upload.module.css
│   └── uploadNFTIndex.js
├── hardhat.config.js
├── next.config.js
├── package.json
├── package-lock.json
├── Temp.md
└── .gitignore
```

---

## Prerequisites

- **Node.js**: v16.20.2 (Recommended for Next.js 12 and Hardhat 2.11.2)
- **npm**: v8.19.4 or higher
- **Hardhat**: ^2.11.2 (installed via npm)

> ⚠️ Node.js v18+ may cause compatibility issues with Hardhat 2.11.2. Use Node.js v16.x for best results.

---

## Installation Steps

1. **Clone the repository:**

   ```sh
   git clone https://github.com/STIWARTs/HackIndia-Spark-4-2025-CryptoCrafters.git
   cd "HackIndia-Spark-4-2025-CryptoCrafters/NFT MARKETPLACE"
   ```

2. **Install dependencies:**

   ```sh
   npm install
   ```

3. **Run the development server:**

   ```sh
   npm run dev
   ```

   The app will be available at [http://localhost:3000](http://localhost:3000)

4. **Compile smart contracts (optional):**
   ```sh
   npx hardhat compile
   ```

---

## Notes

- `node_modules` and `.next` folders are not included in the repository. They will be generated when you run `npm install` and `npm run build`/`npm run dev`.
- If you encounter issues with Hardhat, ensure your Node.js version is v16.20.2.
- For contract deployment and testing, refer to the `contracts/` and `test/` folders.

---

## Main Versions Used

- **Node.js:** v16.20.2
- **npm:** v8.19.4
- **Next.js:** 12.2.5
- **React:** 18.2.0
- **Hardhat:** ^2.11.2
- **Solidity:** 0.8.28

---

## Contact

For any issues, please open an issue on the repository or contact the maintainers.

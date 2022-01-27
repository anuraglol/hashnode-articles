## 💫 Introducing Vault3 - Your safest decentralized vault!

![hello](https://media.giphy.com/media/3ornk57KwDXf81rjWM/giphy.gif)

## ❓ What is Vault3?

Simply speaking, Vault3 is a decentralized vault for all your digital belongings, like **Passwords, Images, and Files.**

Vault3 is our submission for the **[Hashnode x ThirdWeb](https://townhall.hashnode.com/thirdweb-hackathon)** Hackathon

[`Try Vault3`](https://vault3.live)

## ✏️ Hashnode

In case you don’t know, **[Hashnode](https://hashnode.com)** is the easiest way to start a developer blog on your personal domain for free and connect with the readers through its global dev community! 

## 🌐 ThirdWeb

These days, Web3.0 is catching everyone’s eyes, and as a developer myself, the learning curve is pretty steep. That’s where **ThirdWeb** comes in! **ThirdWeb** is a sweet collection of tools that can be used to build sophisticated Web3 apps, with ease.

Tracing Back to Vault3, let’s first see where the Idea came from.

## 😕 The Problem

It is a normal tendency for humans to forget things that are long or things that cant be remembered easily. Hence, we write them down in a place to use them when needed. But in the digital world, writing important things that are hard to remember like passwords in physical objects like paper has become highly unlikely. It has become quite common to store important things in applications like password/note managers.

But have we ever thought about the safety of our digital belongings in those applications that are centralized? Have we ever thought that our data can be easily censored by the applications where we store them in? 

Enter Vault3, a safe and secure digital vault.

## 🔭 Deep Dive into Vault3

Speaking of Vault3, it’s a web application built with technologies like **NextJS**, **Chakra UI** and some external libraries.

Vault3 provides users with a safe vault, which they can use to store important belongings such as **Photos**, **Passwords** and **Files**.

The way it works is:

- User first connects their wallet, like **Metamask**
- Then they create a private key to access their vault. To create a private key, user needs to upload an **Image** of their choice. This Image is hashed and will be used as a private key to access the vault.
- Now the user can access their vault through a Dashboard
- Here the user can upload **Passwords**, **Images** and **Files**
- Users can also delete, download and view their stats.

## ✨ The Tech Stack

- **NextJS**
- **Chakra UI**
- **Thirdweb**
- **Hardhat**

## 👀 Understanding the flow of the app

### 🔒 Authentication

The auth flow is handled by crypto wallets as in **web3.0** protocols. We are using **Thirdweb** as our provider. At the time of writing this article, **Vault3** only supports **Metamask** wallet.

### 🔑 Generating the private key

The private key to access the vault is basically generated from the **Image** that the user provides when creating a new private key. 

The **Image** is first converted into byte data, and then its hashed using the HmacSHA256 algorithm, which is then used as a private key to access the vault.

To access their vault again, users must provide the same **Image.**

## 💽 Uploading Flow

> All of your data is stored safely on the **Polygon** blockchain using the **AES** encryption algorithm.

### 🔑 Uploading Password

Storing a password is extremely simple. You are just required to enter the **Website** for which you want to store the password, your **Username** or **Email** you used for that site and lastly the **Password** itself. You can also copy the password and also reveal it once it has been stored. You can also filter your passwords by searching for the site address that you have given while storing a new password.

### 🌆 Uploading Image

The process for storing an image relatively remains the same as storing a password except the field where you would enter the name of the site is now replaced by a field for Name of the image. And, you now have a field to insert your image. Vault3 supports various image formats such as PNG, JPG, SVG, GIF and WEBP. Ta-da! Your image is now stored in your vault!

### 📁 Uploading Files

Moving onto importing a file. Vault3 supports insertion of files of all kinds, so you do not have to worry about the format of your file. You just need to insert your file and the Name field is populated by the name of the file you have chosen and you cannot change the Name for a file unlike the situation of storing an Image.

> Apart from uploading Passwords, Images, and Files, users can also delete and download the data stored in their vault.

> **Note**: Since Vault3 is based on web 3.0, most of these operations require **Gas Fees** in the form of **MATIC** tokens.

### ℹ️ On a sidenote:

> Vault3 currently operates on the **Mumbai Polygon Testnet** Network, and you can get some fake **MATIC** [here](https://faucet.polygon.technology/)

### 👥 Moving from this, Let’s meet the Team:

- Saptarshi Basu - Builder, [saptarshii.me@gmail.com](mailto:saptarshii.me@gmail.com)
- Anurag - Co-Builder, [kr.anurag24@gmail.com](mailto:kr.anurag24@gmail.com)

%[https://twitter.com/imsaptarshiii/status/1484802359956230147]

### 🔗 External Links

- [`Vault3`](https://vault3.live)
- [`Github`](https://github.com/imsaptarshi/vault3)
- [`Product Hunt`](https://www.producthunt.com/posts/vault3-1)
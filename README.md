# 📊 Budgify

A web app that helps you budget and gain insight into your spending habits with Programmable Banking.

- Budgify provides a dashboard view of your current account balance, total income and total expenses as well as automated categorisation of your transactions.
- It also provides you with a weekly breakdown of your income and expenses.
- Budgify uses the [Investec Transaction History API](https://developer.investec.com/za/api-products)

![Dashboard](/docs/dashboard.png)

## ☑️ Requirements

- Terminal Application
  - [MAC](https://support.apple.com/en-za/guide/terminal/apd5265185d-f365-44cb-8b09-71a064a42125/mac)
  - [Windows](https://www.youtube.com/watch?v=EqaEPL9ZKGA)
- Node installed on your machine ([see this guide on how to install](https://kinsta.com/blog/how-to-install-node-js/))
- Access to the [Investec Programmable Banking API](https://developer.investec.com/za/api-products)

## 🔑 Preparations

You will need to have your Investec API keys at hand.
Specifically, your client ID, client secret and API key. You can learn more about getting your Investec API keys in the [Quick Start Quide](https://offerzen.gitbook.io/programmable-banking-community-wiki/developer-tools/quick-start-guide#how-to-get-your-api-keys).

## 🚀 Getting Started

We encourage you to fork this repository to your GitHub account. This allows you to easily stay up to date with new changes to the app without losing any local customizations you may make to it. To fork this app, please see the [following guide](https://docs.github.com/en/get-started/quickstart/fork-a-repo)

Once you have forked the repo, please clone it.

Open your terminal and run the following:

```bash
git clone https://github.com/programmable-banking-community/budgify
Rename the `.env.local.example` to `.env.local`
```

Then run the following:

```bash
cd budgify
npm install
npm run dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.


## 🧑‍💻 Contributions

Possible additions:

```
- The ability to select a specific date to filter transactions
- Select a different accounts and see the transactions per account
- A graph which displays the spend for each category
- Allow a user to edit/create/select categories
```

Pull requests and changes are welcome.

## 📄 License

This project is MIT licensed.

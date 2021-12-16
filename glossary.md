---
description: Terms that are used throughout the guides will be defined here.
---

# 🗒 Glossary

#### ``:moneybag:`Wallet`

The purpose of a wallet is to generate your Bitcoin private keys so that you can receive, send, store and manage your bitcoin. It can be on your mobile device, computer or on a dedicated piece of hardware. \
\
There are also different types of wallets depending on their connectivity to the Internet. Your wallet can either be:

* Hot : It has an online connection in order to communicate with the rest of the Bitcoin network;
* Cold : Your private keys are generated offline. You can approve the transactions you wish to spend, but must transfer this signature to a wallet that is connected to the Bitcoin network.

#### ``:floppy\_disk:`Hardware wallet`

This serves the same purpose as the wallet defined above, except that it is entirely generated on a specialized piece of hardware that only serves your Bitcoin purposes.&#x20;

This is to isolate your Bitcoin stuff from your other devices.&#x20;

``:warning:`Seed phrase/Backup/Private key`

These terms can be used interchangeably. This is what your Bitcoin wallet generates. It can be represented as a list of either 12 or 24 English words.&#x20;

{% hint style="success" %}
Keep your Backup in a safe location, that only you can access.
{% endhint %}

{% hint style="danger" %}
Anyone that has access to your Backup can steal the bitcoins that are sent to it!
{% endhint %}

#### ``:money\_mouth:`Non-custodial`

This is the term we use to define everything that is in the complete control of the user. You have the tools at your disposition to retain full control of your bitcoins during the process and storage.

#### :key:`Self-custody`

This is when you hold onto your own Backup. You do not require trusting a third-party for the security of your funds since the entire responsibility falls within the hands of the person controlling it (you).

#### ``:closed\_lock\_with\_key:`Passphrase`

This is a set of words and/or characters that you can fully customize. Your Passphrase is added to your Backup in order to generate an entirely new and unique Bitcoin wallet. This acts as an added layer of protection to your Backup, so that anyone that might come into contact with your Backup won't be able to steal your funds, unless they also find your Passphrase.

{% hint style="danger" %}
Do not store your Passphrase in the same location as your Backup!
{% endhint %}

{% hint style="info" %}
You can always add a new `P`assphrase to your original Backup in order to generate a new Wallet, but you must properly save that word in order to recuperate your funds later.
{% endhint %}

#### ``:passport\_control:`Password /`:pushpin:`PIN`

These are used to prevent unwarranted access to your Wallet. Only you should know your Password/PIN, else someone else might be able to unlock your Wallet and steal your bitcoin.

{% hint style="info" %}
Passwords & PINs are for unlocking a wallet, like you would unlock your phone so that you can use it.
{% endhint %}

{% hint style="warning" %}
The term Password in Wasabi Wallet actually refers to a Passphrase! You must keep this information safe in case you need to recover your funds.
{% endhint %}

#### ``:mag:`Anti-phishing words`

This is a security measure implemented in the Coldcard hardware wallet. Two words are randomly generated based on the first part (prefix) of your PIN.&#x20;

They are for verifying that the Coldcard is safe for you to input the suffix (second part of your PIN) so you don't give away your entire PIN, should your Coldcard be compromised.

#### ``:coin:`Unspent Transaction Output (UTXO)`

A UTXO is like a piece of bitcoin. Bitcoin's do not exist per se, only the transaction history and ownership of these pieces are recorded in Bitcoin's open and distributed ledger.&#x20;

#### ``:currency\_exchange:`Change Address`

If the piece of bitcoin you send is greater than the amount the recipient is supposed to receive, a piece will be broken off and sent back to you in that same transaction. Your wallet might identify the addresses where you receive your change for better coin management.&#x20;

#### ``:money\_with\_wings:`Mining fee`

In order for your transaction to be processed, you must pay a fee to those doing the processing (miners). The higher the fee, the more likely your transaction is to be processed.&#x20;

The amount of fees to be paid depend on the amount of requests there are for transactions to be processed, as well as the amount of data that makes up your transaction.

{% hint style="info" %}
Fees do not depend on the quantity (in bitcoin or fiat) you are spending, but on the amount of data that is in that transaction.
{% endhint %}

#### ``:purse:`Coin Control`

This is the process of selecting a subset of UTXOs in your wallet for spending. This can help you save on fees, avoid receiving change and also improve your privacy.&#x20;

#### ``:shield:`CoinJoin`

This is a privacy-enhancing proceedure. It is the process through which the traceability of your UTXOs to your wallet is broken. UTXOs from multiple parties are pooled together, mixed and redistributed in equal amounts, thus breaking any heuristics used by those attempting to analyse transactions.

#### ``:pencil:`Bitcoin Improvement Proposal (BIP)`

These are formal proposals for changing code, fixing bugs or bringing efficiency improvements in Bitcoin.&#x20;

#### ``:notebook\_with\_decorative\_cover:`BIP-39`

It is the standardized way of creating a private key using words from a predetermined [list of 2048 words](https://github.com/bitcoin/bips/blob/master/bip-0039/english.txt). Most wallets today use this standard.

It also allows users to add an additional set of words or characters to their original seed (called Passphrase), thus producing a new, different seed.

#### ``:zap:`Seggregated Witness (SegWit)`

A successful soft-fork in 2017 has lead to the activation of SegWit. This update provides protection from transaction malleability, allows for better fee savings and is the foundational layer allowing for the Lightning Network to exist.

#### ``:bar\_chart:`Bech32`

Bech32 is an encoding scheme for the addresses used with SegWit. These addresses begin with `bc1`.

#### ``:guide\_dog:`BIP-84`

This defines the derivation path for wallets utilizing the SegWit implementation. The derivation path begins with `m/84’/`.

#### ``:evergreen\_tree:`Hierarchical Deterministic Wallets (BIP-32/BIP-44)` <a href="#hd-wallets-bip-32-bip-44" id="hd-wallets-bip-32-bip-44"></a>

A HD wallet generates multiple keys from a single private key, however, each one of those keys can also generate their own set of keys and so on to an infinite number of series. Your seed can generate a parent or master key, which can then generate child keys, which can then generate grandchild seeds and so on.

#### ``:book:`Open Source`

A project is open source when its code is publicly available and can be used and altered freely.

<!-- Output copied to clipboard! -->

<!-----
NEW: Check the "Suppress top comment" option to remove this info from the output.

Conversion time: 0.726 seconds.


Using this Markdown file:

1. Paste this output into your source file.
2. See the notes and action items below regarding this conversion run.
3. Check the rendered output (headings, lists, code blocks, tables) for proper
   formatting and use a linkchecker before you publish this page.

Conversion notes:

* Docs to Markdown version 1.0β30
* Sat Jul 03 2021 05:41:43 GMT-0700 (PDT)
* Source doc: Luxury Wallet
* Tables are currently converted to HTML tables.
----->



# 
# NFT Based Luxury Wallet Skins (DRAFT)


<table>
  <tr>
   <td><strong>Author</strong>
   </td>
   <td>Rogelio Morrell, Roberto Chockee
   </td>
  </tr>
  <tr>
   <td><strong>Category</strong>
   </td>
   <td>Skins, NFT, Luxury
   </td>
  </tr>
  <tr>
   <td><strong>Created</strong>
   </td>
   <td>2021-07-01
   </td>
  </tr>
</table>



##   Simple Summary

Branded or personalized digital wallet skin, using [ERC-721](https://eips.ethereum.org/EIPS/eip-721) NFT Protocol.


##  Abstract

We propose a special NFT Metadata Schema that has the style content to load a personalized skin that users can use in their wallet to brand their whole wallet experience.

This proposal also includes brands that can be visually verified, with metadata verification.


##  Motivation

Since Blockchain tech is going mainstream, and the NFT’s exploration of possibilities seems now endless..  Now, we could offer brands and push personalization that will be important as wallets will be part of our day to day activities. 

Also, Innovation on luxury brands will evolve outside their current niche and as Milton Pedraza, from the Luxury Institute, [has pointed out](https://www.linkedin.com/posts/milton-pedraza-1141272_shopping-for-high-end-brands-is-harder-than-activity-6816697734565793792-IGqX/) that “the brightest future of luxury is beyond fashion into a multitude of innovative luxury categories”.


##  Prior Art

Inspired by user-personalized skins on interfaces that have been used to brand and personalize user experiences.

[Winamp Skins](https://en.wikipedia.org/wiki/Winamp): Skins are bitmap files which alter the aesthetic design of the Winamp graphical user interface (GUI) and can add functionality with scripting. Winamp published documentation on skin creation in 1998 with the release of Winamp 2 and invited Winamp users to publish skins on Winamp.com. 


## 





## Specification


###  Container

The assets will be contained in a zip and it has 4 folders



* /js 
* /css
* /images
* /fonts

The root file is called



* index.json

### Universal Wallet Skin Guidelines


#### 
Three types of wallets that exist:

1. Blockchain Wallets
2. Verified Credential Wallets
3. NFT Wallets

####  Blockchain Wallets


index.json: Which contains the type of wallet that defines the following

use cases:



* Transfer Funds
* Create Wallet
* Import Wallet
* Confirmation Dialog
* Export Wallet
* TransactionLog

####  Verified Credential Wallets


TO-DO:

Needs to follow  presentation standard defined by the DIF.


####  NFT Wallets

index.json: Which contains the type of wallet that defines the following

use cases:



* Create Wallet
* Import Wallet
* Confirmation Dialog
* Export Wallet
* TransactionLog
* TransferNFT
* ViewMetadata

###  Universal Wallet Skin Implementation


Each wallet maker defines a series of slots, based on the [W3C Web Components Specification Slots Proposal](https://github.com/WICG/webcomponents/blob/gh-pages/proposals/Slots-Proposal.md) in this draft; each use case should define the slots where the skinnable content will be blinded.


### Skinable NFT Distribution

The **NFT Metadata URI** is self-describable, it contains the package with the definition of how to render the wallet skin, it also contains the license in JSON format with a digital signature of the owner or designer brand. Thus, not only this token will be signed by the publisher, it also has the certification that can be displayed as an about box (a verification that could be also displayed visually) similar to software licenses.


### Updates

This Specification also allow for skins to be updatable,  that can be done using technologies like IPNS which allows dynamic content ID’s to be updatable, or it can be customized in the smart contract of the NFT.


##  Test Cases


### Blockchain Wallets

For Blockchain-type wallet types, the following _Slots_ will exist for:


#### Transfer Funds:



* From/To Address
* Amount Slot
* Token Type Slot
* Transaction Cost Slot
* Transactions Settings Slot
* Logo/Brand Slot
* Buttons Slot
* Confirmation Slot


#### Create Wallet:

<span style="text-decoration:underline;">TO-DO</span>


#### Import Wallet:

<span style="text-decoration:underline;">TO-DO</span>


#### Confirmation Dialog:

<span style="text-decoration:underline;">TO-DO</span>


#### Export Wallet:

<span style="text-decoration:underline;">TO-DO</span>


#### Transaction Log:

<span style="text-decoration:underline;">TO-DO</span>


### Verified Credential Wallets

For Verified Credential Wallets types, the following _Slots_ will exist for:

<span style="text-decoration:underline;">TO-DO</span>


### NFT Wallets types

For NFT Wallets types, the following _Slots_ will exist for:

<span style="text-decoration:underline;">TO-DO</span>

 


##  Copyright

Copyright Industrias de Firmas Electrónicas, S.A. (IFESA) and Industrias DAO Blockchain. July 3rd, 2021.

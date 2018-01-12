 

Web3Keypass  
=======================================

### Simple Proof of Payment

Creating a Keypass is easy and has no extra fee. Just specify:
  * A Unique Name
  * A Quantity of Passes to Distribute
  * A Price for a Pass (in Ether)

Once you create a new Keypass, anyone with an Ethereum account can purchase a token from you which represents a proof of payment, like a receipt.  You will receive their payment in the Ethereum account you used to create the Keypass.  Then, any web services can check the user's token balance and grant or prevent access based on token ownership.  This just requires a connection to the Ethereum blockchain.

[Visit Web3Keypass.com](https://www.web3keypass.com)

Definitions Used
=======================================
For the purposes of this documentation:

 A 'keypass creator' is someone who defines a new keypass and sells 'keypass tokens' to other users for Ether.  

 A 'keypass user' is someone who purchases a keypass token from a 'keypass creator' so that they can experience additional access from the creator's web services (websites, apps, games, etc.)  

 A 'keypass service' is any web service controlled by a 'keypass creator' which asks a 'keypass user' to provide their Ethereum Public Address and then conditionally grants service based on ownership of a keypass token.  

 A 'keypass token' is a unique ERC721 Ethereum token that a user purchases from a creator and stores in their Ethereum account.

Web3Keypass is powered by the decentralized Ethereum database.  Keypass creators and users will need to have a free Ethereum Account.  They will also need to use Web3.js and an Ethereum-enabled browser extension such as Metamask.    

Usecases
========================================

Why would another user purchase a token of your Keypass? Here are some possible examples:

  * Your web server will allow users with your keypass token to access additional content on your website

  * Your web API will allow robots with your keypass token to access additional methods or allow access entirely

  * Your online game will allow players access if they hold your keypass token

  * Your service will stream music, video, or allow for download of digital art content if the user holds your keypass token


Keypass tokens are held by users in their Ethereum account.  


Keypass Tools
========================================
 
A library of NodeJS tools allows keypass creators to easily turn their web service, online game, or web app into a 'keypassed service'.  This means that the server will ask users for their Ethereum Account Public Address, will check to see if that account holds the right 'keypass token', and will grant additional access if so.  This allows the content creator to very easily be paid by users of the service, without using a centralized service such as PayPal or Credit Cards

When a user logs in to a 'keypass-enabled service', they will provide their Ethereum Public Address.  Typically this is done using Metamask.  The service then asks the Ethereum network whether or not this user's account holds a token.  If it does, the server will grant the user access.  Otherwise, it will not.  
 
Web3Keypass is 100% free.  The only costs are Ethereum gas prices.  

Access is Owned by Users
========================================
Web3Keypass tokens held by users can be traded, bought, and sold among other users.  Every token has a unique ID which can be read by 'keypassed services'.  

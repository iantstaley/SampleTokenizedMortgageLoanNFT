# SampleTokenizedMortgageLoanNFT
An example Solidity smart contract code that can be used to tokenize a mortgage loan as an NFT on the Ethereum network
This smart contract extends the ERC721 contract from the OpenZeppelin library, which is used for creating non-fungible tokens (NFTs) on the Ethereum network.

The MortgageLoanNFT contract defines a MortgageLoan struct that contains the details of the mortgage loan, such as its value, interest rate, duration, and borrower address. The createMortgageLoanNFT function is used to mint a new NFT and store the corresponding mortgage loan details in the _mortgageLoans mapping.

The getMortgageLoan function is used to retrieve the mortgage loan details associated with a given token ID.

Note that this is just an example and you may need to modify the code to suit your specific requirements. You would also need to compile and deploy the contract on the Ethereum network using tools such as Remix or Truffle.

# (Aave x Mstable) Loan Pool
===========================
 <img src="https://github.com/Developer-piyush/Aave_X_Mstable/blob/main/src/assets/logo.png" height="150" width="300">
 <img src="https://github.com/Developer-piyush/Aave_X_Mstable/blob/main/src/assets/10.png" height="" width="">
 ![pic](https://github.com/Developer-piyush/Aave_X_Mstable/blob/main/src/assets/10.png)
 
=> A project that uses a factory contract to spawn new loan pools. 
=> It combines a browser-based frontend with the ethereum smart contract using web3.js. 

*Anyone can create the pool using the form on the application. 
*During the creation of the pool, the pool creator needs to fill in the necessary details and, need to choose the lending pool between Aave & Mstable. 
*Based on the choice, a new smart contract will get generated using the factory contract. The details of the pool will get stored on the graph using the-graph SDK. 
*The participants will be able to join any pool available to participate from the frontend. They need to deposit the collateral amount and, the collateral will generate a yield from the lending platforms (Aave or Mstable). 

*The loan auction will start once at least 2 participants will join the pool. 
*During the auction, the participant can bid the amount to win the loan if they want. 
*The number of the auction will depend upon the total number of participants in the pool. 
*The highest bidder will be able to claim the loan, once the auction period will be over. 
*The loan amount will be equal to the loan amount - bid amount (the loan amount is also equal to the collateral deposited at the beginning). 
*The bid amount will remain stored on the lending pool and it will get distributed among all the participants with yield generated from lending pools after all auctions. 

# The advantage of this approach is that the last participant gets the loan interest free and on top of that earns interest on the collateral. The interest paid by other borrowers is used to earn an additional interest which is also distributed among all the participants.



Running Project Locally
=======================

1. git clone https://github.com/Developer-piyush/Aave_X_Mstable
2. cd Aave_X_Mstable
3. Install dependencies: `yarn install`
4. npm install web3
5. Run the local development server: `yarn start` 

starts at (http://localhost:3000)

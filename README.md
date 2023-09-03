Try running some of the following tasks:

Check out the testing script. I have used loadfixture which is the recommended way. Also I have used ethers V6. Can be helpful

I  hard coded  MINIMUM_USD to 50;

feel free to make changes.


npx hardhat help
npx hardhat test
REPORT_GAS=true npx hardhat test
npx hardhat node
npx hardhat run scripts/deploy.js


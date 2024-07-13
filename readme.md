truffle init in root folder

contracts,migrations and test

contracts and migrations are solidity whereas test is js

open 2 terminals of cmd and not ps and run ganche in one terminal(cmd)

write solidity program in Helloworld.sol

compile it using the command truffle compile in non ganache

after compilation a build folder is established and succumbs contracts folder

create a js file in migrations

later in truffle-config.js uncomment the development in module.exports of networks

now run " truffle migrate --network development" leading to simoultaneous updates in ganache terminal

then " truffle console "

now interact with contract


and do  modifications 
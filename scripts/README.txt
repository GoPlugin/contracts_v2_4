Steps to Compile all contracts

1. Setup network section in hardhat.config file
     networks: {
    apothem: {
      url: 'https://publicnexus.xdcchain.xyz/apothem-rpc',
      accounts: ['private key'],
    },
2. Rename contractsv3_temporary folder to contracts

3. execute the file "native_solc_compile_all" in scripts directory
  ./native_solc_compile_all
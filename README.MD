# CANADE Network Information [TestNET]

## Overview
The CANADE network is a Symbol-based blockchain that enables on-chain traceability and verification of crops and processed products. 

It is used to protect consumers from counterfeiting, imitation, and misrepresentation of origin, ensuring safety and security.

## Information

### Base Mosaic
- canade.cbdp

### Related Services

- [Explorer](https://explorer.test.siamreiwa.com/)
- [Faucet](https://faucet.test.siamreiwa.com/)
- [Wallet](https://wallet.test.siamreiwa.com/)
- [Node list](https://explorer.test.siamreiwa.com/nodes)

*Permission to use the Symbol logo is granted by the core developer only for the test network.

### Running a Node

```bash
# Download the node configuration file to the server
wget https://raw.githubusercontent.com/siamreiwa/canade-cbdp-community-test/main/preset/custom-preset.tar.gz

# Extract the compressed file
tar -xvf custom-preset.tar.gz

# Edit the my-preset.yml file as necessary, similar to the Symbol node

# Start the node with the following command:
symbol-bootstrap start -p custom-network-preset.yml -a dual -c custom-preset.yml -d

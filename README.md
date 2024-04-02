### Install Subnet

- **Running locally**: Follow the step-by-step instructions described in this section: [Running Subnet Locally](./docs/running_on_staging.md).

### Run the subnet miner and subnet validator. Make sure to specify your subnet parameters.

Run the subnet miner:

### 1. Create miner configuration to run: <br>
Script Path: /Path/to/neurons/miner.py <br>
Parameters:--netuid 1 --subtensor.chain_endpoint ws://127.0.0.1:9946 --wallet.name miner --wallet.hotkey default --logging.debug


Run the subnet validator:
### 2. Create validator configuration to run: <br>
Script Path: /Path/to/neurons/validator.py <br>
Parameters: --netuid 1 --subtensor.chain_endpoint ws://127.0.0.1:9946 --wallet.name validator --wallet.hotkey default --logging.debug


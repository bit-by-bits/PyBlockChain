# PyBlockChain

This is a simple implementation of a blockchain in Python, called PyBlockChain.. It provides a basic framework for creating a blockchain and adding new transactions to it. The code uses proof-of-work to validate new blocks and ensures that each block is linked to the previous block in the chain.

## Features

- Simple and easy-to-use Python code
- Proof-of-work validation for new blocks
- Transactions can be added to the blockchain
- Each block is linked to the previous block in the chain

## Getting Started

To get started with this blockchain, clone this repository to your local machine:

```shell
$ git clone https://github.com/your-username/PyBlockChain.git
```

### Prerequisites

This project requires Python 3.6 or higher.

### Usage

To start the blockchain, run the `pyblockchain.py` script:

```shell
$ python pyblockchain.py
```

This will start the blockchain on your local machine.

You can add new transactions to the blockchain using the `new_transaction` method of the `Blockchain` class:

```python
blockchain.new_transaction(sender='Alice', recipient='Bob', amount=2)
```

To mine a new block and add it to the blockchain, you can use the mine method:

```python
blockchain.mine()
```

## Contributing
Contributions to this project are welcome. To contribute, please fork this repository, make your changes, and submit a pull request.

## License
This project is licensed under the MIT License. See the LICENSE.md file for details.

## Acknowledgments
This project was inspired by Daniel van Flymen's article on building a blockchain from scratch.

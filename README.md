# 🌐 EnumRust: Subdomain Enumerator and Simple Crawler

![GitHub release](https://img.shields.io/github/release/D3435/enumrust.svg)

Welcome to **EnumRust**, a powerful tool designed for subdomain enumeration and simple web crawling. This repository provides users with a straightforward way to discover subdomains and crawl websites efficiently. Whether you're a security researcher, developer, or hobbyist, EnumRust can help you gather valuable information about web domains.

## Table of Contents

- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Examples](#examples)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

## Features

- **Subdomain Enumeration**: Quickly discover subdomains associated with a given domain.
- **Simple Crawling**: Navigate through web pages to gather information.
- **Easy to Use**: Designed with a user-friendly interface.
- **Fast and Efficient**: Built for speed and performance.

## Installation

To get started with EnumRust, you need to download the latest release. You can find the releases [here](https://github.com/D3435/enumrust/releases). Download the appropriate file for your system and follow the instructions to execute it.

### Prerequisites

Before you begin, ensure you have the following installed:

- Rust programming language
- Cargo package manager

If you don't have Rust installed, you can find instructions on the [official Rust website](https://www.rust-lang.org/tools/install).

### Steps to Install

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/D3435/enumrust.git
   cd enumrust
   ```

2. **Build the Project**:
   ```bash
   cargo build --release
   ```

3. **Run the Tool**:
   ```bash
   ./target/release/enumrust
   ```

## Usage

EnumRust is simple to use. After installation, you can run the tool with various options to customize its behavior. Here are some common commands:

### Basic Command

To enumerate subdomains for a specific domain, use the following command:

```bash
./target/release/enumrust -d example.com
```

### Options

- `-d, --domain <domain>`: Specify the target domain.
- `-o, --output <file>`: Save the results to a file.
- `-h, --help`: Display help information.

### Example Command

To enumerate subdomains and save the results:

```bash
./target/release/enumrust -d example.com -o results.txt
```

## Examples

Here are some examples of how to use EnumRust effectively:

### Example 1: Basic Subdomain Enumeration

```bash
./target/release/enumrust -d github.com
```

This command will list all discovered subdomains for `github.com`.

### Example 2: Save Output to File

```bash
./target/release/enumrust -d google.com -o google_subdomains.txt
```

This command saves the subdomains of `google.com` to a file named `google_subdomains.txt`.

### Example 3: Help Command

If you need help, simply run:

```bash
./target/release/enumrust -h
```

This will display all available options and their usage.

## Contributing

We welcome contributions to EnumRust! If you'd like to contribute, please follow these steps:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature-branch`).
3. Make your changes.
4. Commit your changes (`git commit -m 'Add new feature'`).
5. Push to the branch (`git push origin feature-branch`).
6. Open a pull request.

Please ensure your code adheres to our coding standards and includes appropriate tests.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Contact

For questions or feedback, please reach out via the GitHub issues page or contact the repository owner.

To download the latest release, visit [here](https://github.com/D3435/enumrust/releases). Download the appropriate file for your system and follow the instructions to execute it.

## Conclusion

EnumRust provides a robust solution for subdomain enumeration and web crawling. Its simple interface and powerful features make it an essential tool for developers and security professionals. We encourage you to explore the tool, contribute, and provide feedback.

Thank you for using EnumRust!
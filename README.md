
# Mojeed Token (MJDT) on Aleo

A privacy-focused token implementation built on the Aleo blockchain platform.

## Deployment Information

- **Program Name:** `mojeed_token.aleo`
- **Deployment ID:** `at18wvfqcrtfggfar078vpjce2gd6ywg3nzsm0p7kc24fwhd0p2q5zsyukpl4`
- **Transaction ID:** `at1n3hjzee079gknjad9hzwq0m6grzzy8sguu9hu20za3lhsxpt2v9sat5l4r`
- **Repository:** [GitHub](https://github.com/mojeed-painless/mjd_private-token-workshop-token-template)

## Features

- Private token transfers
- OFAC compliance integration
- Zero-knowledge proof implementation
- Secure balance management

## Project Structure

```
├── build/
│   ├── main.aleo
│   ├── program.json
│   └── imports/
│       └── workshop_ofac.aleo
├── src/
│   └── main.leo
└── tests/
    └── test_token.leo
```

## Getting Started

### Prerequisites

- Aleo SDK
- Leo Programming Language
- Node.js (for development tools)

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/mojeed-painless/mjd_private-token-workshop-token-template.git
   cd mjd_private-token-workshop-token-template
   ```

2. Build the program:
   ```bash
   leo build
   ```

3. Run tests:
   ```bash
   leo test
   ```

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Contact

- Developer: Mojeed
- GitHub: [@mojeed-painless](https://github.com/mojeed-painless)

## Acknowledgments

- Aleo Team for the blockchain platform
- Contributors to the privacy token workshop

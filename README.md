# Command-Line-IP-range-Search
Scans a /24 IPv4 subnet by iterating the final octet to identify active hosts. Designed for modular integration and future expansion into port scanning and device identification. Intended for authorized network diagnostics and testing.
# Remote IP Mapping Tool (C++)

## Overview

The Remote IP Mapping Tool is a modular C++ application designed to perform network discovery across IPv4 subnets. The current implementation focuses on scanning a /24 subnet by iterating through the final octet (e.g., `192.168.1.0/24`) to identify active hosts.

This project is being developed as a lightweight, extensible network utility that can be integrated into larger systems, including automation platforms, embedded environments, and diagnostic toolchains.

---

## Scope

This application performs host discovery by scanning all possible addresses within the final octet of a target IPv4 subnet.

Planned enhancements include:

* Port scanning and service interrogation
* Device identification and classification
* Expanded subnet support beyond /24
* Integration with logging and reporting systems

This tool is intended for **authorized network diagnostics, testing, and educational use only**.

---

## Features

* IPv4 /24 subnet scanning
* Command-line interface with user input handling
* Structured output of discovered hosts
* Modular architecture for future expansion
* Designed for cross-platform compatibility

---

## Example Usage

```bash
# Run with default network
./fast_scanner

# Run with specified network
./fast_scanner 192.168.1.0
```

---

## Architecture

The system is designed using object-oriented principles to support scalability and integration into larger applications.

Core components include:

* **Network Scanner** – Handles IP iteration and host discovery
* **IP Address Module** – Manages parsing and formatting of IPv4 addresses
* **Console Interface** – Handles user interaction and output

This modular design allows individual components to be reused or extended independently.

---

## Roadmap

This project is actively under development. Future versions will include:

* Multi-threaded scanning for improved performance
* Windows GUI interface
* macOS UX/UI interface
* Linux graphical implementation
* Advanced network interrogation capabilities
* Integration with external systems and APIs

---

## Technologies Used

* C++
* Standard Library / System Networking APIs
* Cross-platform design principles

---

## Installation

```bash
# Clone the repository
git clone https://github.com/yourusername/remote-ip-mapper.git

# Navigate to project directory
cd remote-ip-mapper

# Build (example using g++)
g++ -o fast_scanner src/main.cpp

# Run
./fast_scanner
```

---

## License

This project is licensed under the MIT License. See the LICENSE file for details.

---

## Author

Nathan Gerwig
Code Alias: GrumpyGrayBeard

---

## Notes

This project is a work in progress and will continue to evolve with additional features, performance improvements, and platform-specific interfaces. Contributions, feedback, and collaboration are welcome.

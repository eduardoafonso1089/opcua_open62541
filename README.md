# OPC UA Examples with open62541

Welcome to the `opcua_examples` repository! This repository provides a collection of examples using the open62541 library to help developers implement OPC UA solutions. The goal is to offer a variety of examples that can serve as a foundation for your own implementations.

## Table of Contents

- [Introduction](#introduction)
- [Repository Structure](#repository-structure)
- [Installation](#installation)
- [Usage](#usage)
- [Examples](#examples)
- [Contribution](#contribution)
- [License](#license)

## Introduction

OPC UA (Open Platform Communications Unified Architecture) is a machine-to-machine communication protocol for industrial automation developed by the OPC Foundation. The open62541 library is an open-source implementation of OPC UA, written in C. This repository provides practical examples to demonstrate how to use the open62541 library for various OPC UA use cases.

## Repository Structure

The repository is organized as follows:

```

/opcua_examples
|-- /examples
| |-- basic_server.c
| |-- basic_client.c
| |-- data_access_server.c
| |-- data_access_client.c
| |-- event_server.c
| |-- event_client.c
|-- .gitignore
|-- LICENSE
|-- README.md
```


- **/examples**: Contains example source files demonstrating different OPC UA functionalities.
- **.gitignore**: Specifies files and directories to be ignored by git.
- **LICENSE**: The license under which the repository is distributed.
- **README.md**: The file you are currently reading.

## Installation

To compile and run the examples, you need to have the open62541 library installed on your system. Follow these steps to install the library and set up the repository:

1. **Clone the repository**:

   ```
   sh
   git clone https://github.com/yourusername/opcua_examples.git
   cd opcua_examples
   ```

2. **Install the open62541 library**:

Follow the installation instructions from the open62541 GitHub repository.

3. **Compile the examples**:

You can use the provided Makefile to compile the examples. Run the following command in the root directory of the repository:
```
make
```
## Usage
After compiling the examples, you can run them from the command line. Here are some usage examples:

1. Running the basic server:

```
./basic_server
```

2. Running the basic client:
```
./basic_client
```

For detailed instructions on running each example, refer to the comments in the source files located in the /examples directory.

## Examples

### Basic Server and Client

basic_server.c: A simple OPC UA server that provides a basic set of services.
basic_client.c: A client that connects to the basic server and performs basic operations.

### Data Access

data_access_server.c: A server that supports data access services.
data_access_client.c: A client that reads and writes data from/to the data access server.

### Events

event_server.c: A server that generates events.
event_client.c: A client that subscribes to and processes events from the event server.

## Contribution

Contributions are welcome! If you have any examples you would like to add or improvements to the existing ones, feel free to open issues and submit pull requests. To contribute:

- Fork the repository.
- Create a branch for your feature (git checkout -b feature/MyFeature).
- Commit your changes (git commit -m 'Add MyFeature').
- Push to the branch (git push origin feature/MyFeature).
- Open a Pull Request.

## License
This project is licensed under the MIT License - see the LICENSE file for details.


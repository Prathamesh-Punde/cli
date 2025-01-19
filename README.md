# Counter CLI

## Overview
Counter CLI is a simple command-line tool for performing file-based tasks, such as counting the number of lines in a file. It is built using Node.js and leverages the `commander` library for command-line interface functionality.

## Features
- Count the number of lines in a file.

## Prerequisites
- Node.js (version 12 or higher)
- npm (Node Package Manager)

## Installation
1. Clone the repository or download the source code.
2. Navigate to the project directory in your terminal.
3. Install the dependencies by running:
   ```bash
   npm install
## Usage
1. Navigate to the project directory in your terminal.
2. Run the program with the following syntax:
'''bash
node index.js count <file>
Replace <file> with the path to the file you want to count lines for.
# Example
To count the lines in a file named example.txt:

bash'''
node index.js count a.txt
Output:

bash'''
There are 3 lines in a.txt

# Dependencies
[commander](https://www.npmjs.com/package/commander): For creating the CLI interface.

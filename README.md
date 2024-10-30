# FQDN and IP Address Processor

This repository contains a Bash script that processes text files containing Fully Qualified Domain Names (FQDNs) and IP addresses from Amass output file.

Sometimes, the output from Amass can be hard to use as a list for input to other tools, as it may contain ANSI codes and duplicate entries. This script removes those ANSI codes, extracts unique FQDNs and IP addresses from the input, and formats the output in a clean manner.


## Features

- **Remove ANSI Codes:** Strips out any ANSI escape codes from the input text.
- **Extract FQDNs and IP Addresses:** Processes the input file to extract relevant FQDNs and IP addresses.
- **Unique Lines:** Ensures that the output only contains unique lines, eliminating duplicates.

## Usage

### Prerequisites

Make sure you have Bash and `awk` installed on your system.

### Script Execution

1. Clone the repository:

   ```bash
   git clone https://github.com/jadu101/your-repo-name.git
   cd your-repo-name

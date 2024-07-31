# havamal

# Hávamál Quote Generator

This repository contains a Bash script for randomly selecting and displaying quotes from the Hávamál, a collection of Old Norse poems.

## Overview

The `havamal` script randomly selects a quote from a text file containing Hávamál verses. The script supports multiple languages (currently only English) and can be easily integrated into your `.bashrc` file for automatic quote display in your terminal.

## Features

- **Random Quote Selection**: Get a different Hávamál quote each time you run the script.
- **Language Support**: Easily switch between supported languages by modifying a single variable (currently only English is available).
- **Simple Integration**: Can be added to your `.bashrc` for automatic execution in your terminal.

## Setup

1. **Clone the Repository**

   ```bash
   git clone https://github.com/nirucon/havamal
   cd havamal
   ```

2. **Prepare Your Environment**

   Create a directory for your Hávamál files:

   ```bash
   mkdir -p ~/.config/havamal
   ```

   Place your Hávamál text file (`havamal-eng.txt`) into this directory. Ensure it is formatted with each verse starting with a number followed by a period.

3. **Configure the Script**

   Edit the `havamal` script to set your preferred language:

   ```bash
   LANGUAGE="eng"
   ```

4. **Add to `.bashrc`**

   Add the following line to your `.bashrc` to execute the script on terminal startup:

   ```bash
   ~/.config/havamal/havamal.sh
   ```
   My .bashrc https://github.com/nirucon/nirucon-suckless-arch

5. **Run the Script**

   Execute the script manually or restart your terminal to see a random Hávamál quote displayed with the prefix `Hávamál: `.

## Usage

Simply run the script to get a random quote:

```bash
~/.config/havamal/havamal
```

## License

Feel free to do what you want, buy me sparkling water if you want ;)

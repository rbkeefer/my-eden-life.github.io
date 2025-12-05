# My Eden Life Registration

A GitHub Pages website that allows users to enter a serial number and generates a 6-digit registration code based on the SHA-256 hash of that serial number.

## Features

- Clean, responsive web interface
- SHA-256 hash calculation using browser's built-in Web Crypto API
- Extracts the last 6 digits from the hash for display
- Input validation and error handling
- Enter key support for quick submission

## How it works

1. User enters a serial number in the text input
2. The application calculates the SHA-256 hash of the serial number
3. Extracts numeric digits from the hash and displays the last 6 digits
4. If insufficient digits are available, it converts part of the hash to a number and uses modulo operation to ensure 6 digits

## Usage

Visit the deployed GitHub Pages site and enter your device's serial number to get the 6-digit registration code.

## Technical Details

- Built with vanilla HTML, CSS, and JavaScript
- Uses Web Crypto API for secure hash calculation
- No external dependencies
- Compatible with all modern browsers

# Braille-Translator

## Overview
The **Braille-Translator** is a Python-based tool that seamlessly translates between Braille and English on the same input line. Unlike many translation tools, this program intelligently detects whether the input is Braille or English, eliminating the need for users to manually specify the input type. This makes it efficient, easy to use, and accessible for all types of users.

## Features
- **Automatic Detection**: The program distinguishes whether the input is Braille or English without requiring user selection, allowing for a more streamlined experience.
- **Bi-directional Translation**: Supports translation from Braille to English and from English to Braille within a single line of input.
- **Support for Letters and Numbers**: Translates both alphabetic characters and numeric digits. It also supports capitalization and number mode in Braille for accurate representation.
- **Error Handling**: Designed to handle invalid or unexpected inputs gracefully, ensuring a smooth user experience.

## How It Works
The program uses dictionaries to map characters between Braille and English. It reads the input, determines whether it is Braille or English based on the format, and then translates accordingly. If Braille input is detected, it converts it to English; if English is detected, it converts it to Braille. The user can input any combination of Braille and English, and the program will automatically handle it.

## Usage
To run the translator, use the following command:

```bash
python3 braille_translator.py <input>

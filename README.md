# LogoSyntaxAnalyzer

## Overview

LogoSyntaxAnalyzer is a syntax analyzer for the Logo programming language. It is designed to parse and validate Logo source code, helping users identify syntax errors and understand the structure of Logo programs.

## Features

- Parses Logo language constructs
- Reports syntax errors with descriptive messages
- Supports basic Logo commands and control structures
- Modular and extensible design for future enhancements

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/LogoSyntaxAnalyzer.git
   ```
2. Navigate to the project directory:
   ```bash
   cd LogoSyntaxAnalyzer
   ```
3. Follow the setup instructions in the `INSTALL.md` or run the provided setup script.

## Usage

To analyze a Logo source file, run:

```bash
python main.py path/to/source.logo
```

Replace `path/to/source.logo` with your Logo file.

## Project Structure

- `main.py` - Entry point for the analyzer
- `lexer/` - Lexical analysis components
- `parser/` - Syntax analysis components
- `tests/` - Unit tests and example Logo files

README file developed with Github Copilot.

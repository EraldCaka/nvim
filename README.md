# Neovim Configuration Package Installation

Neovim Configuration Package for better Go Development

## Installation

```bash
git clone https://github.com/EraldCaka/nvim.git %USERPROFILE%\AppData\Local\nvim --depth 1 && nvim
```

1. **goimports-reviser/v3**:

   - Description: A tool to automatically add, remove, or adjust Go imports.
   - Installation:
     ```bash
     go install github.com/incu6us/goimports-reviser/v3@latest
     ```

2. **gofumpt**:

   - Description: A formatter for Go code that integrates with your editor.
   - Installation:
     ```bash
     go install mvdan.cc/gofumpt@latest
     ```

3. **golines**:
   - Description: A tool to clean up and format Go source code.
   - Installation:
     ```bash
     go install github.com/segmentio/golines@latest
     ```

Make sure you have Go installed and configured on your system before executing the installation commands. These packages will help you maintain clean and organized Go code within Neovim.

**Note**: Ensure that the Go binaries are added to your system's PATH after installation so that Neovim can access them properly.

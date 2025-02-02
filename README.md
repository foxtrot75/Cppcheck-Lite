# Cppcheck Lite

**Cppcheck Lite** is a minimalistic Visual Studio Code extension that runs [cppcheck](https://cppcheck.sourceforge.net/) against C/C++ files upon save and reports any warnings or errors in the Problems panel.

## Features

- **On-save linting**: When you save a c/cpp file, `cppcheck` is automatically run on that file.
- **Per-file diagnostics**: Only diagnostics relevant to the saved file are displayed.
- **Configurable severity threshold**: Filter out messages below a chosen severity level (`info`, `warning`, or `error`).
- **Set C/C++ standard**: Easily specify `--std=<id>` (e.g. `c++17`, `c99`, etc.).
- **Diagnostic cleanup**: When you close a file, its diagnostics are automatically cleared.

## Requirements

- **cppcheck** must be installed and available on your system's PATH.
  - On Linux (Debian/Ubuntu), install via `sudo apt-get install cppcheck`.
  - On macOS with Homebrew: `brew install cppcheck`.
  - On Windows, install from [cppcheck's website](https://cppcheck.sourceforge.net/), and ensure the binary is on your PATH.

## Extension Settings

This extension contributes the following settings under `cppcheck.*`:

- **`cppcheck-lite.enable`**: (boolean) Enable or disable the extension.  
- **`cppcheck-lite.arguments`**: (string) Additional [command line arguments](https://cppcheck.sourceforge.io/manual.pdf?#page=5) to pass to `cppcheck`.  
- **`cppcheck-lite.minSeverity`**: (string) Minimum severity to report (`info`, `warning`, or `error`).  `info` shows style, performance, portability and information messages.
- **`cppcheck-lite.standard`**: (string) Sets the C/C++ standard with `--std=<id>` (e.g. `c11`, `c++17`).

## Reporting Issues
Please submit any issues or feature requests via the [GitHub Issues page](https://github.com/JustusRijke/Cppcheck-Lite/issues).

---

**Enjoy using Cppcheck Lite!**

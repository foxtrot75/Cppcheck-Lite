# Change Log

## [1.3.2] - 2025-07-14
- Added `cppcheck-lite.project` setting to specify passing file path to `cppcheck` when work with project.

## [1.3.1] - 2025-07-11
- Fix bug with negative column number in range vscode ([#2](https://github.com/JustusRijke/Cppcheck-Lite/pull/2))

## [1.3.0] - 2025-05-28
- Added <none> option to `cppcheck-lite.standard`, allowing users to specify it manually via `cppcheck-lite.arguments` or let `cppcheck` use its default setting.
- Improved Windows compatibility by quoting paths and normalizing backslashes in executable and file paths.

## [1.2.1] - 2025-02-08
- **FIX** Ignore background file openings (e.g., during symbol renaming) to prevent unnecessary Cppcheck runs and clutter in the Problems tab.

## [1.2.0] - 2025-02-02
- Added `cppcheck-lite.path` setting to specify a custom path to the `cppcheck` executable.
- Improved error handling to display a message if `cppcheck` is not found or cannot be run.

## [1.1.0] - 2025-02-02
- Added "Code" field showing the applied C/C++ standard to items in the Problems panel.
- Enabled cppcheck execution when opening a new file.
- Ensured cppcheck runs for all open files when a workspace is opened.

## [1.0.0] - 2025-02-02
Initial release

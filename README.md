# Sola Compiler
Version 1.0.0.3 Alpha (Revision 3)

Welcome to the Sola Compiler! This application is designed to compile and execute scripts written in the Sola programming language. 
Please note, this project is still in development and all features are subject to change pending future updates.


# What's new?

Aesthetic:
- Added line and source information to build and warning logs.
- Defaulted console, debug, and log commands to simplify development.
- Designated MacOS, Window, and Platform-Independent versions with version information, and icons.
- Updated Console settings with optional toggles for line and source control.
- Updated application package icon.

Functional:
- Alpha version of Air (Automatic Interface Rendering) GUI langauge for interface compilation.
- Added additional commands for intercting with the console, such as toggling it's visibility.
- Split Salt (Sola Application Language Translator) shell language for application-level scripting.
- Implemented Sea (Sola Embedded Annotation) markup language for comment-based documentation.
- Included a new example project 'Deploy.sola' that launches a blank stand-alone window.

Bug Fixes:
- 'file.create()' now verifies a file does not already exist to avoid overwriting by default.
- 'file.overwrite()' explicity deletes and overwrites specified filepaths.

Environment:
- Added debugging for deployment testing.
- Reconfigured Sola application framework to be console independent.


# What's next?

Aesthetic:
- Consolidated log menu for easier output switching.
- Built-in execute, recompile and suspend buttons.
- Native file system visual-navigation support.
- Ouput logs organized by filters.

Functional:
- Salt-based debugging breakpoints.

Environment:
- Expanded Air functionality for enhanced user-interface development.
- Implement functionality to open '.sola' files with the compiler by default, making them executable.


Please visit www.solalabs.github.io for more information.

Forked from https://github.com/ivalexa/vscode-angular2-files

This extension is for the purpose of providing a common interface for everyone to create components, services, modules, pipes etc.
Most of the edits/updates are based on our particular requirements.
1. Removed Testbed from default templates
2. Reordered default imports to pass linting
3. Made it not produce a style sheet for components, or add a style prop to the components
For more information see the original repository.

## Installation

1. Install Visual Studio Code 1.5.0 or higher
2. Clone This Repository
3. Open Terminal on repository folder
4. npm install -g vsce
5. vsce package (it will give you a file path)
6. code --install-extension {fileName}
7. Restart Code

# Disclaimer

**Important:** This extension due to the nature of it's purpose will create
files on your hard drive and if necessary create the respective folder structure.
While it should not override any files during this process, I'm not giving any guarantees
or take any responsibility in case of lost data. 

# License

MIT

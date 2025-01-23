# Setup Instructions for MacOS users

Hey Devslopes Student!

Welcome to the first step in the Devslopes Web Academy, where you will set up your computer for this exciting learning journey. Please ensure that you complete each installation in the specified order.

These instructions have been tested on various types of machines, but there may be instances where things don't work exactly as expected. Make sure to carefully read the descriptive terminal messages and, if needed, repeat the previous step. If the issue persists,there is a question asking template that we require you to use to get the best and most accurate answer from the mentors. This template can be added to the all-questions. It can be found [here](https://github.com/devslopes/dwa-orientation-curriculum/blob/master/how-to-get-setup-help/Software-setup-all-questions-template.md)

Note: Remember to press "enter" after copying and pasting the command into the terminal to run it.

## Table of contents

Here is a list of software you should have installed and configured before you begin the program to optimize your learning experience with Devslopes:

- [Setup Instructions for MacOS users](#setup-instructions-for-macos-users)
  - [Table of contents](#table-of-contents)
  - [System Requirements](#system-requirements)
  - [Homebrew](#homebrew)
    - [Instructions to install Homebrew](#instructions-to-install-homebrew)
    - [Test your Homebrew installation](#test-your-homebrew-installation)
  - [Google Chrome Browser](#google-chrome-browser)
    - [Instructions to install Google Chrome Browser with Homebrew](#instructions-to-install-google-chrome-browser-with-homebrew)
  - [Discord](#discord)
    - [Instructions to install Discord with Homebrew](#instructions-to-install-discord-with-homebrew)
  - [Zoom](#zoom)
    - [Instructions to install Zoom with Homebrew](#instructions-to-install-zoom-with-homebrew)
  - [Loom](#loom)
    - [Instructions to install Loom with Homebrew](#instructions-to-install-loom-with-homebrew)
  - [VSCode IDE](#vscode-ide)
    - [Instructions to install VSCode IDE with Homebrew](#instructions-to-install-vscode-ide-with-homebrew)
  - [Z Shell (ZSH)](#z-shell-zsh)
    - [Get Started with ZSH](#get-started-with-zsh)
    - [Instructions to check if ZSH is installed and set as the default shell](#instructions-to-check-if-zsh-is-installed-and-set-as-the-default-shell)
      - [Options to proceed](#options-to-proceed)
    - [Instructions to switch the default shell to ZSH if the default shell is BASH](#instructions-to-switch-the-default-shell-to-zsh-if-the-default-shell-is-bash)
    - [Instructions to install Z Shell (ZSH)](#instructions-to-install-z-shell-zsh)
  - [Oh My Zsh (OMZ)](#oh-my-zsh-omz)
    - [Instructions to install Oh My Zsh (OMZ)](#instructions-to-install-oh-my-zsh-omz)
  - [Node Version Manager (NVM)](#node-version-manager-nvm)
    - [Instructions to install Node Version Manager (NVM)](#instructions-to-install-node-version-manager-nvm)
    - [Test your Node Version Manager Installation](#test-your-node-version-manager-installation)
  - [Node.js](#nodejs)
    - [Instructions to install Node.js with NVM](#instructions-to-install-nodejs-with-nvm)
      - [Test your Node.js installation](#test-your-nodejs-installation)
  - [Node Package Manager (NPM)](#node-package-manager-npm)
    - [Test your NPM installation](#test-your-npm-installation)
  - [GIT](#git)
    - [Instructions to configure GIT](#instructions-to-configure-git)
    - [Instructions to update GIT to the latest version](#instructions-to-update-git-to-the-latest-version)
      - [Test your GIT installation](#test-your-git-installation)
    - [Instructions to set the SSH key for GITHUB](#instructions-to-set-the-ssh-key-for-github)
      - [Test your SSH connection to Github](#test-your-ssh-connection-to-github)
  - [Setup VSCode (Optional)](#setup-vscode-optional)
    - [Instructions to set the tab default size to 2 spaces](#instructions-to-set-the-tab-default-size-to-2-spaces)
    - [Instructions to install the Live Server extension in VSCode](#instructions-to-install-the-live-server-extension-in-vscode)
    - [Instructions to install the Prettier extension in VSCode](#instructions-to-install-the-prettier-extension-in-vscode)
    - [Instructions to make Prettier your default code formatting tool](#instructions-to-make-prettier-your-default-code-formatting-tool)
    - [Instructions for automatically formatting code when saving a file](#instructions-for-automatically-formatting-code-when-saving-a-file)
    - [Instructions to install the "Indent-rainbow" extension in VSCode](#instructions-to-install-the-indent-rainbow-extension-in-vscode)
    - [Instructions to install the "Auto close tag" extension in VSCode](#instructions-to-install-the-auto-close-tag-extension-in-vscode)
    - [Instructions to install the "Auto rename tag" extension in VSCode](#instructions-to-install-the-auto-rename-tag-extension-in-vscode)

## System Requirements

MacOS v12 (Monterey) or a higher version is required to successfully complete all the computer setup instructions for MacOS users.

1. Launch the MacOS Terminal application.
2. Run the command `sw_vers`.
3. Make sure the output includes the ProductVersion of 12.XX.XX or higher.

## Homebrew

Homebrew is a package manager for macOS that allows users to easily install, update, and manage software packages and dependencies from the command line. It provides a simple and efficient way to install tools, libraries, and applications that are not included in the default macOS installation. With Homebrew, users can quickly set up their development environment by effortlessly installing and managing a wide range of software packages, making it a valuable tool for developers and power users on macOS. It simplifies the process of installing and updating software, ensuring that users have access to the latest versions and can easily manage their dependencies.

### Instructions to install Homebrew

[Install Command Source](https://brew.sh/)

1. Launch the MacOS Terminal application.
2. Run the command

```sh
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
```

3. Follow the terminal instruction to complete the installation.

[Video guide on how to install Homebrew](https://www.loom.com/share/903850d90b4a4fd7bc6ba06ed61be65b?sid=a27d4f25-b3be-4f67-be7a-78c94d5d2dff)

### Test your Homebrew installation

Run the command `brew doctor` to check the status of Homebrew. Wait for the "Your system is ready to brew" message.

[Back to TOP](#table-of-contents)

---

## Google Chrome Browser

For beginners, the Google Chrome Browser is the optimal option as it offers the most comprehensive Web Developer experience. While other Webkit engine browsers like Brave or Opera will suffice, we highly recommend starting with Google Chrome to grasp the foundational concepts. Once proficient, you can explore other browsers and determine which suits you best.

### Instructions to install Google Chrome Browser with Homebrew

[Cask Install Command Source](https://formulae.brew.sh/cask/google-chrome#default)

1. Launch the MacOS Terminal application.
2. Run the command `brew update` to update homebrew.
3. Run the command `brew install --cask google-chrome` to install the Google Chrome Browser.
4. Once the installation is complete launch Google Chrome by searching for it in the Launchpad.
5. Upon launching Chrome, you will be prompted to open the App. Click "Open".
6. Upon launching Chrome, you will be prompted to sign in with your Google account. You can choose to skip this step if you prefer.
7. Congratulations! You have successfully installed Google Chrome. Enjoy browsing the web with one of the most popular and feature-rich browsers available.
8. (Optional) Pin the app to the doc for quick access.

[Video guide on how to install Google Chrome Browser](https://www.loom.com/share/8635c1c4404143ada10a4d47daa6cdf0?sid=474b8e43-1ba7-4133-8ee3-c878df09ea04)

[Back to TOP](#table-of-contents)

---

## Discord

Discord is a popular communication platform designed for creating communities and fostering real-time interaction among users. It offers features like text chat, voice chat, and video chat, allowing individuals or groups to communicate with each other seamlessly. The Devslopes Web Academy community is using that messenger to communicate, schedule meetups and events, track student progress, and ensure the community stays informed about all the latest updates and changes in the frequently updated curriculum.

### Instructions to install Discord with Homebrew

[Cask Install Command Source](https://formulae.brew.sh/cask/discord#default)

1. Launch the MacOS Terminal application.
2. Run the command `brew update` to update homebrew.
3. Run the command `brew install --cask discord` to install Discord.
4. If prompted, enter the user password in the Terminal.
5. Once the installation is complete launch Discord by searching for it in the Launchpad.
6. Sign in with your login and password or click on the "Register" link to sign up.

[Video guide on how to install Discord](https://www.loom.com/share/8aecd89ee3934fcf877b2d5b93c34642?sid=3d5a8aa4-6904-41df-80e7-fa356996cb78)

[Back to TOP](#table-of-contents)

---

## Zoom

Zoom is a widely-used video conferencing platform that enables users to remotely connect and collaborate. With its user-friendly interface and comprehensive set of features, Zoom has become a preferred solution for businesses, schools, and individuals globally. Students are able to attend daily meetings, engage in webinars, and facilitate virtual events using functionalities such as screen sharing, text-based chat, and voice calls with Devslopes Web Academy mentors.

### Instructions to install Zoom with Homebrew

[Cask Install Command Source](https://formulae.brew.sh/cask/zoom#default)

1. Launch the MacOS Terminal application.
2. Run the command `brew update` to update homebrew.
3. Run the command `brew install --cask zoom` to install Zoom.
4. If prompted, enter the user password in the Terminal.
5. Once the installation is complete launch Zoom by searching for it in the Launchpad.
6. Click the "Open" button if prompted to confirm the launch of the application.
7. Click on the "Sign Up" or "Sign In" button in the popup window that appears after the installation process.
8. Follow the prompts to complete the sign-up process.

[Video guide on how to install Zoom](https://www.loom.com/share/bacccde45d6940cda5756164e586938d?sid=90fafa34-6c9e-4008-b876-c96954ae39ff)

[Back to TOP](#table-of-contents)

---

## Loom

Loom is a video messaging and screen recording platform that allows users to easily create and share videos. With Loom, students can quickly capture their screen, record their webcam, or create a combination of both to effectively communicate ideas, share tutorials, provide feedback or demonstrate the issue they struggle on for the Discord all-question posts.

### Instructions to install Loom with Homebrew

[Cask Install Command Source](https://formulae.brew.sh/cask/loom#default)

1. Launch the MacOS Terminal application.
2. Run the command `brew update` to update homebrew.
3. Run the command `brew install --cask loom` to install Loom.
4. If prompted, enter the user password in the Terminal.
5. Once the installation is complete launch Loom by searching for it in the Launchpad.
6. Click the "Open" button if prompted to confirm the launch of the application.
7. The Loom icon will appear on the right side of the top panel in MacOS. Click on the icon and sign in or create an account to start using Loom.
8. Follow the prompts to complete the sign-in or sign-up process.

[Video guide on how to install Loom](https://www.loom.com/share/40581cede0364a89bb63fa654c4f2f44?sid=29700266-63db-454b-8d2a-cdbdeee97d15)

[Back to TOP](#table-of-contents)

---

## VSCode IDE

VSCode, short for Visual Studio Code, is a popular Integrated Development Environment (IDE) developed by Microsoft. It has quickly become one of the top choices among developers and is particularly well-suited for web development using languages such as HTML, CSS, and JavaScript. Moreover, it is available for free, making it an accessible option for programmers.

### Instructions to install VSCode IDE with Homebrew

[Cask Install Command Source](https://formulae.brew.sh/cask/visual-studio-code#default)

1. Launch the MacOS Terminal application.
2. Run the command `brew update` to update homebrew.
3. Run the command `brew install --cask visual-studio-code` to install the VSCode IDE.
4. Once the installation is complete launch VSCode by searching for it in the Launchpad.
5. Upon launching VSCode, you will be prompted to open the app. Click "Open".
6. (Optional) Pin the app to the doc for quick access.

[Video guide on how to install Visual Studio Code (VSCode)](https://www.loom.com/share/77de0a1ccaec40e8952faf8fc5e529a2?sid=58841e1e-9a8d-499b-8525-ecd7e4bdbfb5)

[Back to TOP](#table-of-contents)

---

## Z Shell (ZSH)

ZSH, short for Z Shell, is an alternative shell to the widely used Bash shell in Unix-based operating systems. It offers a more powerful and customizable command-line experience with additional features such as advanced tab completion, spelling correction, plugin support, and extensive prompt customization options. ZSH also provides improved performance with optimizations and enhancements over the traditional Bash shell. With its user-friendly interface and extensive configurability, ZSH has become a popular choice among developers and power users for enhancing productivity and efficiency in the command-line environment.

### Get Started with ZSH

We will frequently use two commands in these instructions:

1. `which packageName` - This command will provide the path to the package if it is installed on the system. Otherwise, it will return either nothing or a message indicating that the package was not found.
2. `echo $SHELL` - This command will return the path to the package that is currently used as the default shell in your system.

### Instructions to check if ZSH is installed and set as the default shell

1. Launch the MacOS Terminal application.
2. Run the command `which zsh` to ensure it returns a path that ends with "/zsh".
3. Run the command `echo $SHELL` to ensure it returns a path that ends with "/zsh".

#### Options to proceed

- If the command `which zsh` didn't return any output or displayed "zsh not found," proceed to the [Instructions for installing Z Shell (ZSH)](#instructions-to-install-z-shell-zsh).
- If the command `echo $SHELL` returned a path that doesn't end with "/zsh," proceed to the [Instructions to switch the default shell to ZSH if the default shell is BASH](#instructions-to-switch-the-default-shell-to-zsh-if-the-default-shell-is-bash).
- If both commands returned paths that end with "/zsh," ZSH is properly set up. Please, SKIP the remaining ZSH instructions.

### Instructions to switch the default shell to ZSH if the default shell is BASH

1. Run the command `chsh -s $(which zsh)` to switch the default shell to ZSH.
2. Enter your user password when prompted by the Terminal app.
3. Restart the Terminal application.
4. Repeat the [Instructions to check if ZSH is installed and set as the default shell](#instructions-to-check-if-zsh-is-installed-and-set-as-the-default-shell)

### Instructions to install Z Shell (ZSH)

[Install Command Source](https://formulae.brew.sh/formula/zsh#default)

1. Run the command `brew install zsh` to install the most recent version of Z Shell.
2. Follow the terminal instructions to finish the installing.
3. Run the command `which zsh` to ensure it returns the homebrew path to zsh package "/opt/homebrew/bin/zsh".
4. Run the command `chsh -s $(which zsh)` to change the default shell to ZSH.
5. Enter your user password when prompted by the Terminal app.

> If you didn't see a message saying "non-standard shell" after entering the password, please go to the [Instructions to check if ZSH is installed and set as the default shell](#instructions-to-check-if-zsh-is-installed-and-set-as-the-default-shell). Otherwise, continue:

6. Run the command `sudo echo "$(which zsh)" >> /etc/shells` to add the homebrew zsh package path to the list of shells.
7. Enter your user password when prompted by the Terminal app.

> If there was NO message saying "Permission denied" after you entered the password, please SKIP items 8 and 9 and move to 10.

8. Run the command `sudo sh -c "echo $(which zsh) >> /etc/shells"` to force adding the homebrew zsh package path to the list of shells.
9. Provide the terminal with the user password.
10. Repeat the [Instructions to check if ZSH is installed and set as the default shell](#instructions-to-check-if-zsh-is-installed-and-set-as-the-default-shell)

[Video guide on how to default your shell to ZSH and to install ZSH with Homebrew](https://www.loom.com/share/57e620e5bd7544b88c148a81a1700b95?sid=05c9fa64-ad04-424c-8fba-c1fc4cadd940)

[Back to TOP](#table-of-contents)

---

## Oh My Zsh (OMZ)

### Instructions to install Oh My Zsh (OMZ)

[Install Command Source](https://ohmyz.sh/#install)

1. launch the MacOS Terminal application.
2. Run the command and follow the terminal instructions.

```sh
sh -c "$(curl -fsSL https://raw.githubusercontent.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"
```

[Video guide on how to install Oh My Zsh (OMZ)](https://www.loom.com/share/f5ec09e0e03a4447989b3ed2c2fcb0fb?sid=ddc13ea0-5a4f-45a0-8000-4218acb6cdb6)

[Back to TOP](#table-of-contents)

---

## Node Version Manager (NVM)

Node Version Manager (NVM) is a tool that allows developers to easily install, manage, and switch between multiple versions of Node.js on a single machine. It provides a command-line interface to install Node.js versions from the official Node.js distribution, as well as other sources, and enables developers to quickly switch between different versions to ensure compatibility with their projects or to test their code against different Node.js versions. NVM simplifies the process of managing Node.js versions, making it easier for developers to work with different versions of Node.js and ensuring their projects are running on the appropriate runtime environment.

### Instructions to install Node Version Manager (NVM)

[Install Command Source](https://formulae.brew.sh/formula/zsh#default)

1. Launch the MacOS Terminal application.
2. Run the command `brew install nvm` to install NVM.
3. Copy the commands from the "Next steps" section of the terminal output. Please note that although the command may look very similar to the one below, it’s likely to be slightly different. Make sure you copy the entire command that you see in your terminal.

```sh
export NVM_DIR="$HOME/.nvm"
  [ -s "/opt/homebrew/opt/nvm/nvm.sh" ] && \. "/opt/homebrew/opt/nvm/nvm.sh"  # This loads nvm
  [ -s "/opt/homebrew/opt/nvm/etc/bash_completion.d/nvm" ] && \. "/opt/homebrew/opt/nvm/etc/bash_completion.d/nvm"  # This loads nvm bash_completion

```

4. Check if the .zshrc file exists in the user's folder. If it exists, please, skip step 4.

```sh
cd ~
```

```sh
ls -a
```

5. Run the command `touch ~/.zshrc` to create ZSH configuration file.
6. Run the command `open ~/.zshrc` to open ZSH configuration file in the default text editor.
7. Paste the command you copied in step 3 into the configuration file.
8. Save the file and close the default text editor.
9. Restart the MacOS Terminal application.

[Video guide on how to install Node Version Manager (NVM)](https://www.loom.com/share/5fcb934cc3d941ccbe64c41da5eb5ade?sid=cb6fe6c7-6941-448b-8346-5406c8e3aa60)

### Test your Node Version Manager Installation

1. Run the command `nvm --version` to check the installed version of NVM.
2. Run the command `nvm` to see the available arguments that can be used with nvm.

[Back to TOP](#table-of-contents)

---

## Node.js

Node.js is an open-source, server-side JavaScript runtime environment that allows developers to build scalable and high-performance applications. It uses an event-driven, non-blocking I/O model that makes it lightweight and efficient, making it particularly well-suited for applications that require real-time communication and data-intensive tasks. Node.js enables developers to write server-side code using JavaScript, which reduces the complexity of having separate client-side and server-side languages. It has a vibrant ecosystem with a wide range of libraries and frameworks, which makes it a popular choice for web and network application development.

### Instructions to install Node.js with NVM

1. Launch the MacOS Terminal application.
2. Run the command `nvm install v18.17.1` to install the latest long term support version of Node.js.

[Video guide on how to install Node.js with](https://www.loom.com/share/2a692a493a2e4360a591628d4d7ff687?sid=ab393b94-7320-4687-aa33-a3afd559e9ba)

#### Test your Node.js installation

1. Run the command `nvm list` to check the default version of Node.js is 18.17.1.
2. Run the command `node -v` to check the current version of Node.js is 18.17.1.

[Back to TOP](#table-of-contents)

---

## Node Package Manager (NPM)

Node Package Manager (NPM) is a package manager for the JavaScript programming language. It is bundled with the Node.js runtime and allows developers to easily install, manage, and share reusable JavaScript code packages. NPM provides a vast repository of over a million packages that developers can leverage in their projects, ranging from small utility libraries to full-fledged frameworks and tools. With NPM, developers can easily add new functionality to their applications, handle dependencies, and manage project dependencies efficiently. NPM has become an essential tool in the JavaScript ecosystem, enabling developers to streamline their workflows and build robust and scalable applications.

### Test your NPM installation

1. Make sure Node.js is installed ([Instructions to install Node.js with NVM](#instructions-to-install-nodejs-with-nvm)).
2. Launch the MacOS Terminal application.
3. Run the command `npm -v` to check the installed version of Node Package Manager (NPM)

[Video guide on how to test the installation of Node Package Manager (NPM)](https://www.loom.com/share/b4b099ac94324f0eb8eaecbbc8d46fd8?sid=4da2e56d-8658-4c39-a2c4-1ab36b11eca5)

[Back to TOP](#table-of-contents)

---

## GIT

GIT is a distributed version control system that allows developers to track changes, collaborate on projects, and manage source code effectively. It provides a way to keep a history of changes made to files, allowing developers to revert to previous versions if needed. GIT's decentralized architecture allows multiple developers to work on the same project simultaneously, independently making changes and merging them seamlessly. It also supports branching, which enables developers to work on separate features or experiments without affecting the main project, and later merge those branches back together. GIT has become an essential tool for software development, enabling teams to work collaboratively, track changes, and ensure code integrity.

GIT is already included in the Windows Subsystem for Linux (WSL), so there is no need for a separate installation. However, you may still need to configure GIT to work properly within the WSL environment and Github remote repos.

### Instructions to configure GIT

1. Create an account on [GitHub](https://github.com/signup).
2. Launch the MacOS Terminal application.
3. Run the command `git config --global user.name "John Doe"` to set the default user name.
4. Run the command `git config --global user.email name@domain.zone` to set the default email, which should match the email used during GitHub sign-up.
5. Run the command `git config user.name` to verify that the user name is set correctly.
6. Run the command `git config user.email` to verify that the user email is set correctly.

### Instructions to update GIT to the latest version

1. Launch the MacOS Terminal application.
2. Run the commands in order:

```sh
brew install git
```

```sh
export PATH=/usr/local/bin:$PATH
```

[Video guide on how to install GIT with Homebrew](https://www.loom.com/share/8c24b0f2369a477d98a680a123ebcbec?sid=cdf45803-597b-46b1-b7e8-2499520c27dc)

#### Test your GIT installation

1. Run the command `git --version` to check the installed version of Git.
2. Visit [https://git-scm.com](https://git-scm.com) to confirm that your Git version matches the latest available version.

### Instructions to set the SSH key for GITHUB

1. Launch the MacOS Terminal application.
2. Follow the [Generate new SSH key](https://docs.github.com/en/authentication/connecting-to-github-with-ssh/generating-a-new-ssh-key-and-adding-it-to-the-ssh-agent?platform=mac) instructions to generate a new SSH key. Be sure to omit the "Generating a new SSH key for a hardware security key" section.
3. Follow the [Add a new SSH key](https://docs.github.com/en/authentication/connecting-to-github-with-ssh/adding-a-new-ssh-key-to-your-github-account?platform=mac&tool=webui) instructions to add a new SSH key to your GitHub account.

#### Test your SSH connection to Github

Run the command `ssh -T git@github.com` to test your connection to GitHub. Wait wor the message "Hi user.name! You've successfully authenticated, but GitHub does not provide shell access."

[Video guide on how to generate the SSH Key and add it to your GitHub profile](https://www.loom.com/share/f9e5ef63f77441c989d1b32eb5046417?sid=ba3e277d-ce51-49bf-bf31-009d11da7fac)

[Back to TOP](#table-of-contents)

---

## Setup VSCode (Optional)

### Instructions to set the tab default size to 2 spaces

1. Launch the VSCode application.
2. Press `Shift + Command + P` to open the Command Palette.
3. Enter "Settings" in the search field that appears after the caret symbol (>)
4. Select the option "Preferences: Open Settings (UI)" from the list of suggestions.
5. Enter "tab size" in the search field and set "2" in the "Editor: Tab Size" setting field.

### Instructions to install the Live Server extension in VSCode

1. Launch the VSCode application.
2. Open the "Extensions" sidebar by pressing `Shift + Command + X`.
3. Search for the "Live Server" extension, which should have over 48 million installations.
4. Click on the "Install" button to install the extension.
5. Ensure the "Go Live" button appears in the VSCode status bar.

### Instructions to install the Prettier extension in VSCode

1. Launch the VSCode application.
2. Open the "Extensions" sidebar by pressing `Shift + Command + X`.
3. Search for the "Prettier" extension, which should have over 35 million installations.
4. Click on the "Install" button to install the extension.

### Instructions to make Prettier your default code formatting tool

1. Launch the VSCode application.
2. Create a new folder and open it using the "Explorer -> Open Folder" option.
3. You will be prompted to trust the current location. Press "Trust the author".
4. Create three files: index.html, styles.css, and scripts.js.
5. For each file (active tab), follow these instructions:
6. Press `Shift + Command + P` to open the Command Palette.
7. Enter "format" in the search field that appears after the caret symbol (>)
8. Select the option "Format Document" from the list of suggestions.
9. Click on "Configure" when prompted.
10. In the dropdown menu, choose "Prettier" for formatting the document.

### Instructions for automatically formatting code when saving a file

1. Launch the VSCode application.
2. Press `Shift + Command + P` to open the Command Palette.
3. Enter "settings" in the search field that appears after the caret symbol (>)
4. Select the option "Preferences: Open Settings (UI)" from the list of suggestions.
5. In the Settings tab, type "format on save" in the search bar.
6. Enable the checkbox for "Editor: Format On Save" to automatically format your code when you save the file.
7. Close the Settings tab.

### Instructions to install the "Indent-rainbow" extension in VSCode

1. Launch the VSCode application.
2. Open the "Extensions" sidebar by pressing `Shift + Command + X`.
3. Search for the "indent-rainbow" extension, which has over 5 million installations.
4. Click on the "Install" button to install the extension.

### Instructions to install the "Auto close tag" extension in VSCode

1. Launch the VSCode application.
2. Open the "Extensions" sidebar (press `Shift + Command + X`).
3. Search for the "auto close tag" extension, which should have over 10 million installations.
4. Proceed to install the extension by clicking on the "Install" button.

### Instructions to install the "Auto rename tag" extension in VSCode

1. Launch the VSCode application.
2. Open the "Extensions" sidebar (press `Shift + Command + X`).
3. Search for the "auto rename tag" extension, which should have over 15 million installations.
4. Proceed to install the extension by clicking on the "Install" button.

[Back to TOP](#table-of-contents)

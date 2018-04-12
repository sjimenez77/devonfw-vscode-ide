# OASP | Devonfw VS Code extensions

* **UPDATE 09/05/2017:** Swagger and C# support extensions included.
* **UPDATE 12/05/2017:** AsciiDoc support extension included.
* **UPDATE 31/10/2017:** Rust and C++ support extensions included. README improved.
* **UPDATE 20/12/2017:** Python support extension included.

## Introduction

Visual Studio Code is a light and powerful open source editor, developed and
maintained by Microsoft, which integrates some powerful tools and characteristics.
Among them we can highlight the incorporation of git by default, a fast and
configurable debugging tool and the possibility of being extended and customized
by a vast number of [extensions](https://marketplace.visualstudio.com/VSCode).

## Installation

The only requirement to install the extensions is to have installed the editor,
which can be installed through his [official page](https://code.visualstudio.com/).
The next and last step is to run the script corresponding to your OS.

## Install extensions with Sync Settings

It is safer to install the above extensions using **Sync Settings**:

1.  Install [Settings Sync](https://marketplace.visualstudio.com/items?itemName=Shan.code-settings-sync) extension.
2.  Select in VS Code the command **Sync: Download Settings**.
3.  Provide GIST ID: **3b1d9d60e842f499fc39334a1dd28564**.

**IMPORTANT:** The extensions will be downloaded and installed in the background, therefore please, be patient.

**KNOWN ISSUES:** Some users reported Access Token errors. In this case, please follow the instructions below:

Create a Personal Access Token from your GitHub account. You can create one by simply following the steps shown in the pictures below. Make sure you add **Gist** in scope.

**Go to [Settings](https://github.com/settings) / [Developer settings](https://github.com/settings/tokens) / [Personal access tokens](https://github.com/settings/tokens) / Generate New Token**

![Goto Settings / Developer settings / Personal Access Tokens](https://shanalikhan.github.io/img/github1.PNG)

**Select Gist From Scopes.**

![Select Scopes](https://shanalikhan.github.io/img/github2.PNG)

**Get an Access Token.**

![Get Access Token](https://shanalikhan.github.io/img/github3.PNG)

> Save the Token somewhere for future use (i.e. to upload from other machines).

## Extensions

The extensions included in the scripts involve several aspects as Angular, Ionic and NativeScript development, other interesting languages, code running, testing, linting and IDE configuration:

* Settings Sync
  * [Shan.code-settings-sync](https://marketplace.visualstudio.com/items?itemName=Shan.code-settings-sync)
* Project Management
  * [alefragnani.project-manager](https://marketplace.visualstudio.com/items?itemName=alefragnani.project-manager)
* Code and documentation helpers
  * [christian-kohler.path-intellisense](https://marketplace.visualstudio.com/items?itemName=christian-kohler.path-intellisense)
  * [CoenraadS.bracket-pair-colorizer](https://marketplace.visualstudio.com/items?itemName=CoenraadS.bracket-pair-colorizer)
  * [esbenp.prettier-vscode](https://marketplace.visualstudio.com/items?itemName=esbenp.prettier-vscode)
    * In order to avoid TS lint errors, you must set the `prettier.singleQuote` and `prettier.semi` variables to `true` in the VS Code User Settings (Keyboard shortcut `Ctrl+,` in Windows and Linux or `Cmd+,` in macOS or press `F1` and start writing _User settings_).
    * Another useful feature to avoid TS lint errors is to set the `prettier.trailingComma` variable to `all` to trail commas wherever possible.
  * [joelday.docthis](https://marketplace.visualstudio.com/items?itemName=joelday.docthis)
  * [silverlakesoftware.searchdocsets-vscode](https://marketplace.visualstudio.com/items?itemName=silverlakesoftware.searchdocsets-vscode)
  * [wayou.vscode-todo-highlight](https://marketplace.visualstudio.com/items?itemName=wayou.vscode-todo-highlight)
  * [dcortes92.FreeMarker](https://marketplace.visualstudio.com/items?itemName=dcortes92.FreeMarker)
  * [pnp.polacode](https://marketplace.visualstudio.com/items?itemName=pnp.polacode)
* Code runners
  * [formulahendry.code-runner](https://marketplace.visualstudio.com/items?itemName=formulahendry.code-runner)
  * [WallabyJs.quokka-vscode](https://marketplace.visualstudio.com/items?itemName=WallabyJs.quokka-vscode)
* Angular, Ionic, NativeScript and TypeScript
  * [johnpapa.Angular2](https://marketplace.visualstudio.com/items?itemName=johnpapa.Angular2)
  * [eg2.tslint](https://marketplace.visualstudio.com/items?itemName=eg2.tslint)
  * [infinity1207.angular2-switcher](https://marketplace.visualstudio.com/items?itemName=infinity1207.angular2-switcher)
  * [jakethashi.vscode-angular2-emmet](https://marketplace.visualstudio.com/items?itemName=jakethashi.vscode-angular2-emmet)
  * [natewallace.angular2-inline](https://marketplace.visualstudio.com/items?itemName=natewallace.angular2-inline)
  * [Thavarajan.ionic2](https://marketplace.visualstudio.com/items?itemName=Thavarajan.ionic2)
  * [Telerik.nativescript](https://marketplace.visualstudio.com/items?itemName=Telerik.nativescript)
  * [vsmobile.cordova-tools](https://marketplace.visualstudio.com/items?itemName=vsmobile.cordova-tools)
  * [sasxa-net.angular-gui](https://marketplace.visualstudio.com/items?itemName=sasxa-net.angular-gui)
  * [pnp.polacode](https://marketplace.visualstudio.com/items?itemName=pnp.polacode)
* Debuggers
  * [msjsdiag.debugger-for-chrome](https://marketplace.visualstudio.com/items?itemName=msjsdiag.debugger-for-chrome)
  * [vscjava.vscode-java-debug](https://marketplace.visualstudio.com/items?itemName=vscjava.vscode-java-debug)
* Git
  * [donjayamanne.githistory](https://marketplace.visualstudio.com/items?itemName=donjayamanne.githistory)
  * [eamodio.gitlens](https://marketplace.visualstudio.com/items?itemName=eamodio.gitlens)
* Swagger and API definition
  * [Arjun.swagger-viewer](https://marketplace.visualstudio.com/items?itemName=Arjun.swagger-viewer)
* Rust
  * [kalitaalexey.vscode-rust](https://marketplace.visualstudio.com/items?itemName=kalitaalexey.vscode-rust)
* Python
  * [ms-python.python](https://marketplace.visualstudio.com/items?itemName=ms-python.python)
* C++
  * [ms-vscode.cpptools](https://marketplace.visualstudio.com/items?itemName=ms-vscode.cpptools)
* C#
  * [ms-vscode.csharp](https://marketplace.visualstudio.com/items?itemName=ms-vscode.csharp)
* Java
  * [vscjava.vscode-java-pack](https://marketplace.visualstudio.com/items?itemName=vscjava.vscode-java-pack) that will install automatically:
    * [redhat.java](https://marketplace.visualstudio.com/items?itemName=redhat.java)
    * [vscjava.vscode-java-debug](https://marketplace.visualstudio.com/items?itemName=vscjava.vscode-java-debug)
    * [vscjava.vscode-java-test](https://marketplace.visualstudio.com/items?itemName=vscjava.vscode-java-test)
    * [vscjava.vscode-maven](https://marketplace.visualstudio.com/items?itemName=vscjava.vscode-maven)
  * In order to make Java work properly you must set the `java.home` variable in the VS Code User Settings (Keyboard shortcut `Ctrl+,` in Windows and Linux or `Cmd+,` in macOS or press `F1` and start writing _User settings_)
* Key bindings
  * [ms-vscode.sublime-keybindings](https://marketplace.visualstudio.com/items?itemName=ms-vscode.sublime-keybindings)
* Docker
  * [PeterJausovec.vscode-docker](https://marketplace.visualstudio.com/items?itemName=PeterJausovec.vscode-docker)
* Themes
  * [wesbos.theme-cobalt2](https://marketplace.visualstudio.com/items?itemName=wesbos.theme-cobalt2) - Press F1, choose **Color Theme** option and select **Cobalt**.
  * [robertohuertasm.vscode-icons](https://marketplace.visualstudio.com/items?itemName=robertohuertasm.vscode-icons) - Press F1, choose **File Icon Theme** option and select **VSCode Icons**.
* Spell checking
  * [swyphcosmo.spellchecker](https://marketplace.visualstudio.com/items?itemName=swyphcosmo.spellchecker)
* AsciiDoc
  * [joaompinto.asciidoctor-vscode](https://marketplace.visualstudio.com/items?itemName=joaompinto.asciidoctor-vscode)

## AsciiDoc support

In order to be able to use the AsciiDoc extension you will need to install **Ruby** on your system and the **Asciidoctor** tool running the following command in the terminal:

```bash
$ gem install asciidoctor
```

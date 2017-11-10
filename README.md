# OASP | Devonfw VS Code extensions

- **UPDATE 09/05/2017:** Swagger and C# support extensions included.
- **UPDATE 12/05/2017:** AsciiDoc support extension included.
- **UPDATE 31/10/2017:** Rust and C++ support extensions included. README improved. 

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

1. Install [Settings Sync](https://marketplace.visualstudio.com/items?itemName=Shan.code-settings-sync) extension.
2. Select in VS Code the command **Sync: Download Settings**.
3. Provide GIST ID: **d976bc200f0403d8045b7e4ee39d4361**.

**IMPORTANT:** The extensions will be downloaded and installed in the background, therefore please, be patient. 

## Extensions

The extensions included in the scripts involve several aspects as Angular, Ionic and NativeScript development, other interesting languages, code running, testing, linting and IDE configuration:

- Settings Sync
    - [Shan.code-settings-sync](https://marketplace.visualstudio.com/items?itemName=Shan.code-settings-sync)
- Project Management
    - [alefragnani.project-manager](https://marketplace.visualstudio.com/items?itemName=alefragnani.project-manager)
- Code and documentation helpers
    - [christian-kohler.path-intellisense](https://marketplace.visualstudio.com/items?itemName=christian-kohler.path-intellisense)
    - [CoenraadS.bracket-pair-colorizer](https://marketplace.visualstudio.com/items?itemName=CoenraadS.bracket-pair-colorizer)
    - [HookyQR.beautify](https://marketplace.visualstudio.com/items?itemName=HookyQR.beautify)
    - [joelday.docthis](https://marketplace.visualstudio.com/items?itemName=joelday.docthis)
    - [silverlakesoftware.searchdocsets-vscode](https://marketplace.visualstudio.com/items?itemName=silverlakesoftware.searchdocsets-vscode)
    - [wayou.vscode-todo-highlight](https://marketplace.visualstudio.com/items?itemName=wayou.vscode-todo-highlight)
- Code runners
    - [formulahendry.code-runner](https://marketplace.visualstudio.com/items?itemName=formulahendry.code-runner)
    - [WallabyJs.quokka-vscode](https://marketplace.visualstudio.com/items?itemName=WallabyJs.quokka-vscode)
- Angular, Ionic, NativeScript and TypeScript
    - [johnpapa.Angular2](https://marketplace.visualstudio.com/items?itemName=johnpapa.Angular2)
    - [eg2.tslint](https://marketplace.visualstudio.com/items?itemName=eg2.tslint)
    - [infinity1207.angular2-switcher](https://marketplace.visualstudio.com/items?itemName=infinity1207.angular2-switcher)
    - [jakethashi.vscode-angular2-emmet](https://marketplace.visualstudio.com/items?itemName=jakethashi.vscode-angular2-emmet)
    - [natewallace.angular2-inline](https://marketplace.visualstudio.com/items?itemName=natewallace.angular2-inline)
    - [Thavarajan.ionic2](https://marketplace.visualstudio.com/items?itemName=Thavarajan.ionic2)
    - [Telerik.nativescript](https://marketplace.visualstudio.com/items?itemName=Telerik.nativescript)
    - [vsmobile.cordova-tools](https://marketplace.visualstudio.com/items?itemName=vsmobile.cordova-tools)
- Debuggers
    - [msjsdiag.debugger-for-chrome](https://marketplace.visualstudio.com/items?itemName=msjsdiag.debugger-for-chrome)
- Git
    - [donjayamanne.githistory](https://marketplace.visualstudio.com/items?itemName=donjayamanne.githistory)
- Swagger and API definition
    - [Arjun.swagger-viewer](https://marketplace.visualstudio.com/items?itemName=Arjun.swagger-viewer)
- Rust
    - [kalitaalexey.vscode-rust](https://marketplace.visualstudio.com/items?itemName=kalitaalexey.vscode-rust)
- C++
    - [ms-vscode.cpptools](https://marketplace.visualstudio.com/items?itemName=ms-vscode.cpptools)
- C#
    - [ms-vscode.csharp](https://marketplace.visualstudio.com/items?itemName=ms-vscode.csharp)
- Java
    - [redhat.java](https://marketplace.visualstudio.com/items?itemName=redhat.java)
- Key bindings
    - [ms-vscode.sublime-keybindings](https://marketplace.visualstudio.com/items?itemName=ms-vscode.sublime-keybindings)
- Docker
    - [PeterJausovec.vscode-docker](https://marketplace.visualstudio.com/items?itemName=PeterJausovec.vscode-docker)
- Themes
    - [wesbos.theme-cobalt2](https://marketplace.visualstudio.com/items?itemName=wesbos.theme-cobalt2) - Press F1, choose **Color Theme** option and select **Cobalt**.
    - [robertohuertasm.vscode-icons](https://marketplace.visualstudio.com/items?itemName=robertohuertasm.vscode-icons) - Press F1, choose **File Icon Theme** option and select **VSCode Icons**.
- Spell checking
    - [swyphcosmo.spellchecker](https://marketplace.visualstudio.com/items?itemName=swyphcosmo.spellchecker)
- AsciiDoc
    - [joaompinto.asciidoctor-vscode](https://marketplace.visualstudio.com/items?itemName=joaompinto.asciidoctor-vscode)

## AsciiDoc support

In order to be able to use the AsciiDoc extension you will need to install **Ruby** on your system and the **Asciidoctor** tool running the following command in the terminal:

```bash
$ gem install asciidoctor
```


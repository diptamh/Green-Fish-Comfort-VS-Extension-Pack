# Green Fish Comfort
## _Created keeping Salesforce Apex Development in mind_


This extension pack contains a list of highly opinionated extension selecstions by Diptam. Salesforce developers who wants to quick start their VSCode environment for productive, rapid Salesforce development should install this pack!


## Features
The list of original Extension catered in the pack 

- [Salesforce Extension Pack](https://marketplace.visualstudio.com/items?itemName=salesforce.salesforcedx-vscode)
- [Salesforce Extension Pack (Expanded)](https://marketplace.visualstudio.com/items?itemName=salesforce.salesforcedx-vscode-expanded)
- [Apex Log Analyzer](https://marketplace.visualstudio.com/items?itemName=financialforce.lana)
- [Apex PMD](https://marketplace.visualstudio.com/items?itemName=chuckjonas.apex-pmd)
- [ESLint](https://marketplace.visualstudio.com/items?itemName=dbaeumer.vscode-eslint)
- [GitHub](https://marketplace.visualstudio.com/items?itemName=KnisterPeter.vscode-github)
- [Prettier - Code formatter](https://marketplace.visualstudio.com/items?itemName=esbenp.prettier-vscode)
- [Material Icon Theme](https://marketplace.visualstudio.com/items?itemName=PKief.material-icon-theme)
- [YAML](https://marketplace.visualstudio.com/items?itemName=redhat.vscode-yaml)
- [Git History](https://marketplace.visualstudio.com/items?itemName=donjayamanne.githistory) 
- [Bracket Pair Colorizer 2](https://marketplace.visualstudio.com/items?itemName=CoenraadS.bracket-pair-colorizer-2) 
- [Git Graph](https://marketplace.visualstudio.com/items?itemName=mhutchie.git-graph) 
- [Apex Code Coverage Visualizer](https://marketplace.visualstudio.com/items?itemName=modicatech.apex-code-coverage-visualizer) 
- [Codey's in bed by 10](https://marketplace.visualstudio.com/items?itemName=salesforce.codey-s-in-bed-by-10) 



## Installation
- VSCode >= 1.52.0
- Java 11 installed and working
- A working install of the SFDX CLI

## How to update the list of extension
- Make the changes on the package.json and add/remove the extensions
- Run `npm install -g @vscode/vsce`
- Then go to https://dev.azure.com/
- Login and go to User Settings and click on Personal Access token
- Create a new token and copy it.
- Go back to terminal and run `vsce publish`
- When the token is asked for paste it and the changes will get published.
- You can see the published status at https://marketplace.visualstudio.com/manage/publishers/diptam?noPrompt=true

## Extra

Installing 'Cascadia Code' : 
- Go to https://github.com/microsoft/cascadia-code/releases
- Download the latest release and unpack
- Install the desired version
- To apply to VsCode follow the steps here : https://github.com/microsoft/cascadia-code/wiki/Installing-Cascadia-Code


## Development

Want to contribute? Great!

## License

MIT

**Free Software, Hell Yeah!**
# Open World Lego

## Description
This project is carried out by a team of 6 students in their 5rd year of engineering school at Polytech Grenoble.
This project is a fully fonctionnal website based on [JHipster](https://www.jhipster.tech/) to reproduce and help our customer ["Mes meilleurs menus"](https://mmmenus.fr/)

## Concept
The aim of this project is to create an website using [JHipster](https://www.jhipster.tech/) and deploy it on an Azure Cloud.
This project use a Scrum project management and as to be as clean as possible using CI/CD and many other project tool.

## Repository

- [Documentation repository](./docs)

- [Playground repository](./sandbox)

- [Application repository](./app)

## Diagram of branches
```mermaid
%%{init: { 'logLevel': 'debug', 'theme': 'base', 'gitGraph': {'showBranches': true}} }%%
gitGraph
   commit id:"c0"
   commit id:"c1"
   branch dev
   checkout dev
   commit id:"c2"
   branch username.featureName
   commit tag:"Adding a new feature" id:"c3"
   checkout dev
   branch dev_backup
   checkout username.featureName
   commit id:"c4"
   checkout dev
   merge username.featureName tag:"Merge request required"
   checkout main
   merge dev tag:"version 1"
   checkout dev
   commit id:"c5"
   branch username.bugBugName
   commit tag:"Fixing bug" id:"c6"
   commit id:"c7"
   checkout dev
   merge username.bugBugName tag:"Merge request required"
   commit id:"c8"
   checkout dev_backup
   merge dev
   checkout main
   merge dev tag:"version 2"
   commit id:"c9"
   
```

*NB : this is template is use only in the [code repository](./app)*
## Support
- Subject : [Mes meilleurs menus](https://mmmenus.fr/)

## Contact
- Project manager : romain.miras@etu.univ-grenoble-alpes.fr
- Scrum master : alexandre.arle@etu.univ-grenoble-alpes.fr

## Authors
- Romain MIRAS @RomainMIRAS
- Alexandre ARLE @horlavia
- Amaury GOGUILLOT @Amaurax
- Romain HOQUET @Butterjuice
- Achraf KHRIBECH @achrafkhribech
- Yann ROUX @yannroux26

# [Workshop] Les requêtes API avec Angular
Voici les différentes étapes que vous pourrez apprendre durant ce **workshop**:
* Installer Angular
* Apprendre les bases en Angular
* Apprendre les bases en Typescript
* Apprendre à réaliser des requêtes API avec Angular

## Installation
Pour Angular nous allons installer la version 12 au lieu de la version 13 car la version 13 est sortis il y à pas longtemps et il peut y à avoir des problèmes de "deprecated dependencies" entre les différents package que vous installerez vu que ceux qui ont créent le package ne l'ont pas encore adapté à la nouvelle version d'Angular. <br/>

Si vous avez déja installer nodejs vous pouvez skip l'installation de nodejs. <br/>
Dans le cas où vous ne savez pas si vous l'avez installer vous pouvez le vérifier avec cette commande: <br/>

```nodejs -v```&emsp;ou&emsp;```npm -v```

### &emsp;Linux
&emsp;&emsp; **Nodejs** <br/>
&emsp;&emsp;&emsp;&emsp; **Fedora** <br/>
&emsp;&emsp;&emsp;&emsp;&emsp;&emsp; ```sudo dnf install nodejs```<br/>
<br/>
&emsp;&emsp;&emsp;&emsp; **Ubuntu** <br/>
&emsp;&emsp;&emsp;&emsp;&emsp;&emsp; ```sudo apt install nodejs```<br/>
&emsp;&emsp;&emsp;&emsp;&emsp;&emsp; ```sudo apt install npm```<br/>
<br/>
&emsp;&emsp;**TypeScript** <br/>
&emsp;&emsp;&emsp;&emsp;```npm install typescript```<br/>
<br/>
&emsp;&emsp;**Angular** <br/>
&emsp;&emsp;&emsp;&emsp;```npm install -g @angular/cli@12```<br/>
### &emsp;Window
&emsp;&emsp;&emsp;https://ccbill.com/kb/install-angular-on-windows#ftoc-heading-6

## Débuter avec Angular
### Création d'un projet Angular
```ng new "Nom du projet"``` <br/><br/>
Pour pouvoir réaliser le design de votre page web angular vous laissera le choix entre CSS, SCSS, SASS, LESS, je vous conseille de prendre CSS si vous ne conaissez pas les autres proposés.

### Creé un composant Angular
Un composant angular est un ensemble visuel composé (d'un fichier typescript, d'un fichier spec.ts, d'un fichier css et d'un fichier html). Vous pouvez suprimer le fichier spec.ts quand vous aurez créer le composant car vous n'en aurez pas besoin.<br/><br/>

![image info](./Pictures/composant_angular.png)

Pour créer un composant il faut taper cette commande: <br/><br/>
```ng g c "nom du composant"```<br/>

## Débuter avec Typescript

## Réaliser une requête API avec Angular

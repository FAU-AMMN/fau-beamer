# fau-beamer

![TitleColor](https://user-images.githubusercontent.com/44805883/151393444-20ba6577-121c-44b9-bf77-6bf8682fd6e8.gif)

A LaTeX beamer template according to the 2021 [style guide](https://www.intern.fau.de/kommunikation-marketing-und-corporate-identity/corporate-identity/) of [Friedrich--Alexander-Universität Erlangen--Nürnberg](https://www.fau.de/).

The given template allows you to create LaTex presentations with the [beamer class](https://ctan.org/pkg/beamer?lang=en) in the corporate style of FAU.

## :gear: Usage and Most Important Options

To use this template you can either clone this repository or download the code. The example document should provide a basic introduction how to set up a document with this template. We are only going over the most important steps here.

Typically you would start your LaTeX document with

```LaTeX
\documentclass[<optional arguments>]{beamer}
\usepackage[<optional arguments>]{styles/beamerthemefau}
```

where the first line loads the beamer class and the second line employs the template. In the following we will explain some of the optional arguments you can pass to ```beamerthemefau```.

## :fleur_de_lis: Choosing The Institute

The option ```institute``` specifies which institute template should be used. For example

```LaTeX
\usepackage[institute=FAU]{styles/beamerthemefau}
```

can be used to use the generic FAU style. The following style are available

* ```[institute=FAU]```: Generic style for FAU,

* ```[institute=Med]```: style for Medizinische Fakultät,

* ```[institute=Nat]```: style for Naturwissenschaftliche Fakultät,

* ```[institute=Phil]```: style for Philosophische Fakultät und Fachbereich Theologie,

* ```[institute=RW]```: style for Rechts- und Wirtschaftswissenschaftliche Fakultät,

* ```[institute=Tech]```: style for Technische Fakultät

This option influences

1. the color scheme,

2. the left word mark for the title page

see the sections on [lolors](##Colors) and [logos](##Logos). The default option is ```[institute=FAU]```.

## Colors

## Logos

## :paperclip: Questions or Remarks

## Credit

This template was designed by [Tim Roith](https://timroith.github.io/) using the given style from the FAU corporate style guide 2021.


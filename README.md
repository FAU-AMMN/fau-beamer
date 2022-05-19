![TitleColor](https://user-images.githubusercontent.com/44805883/151393444-20ba6577-121c-44b9-bf77-6bf8682fd6e8.gif)

# fau-beamer

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

## :paintbrush: Colors

The template employs the color scheme as specified by the FAU style guide. Each institute has two colors a base color and a dark base color. These colors are available via the commands ```\BaseColor``` and ```\BaseDarkColor```

| Institute | ```\BaseColor``` | RGB | ```\BaseDarkColor``` | RGB |
| --------- | ---------------- | --- | ----------------- | --- |
| FAU       | <img src="https://user-images.githubusercontent.com/44805883/169272361-71da6b14-2b6d-454c-ae73-f581dd75640b.png" width="100" height="100"> | 0,47,108 | <img src="https://user-images.githubusercontent.com/44805883/169272896-3e2e90bf-5465-4f9a-afc4-4c0f952a7ce3.png" width="100" height="100"> | 4,30,66 |
| Med       | <img src="https://user-images.githubusercontent.com/44805883/169273738-b598bb45-5538-4b3b-b5ff-b120019e71d6.png" width="100" height="100"> | 0, 163, 224 | <img src="https://user-images.githubusercontent.com/44805883/169273182-326a694e-0511-4e3c-a8d3-523b5b5a72aa.png" width="100" height="100"> | 0, 97, 160 |
| Nat       | <img src="https://user-images.githubusercontent.com/44805883/169273312-2f7d0130-1dd4-44e5-a920-497cbc8a4374.png" width="100" height="100"> | 67, 176, 42 | <img src="https://user-images.githubusercontent.com/44805883/169273381-0f8fcaed-54b1-4fb4-9c60-4b47af35af25.png" width="100" height="100"> | 34, 136, 72 |
| Phil      | <img src="https://user-images.githubusercontent.com/44805883/169273473-6008ad50-2d7f-4ada-b01f-39325940c8bd.png" width="100" height="100"> | 255, 184, 28 | <img src="https://user-images.githubusercontent.com/44805883/169273551-f059d603-75c9-49ed-91cc-610fd83a4a58.png" width="100" height="100"> | 232, 119, 34 |
| RW        | <img src="https://user-images.githubusercontent.com/44805883/169273830-aeec45b8-16f6-436e-8e3c-99b87da42d3a.png" width="100" height="100"> | 200, 16, 46 | <img src="https://user-images.githubusercontent.com/44805883/169273919-371bcf69-9e5d-4070-8e1f-ba1939979f51.png" width="100" height="100"> | 151,27,47 |
| Tech      | <img src="https://user-images.githubusercontent.com/44805883/169273976-d9cd9890-883f-4a1a-9994-b6eae1333492.png" width="100" height="100"> | 119, 159, 181 | <img src="https://user-images.githubusercontent.com/44805883/169274039-0e0f4f96-8f2d-4191-96cd-641332769acb.png" width="100" height="100"> | 65, 116, 141 |


## Logos

## :paperclip: Questions or Remarks

## Credit

This template was designed by [Tim Roith](https://timroith.github.io/) using the given style from the FAU corporate style guide 2021.


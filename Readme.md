# Vue Simple Template

This template was created to use vue.js with asp.net core using the library [Javascript Script Services](https://github.com/aspnet/JavaScriptServices). It aims to be minimalistic with its approach. It also favors Vue's single file component over Typescript, since one of the efforts is to minimize friction when transitioning from a vue-cli project into this template. 

## Builds

| Appveyor  |
| :---:     |
| [![Build status](https://ci.appveyor.com/api/projects/status/vvnkjjckfv6v1dgk?svg=true)](https://ci.appveyor.com/project/Jaxelr/vuetemplate) |

## Packages

NuGet (Stable) | MyGet (Prerelease)
:---: | :---:
[![NuGet](https://img.shields.io/nuget/v/Vue.Simple.Template.svg)](https://www.nuget.org/packages/Vue.Simple.Template/) | [![MyGet](https://img.shields.io/myget/vue-simple-template/v/Vue.Simple.Template.svg)](https://www.myget.org/feed/vue-simple-template/package/nuget/Vue.Simple.Template) |


## Installation

To install the template, simply use nuget:

`dotnet new -i "Vue.Simple.Template::*"`

where * is the equivalent of the latest version of the template. 

If you would like to tinker with the code locally, you can clone the repository and execute the following command with the dotnet command, using the path of the repo:

`dotnet new -i $PATH_OF_REPO`

Once installed as a template you can properly create your own custom projects from the template using the following command:

`dotnet new simplevue -o MyAppName` 

Then proceed to:

`cd MyAppName`
`npm install`

Using the SpaServices from AspNet Core it will execute the webpack configurations once you build the site.

---

For the full fledge Vue Spa Service template, check [here](https://github.com/aspnet/templating/tree/dev/src/Microsoft.AspNetCore.SpaTemplates/content/Vue-CSharp)   
_Note on the ms template:_ the template has been announced as retired by the ms team:  https://github.com/aspnet/Announcements/issues/289 

## Contributing

Check the [contribution guide](https://github.com/Jaxelr/VueTemplate/blob/master/.github/CONTRIBUTING.md).

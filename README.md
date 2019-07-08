# Loaders Themelet

[![npm version](https://badge.fury.io/js/loaders-themelet.svg)](https://badge.fury.io/js/loaders-themelet)

A themelet providing eight alternative loaders for Liferay 7.x, based on the [Single Element CSS Spinners](https://projects.lukehaas.me/css-loaders/) project created by [Luke Hass](https://lukehaas.me/).

![Loader 1](doc/loader1.gif) 
![Loader 2](doc/loader2.gif)
![Loader 3](doc/loader3.gif)
![Loader 4](doc/loader4.gif)
![Loader 5](doc/loader5.gif)
![Loader 6](doc/loader6.gif)
![Loader 7](doc/loader7.gif)
![Loader 8](doc/loader8.gif)

## Install

Go to your theme's root folder and type:
```bash
gulp extend
```
Choose _Themelet_ :
```
? What kind of theme asset would you like to extend? 
  Base theme 
❯ Themelet 
```
Choose _Search npm registry_ :
```
? Where would you like to search for themelets? 
  Search globally installed npm modules (development purposes only) 
❯ Search npm registry (published modules) 
```
Search for _loaders-themelet_ :
```
? Search npm for themelets: loaders-themelet
```
> If you have an error, try `npm audit fix` and retry installation from the beginning 

Press space to select it :
```
? Select a themelet 
❯◉ loaders-themelet
```

## Usage

Use loader number 8 with default color:  

```
@include loader8;
```

Use loader number 8 with custom color:  

```
@include loader8 ($color: red);
```

The mixins `loader2` and `loader3` accept an optional third argument for background color:

```
@include loader2 ($color: red, $background-color: grey);
```

Loaders index:

| Mixin     | Loader                       |
|:---------:|:---------------------------: |
| `loader1` | ![Loader 1](doc/loader1.gif) |
| `loader2` | ![Loader 2](doc/loader2.gif) |
| `loader3` | ![Loader 3](doc/loader3.gif) |
| `loader4` | ![Loader 4](doc/loader4.gif) |
| `loader5` | ![Loader 5](doc/loader5.gif) |
| `loader6` | ![Loader 6](doc/loader6.gif) |
| `loader7` | ![Loader 7](doc/loader7.gif) |
| `loader8` | ![Loader 8](doc/loader8.gif) |

## License

[MIT](LICENSE)

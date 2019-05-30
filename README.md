
# Rosberry Generamba Templates
It is a collection of templates for [Generamba](https://github.com/strongself/Generamba) code generator.

## Table of contents
- [Installation](#installation)
- [Templates List](#templates-list)

## Installation
1. Install [Generamba](https://github.com/strongself/Generamba#installation)
2. Run `generamba setup` and fill out `Rambafile`. A template of `Rambafile` is [here](Rambafile).
3. Update templates section in your `Rambafile` as follow:

```yaml
### Templates
catalogs:
- 'https://github.com/rosberry/rosberry-generamba-templates'
templates:
- {name: rsb_mvp_vm_list_module}
- {name: rsb_mvp_vm_module}
- {name: rsb_service}
- {name: rsb_cell}
```

4. Run `generamba template install`

## Templates List
- [rsb_mvp_vm_list_module](rsb_mvp_vm_list_module/rsb_mvp_vm_list_module.rambaspec)
- [rsb_mvp_vm_module](rsb_mvp_vm_module/rsb_mvp_vm_module.rambaspec)
- [rsb_service](rsb_service/rsb_service.rambaspec)
- [rsb_cell](rsb_cell/rsb_cell.rambaspec)

## About

<img src="https://github.com/rosberry/Foundation/blob/master/Assets/full_logo.png?raw=true" height="100" />

This project is owned and maintained by [Rosberry](http://rosberry.com). We build mobile apps for users worldwide 🌏.

Check out our [open source projects](https://github.com/rosberry), read [our blog](https://medium.com/@Rosberry) or give us a high-five on 🐦 [@rosberryapps](http://twitter.com/RosberryApps).

## License

Rosberry Generamba Templates is available under the MIT license. See the LICENSE file for more info.

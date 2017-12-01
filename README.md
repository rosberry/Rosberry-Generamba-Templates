
# Rosberry Generamba Templates
It is a collection of templates for [Generamba](https://github.com/rambler-digital-solutions/Generamba) code generator.

## Table of contents
- [Installation](#installation)
- [Templates List](#templates-list)

## Installation
1. Install [Generamba](https://github.com/rambler-digital-solutions/Generamba#installation)
2. Run `generamba setup` and fill out `Rambafile`. A template of `Rambafile` is [here](Rambafile).
3. Update templates section in your `Rambafile` as follow:

```yaml
### Templates
catalogs:
- 'https://github.com/rosberry/rosberry-generamba-templates'
templates:
- {name: rsb_swift_viper_module}
```

4. Run `generamba template install`

## Templates List
### Swift:
- [rsb_swift_mvvm_di_module](rsb_swift_mvvm_di_module/rsb_swift_mvvm_di_module.rambaspec)
- [rsb_swift_viper_vm_module](rsb_swift_viper_vm_module/rsb_swift_viper_vm_module.rambaspec)
- [rsb_swift_viper_vm_di_module](rsb_swift_viper_vm_di_module/rsb_swift_viper_vm_di_module.rambaspec)
- [rsb_swift_viper_module](rsb_swift_viper_module/rsb_swift_viper_module.rambaspec)
- [rsb_swift_viper_di_module](rsb_swift_viper_di_module/rsb_swift_viper_di_module.rambaspec)
- [rsb_swift_viper_vs_module](rsb_swift_viper_vs_module/rsb_swift_viper_vs_module.rambaspec)
- [rsb_swift_table_cell_submodule](rsb_swift_table_cell_submodule/rsb_swift_table_cell_submodule.rambaspec)
- [rsb_swift_collection_cell_submodule](rsb_swift_collection_cell_submodule/rsb_swift_collection_cell_submodule.rambaspec)
- [rsb_swift_service](rsb_swift_service/rsb_swift_service.rambaspec)
- [rsb_swift_mvvm_table_module](rsb_swift_mvvm_table_module/rsb_swift_mvvm_table_module.rambaspec)

### Objective-C:
- [rsb_objc_viper_controller](sb_objc_viper_controller/rsb_objc_viper_controller.rambaspec)
- [rsb_objc_viper_controller_collection_sub](rsb_objc_viper_controller_collection_sub/rsb_objc_viper_controller_collection_sub.rambaspec)
- [rsb_objc_viper_controller_table](rsb_objc_viper_controller_table/rsb_objc_viper_controller_table.rambaspec)
- [rsb_objc_viper_controller_table_sub](rsb_objc_viper_controller_table_sub/rsb_objc_viper_controller_table_sub.rambaspec)
- [rsb_objc_viper_controller_table_sub_collection_sub](rsb_objc_viper_controller_table_sub_collection_sub/rsb_objc_viper_controller_table_sub_collection_sub.rambaspec)
- [rsb_objc_viper_view](rsb_objc_viper_view/rsb_objc_viper_view.rambaspec)
- [rsb_objc_assembly](rsb_objc_assembly/rsb_objc_assembly.rambaspec)
- [rsb_objc_viper_vm_module](rsb_objc_viper_vm_module/rsb_objc_viper_vm_module.rambaspec)
- [rsb_objc_mvvm_module_table](rsb_objc_mvvm_module_table/rsb_objc_mvvm_module_table.rambaspec)
- [rsb_objc_request](rsb_objc_request/rsb_objc_request.rambaspec)

## About

<img src="https://github.com/rosberry/Foundation/blob/master/Assets/full_logo.png?raw=true" height="100" />

This project is owned and maintained by [Rosberry](http://rosberry.com). We build mobile apps for users worldwide 🌏.

Check out our [open source projects](https://github.com/rosberry), read [our blog](https://medium.com/@Rosberry) or give us a high-five on 🐦 [@rosberryapps](http://twitter.com/RosberryApps).

## License

Rosberry Generamba Templates is available under the MIT license. See the LICENSE file for more info.

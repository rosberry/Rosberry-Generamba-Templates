
# Rosberry Generamba Templates
It is a collection of templates for [Generamba](https://github.com/rambler-digital-solutions/Generamba) code generator.

## Table of contents

- [Installation](#installation)
- [Template List](#template-list)

### Installation
1. Install [Generamba](https://github.com/rambler-digital-solutions/Generamba#installation)
2. Run `generamba setup` and fill out `Rambafile`
3. Update templates section in your `Rambafile` as follow:

```
### Templates
catalogs:
- 'https://github.com/rosberry/rosberry-generamba-templates'
templates:
- {name: rsb_swift_viper_module}
```

4. Run `generamba template install`

5. Enjoy

### Template List

#### Swift:
- [rsb_swift_viper_vm_module](https://github.com/rosberry/Rosberry-Generamba-Templates/blob/master/rsb_swift_viper_vm_module/rsb_swift_viper_vm_module.rambaspec)
- [rsb_swift_viper_vm_di_module](https://github.com/rosberry/Rosberry-Generamba-Templates/blob/master/rsb_swift_viper_vm_di_module/rsb_swift_viper_vm_di_module.rambaspec)
- [rsb_swift_viper_module](https://github.com/rosberry/Rosberry-Generamba-Templates/blob/master/rsb_swift_viper_module/rsb_swift_viper_module.rambaspec)
- [rsb_swift_viper_di_module](https://github.com/rosberry/Rosberry-Generamba-Templates/blob/master/rsb_swift_viper_di_module/rsb_swift_viper_di_module.rambaspec)
- [rsb_swift_cell_submodule](https://github.com/rosberry/Rosberry-Generamba-Templates/blob/master/rsb_swift_cell_submodule/rsb_swift_cell_submodule.rambaspec)
- [rsb_swift_service](https://github.com/rosberry/Rosberry-Generamba-Templates/blob/master/rsb_swift_service/rsb_swift_service.rambaspec)

#### Objective-C:
- [rsb_viper_controller](https://github.com/rosberry/Rosberry-Generamba-Templates/blob/master/rsb_viper_controller/rsb_viper_controller.rambaspec)
- [rsb_viper_controller_collection_sub](https://github.com/rosberry/Rosberry-Generamba-Templates/blob/master/rsb_viper_controller_collection_sub/rsb_viper_controller_collection_sub.rambaspec)
- [rsb_viper_controller_table](https://github.com/rosberry/Rosberry-Generamba-Templates/blob/master/rsb_viper_controller_table/rsb_viper_controller_table.rambaspec)
- [rsb_viper_controller_table_sub](https://github.com/rosberry/Rosberry-Generamba-Templates/blob/master/rsb_viper_controller_table_sub/rsb_viper_controller_table_sub.rambaspec)
- [rsb_viper_controller_table_sub_collection_sub](https://github.com/rosberry/Rosberry-Generamba-Templates/blob/master/rsb_viper_controller_table_sub_collection_sub/rsb_viper_controller_table_sub_collection_sub.rambaspec)
- [rsb_viper_view](https://github.com/rosberry/Rosberry-Generamba-Templates/blob/master/rsb_viper_view/rsb_viper_view.rambaspec)
- [rsb_assembly](https://github.com/rosberry/Rosberry-Generamba-Templates/blob/master/rsb_assembly/rsb_assembly.rambaspec)
- [rsb_viper_vm_module](https://github.com/rosberry/Rosberry-Generamba-Templates/blob/master/rsb_viper_vm_module/rsb_viper_vm_module.rambaspec)
- [rsb_mvvm_module_table](https://github.com/rosberry/Rosberry-Generamba-Templates/blob/master/rsb_mvvm_module_table/rsb_mvvm_module_table.rambaspec)
- [rsb_request](https://github.com/rosberry/Rosberry-Generamba-Templates/blob/master/rsb_request/rsb_request.rambaspec)

## License

Rosberry Generamba Templates is available under the MIT license. See the LICENSE file for more info.

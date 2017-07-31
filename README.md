
# Rosberry Generamba Templates
This is the collection of templates for [`Generamba`](https://github.com/rambler-digital-solutions/Generamba) 

- [Installation](#installation)
- [Template List](#template-list)

## Installation
1) Setup [`Generamba`](https://github.com/rambler-ios/Generamba) and run `generamba setup` and fill out `Rambafile`

2) Updates templates section in your `Rambafile` as follow:
```
### Templates
catalogs:
- 'https://github.com/rosberry/generamba-templates'
templates:
- {name: rsb_swift_viper_module}
```

3) Run `generamba template install`

5) Enjoy

## Template List

#### Swift:
- `rsb_swift_viper_vm_module`. Base VIPER+VM template for presentation module in Swift project with simple DI logic. 1.1.0
- `rsb_swift_viper_vm_di_module`. Base VIPER+VM template for presentation module in Swift project with protocol composition and generics for DI in Interactors. 1.1.0

- `rsb_swift_viper_module`. Base VIPER template for presentation module in Swift project with simple DI logic. 1.0.1
- `rsb_swift_viper_di_module`. Base VIPER template for presentation module in Swift project with protocol composition and generics for DI in Interactors. 1.0.0

- `rsb_swift_cell_submodule`. Template for `UITableViewCell` with ViewModel and CellItem classes. 1.0.0
- `rsb_swift_service`. Template for creating services. Check [gist](https://gist.github.com/artemnovichkov/ac281217059300c4a2bdd071b73c3723). 1.0.1

#### Objective-C:

- `rsb_viper_controller`. VIPER module template with UIViewController playing as a View. 1.1.4
- `rsb_viper_controller_collection_sub`. Submodule for working with collection. 1.0.0
- `rsb_viper_controller_table`- VIPER module template with `UIViewController` playing as a View. If ViewController with tableView and you use `RSBTableViewManager` this is right choice. 1.0.2
- `rsb_viper_controller_table_sub`. VIPER module template with `UIViewController` playing as a View. If ViewController with tableView and you use `RSBTableViewManager` this is right choice. 1.0.2
- `rsb_viper_controller_table_sub_collection_sub`. VIPER module template with `UIViewController` playing as a View. If ViewController with tableView and you use `RSBTableViewManager` this is right choice. 1.0.2
- `rsb_viper_view`. VIPER module template with `UIView` playing as a View. 1.0.0
- `rsb_assembly`. Create an assembly with tests. 1.0.0
- `rsb_viper_vm_module`. MVVM module template with `UIViewController` playing as a View. 1.0.1
- `rsb_mvvm_module_table`. MVVM module template with `UIViewController` playing as a View. If ViewController has table view and you use `RSBTableViewManager` this is right choice. 1.0.1
- `rsb_request`. Create request based on `RSBRequest`. Custom parameters: parameters, path_components, headers. 1.0.0

| Name                                          | Description                                                                                                                                                                         | Version |
|-----------------------------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|---------|
| rsb_swift_service                             | Template for creating swift services. Check gist: (https://gist.github.com/artemnovichkov/ac281217059300c4a2bdd071b73c3723) | 1.0.1 |
| rsb_swift_viper_vm_module                        | Base VIPER+VM template for presentation module in Swift project with simple DI logic.  | 1.1.0   |
| rsb_swift_viper_vm_di_module                     | Base VIPER+VM template for presentation module in Swift project with protocol composition and generics for DI in Interactors.  | 1.1.0   |
| rsb_swift_viper_module                     | Base VIPER template for presentation module in Swift project with simple DI logic. 1.0.1  | 1.0.1   |
| rsb_swift_viper_di_module                     | Base VIPER template for presentation module in Swift project with protocol composition and generics for DI in Interactors.  | 1.0.0   |
| rsb_swift_cell_submodule                      | Template for `UITableViewCell` with ViewModel and CellItem classes.                                                                                                                 | 1.0.0   |
| rsb_viper_controller                          | VIPER module template with UIViewController playing as a View.                                                                                                                      | 1.1.4   |
| rsb_viper_controller_collection_sub           | Submodule for working with collection.                                                                                                                                              | 1.0.0   |
| rsb_viper_controller_table                    | VIPER module template with `UIViewController` playing as a View. If ViewController with tableView and you use `RSBTableViewManager` this is right choice.                           | 1.0.2   |
| rsb_viper_controller_table_sub                | VIPER module template with `UIViewController` playing as a View. If ViewController with tableView and you use `RSBTableViewManager` this is right choice.                           | 1.0.2   |
| rsb_viper_controller_table_sub_collection_sub | VIPER module template with `UIViewController` playing as a View. If ViewController with tableView and you use `RSBTableViewManager` this is right choice.                           | 1.0.2   |
| rsb_viper_view                                | VIPER module template with `UIView` playing as a View.                                                                                                                              | 1.0.0   |
| rsb_assembly                                  | Create an assembly with tests.                                                                                                                                                      | 1.0.0   |
| rsb_viper_vm_module                           | MVVM module template with `UIViewController` playing as a View.                                                                                                                     | 1.0.1   |
| rsb_mvvm_module_table                         | MVVM module template with `UIViewController` playing as a View. If ViewController has table view and you use `RSBTableViewManager` this is right choice.                            | 1.0.1   |
| rsb_request                                   | Create request based on `RSBRequest`. Custom parameters: parameters, path_components, headers.                                                                                      | 1.0.0   |

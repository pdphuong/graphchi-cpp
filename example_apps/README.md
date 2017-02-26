Instructions to run example applications are outdated.
For example, if you run connectedcomponents by:
```shell
./connectedcomponents input_file_name graph_name
```
you will get this error:

 ./src/util/cmdopts.hpp:67: std::string graphchi::get_config_option_string(const char*): Assertion `false' failed.
ERROR: could not find option file from config.Aborted (core dumped)

Solution: To pass parameters to example applications, use --param_name=param_value. For example,

```shell
./connectedcomponents --file=input_file_name --graph_name=graph_name_value
```

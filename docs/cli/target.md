## tink target

Target operations.

### Synopsis

Target operations:
```shell
  create      create a target
  delete      delete a target
  get         get a target
  list        list all targets
  update      update a target
```

### Options

```
  -h, --help   help for target
```

### Examples

 - The command below creates a workflow target and returns its UUID.
 ```shell
  $ tink target create '{"targets": {"machine1": {"mac_addr": "98:03:9b:4b:c5:34"}}}' 
 ```

### See Also

 - [tink hardware](hardware.md) - Hardware (worker) data operations 
 - [tink template](template.md) - Template operations
 - [tink workflow](workflow.md) - Workflow operations


### Using Stackable Demos

Stackable provides several pre-configured demos to help you get started with the Stackable Data Platform.

#### Installing Demos

To install a demo, use the `stackablectl demo install` command followed by the demo name and the demos configuration file:

```bash
stackablectl demo install <demo-name> -d demos/demos-v2.yaml
```

For example:
```bash
stackablectl demo install x-jupyterhub-pyspark-hdfs -d demos/demos-v3.yaml -s stacks/stacks-v3.yaml
```

Options:
  --no-cache: Do not cache the remote (default) demo, stack and release files

  --release (24.11): Target a specific Stackable release

  -s, --stack-file <STACK_FILE>: Provide one or more additional (custom) stack file(s)

  -d, --demo-file <DEMO_FILE>: Provide one or more additional (custom) demo file(s)

### Clear cache

```bash
stackablectl cache clean
```

#### Available Demos

Here are some of the available demos:

- `x-

#### List Available Demos

To see all available demos:

```bash
stackablectl demo list -d demos/demos-v2.yaml
```

#### Removing Demos

Currently, there is no support for uninstalling a demo again. However, this functionality will come soon.

For more information, visit the [Stackable documentation](https://docs.stackable.tech/home/stable/demos/).
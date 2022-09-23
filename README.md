# setup-tfmigrate
Sets up [tfmigrate](https://github.com/minamijoyo/tfmigrate) CLI in your GitHub Actions workflow. This actions runs install only.  

## Usage
Currently only Linux is supported.

```yaml
steps:
  - name: Install tfmigrate
    uses: ponkio-o/setup-tfmigrate@v0.1.0
    with:
      version: v0.3.8 # renovate: depName=minamijoyo/tfmigrate
```

### Input
See [action.yml](https://github.com/ponkio-o/setup-tfmigrate/blob/main/action.yml)

#### `version`
required: false

The version of tfmigrate. Default is to use `latest`.  

### Output
None

## LICENSE
MIT

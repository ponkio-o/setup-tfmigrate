# setup-tfmigrate
Sets up [tfmigrate](https://github.com/minamijoyo/tfmigrate) CLI in your GitHub Actions workflow. This actions runs install only.  

## Usage
```yaml
steps:
  - name: Install tfmigrate
    uses: ponkio-o/setup-tfmigrate@v0.0.1
    with:
      version: v0.3.3
```

## Action inputs
|Name   |Description      |Default|
|-------|-----------------|-------|
|version|tfmigrate version|latest |

## LICENSE
MIT

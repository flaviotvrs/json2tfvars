# TFVars 2 JSON

Converts TFVars files to Json files and vice-versa

## How to use

*TFVars to Json*

```
cat terraform.tfvars | tfvars2json -r > terraform.json

# or

tfvars2json -r -i terraform.tfvars -o terraform.json
```

*Json to TFVars*

```
cat terraform.tfvars | tfvars2json > terraform.json

# or

tfvars2json -i terraform.tfvars -o terraform.json
```
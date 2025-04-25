# MsTest.Sdk Extensions

## Generating the schema

Use corvis to generate the types.
Install the tool with
```dotnet tool install --global Corvus.Json.JsonSchema.TypeGeneratorTool```

Output the types with
```generatejsonschematypes --rootNamespace TestML.Api --rootPath #/$definitions/testCase testml.json```

# openapi-generator-cli-docker-quickstart

Try OpenAPI Generator fast and without Java. Based on Petstore example.

NOTE: Requires Docker.

```bash
usage: ./openapi_gen_quickstart.sh <generator_name> <output_dir>
```

To see all available generators, run:
```bash
docker pull openapitools/openapi-generator-cli:latest
docker run openapitools/openapi-generator-cli:latest list
```

## Example Usage
```bash
❯ ./openapi_gen_quickstart.sh typescript-axios ./test
[main] INFO  o.o.codegen.DefaultGenerator - Generating with dryRun=false
[main] INFO  o.o.c.ignore.CodegenIgnoreProcessor - No .openapi-generator-ignore file found.
[main] INFO  o.o.codegen.DefaultGenerator - OpenAPI Generator: typescript-axios (client)
[main] INFO  o.o.codegen.DefaultGenerator - Generator 'typescript-axios' is considered stable.
[main] INFO  o.o.c.l.AbstractTypeScriptClientCodegen - Hint: Environment variable 'TS_POST_PROCESS_FILE' (optional) not defined. E.g. to format the source code, please try 'export TS_POST_PROCESS_FILE="/usr/local/bin/prettier --write"' (Linux/Mac)
[main] INFO  o.o.c.l.AbstractTypeScriptClientCodegen - Note: To enable file post-processing, 'enablePostProcessFile' must be set to `true` (--enable-post-process-file for CLI).
[main] INFO  o.o.codegen.DefaultGenerator - Model Pets not generated since it's an alias to array (without property) and `generateAliasAsModel` is set to false (default)
[main] WARN  o.o.c.l.AbstractTypeScriptClientCodegen - Error (model name matches existing language type) cannot be used as a model name. Renamed to ModelError
[main] WARN  o.o.c.l.AbstractTypeScriptClientCodegen - Error (model name matches existing language type) cannot be used as a model name. Renamed to ModelError
[main] WARN  o.o.c.l.AbstractTypeScriptClientCodegen - Error (model name matches existing language type) cannot be used as a model name. Renamed to ModelError
[main] WARN  o.o.c.l.AbstractTypeScriptClientCodegen - Error (model name matches existing language type) cannot be used as a model name. Renamed to ModelError
[main] WARN  o.o.c.l.AbstractTypeScriptClientCodegen - Error (model name matches existing language type) cannot be used as a model name. Renamed to ModelError
[main] WARN  o.o.c.l.AbstractTypeScriptClientCodegen - Error (model name matches existing language type) cannot be used as a model name. Renamed to ModelError
[main] WARN  o.o.c.l.AbstractTypeScriptClientCodegen - Error (model name matches existing language type) cannot be used as a model name. Renamed to ModelError
[main] WARN  o.o.c.l.AbstractTypeScriptClientCodegen - Error (model name matches existing language type) cannot be used as a model name. Renamed to ModelError
[main] INFO  o.o.codegen.TemplateManager - writing file /var/./test/index.ts
[main] INFO  o.o.codegen.TemplateManager - writing file /var/./test/base.ts
[main] INFO  o.o.codegen.TemplateManager - writing file /var/./test/common.ts
[main] INFO  o.o.codegen.TemplateManager - writing file /var/./test/api.ts
[main] INFO  o.o.codegen.TemplateManager - writing file /var/./test/configuration.ts
[main] INFO  o.o.codegen.TemplateManager - writing file /var/./test/git_push.sh
[main] INFO  o.o.codegen.TemplateManager - writing file /var/./test/.gitignore
[main] INFO  o.o.codegen.TemplateManager - writing file /var/./test/.npmignore
[main] INFO  o.o.codegen.TemplateManager - writing file /var/./test/.openapi-generator-ignore
[main] INFO  o.o.codegen.TemplateManager - writing file /var/./test/.openapi-generator/VERSION
[main] INFO  o.o.codegen.TemplateManager - writing file /var/./test/.openapi-generator/FILES
################################################################################
# Thanks for using OpenAPI Generator.                                          #
# Please consider donation to help us maintain this project 🙏                 #
# https://opencollective.com/openapi_generator/donate                          #
################################################################################

```

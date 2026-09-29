# Whoknows Variations

[![Docker Build](https://github.com/who-knows-inc/whoknows_variations/actions/workflows/continuous_delivery.yml/badge.svg?branch=continuous_delivery)](https://github.com/who-knows-inc/whoknows_variations/actions/workflows/continuous_delivery.yml)

---

## Get started

To get started, copy the `.env.sample` file in `src/backend` to `.env` and fill in the values. 

Then run the following command to start the application:

```bash
$ docker compose -f compose.dev.yaml up --build
```

You can now access the application at `http://localhost:8080`.

---

## Github Packages

There are many container registries to choose from. This repository uses the Github Packages:

https://github.com/features/packages

The workflow can be modified to deploy to another container registry such as Docker Hub etc. 

---

## Tutorials

[01. Setup overview and what you need to change](./tutorials/01._Overview.md)

[02. CLI Example](./tutorials/02._CLI_Example.md)

[03. Workflow File](./tutorials/03._Workflow_File.md)

[04. Environment Variables](./tutorials/04._Environment_Variables.md)
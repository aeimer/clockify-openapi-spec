# In-official Clockify OpenAPI spec

This is a inofficial Clockify OpenAPI spec based on the
[official docs](https://docs.clockify.me).

The main goal of this repo is to have a better spec than the API docs.
Sadly Clockify does not publishes a OpenAPI spec (or do they?) and the API docs seem to be incomplete.
Therefore, this OpenAPI spec should help you to e.g. generate SDKs in the language you need.

See
[Swagger UI](https://petstore.swagger.io/?url=https://raw.githubusercontent.com/aeimer/clockify-openapi-spec/refs/heads/main/clockify-openapi-spec.yaml).

DISCLAIMER:
This is 100% best effort and not related in any kind to Clockify!

Last updated: 2024-11-18

## Official Clockify OpenAPI spec

There is also an OpenAPI spec available under
https://api.clockify.me/api/v3/api-docs

See
[Swagger UI](https://petstore.swagger.io/?url=https://api.clockify.me/api/v3/api-docs).

A copy can be found in the file [`official-clockify-openapi-spec.yaml`](official-clockify-openapi-spec.yaml).
The copy was created at 2024-11-19 with
`http GET https://api.clockify.me/api/v3/api-docs | yq -P -`.

DISCLAIMER:
This is an undocumented endpoint, use with caution!

## Contribution

If you want to help me keeping this API spec uptodate, I would love get some pull-requests 🤓

This API spec is generated with
[APIbldr](https://apibldr.com).

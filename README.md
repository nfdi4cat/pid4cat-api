# Gateway API

[OpenAPI](https://swagger.io/specification/) descriptions of HLRS´s handle gateway server.

This gateway is part of the pid4cat persistent identifier service. It can be accessd at

- [API V1](https://api.nfdi4cat.org/testpid/v1/index.html)
- [API V2](https://api.nfdi4cat.org/testpid/v2/index.html)

For more on pid4cat see

- [pid4cat documentation](https://nfdi4cat.github.io/pid4cat-model/)
- [API section](https://nfdi4cat.github.io/pid4cat-model/latest/apis/) in pid4cat documentation

If you observe any problem or have questions or suggestion, please create an issue in the [pid4cat-repository](https://github.com/nfdi4cat/pid4cat-model/issues/new?labels=gateway-API) using the label *gateway-API*.

## Development

This repository uses [pre-commit](https://pre-commit.com/) to check for spelling errors and for syntax checks.

To install make sure that you have either [pipx](https://pipx.pypa.io/stable/) or [uv](https://docs.astral.sh/uv/getting-started/installation/) installed. Then install pre-commit by executing

```bash
pipx install pre-commit
```

or

```bash
uv tool install pre-commit
```

After installation, the checks will run on each commit.
You may also run the checks manually with

```bash
pre-commit run --all
```

## Contributors

Main developer:

- Preston Rodriguez (ORCID: [0000-0002-0377-5018](https://orcid.org/0000-0002-0377-5018)), GitHub [@prestonrodrigues](https://github.com/prestonrodrigues) (implementation of handle API gateway server, operation of handle server)

Contributors (see also [GitHub contributors](https://github.com/nfdi4cat/pid4cat-api/graphs/contributors)):

- David Linke (ORCID: [0000-0002-5898-1820](https://orcid.org/0000-0002-5898-1820)), GitHub [@dalito](https://github.com/dalito): Initial setup of repository

## Acknowledgement

This work was funded by the German Research Foundation (DFG) through the project "[NFDI4Cat](https://www.nfdi4cat.org) - NFDI for Catalysis-Related Sciences" (DFG project no. [441926934](https://gepris.dfg.de/gepris/projekt/441926934)), within the National Research Data Infrastructure ([NFDI](https://www.nfdi.de)) programme of the Joint Science Conference (GWK).

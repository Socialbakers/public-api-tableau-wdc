# Socialbakers API Tableau Web Data Connector v2.0

[Tableau Documentation](https://tableau.github.io/webdataconnector)

Tableau Web Data Connectors are static web pages that use JS to connect to data-source.

The Tableau WDC SDK provides a way to securely store the credentials and configuration so connectors can be reused
without providing credentials on each execution.

## Deployment

The deployment of Tableau WDC can be done on any HTTP server, making the contents of `src` directory publicly available.

To submit the connector to [Tableau WDC Community Portal](https://tableau.github.io/webdataconnector/community),
the source code repository needs to be hosted on a public repository (github.com, gitlab.com, ...).

The `.gitlab.ci.yml` is already included that configures and automatically deploys `master` to gitlab pages
 - https://api-connectors.git.ccl/tableau-connector/socialbakers_api_wdc.html
 - this cannot be used for testing in Tableau because the `.ccl` domain is hidden behind VPN
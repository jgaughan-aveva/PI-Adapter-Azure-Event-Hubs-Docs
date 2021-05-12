---
uid: AzureEventHubsConfiguration
---

# Configuration

PI Adapter for Azure Event Hubs provides configuration of data source and data selection.

The examples in the configuration topics use `curl`, a commonly available tool on both Windows and Linux. You can configure the adapter with any programming language or tool that supports making REST calls or with the EdgeCmd utility. For more information, see the [EdgeCmd utility documentation](https://osisoft.github.io/Edgecmd-Docs/content/edgecmd-utility.html). To validate successful configurations, you can perform data retrieval (`GET` commands) with a browser, if available, on your device.

For more information on PI Adapter configuration tools, see [Configuration tools](xref:ConfigurationTools).

## Quick start

This Quick Start guides you through setup of each configuration file available for PI Adapter for Azure Event Hubs. As you complete each step, perform each required configuration to establish a data flow from a data source to one or more endpoints. Some configurations are optional.

**Important:** If you want to complete the optional configurations, complete those tasks before the required tasks.

1. Configure one or more Azure Event Hubs system components.<br>See [System components configuration](xref:SystemComponentsConfiguration#configure-system-components).

2. Configure an Azure Event Hubs data source for each Azure Event Hubs device.<br>See [PI Adapter for Azure Event Hubs data source configuration](xref:PIAdapterForAzureEventHubsDataSourceConfiguration#configure-azure-event-hubs-data-source).

3. **Optional**: Configure client settings.<br> See [PI Adapter for Azure Event Hubs client settings configuration](xref:PIAdapterForAzureEventHubsClientSettingsConfiguration#configure-azure-event-hubs-client-settings).

4. Configure an Azure Event Hubs data selection for each Azure Event Hubs data source.<br>See [PI Adapter for Azure Event Hubs data selection configuration](xref:PIAdapterForAzureEventHubsDataSelectionConfiguration#configure-azure-event-hubs-data-selection).

5. **Optional**: Configure data filters and if there is a proxy between the adapter and your egress endpoints, define it.<br>See the following topics:

    - [Data filters configuration](xref:DataFiltersConfiguration#configure-data-filters) 
    - [Configure a network proxy](xref:ConfigureANetworkProxy)

6. Configure one or more egress endpoints.<br>See [Egress endpoints configuration](xref:EgressEndpointsConfiguration#configure-egress-endpoints).

7. **Optional**: Configure health endpoints, general (diagnostics and metadata), buffering, and logging. See the following topics:

    - [Health endpoint configuration](xref:HealthEndpointConfiguration#configure-health-endpoint)
    - [General configuration](xref:GeneralConfiguration#configure-general)
    - [Buffering configuration](xref:BufferingConfiguration#configure-buffering)
    - [Logging configuration](xref:LoggingConfiguration#configure-logging)
# ![LOGO](logo.png) ServiceBusManagementClient **flow**ground Connector

## Description

A generated **flow**ground connector for the ServiceBusManagementClient API (version 2018-01-01-preview).

Generated from: https://api.apis.guru/v2/specs/azure.com/servicebus-servicebus-preview/2018-01-01-preview/swagger.json<br/>
Generated at: 2019-05-07T17:38:57+03:00

## API Description

Azure Service Bus client for managing Namespace, IPFilter Rules, VirtualNetworkRules and Zone Redundant

## Authorization

Supported authorization schemes:
- OAuth2

For OAuth 2.0 you need to specify OAuth Client credentials as environment variables in the connector repository:
* `OAUTH_CLIENT_ID` - your OAuth client id
* `OAUTH_CLIENT_SECRET` - your OAuth client secret

## Actions

### Lists all of the available ServiceBus REST API operations.

*Tags:* `Operations`

#### Input Parameters
* `api-version` - _required_ - Client API version.

### Gets all the available namespaces within the subscription, irrespective of the resource groups.

*Tags:* `Namespaces`

#### Input Parameters
* `api-version` - _required_ - Client API version.
* `subscriptionId` - _required_ - Subscription credentials that uniquely identify a Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.

### Gets the available namespaces within a resource group.

*Tags:* `Namespaces`

#### Input Parameters
* `resourceGroupName` - _required_ - Name of the Resource group within the Azure subscription.
* `api-version` - _required_ - Client API version.
* `subscriptionId` - _required_ - Subscription credentials that uniquely identify a Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.

### Deletes an existing namespace. This operation also removes all associated resources under the namespace.

*Tags:* `Namespaces`

#### Input Parameters
* `resourceGroupName` - _required_ - Name of the Resource group within the Azure subscription.
* `namespaceName` - _required_ - The namespace name
* `api-version` - _required_ - Client API version.
* `subscriptionId` - _required_ - Subscription credentials that uniquely identify a Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.

### Gets a description for the specified namespace.

*Tags:* `Namespaces`

#### Input Parameters
* `resourceGroupName` - _required_ - Name of the Resource group within the Azure subscription.
* `namespaceName` - _required_ - The namespace name
* `api-version` - _required_ - Client API version.
* `subscriptionId` - _required_ - Subscription credentials that uniquely identify a Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.

### Updates a service namespace. Once created, this namespace's resource manifest is immutable. This operation is idempotent.

*Tags:* `Namespaces`

#### Input Parameters
* `resourceGroupName` - _required_ - Name of the Resource group within the Azure subscription.
* `namespaceName` - _required_ - The namespace name
* `api-version` - _required_ - Client API version.
* `subscriptionId` - _required_ - Subscription credentials that uniquely identify a Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.

### Creates or updates a service namespace. Once created, this namespace's resource manifest is immutable. This operation is idempotent.

*Tags:* `Namespaces`

#### Input Parameters
* `resourceGroupName` - _required_ - Name of the Resource group within the Azure subscription.
* `namespaceName` - _required_ - The namespace name.
* `api-version` - _required_ - Client API version.
* `subscriptionId` - _required_ - Subscription credentials that uniquely identify a Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.

### Gets a list of IP Filter rules for a Namespace.

*Tags:* `Namespaces`

#### Input Parameters
* `resourceGroupName` - _required_ - Name of the Resource group within the Azure subscription.
* `namespaceName` - _required_ - The namespace name
* `api-version` - _required_ - Client API version.
* `subscriptionId` - _required_ - Subscription credentials that uniquely identify a Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.

### Deletes an IpFilterRule for a Namespace.

*Tags:* `Namespaces`

#### Input Parameters
* `resourceGroupName` - _required_ - Name of the Resource group within the Azure subscription.
* `namespaceName` - _required_ - The namespace name
* `ipFilterRuleName` - _required_ - The IP Filter Rule name.
* `api-version` - _required_ - Client API version.
* `subscriptionId` - _required_ - Subscription credentials that uniquely identify a Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.

### Gets an IpFilterRule for a Namespace by rule name.

*Tags:* `Namespaces`

#### Input Parameters
* `resourceGroupName` - _required_ - Name of the Resource group within the Azure subscription.
* `namespaceName` - _required_ - The namespace name
* `ipFilterRuleName` - _required_ - The IP Filter Rule name.
* `api-version` - _required_ - Client API version.
* `subscriptionId` - _required_ - Subscription credentials that uniquely identify a Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.

### Creates or updates an IpFilterRule for a Namespace.

*Tags:* `Namespaces`

#### Input Parameters
* `resourceGroupName` - _required_ - Name of the Resource group within the Azure subscription.
* `namespaceName` - _required_ - The namespace name
* `ipFilterRuleName` - _required_ - The IP Filter Rule name.
* `api-version` - _required_ - Client API version.
* `subscriptionId` - _required_ - Subscription credentials that uniquely identify a Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.

### Gets NetworkRuleSet for a Namespace.

*Tags:* `Namespaces`

#### Input Parameters
* `resourceGroupName` - _required_ - Name of the Resource group within the Azure subscription.
* `namespaceName` - _required_ - The namespace name
* `api-version` - _required_ - Client API version.
* `subscriptionId` - _required_ - Subscription credentials that uniquely identify a Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.

### Gets NetworkRuleSet for a Namespace.

*Tags:* `Namespaces`

#### Input Parameters
* `resourceGroupName` - _required_ - Name of the Resource group within the Azure subscription.
* `namespaceName` - _required_ - The namespace name
* `api-version` - _required_ - Client API version.
* `subscriptionId` - _required_ - Subscription credentials that uniquely identify a Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.

### Gets a list of VirtualNetwork rules for a Namespace.

*Tags:* `Namespaces`

#### Input Parameters
* `resourceGroupName` - _required_ - Name of the Resource group within the Azure subscription.
* `namespaceName` - _required_ - The namespace name
* `api-version` - _required_ - Client API version.
* `subscriptionId` - _required_ - Subscription credentials that uniquely identify a Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.

### Deletes an VirtualNetworkRule for a Namespace.

*Tags:* `Namespaces`

#### Input Parameters
* `resourceGroupName` - _required_ - Name of the Resource group within the Azure subscription.
* `namespaceName` - _required_ - The namespace name
* `virtualNetworkRuleName` - _required_ - The Virtual Network Rule name.
* `api-version` - _required_ - Client API version.
* `subscriptionId` - _required_ - Subscription credentials that uniquely identify a Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.

### Gets an VirtualNetworkRule for a Namespace by rule name.

*Tags:* `Namespaces`

#### Input Parameters
* `resourceGroupName` - _required_ - Name of the Resource group within the Azure subscription.
* `namespaceName` - _required_ - The namespace name
* `virtualNetworkRuleName` - _required_ - The Virtual Network Rule name.
* `api-version` - _required_ - Client API version.
* `subscriptionId` - _required_ - Subscription credentials that uniquely identify a Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.

### Creates or updates an VirtualNetworkRule for a Namespace.

*Tags:* `Namespaces`

#### Input Parameters
* `resourceGroupName` - _required_ - Name of the Resource group within the Azure subscription.
* `namespaceName` - _required_ - The namespace name
* `virtualNetworkRuleName` - _required_ - The Virtual Network Rule name.
* `api-version` - _required_ - Client API version.
* `subscriptionId` - _required_ - Subscription credentials that uniquely identify a Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.

## License

**flow**ground :- Telekom iPaaS / azure-com-servicebus-servicebus-preview-connector<br/>
Copyright © 2019, [Deutsche Telekom AG](https://www.telekom.de)<br/>
contact: flowground@telekom.de

All files of this connector are licensed under the Apache 2.0 License. For details
see the file LICENSE on the toplevel directory.

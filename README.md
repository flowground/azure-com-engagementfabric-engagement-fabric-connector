# ![LOGO](logo.png) EngagementFabric **flow**ground Connector

## Description

A generated **flow**ground connector for the EngagementFabric API (version 2018-09-01-preview).

Generated from: https://api.apis.guru/v2/specs/azure.com/engagementfabric-EngagementFabric/2018-09-01-preview/swagger.json<br/>
Generated at: 2019-05-07T17:38:07+03:00

## API Description

Microsoft Customer Engagement Fabric

## Authorization

Supported authorization schemes:
- OAuth2

For OAuth 2.0 you need to specify OAuth Client credentials as environment variables in the connector repository:
* `OAUTH_CLIENT_ID` - your OAuth client id
* `OAUTH_CLIENT_SECRET` - your OAuth client secret

## Actions

### List operation of EngagementFabric resources

*Tags:* `Operations`

#### Input Parameters
* `api-version` - _required_ - API version

### List the EngagementFabric accounts in given subscription

*Tags:* `Accounts`

#### Input Parameters
* `subscriptionId` - _required_ - Subscription ID
* `api-version` - _required_ - API version

### List available SKUs of EngagementFabric resource

*Tags:* `Skus`

#### Input Parameters
* `subscriptionId` - _required_ - Subscription ID
* `api-version` - _required_ - API version

### List EngagementFabric accounts in given resource group

*Tags:* `Accounts`

#### Input Parameters
* `subscriptionId` - _required_ - Subscription ID
* `resourceGroupName` - _required_ - Resource Group Name
* `api-version` - _required_ - API version

### Delete the EngagementFabric account

*Tags:* `Accounts`

#### Input Parameters
* `subscriptionId` - _required_ - Subscription ID
* `resourceGroupName` - _required_ - Resource Group Name
* `accountName` - _required_ - Account Name
* `api-version` - _required_ - API version

### Get the EngagementFabric account

*Tags:* `Accounts`

#### Input Parameters
* `subscriptionId` - _required_ - Subscription ID
* `resourceGroupName` - _required_ - Resource Group Name
* `accountName` - _required_ - Account Name
* `api-version` - _required_ - API version

### Update EngagementFabric account

*Tags:* `Accounts`

#### Input Parameters
* `subscriptionId` - _required_ - Subscription ID
* `resourceGroupName` - _required_ - Resource Group Name
* `accountName` - _required_ - Account Name
* `api-version` - _required_ - API version

### Create or Update the EngagementFabric account

*Tags:* `Accounts`

#### Input Parameters
* `subscriptionId` - _required_ - Subscription ID
* `resourceGroupName` - _required_ - Resource Group Name
* `accountName` - _required_ - Account Name
* `api-version` - _required_ - API version

### List the EngagementFabric channels

*Tags:* `Channels`

#### Input Parameters
* `subscriptionId` - _required_ - Subscription ID
* `resourceGroupName` - _required_ - Resource Group Name
* `accountName` - _required_ - Account Name
* `api-version` - _required_ - API version

### Delete the EngagementFabric channel

*Tags:* `Channels`

#### Input Parameters
* `subscriptionId` - _required_ - Subscription ID
* `resourceGroupName` - _required_ - Resource Group Name
* `accountName` - _required_ - Account Name
* `channelName` - _required_ - The EngagementFabric channel name
* `api-version` - _required_ - API version

### Get the EngagementFabric channel

*Tags:* `Channels`

#### Input Parameters
* `subscriptionId` - _required_ - Subscription ID
* `resourceGroupName` - _required_ - Resource Group Name
* `accountName` - _required_ - Account Name
* `channelName` - _required_ - Channel Name
* `api-version` - _required_ - API version

### Create or Update the EngagementFabric channel

*Tags:* `Channels`

#### Input Parameters
* `subscriptionId` - _required_ - Subscription ID
* `resourceGroupName` - _required_ - Resource Group Name
* `accountName` - _required_ - Account Name
* `channelName` - _required_ - Channel Name
* `api-version` - _required_ - API version

### List available EngagementFabric channel types and functions

*Tags:* `Accounts`

#### Input Parameters
* `subscriptionId` - _required_ - Subscription ID
* `resourceGroupName` - _required_ - Resource Group Name
* `accountName` - _required_ - Account Name
* `api-version` - _required_ - API version

### List keys of the EngagementFabric account

*Tags:* `Accounts`

#### Input Parameters
* `subscriptionId` - _required_ - Subscription ID
* `resourceGroupName` - _required_ - Resource Group Name
* `accountName` - _required_ - Account Name
* `api-version` - _required_ - API version

### Regenerate key of the EngagementFabric account

*Tags:* `Accounts`

#### Input Parameters
* `subscriptionId` - _required_ - Subscription ID
* `resourceGroupName` - _required_ - Resource Group Name
* `accountName` - _required_ - Account Name
* `api-version` - _required_ - API version

### Check availability of EngagementFabric resource

*Tags:* `NameAvailability`

#### Input Parameters
* `subscriptionId` - _required_ - Subscription ID
* `resourceGroupName` - _required_ - Resource Group Name
* `api-version` - _required_ - API version

## License

**flow**ground :- Telekom iPaaS / azure-com-engagementfabric-engagement-fabric-connector<br/>
Copyright © 2019, [Deutsche Telekom AG](https://www.telekom.de)<br/>
contact: flowground@telekom.de

All files of this connector are licensed under the Apache 2.0 License. For details
see the file LICENSE on the toplevel directory.

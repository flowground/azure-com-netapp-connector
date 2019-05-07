# ![LOGO](logo.png) Microsoft NetApp **flow**ground Connector

## Description

A generated **flow**ground connector for the Microsoft NetApp API (version 2017-08-15).

Generated from: https://api.apis.guru/v2/specs/azure.com/netapp/2017-08-15/swagger.json<br/>
Generated at: 2019-05-07T17:38:30+03:00

## API Description

Microsoft NetApp Azure Resource Provider specification

## Authorization

Supported authorization schemes:
- OAuth2

For OAuth 2.0 you need to specify OAuth Client credentials as environment variables in the connector repository:
* `OAUTH_CLIENT_ID` - your OAuth client id
* `OAUTH_CLIENT_SECRET` - your OAuth client secret

## Actions

### Lists all of the available Microsoft.NetApp Rest API operations

*Tags:* `Operations`

#### Input Parameters
* `api-version` - _required_ - Version of the API to be used with the client request.

### Lists all NetApp accounts in the resource group

*Tags:* `NetApp Accounts`

#### Input Parameters
* `subscriptionId` - _required_ - Subscription credentials which uniquely identify Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.
* `resourceGroupName` - _required_ - The name of the resource group.
* `api-version` - _required_ - Version of the API to be used with the client request.

### Delete a NetApp account

*Tags:* `NetApp Accounts`

#### Input Parameters
* `subscriptionId` - _required_ - Subscription credentials which uniquely identify Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.
* `resourceGroupName` - _required_ - The name of the resource group.
* `accountName` - _required_ - The name of the NetApp account
* `api-version` - _required_ - Version of the API to be used with the client request.

### Get the NetApp account

*Tags:* `NetApp Accounts`

#### Input Parameters
* `subscriptionId` - _required_ - Subscription credentials which uniquely identify Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.
* `resourceGroupName` - _required_ - The name of the resource group.
* `accountName` - _required_ - The name of the NetApp account
* `api-version` - _required_ - Version of the API to be used with the client request.

### Patch a NetApp account

*Tags:* `NetApp Accounts`

#### Input Parameters
* `subscriptionId` - _required_ - Subscription credentials which uniquely identify Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.
* `resourceGroupName` - _required_ - The name of the resource group.
* `accountName` - _required_ - The name of the NetApp account
* `api-version` - _required_ - Version of the API to be used with the client request.

### Create or update a NetApp account

*Tags:* `NetApp Accounts`

#### Input Parameters
* `subscriptionId` - _required_ - Subscription credentials which uniquely identify Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.
* `resourceGroupName` - _required_ - The name of the resource group.
* `accountName` - _required_ - The name of the NetApp account
* `api-version` - _required_ - Version of the API to be used with the client request.

### Lists all capacity pools in the NetApp Account

*Tags:* `Capacity Pools`

#### Input Parameters
* `subscriptionId` - _required_ - Subscription credentials which uniquely identify Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.
* `resourceGroupName` - _required_ - The name of the resource group.
* `accountName` - _required_ - The name of the NetApp account
* `api-version` - _required_ - Version of the API to be used with the client request.

### Delete a capacity pool

*Tags:* `Capacity Pools`

#### Input Parameters
* `subscriptionId` - _required_ - Subscription credentials which uniquely identify Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.
* `resourceGroupName` - _required_ - The name of the resource group.
* `accountName` - _required_ - The name of the NetApp account
* `poolName` - _required_ - The name of the capacity pool
* `api-version` - _required_ - Version of the API to be used with the client request.

### Get a capacity pool

*Tags:* `Capacity Pools`

#### Input Parameters
* `subscriptionId` - _required_ - Subscription credentials which uniquely identify Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.
* `resourceGroupName` - _required_ - The name of the resource group.
* `accountName` - _required_ - The name of the NetApp account
* `poolName` - _required_ - The name of the capacity pool
* `api-version` - _required_ - Version of the API to be used with the client request.

### Patch a capacity pool

*Tags:* `Capacity Pools`

#### Input Parameters
* `subscriptionId` - _required_ - Subscription credentials which uniquely identify Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.
* `resourceGroupName` - _required_ - The name of the resource group.
* `accountName` - _required_ - The name of the NetApp account
* `poolName` - _required_ - The name of the capacity pool
* `api-version` - _required_ - Version of the API to be used with the client request.

### Create or Update a capacity pool

*Tags:* `Capacity Pools`

#### Input Parameters
* `subscriptionId` - _required_ - Subscription credentials which uniquely identify Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.
* `resourceGroupName` - _required_ - The name of the resource group.
* `accountName` - _required_ - The name of the NetApp account
* `poolName` - _required_ - The name of the capacity pool
* `api-version` - _required_ - Version of the API to be used with the client request.

### List volumes

*Tags:* `Volumes`

#### Input Parameters
* `subscriptionId` - _required_ - Subscription credentials which uniquely identify Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.
* `resourceGroupName` - _required_ - The name of the resource group.
* `accountName` - _required_ - The name of the NetApp account
* `poolName` - _required_ - The name of the capacity pool
* `api-version` - _required_ - Version of the API to be used with the client request.

### Delete a volume

*Tags:* `Volumes`

#### Input Parameters
* `subscriptionId` - _required_ - Subscription credentials which uniquely identify Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.
* `resourceGroupName` - _required_ - The name of the resource group.
* `accountName` - _required_ - The name of the NetApp account
* `poolName` - _required_ - The name of the capacity pool
* `volumeName` - _required_ - The name of the volume
* `api-version` - _required_ - Version of the API to be used with the client request.

### Get a volume

*Tags:* `Volumes`

#### Input Parameters
* `subscriptionId` - _required_ - Subscription credentials which uniquely identify Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.
* `resourceGroupName` - _required_ - The name of the resource group.
* `accountName` - _required_ - The name of the NetApp account
* `poolName` - _required_ - The name of the capacity pool
* `volumeName` - _required_ - The name of the volume
* `api-version` - _required_ - Version of the API to be used with the client request.

### Patch a volume

*Tags:* `Volumes`

#### Input Parameters
* `subscriptionId` - _required_ - Subscription credentials which uniquely identify Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.
* `resourceGroupName` - _required_ - The name of the resource group.
* `accountName` - _required_ - The name of the NetApp account
* `poolName` - _required_ - The name of the capacity pool
* `volumeName` - _required_ - The name of the volume
* `api-version` - _required_ - Version of the API to be used with the client request.

### Create or update a volume

*Tags:* `Volumes`

#### Input Parameters
* `subscriptionId` - _required_ - Subscription credentials which uniquely identify Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.
* `resourceGroupName` - _required_ - The name of the resource group.
* `accountName` - _required_ - The name of the NetApp account
* `poolName` - _required_ - The name of the capacity pool
* `volumeName` - _required_ - The name of the volume
* `api-version` - _required_ - Version of the API to be used with the client request.

### List mount targets

*Tags:* `MountTargets`

#### Input Parameters
* `subscriptionId` - _required_ - Subscription credentials which uniquely identify Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.
* `resourceGroupName` - _required_ - The name of the resource group.
* `accountName` - _required_ - The name of the NetApp account
* `poolName` - _required_ - The name of the capacity pool
* `volumeName` - _required_ - The name of the volume
* `api-version` - _required_ - Version of the API to be used with the client request.

### List snapshots

*Tags:* `Snapshots`

#### Input Parameters
* `subscriptionId` - _required_ - Subscription credentials which uniquely identify Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.
* `resourceGroupName` - _required_ - The name of the resource group.
* `accountName` - _required_ - The name of the NetApp account
* `poolName` - _required_ - The name of the capacity pool
* `volumeName` - _required_ - The name of the volume
* `api-version` - _required_ - Version of the API to be used with the client request.

### Delete snapshot

*Tags:* `Snapshots`

#### Input Parameters
* `subscriptionId` - _required_ - Subscription credentials which uniquely identify Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.
* `resourceGroupName` - _required_ - The name of the resource group.
* `accountName` - _required_ - The name of the NetApp account
* `poolName` - _required_ - The name of the capacity pool
* `volumeName` - _required_ - The name of the volume
* `snapshotName` - _required_ - The name of the mount target
* `api-version` - _required_ - Version of the API to be used with the client request.

### Get a snapshot

*Tags:* `Snapshots`

#### Input Parameters
* `subscriptionId` - _required_ - Subscription credentials which uniquely identify Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.
* `resourceGroupName` - _required_ - The name of the resource group.
* `accountName` - _required_ - The name of the NetApp account
* `poolName` - _required_ - The name of the capacity pool
* `volumeName` - _required_ - The name of the volume
* `snapshotName` - _required_ - The name of the mount target
* `api-version` - _required_ - Version of the API to be used with the client request.

### Patch a snapshot

*Tags:* `Snapshots`

#### Input Parameters
* `subscriptionId` - _required_ - Subscription credentials which uniquely identify Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.
* `resourceGroupName` - _required_ - The name of the resource group.
* `accountName` - _required_ - The name of the NetApp account
* `poolName` - _required_ - The name of the capacity pool
* `volumeName` - _required_ - The name of the volume
* `snapshotName` - _required_ - The name of the mount target
* `api-version` - _required_ - Version of the API to be used with the client request.

### Create a snapshot

*Tags:* `Snapshots`

#### Input Parameters
* `subscriptionId` - _required_ - Subscription credentials which uniquely identify Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.
* `resourceGroupName` - _required_ - The name of the resource group.
* `accountName` - _required_ - The name of the NetApp account
* `poolName` - _required_ - The name of the capacity pool
* `volumeName` - _required_ - The name of the volume
* `snapshotName` - _required_ - The name of the mount target
* `api-version` - _required_ - Version of the API to be used with the client request.

## License

**flow**ground :- Telekom iPaaS / azure-com-netapp-connector<br/>
Copyright © 2019, [Deutsche Telekom AG](https://www.telekom.de)<br/>
contact: flowground@telekom.de

All files of this connector are licensed under the Apache 2.0 License. For details
see the file LICENSE on the toplevel directory.

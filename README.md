# ![LOGO](logo.png) Uptrends API v4 **flow**ground Connector

## Description

A generated **flow**ground connector for the Uptrends API v4 API (version 1.0.0).

Generated from: https://api.uptrends.com/v4/swagger/v1/swagger.json<br/>
Generated at: 2019-08-02T15:29:24+03:00

## API Description

This document describes Uptrends API version 4. This Swagger environment also lets you execute API methods directly.<br/>
<br/>
Please note that this is not a sandbox environment: these API methods operate directly on your actual Uptrends account.<br/>
<br/>
For more information, please visit https://www.uptrends.com/api.<br/>

## Authorization

Supported authorization schemes:
- Basic Authentication - Authentication with API account
- Basic Authentication - Authentication with user account (for API account registration only)

## Actions

### Returns all the checkpoints.

*Tags:* `Checkpoint`

### Returns the specified checkpoint.

*Tags:* `Checkpoint`

#### Input Parameters
* `checkpointId` - _required_

### Returns the specified checkpoint server.

*Tags:* `Checkpoint`

#### Input Parameters
* `serverId` - _required_

### Anonymous call, returns all the IPv4 addresses of all the checkpoint servers.

*Tags:* `Checkpoint`

### Anonymous call, returns all the IPv6 addresses of all the checkpoint servers.

*Tags:* `Checkpoint`

### Gets all monitor groups

*Tags:* `MonitorGroup`

### Creates a new monitor group

*Tags:* `MonitorGroup`

### Gets the details of a monitor group

*Tags:* `MonitorGroup`

#### Input Parameters
* `monitorGroupGuid` - _required_ - The Guid of the monitor group to be retrieved<br/>

### Updates the monitor group with the Guid specified

*Tags:* `MonitorGroup`

#### Input Parameters
* `monitorGroupGuid` - _required_ - The Guid of the monitor group to be updated<br/>

### Deletes the specified monitor group

*Tags:* `MonitorGroup`

#### Input Parameters
* `monitorGroupGuid` - _required_ - The Guid of the monitor group to be deleted<br/>

### Gets a list of all members of a monitor group

*Tags:* `MonitorGroup`

#### Input Parameters
* `monitorGroupGuid` - _required_ - The Guid of the monitor group to retrieve the members for<br/>

### Adds the provided maintenance period to all monitors in the group specified

*Tags:* `MonitorGroup`

#### Input Parameters
* `monitorGroupGuid` - _required_

### Adds the specified monitor to the monitor group

*Tags:* `MonitorGroup`

#### Input Parameters
* `monitorGroupGuid` - _required_ - The Guid of the monitor group to add the monitor to<br/>
* `monitorGuid` - _required_ - The monitor Guid<br/>

### Removes the specified monitor from the monitor group

*Tags:* `MonitorGroup`

#### Input Parameters
* `monitorGroupGuid` - _required_ - The Guid of the monitor group to remove the monitor from<br/>
* `monitorGuid` - _required_ - The monitor Guid to be removed<br/>

### Stops all monitors that are a member of the monitor group specified by the monitor group GUID

*Tags:* `MonitorGroup`

#### Input Parameters
* `monitorGroupGuid` - _required_ - The monitor group GUID<br/>

### Starts all monitors that are a member of the monitor group specified by the monitor group GUID

*Tags:* `MonitorGroup`

#### Input Parameters
* `monitorGroupGuid` - _required_ - The monitor group GUID<br/>

### Stops alerting for all monitors that are a member of the monitor group specified by the monitor group GUID

*Tags:* `MonitorGroup`

#### Input Parameters
* `monitorGroupGuid` - _required_ - The monitor group GUID<br/>

### Starts alerting for all monitors that are a member of the monitor group specified by the monitor group GUID

*Tags:* `MonitorGroup`

#### Input Parameters
* `monitorGroupGuid` - _required_ - The monitor group GUID<br/>

### Gets a list of all operators.

*Tags:* `Operator`

### Creates a new operator.

*Tags:* `Operator`

### Gets the details of the operator with the provided OperatorGuid.

*Tags:* `Operator`

#### Input Parameters
* `operatorGuid` - _required_ - The Guid of the operator for which to retrieve the details<br/>

### Updates an existing operator.

*Tags:* `Operator`

#### Input Parameters
* `operatorGuid` - _required_ - The Guid of the operator to update<br/>

### Deletes an existing operator.

*Tags:* `Operator`

#### Input Parameters
* `operatorGuid` - _required_ - The Guid of the operator to delete<br/>

### Gets a list of all operator groups of which the operator with the provided OperatorGuid is a member

*Tags:* `Operator`

#### Input Parameters
* `operatorGuid` - _required_ - The Guid of the operator for which to retrieve the operator group guids<br/>

### Gets the duty schedule for an existing operator.

*Tags:* `Operator`

#### Input Parameters
* `operatorGuid` - _required_ - The Guid of the operator to get the duty schedule for<br/>

### Adds a duty schedule for an existing operator.

*Tags:* `Operator`

#### Input Parameters
* `operatorGuid` - _required_ - The Guid of the operator to add the duty period to<br/>

### Updates the specified duty period from the specified Operator

*Tags:* `Operator`

#### Input Parameters
* `operatorGuid` - _required_
* `dutyScheduleId` - _required_

### Deletes the specified duty period from the specified Operator

*Tags:* `Operator`

#### Input Parameters
* `operatorGuid` - _required_
* `dutyScheduleId` - _required_

### Gets all timezones available.

*Tags:* `Miscellaneous`

### Gets the timezone with the specified Id.

*Tags:* `Miscellaneous`

#### Input Parameters
* `timezoneId` - _required_

### Gets a list of all outgoing phone numbers available.

*Tags:* `Miscellaneous`

### Gets all operator groups

*Tags:* `OperatorGroup`

### Creates a new operator group

*Tags:* `OperatorGroup`

### Gets the details of a operator group

*Tags:* `OperatorGroup`

#### Input Parameters
* `operatorGroupGuid` - _required_ - The Guid of the operator group to be retrieved<br/>

### Updates the operator group with the Guid specified

*Tags:* `OperatorGroup`

#### Input Parameters
* `operatorGroupGuid` - _required_ - The Guid of the operator group to be updated<br/>

### Deletes the specified operator group

*Tags:* `OperatorGroup`

#### Input Parameters
* `operatorGroupGuid` - _required_ - The Guid of the operator group to be deleted<br/>

### Gets a list of all members of a operator group

*Tags:* `OperatorGroup`

#### Input Parameters
* `operatorGroupGuid` - _required_ - The Guid of the operator group to retrieve the members for<br/>

### Adds the provided duty schedule to all operators in the group specified

*Tags:* `OperatorGroup`

#### Input Parameters
* `operatorGroupGuid` - _required_

### Adds the specified operator to the operator group

*Tags:* `OperatorGroup`

#### Input Parameters
* `operatorGroupGuid` - _required_ - The Guid of the operator group to add the operator to<br/>
* `operatorGuid` - _required_ - The operator Guid<br/>

### Removes the specified operator from the operator group

*Tags:* `OperatorGroup`

#### Input Parameters
* `operatorGroupGuid` - _required_ - The Guid of the operator group to remove the operator from<br/>
* `operatorGuid` - _required_ - The operator Guid to be removed<br/>

### Returns all monitor check data.

*Tags:* `MonitorCheck`

#### Input Parameters
* `period` - _optional_ - The requested time period. (default = Last24Hours)<br/>
    Possible values: CurrentDay, CurrentWeek, CurrentMonth, PreviousDay, PreviousWeek, PreviousMonth, Last24Hours, Last48Hours, Last7Days, Last30Days, Last60Days, Last90Days.
* `start` - _optional_ - The start of a custom period (can't be used together with the period parameter)<br/>
* `end` - _optional_ - The end of a custom period (can't be longer than 90 days)<br/>
* `errorLevel` - _optional_ - Error level filter that should be applied. (default = NoError and above)<br/>
    Possible values: NoError, Unconfirmed, Confirmed.
* `cursor` - _optional_ - A cursor value that should be used for traversing the dataset.<br/>
* `sorting` - _optional_ - Sorting direction based on monitor check timestamp. (default = Descending)<br/>
    Possible values: Ascending, Descending.
* `take` - _optional_ - The number of checks to return (default = 100, max = 100)<br/>

### Returns a single monitor check.

*Tags:* `MonitorCheck`

#### Input Parameters
* `monitorCheckId` - _required_

### Returns monitor check data for a specific monitor.

*Tags:* `MonitorCheck`

#### Input Parameters
* `monitorGuid` - _required_ - The Guid of the specified monitor.<br/>
* `period` - _optional_ - The requested time period. (default = Last24Hours)<br/>
    Possible values: CurrentDay, CurrentWeek, CurrentMonth, PreviousDay, PreviousWeek, PreviousMonth, Last24Hours, Last48Hours, Last7Days, Last30Days, Last60Days, Last90Days.
* `start` - _optional_ - The start of a custom period (can't be used together with the period parameter)<br/>
* `end` - _optional_ - The end of a custom period (can't be longer than 90 days)<br/>
* `errorLevel` - _optional_ - Error level filter that should be applied. (default = NoError and above)<br/>
    Possible values: NoError, Unconfirmed, Confirmed.
* `cursor` - _optional_ - A cursor value that should be used for traversing the dataset.<br/>
* `sorting` - _optional_ - Sorting direction based on monitor check timestamp. (default = Descending)<br/>
    Possible values: Ascending, Descending.
* `take` - _optional_ - The number of checks to return (default = 100, max = 100)<br/>

### Returns monitor check data for a specific monitor group.

*Tags:* `MonitorCheck`

#### Input Parameters
* `monitorGroupGuid` - _required_ - The Guid of the specified monitor group.<br/>
* `period` - _optional_ - The requested time period. (default = Last24Hours)<br/>
    Possible values: CurrentDay, CurrentWeek, CurrentMonth, PreviousDay, PreviousWeek, PreviousMonth, Last24Hours, Last48Hours, Last7Days, Last30Days, Last60Days, Last90Days.
* `start` - _optional_ - The start of a custom period (can't be used together with the period parameter)<br/>
* `end` - _optional_ - The end of a custom period (can't be longer than 90 days)<br/>
* `errorLevel` - _optional_ - Error level filter that should be applied. (default = NoError and above)<br/>
    Possible values: NoError, Unconfirmed, Confirmed.
* `cursor` - _optional_ - A cursor value that should be used for traversing the dataset.<br/>
* `sorting` - _optional_ - Sorting direction based on monitor check timestamp. (default = Descending)<br/>
    Possible values: Ascending, Descending.
* `take` - _optional_ - The number of checks to return (default = 100, max = 100)<br/>

### Returns HTTP details for a monitor check.

*Tags:* `MonitorCheck`

#### Input Parameters
* `monitorCheckId` - _required_ - Monitor check Id to get the detailed data for.<br/>

### Returns Multi-Step API details for a monitor check.

*Tags:* `MonitorCheck`

#### Input Parameters
* `monitorCheckId` - _required_ - Monitor check Id to get the detailed data for.<br/>

### Returns transaction step details for a monitor check.

*Tags:* `MonitorCheck`

#### Input Parameters
* `monitorCheckId` - _required_ - Monitor check Id to get the detailed data for.<br/>

### Returns waterfall information for a monitor check.

*Tags:* `MonitorCheck`

#### Input Parameters
* `monitorCheckId` - _required_ - Monitor check Id to get the detailed data for.<br/>
* `step` - _optional_ - For transaction waterfalls only: the transaction step to get the waterfall for.<br/>

### MonitorCheck_GetScreenshots

*Tags:* `MonitorCheck`

#### Input Parameters
* `monitorCheckId` - _required_
* `screenshotId` - _required_

### Returns the definition of the specified monitor.

*Tags:* `Monitor`

#### Input Parameters
* `monitorGuid` - _required_ - The Guid of the requested monitor.<br/>

### Updates the definition of the specified monitor.
> This methods only accepts a complete monitor definition. We recommend retrieving the existing definition first (using the GET method). You can then process the changes you want to make and send back the updated definition using this PUT method.<br/>

*Tags:* `Monitor`

#### Input Parameters
* `monitorGuid` - _required_ - The Guid of the monitor that should be updated.<br/>

### Deletes the specified monitor.

*Tags:* `Monitor`

#### Input Parameters
* `monitorGuid` - _required_ - The guid of the monitor you want to delete.<br/>

### Creates a clone (duplicate) of the specified monitor.
> Upon creation, the new monitor will be inactive. This allows you to make the necessary changes before you activate it. All other settings will be transferred to the new monitor as-is.<br/>

*Tags:* `Monitor`

#### Input Parameters
* `monitorGuid` - _required_ - The guid of the monitor you want to clone.<br/>
* `includeMaintenancePeriods` - _optional_ - Whether or not to also copy the maintenance periods into the clone.<br/>
* `includeOperatorGroups` - _optional_ - Whether or not to also copy the operator group memberships into the clone.<br/>

### Finds all maintenance periods for a monitor.

*Tags:* `Monitor`

#### Input Parameters
* `monitorGuid` - _required_ - The guid of the monitor you want to find the maintenance periods of.<br/>

### Saves the new maintenance period provided for the specified monitor

*Tags:* `Monitor`

#### Input Parameters
* `monitorGuid` - _required_

### Deletes the specified maintenance period from the specified monitor

*Tags:* `Monitor`

#### Input Parameters
* `monitorGuid` - _required_
* `maintenancePeriodId` - _required_

### Updates the specified maintenance schedule for the specified monitor

*Tags:* `Monitor`

#### Input Parameters
* `monitorGuid` - _required_
* `maintenancePeriodId` - _required_

### Clears out all one-time maintenance periods for the specified monitor older than the specified date

*Tags:* `Monitor`

#### Input Parameters
* `monitorGuid` - _required_
* `beforeDate` - _required_ - A string representing the date, formatted as "yyyy-MM-dd"<br/>

### Creates a new API account.
> This method requires that you specify the username and password of an Uptrends operator login as authentication. When registration is successful, please save the UserName and Password fields from the response: these are your new API credentials.<br/>

*Tags:* `Register`

#### Input Parameters
* `description` - _required_ - A simple text value to give the new API account a name, e.g. "API"<br/>
* `type` - _optional_

### Returns all vault items.

*Tags:* `Vault`

### Creates a new vault item.
> The VaultItemGuid field should be omitted<br/>

*Tags:* `Vault`

### Returns the specified vault item.

*Tags:* `Vault`

#### Input Parameters
* `vaultItemGuid` - _required_ - The Guid of the requested vault item.<br/>

### Updates the specified vault item.
> Only complete definitions are accepted. Fields not specified will be NULLed.<br/>

*Tags:* `Vault`

#### Input Parameters
* `vaultItemGuid` - _required_ - The Guid of the vault item that should be updated.<br/>

### Deletes the specified vault item.

*Tags:* `Vault`

#### Input Parameters
* `vaultItemGuid` - _required_ - The Guid of the vault item that should be deleted.<br/>

### Returns all vault sections.

*Tags:* `Vault`

### Creates a new vault section.
> When a new vault section is created, the user that created the section is granted View and Edit authorizations to that section. The VaultSectionGuid attribute should be omitted in the request body. The Guid of the newly created section will be returned in the response.<br/>

*Tags:* `Vault`

### Returns the specified vault section.

*Tags:* `Vault`

#### Input Parameters
* `vaultSectionGuid` - _required_ - The Guid of the requested vault section.<br/>

### Updates the specified vault section.

*Tags:* `Vault`

#### Input Parameters
* `vaultSectionGuid` - _required_ - The Guid of the vault section that should be updated.<br/>

### Deletes the specified vault section.

*Tags:* `Vault`

#### Input Parameters
* `vaultSectionGuid` - _required_ - The Guid of the vault section that should be deleted.<br/>

### Returns all authorizations for the specified vault section.

*Tags:* `Vault`

#### Input Parameters
* `vaultSectionGuid` - _required_ - The Guid of the vault section for which to return authorizations.<br/>

### Creates a new authorization for the specified vault section.
> The AuthorizationId attribute should be omitted in the request body. The AuthorizationId of the newly created authorization will be returned in the response. In the ContextID attribute, fill in the VaultSectionGuid that identifies the vault section for which to create the new authorization. Valid values for the AuthorizationType field are "ViewVaultSection" and "ChangeVaultSection". An authorization should be granted to either an individual operator, or an operator group. Therefore, either specify the OperatorGuid attribute or the OperatorGroupGuid attribute.<br/>

*Tags:* `Vault`

#### Input Parameters
* `vaultSectionGuid` - _required_ - The Guid of the vault section for which to create the new authorization.<br/>

### Deletes the specified authorization for the specified vault section.

*Tags:* `Vault`

#### Input Parameters
* `vaultSectionGuid` - _required_ - The Guid of the vault section for which the authorization should be deleted.<br/>
* `authorizationGuid` - _required_ - The Guid of the authorization that should be deleted.<br/>

## License

**flow**ground :- Telekom iPaaS / uptrends-api-v4-connector<br/>
Copyright © 2019, [Deutsche Telekom AG](https://www.telekom.de)<br/>
contact: flowground@telekom.de

All files of this connector are licensed under the Apache 2.0 License. For details
see the file LICENSE on the toplevel directory.

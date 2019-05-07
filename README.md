# ![LOGO](logo.png) AdSense Management **flow**ground Connector

## Description

A generated **flow**ground connector for the AdSense Management API (version v1.4).

Generated from: https://api.apis.guru/v2/specs/googleapis.com/adsense/v1.4/swagger.json<br/>
Generated at: 2019-05-07T17:41:07+03:00

## API Description

Accesses AdSense publishers' inventory and generates performance reports.

## Authorization

Supported authorization schemes:
- OAuth2

For OAuth 2.0 you need to specify OAuth Client credentials as environment variables in the connector repository:
* `OAUTH_CLIENT_ID` - your OAuth client id
* `OAUTH_CLIENT_SECRET` - your OAuth client secret

## Actions

### List all accounts available to this AdSense account.

*Tags:* `accounts`

#### Input Parameters
* `maxResults` - _optional_ - The maximum number of accounts to include in the response, used for paging.
* `pageToken` - _optional_ - A continuation token, used to page through accounts. To retrieve the next page, set this parameter to the value of "nextPageToken" from the previous response.
* `key` - _optional_ - API key. Your API key identifies your project and provides you with API access, quota, and reports. Required unless you provide an OAuth 2.0 token.
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Get information about the selected AdSense account.

*Tags:* `accounts`

#### Input Parameters
* `accountId` - _required_ - Account to get information about.
* `tree` - _optional_ - Whether the tree of sub accounts should be returned.
* `key` - _optional_ - API key. Your API key identifies your project and provides you with API access, quota, and reports. Required unless you provide an OAuth 2.0 token.
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### List all ad clients in the specified account.

*Tags:* `accounts`

#### Input Parameters
* `accountId` - _required_ - Account for which to list ad clients.
* `maxResults` - _optional_ - The maximum number of ad clients to include in the response, used for paging.
* `pageToken` - _optional_ - A continuation token, used to page through ad clients. To retrieve the next page, set this parameter to the value of "nextPageToken" from the previous response.
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Get Auto ad code for a given ad client.

*Tags:* `accounts`

#### Input Parameters
* `accountId` - _required_ - Account which contains the ad client.
* `adClientId` - _required_ - Ad client to get the code for.
* `key` - _optional_ - API key. Your API key identifies your project and provides you with API access, quota, and reports. Required unless you provide an OAuth 2.0 token.
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### List all ad units in the specified ad client for the specified account.

*Tags:* `accounts`

#### Input Parameters
* `accountId` - _required_ - Account to which the ad client belongs.
* `adClientId` - _required_ - Ad client for which to list ad units.
* `includeInactive` - _optional_ - Whether to include inactive ad units. Default: true.
* `maxResults` - _optional_ - The maximum number of ad units to include in the response, used for paging.
* `pageToken` - _optional_ - A continuation token, used to page through ad units. To retrieve the next page, set this parameter to the value of "nextPageToken" from the previous response.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Gets the specified ad unit in the specified ad client for the specified account.

*Tags:* `accounts`

#### Input Parameters
* `accountId` - _required_ - Account to which the ad client belongs.
* `adClientId` - _required_ - Ad client for which to get the ad unit.
* `adUnitId` - _required_ - Ad unit to retrieve.
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Get ad code for the specified ad unit.

*Tags:* `accounts`

#### Input Parameters
* `accountId` - _required_ - Account which contains the ad client.
* `adClientId` - _required_ - Ad client with contains the ad unit.
* `adUnitId` - _required_ - Ad unit to get the code for.
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### List all custom channels which the specified ad unit belongs to.

*Tags:* `accounts`

#### Input Parameters
* `accountId` - _required_ - Account to which the ad client belongs.
* `adClientId` - _required_ - Ad client which contains the ad unit.
* `adUnitId` - _required_ - Ad unit for which to list custom channels.
* `maxResults` - _optional_ - The maximum number of custom channels to include in the response, used for paging.
* `pageToken` - _optional_ - A continuation token, used to page through custom channels. To retrieve the next page, set this parameter to the value of "nextPageToken" from the previous response.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### List all custom channels in the specified ad client for the specified account.

*Tags:* `accounts`

#### Input Parameters
* `accountId` - _required_ - Account to which the ad client belongs.
* `adClientId` - _required_ - Ad client for which to list custom channels.
* `maxResults` - _optional_ - The maximum number of custom channels to include in the response, used for paging.
* `pageToken` - _optional_ - A continuation token, used to page through custom channels. To retrieve the next page, set this parameter to the value of "nextPageToken" from the previous response.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Get the specified custom channel from the specified ad client for the specified account.

*Tags:* `accounts`

#### Input Parameters
* `accountId` - _required_ - Account to which the ad client belongs.
* `adClientId` - _required_ - Ad client which contains the custom channel.
* `customChannelId` - _required_ - Custom channel to retrieve.
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### List all ad units in the specified custom channel.

*Tags:* `accounts`

#### Input Parameters
* `accountId` - _required_ - Account to which the ad client belongs.
* `adClientId` - _required_ - Ad client which contains the custom channel.
* `customChannelId` - _required_ - Custom channel for which to list ad units.
* `includeInactive` - _optional_ - Whether to include inactive ad units. Default: true.
* `maxResults` - _optional_ - The maximum number of ad units to include in the response, used for paging.
* `pageToken` - _optional_ - A continuation token, used to page through ad units. To retrieve the next page, set this parameter to the value of "nextPageToken" from the previous response.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### List all URL channels in the specified ad client for the specified account.

*Tags:* `accounts`

#### Input Parameters
* `accountId` - _required_ - Account to which the ad client belongs.
* `adClientId` - _required_ - Ad client for which to list URL channels.
* `maxResults` - _optional_ - The maximum number of URL channels to include in the response, used for paging.
* `pageToken` - _optional_ - A continuation token, used to page through URL channels. To retrieve the next page, set this parameter to the value of "nextPageToken" from the previous response.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### List the alerts for the specified AdSense account.

*Tags:* `accounts`

#### Input Parameters
* `accountId` - _required_ - Account for which to retrieve the alerts.
* `locale` - _optional_ - The locale to use for translating alert messages. The account locale will be used if this is not supplied. The AdSense default (English) will be used if the supplied locale is invalid or unsupported.
* `key` - _optional_ - API key. Your API key identifies your project and provides you with API access, quota, and reports. Required unless you provide an OAuth 2.0 token.
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Dismiss (delete) the specified alert from the specified publisher AdSense account.

*Tags:* `accounts`

#### Input Parameters
* `accountId` - _required_ - Account which contains the ad unit.
* `alertId` - _required_ - Alert to delete.
* `key` - _optional_ - API key. Your API key identifies your project and provides you with API access, quota, and reports. Required unless you provide an OAuth 2.0 token.
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### List the payments for the specified AdSense account.

*Tags:* `accounts`

#### Input Parameters
* `accountId` - _required_ - Account for which to retrieve the payments.
* `fields` - _optional_ - Selector specifying which fields to include in a partial response.
* `key` - _optional_ - API key. Your API key identifies your project and provides you with API access, quota, and reports. Required unless you provide an OAuth 2.0 token.
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Generate an AdSense report based on the report request sent in the query parameters. Returns the result as JSON; to retrieve output in CSV format specify "alt=csv" as a query parameter.

*Tags:* `accounts`

#### Input Parameters
* `accountId` - _required_ - Account upon which to report.
* `currency` - _optional_ - Optional currency to use when reporting on monetary metrics. Defaults to the account's currency if not set.
* `dimension` - _optional_ - Dimensions to base the report on.
* `endDate` - _required_ - End of the date range to report on in "YYYY-MM-DD" format, inclusive.
* `filter` - _optional_ - Filters to be run on the report.
* `locale` - _optional_ - Optional locale to use for translating report output to a local language. Defaults to "en_US" if not specified.
* `maxResults` - _optional_ - The maximum number of rows of report data to return.
* `metric` - _optional_ - Numeric columns to include in the report.
* `sort` - _optional_ - The name of a dimension or metric to sort the resulting report on, optionally prefixed with "+" to sort ascending or "-" to sort descending. If no prefix is specified, the column is sorted ascending.
* `startDate` - _required_ - Start of the date range to report on in "YYYY-MM-DD" format, inclusive.
* `startIndex` - _optional_ - Index of the first row of report data to return.
* `useTimezoneReporting` - _optional_ - Whether the report should be generated in the AdSense account's local timezone. If false default PST/PDT timezone will be used.

### List all saved reports in the specified AdSense account.

*Tags:* `accounts`

#### Input Parameters
* `accountId` - _required_ - Account to which the saved reports belong.
* `maxResults` - _optional_ - The maximum number of saved reports to include in the response, used for paging.
* `pageToken` - _optional_ - A continuation token, used to page through saved reports. To retrieve the next page, set this parameter to the value of "nextPageToken" from the previous response.
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Generate an AdSense report based on the saved report ID sent in the query parameters.

*Tags:* `accounts`

#### Input Parameters
* `accountId` - _required_ - Account to which the saved reports belong.
* `locale` - _optional_ - Optional locale to use for translating report output to a local language. Defaults to "en_US" if not specified.
* `maxResults` - _optional_ - The maximum number of rows of report data to return.
* `savedReportId` - _required_ - The saved report to retrieve.
* `startIndex` - _optional_ - Index of the first row of report data to return.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### List all saved ad styles in the specified account.

*Tags:* `accounts`

#### Input Parameters
* `accountId` - _required_ - Account for which to list saved ad styles.
* `maxResults` - _optional_ - The maximum number of saved ad styles to include in the response, used for paging.
* `pageToken` - _optional_ - A continuation token, used to page through saved ad styles. To retrieve the next page, set this parameter to the value of "nextPageToken" from the previous response.
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### List a specific saved ad style for the specified account.

*Tags:* `accounts`

#### Input Parameters
* `accountId` - _required_ - Account for which to get the saved ad style.
* `savedAdStyleId` - _required_ - Saved ad style to retrieve.
* `key` - _optional_ - API key. Your API key identifies your project and provides you with API access, quota, and reports. Required unless you provide an OAuth 2.0 token.
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### List all ad clients in this AdSense account.

*Tags:* `adclients`

#### Input Parameters
* `maxResults` - _optional_ - The maximum number of ad clients to include in the response, used for paging.
* `pageToken` - _optional_ - A continuation token, used to page through ad clients. To retrieve the next page, set this parameter to the value of "nextPageToken" from the previous response.
* `key` - _optional_ - API key. Your API key identifies your project and provides you with API access, quota, and reports. Required unless you provide an OAuth 2.0 token.
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### List all ad units in the specified ad client for this AdSense account.

*Tags:* `adunits`

#### Input Parameters
* `adClientId` - _required_ - Ad client for which to list ad units.
* `includeInactive` - _optional_ - Whether to include inactive ad units. Default: true.
* `maxResults` - _optional_ - The maximum number of ad units to include in the response, used for paging.
* `pageToken` - _optional_ - A continuation token, used to page through ad units. To retrieve the next page, set this parameter to the value of "nextPageToken" from the previous response.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Gets the specified ad unit in the specified ad client.

*Tags:* `adunits`

#### Input Parameters
* `adClientId` - _required_ - Ad client for which to get the ad unit.
* `adUnitId` - _required_ - Ad unit to retrieve.
* `key` - _optional_ - API key. Your API key identifies your project and provides you with API access, quota, and reports. Required unless you provide an OAuth 2.0 token.
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Get ad code for the specified ad unit.

*Tags:* `adunits`

#### Input Parameters
* `adClientId` - _required_ - Ad client with contains the ad unit.
* `adUnitId` - _required_ - Ad unit to get the code for.
* `key` - _optional_ - API key. Your API key identifies your project and provides you with API access, quota, and reports. Required unless you provide an OAuth 2.0 token.
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### List all custom channels which the specified ad unit belongs to.

*Tags:* `adunits`

#### Input Parameters
* `adClientId` - _required_ - Ad client which contains the ad unit.
* `adUnitId` - _required_ - Ad unit for which to list custom channels.
* `maxResults` - _optional_ - The maximum number of custom channels to include in the response, used for paging.
* `pageToken` - _optional_ - A continuation token, used to page through custom channels. To retrieve the next page, set this parameter to the value of "nextPageToken" from the previous response.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### List all custom channels in the specified ad client for this AdSense account.

*Tags:* `customchannels`

#### Input Parameters
* `adClientId` - _required_ - Ad client for which to list custom channels.
* `maxResults` - _optional_ - The maximum number of custom channels to include in the response, used for paging.
* `pageToken` - _optional_ - A continuation token, used to page through custom channels. To retrieve the next page, set this parameter to the value of "nextPageToken" from the previous response.
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Get the specified custom channel from the specified ad client.

*Tags:* `customchannels`

#### Input Parameters
* `adClientId` - _required_ - Ad client which contains the custom channel.
* `customChannelId` - _required_ - Custom channel to retrieve.
* `key` - _optional_ - API key. Your API key identifies your project and provides you with API access, quota, and reports. Required unless you provide an OAuth 2.0 token.
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### List all ad units in the specified custom channel.

*Tags:* `customchannels`

#### Input Parameters
* `adClientId` - _required_ - Ad client which contains the custom channel.
* `customChannelId` - _required_ - Custom channel for which to list ad units.
* `includeInactive` - _optional_ - Whether to include inactive ad units. Default: true.
* `maxResults` - _optional_ - The maximum number of ad units to include in the response, used for paging.
* `pageToken` - _optional_ - A continuation token, used to page through ad units. To retrieve the next page, set this parameter to the value of "nextPageToken" from the previous response.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### List all URL channels in the specified ad client for this AdSense account.

*Tags:* `urlchannels`

#### Input Parameters
* `adClientId` - _required_ - Ad client for which to list URL channels.
* `maxResults` - _optional_ - The maximum number of URL channels to include in the response, used for paging.
* `pageToken` - _optional_ - A continuation token, used to page through URL channels. To retrieve the next page, set this parameter to the value of "nextPageToken" from the previous response.
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### List the alerts for this AdSense account.

*Tags:* `alerts`

#### Input Parameters
* `locale` - _optional_ - The locale to use for translating alert messages. The account locale will be used if this is not supplied. The AdSense default (English) will be used if the supplied locale is invalid or unsupported.
* `fields` - _optional_ - Selector specifying which fields to include in a partial response.
* `key` - _optional_ - API key. Your API key identifies your project and provides you with API access, quota, and reports. Required unless you provide an OAuth 2.0 token.
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Dismiss (delete) the specified alert from the publisher's AdSense account.

*Tags:* `alerts`

#### Input Parameters
* `alertId` - _required_ - Alert to delete.
* `fields` - _optional_ - Selector specifying which fields to include in a partial response.
* `key` - _optional_ - API key. Your API key identifies your project and provides you with API access, quota, and reports. Required unless you provide an OAuth 2.0 token.
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### List the metadata for the dimensions available to this AdSense account.

*Tags:* `metadata`

#### Input Parameters
* `alt` - _optional_ - Data format for the response.
    Possible values: csv, json.
* `fields` - _optional_ - Selector specifying which fields to include in a partial response.
* `key` - _optional_ - API key. Your API key identifies your project and provides you with API access, quota, and reports. Required unless you provide an OAuth 2.0 token.
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### List the metadata for the metrics available to this AdSense account.

*Tags:* `metadata`

#### Input Parameters
* `alt` - _optional_ - Data format for the response.
    Possible values: csv, json.
* `fields` - _optional_ - Selector specifying which fields to include in a partial response.
* `key` - _optional_ - API key. Your API key identifies your project and provides you with API access, quota, and reports. Required unless you provide an OAuth 2.0 token.
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### List the payments for this AdSense account.

*Tags:* `payments`

#### Input Parameters
* `alt` - _optional_ - Data format for the response.
    Possible values: csv, json.
* `fields` - _optional_ - Selector specifying which fields to include in a partial response.
* `key` - _optional_ - API key. Your API key identifies your project and provides you with API access, quota, and reports. Required unless you provide an OAuth 2.0 token.
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Generate an AdSense report based on the report request sent in the query parameters. Returns the result as JSON; to retrieve output in CSV format specify "alt=csv" as a query parameter.

*Tags:* `reports`

#### Input Parameters
* `accountId` - _optional_ - Accounts upon which to report.
* `currency` - _optional_ - Optional currency to use when reporting on monetary metrics. Defaults to the account's currency if not set.
* `dimension` - _optional_ - Dimensions to base the report on.
* `endDate` - _required_ - End of the date range to report on in "YYYY-MM-DD" format, inclusive.
* `filter` - _optional_ - Filters to be run on the report.
* `locale` - _optional_ - Optional locale to use for translating report output to a local language. Defaults to "en_US" if not specified.
* `maxResults` - _optional_ - The maximum number of rows of report data to return.
* `metric` - _optional_ - Numeric columns to include in the report.
* `sort` - _optional_ - The name of a dimension or metric to sort the resulting report on, optionally prefixed with "+" to sort ascending or "-" to sort descending. If no prefix is specified, the column is sorted ascending.
* `startDate` - _required_ - Start of the date range to report on in "YYYY-MM-DD" format, inclusive.
* `startIndex` - _optional_ - Index of the first row of report data to return.
* `useTimezoneReporting` - _optional_ - Whether the report should be generated in the AdSense account's local timezone. If false default PST/PDT timezone will be used.

### List all saved reports in this AdSense account.

*Tags:* `reports`

#### Input Parameters
* `maxResults` - _optional_ - The maximum number of saved reports to include in the response, used for paging.
* `pageToken` - _optional_ - A continuation token, used to page through saved reports. To retrieve the next page, set this parameter to the value of "nextPageToken" from the previous response.
* `key` - _optional_ - API key. Your API key identifies your project and provides you with API access, quota, and reports. Required unless you provide an OAuth 2.0 token.
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Generate an AdSense report based on the saved report ID sent in the query parameters.

*Tags:* `reports`

#### Input Parameters
* `locale` - _optional_ - Optional locale to use for translating report output to a local language. Defaults to "en_US" if not specified.
* `maxResults` - _optional_ - The maximum number of rows of report data to return.
* `savedReportId` - _required_ - The saved report to retrieve.
* `startIndex` - _optional_ - Index of the first row of report data to return.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### List all saved ad styles in the user's account.

*Tags:* `savedadstyles`

#### Input Parameters
* `maxResults` - _optional_ - The maximum number of saved ad styles to include in the response, used for paging.
* `pageToken` - _optional_ - A continuation token, used to page through saved ad styles. To retrieve the next page, set this parameter to the value of "nextPageToken" from the previous response.
* `key` - _optional_ - API key. Your API key identifies your project and provides you with API access, quota, and reports. Required unless you provide an OAuth 2.0 token.
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Get a specific saved ad style from the user's account.

*Tags:* `savedadstyles`

#### Input Parameters
* `savedAdStyleId` - _required_ - Saved ad style to retrieve.
* `fields` - _optional_ - Selector specifying which fields to include in a partial response.
* `key` - _optional_ - API key. Your API key identifies your project and provides you with API access, quota, and reports. Required unless you provide an OAuth 2.0 token.
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

## License

**flow**ground :- Telekom iPaaS / googleapis-com-adsense-connector<br/>
Copyright © 2019, [Deutsche Telekom AG](https://www.telekom.de)<br/>
contact: flowground@telekom.de

All files of this connector are licensed under the Apache 2.0 License. For details
see the file LICENSE on the toplevel directory.

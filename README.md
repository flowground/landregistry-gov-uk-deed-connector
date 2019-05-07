# ![LOGO](logo.png) Deed **flow**ground Connector

## Description

A generated **flow**ground connector for the Deed API (version 1.0.0).

Generated from: https://api.apis.guru/v2/specs/landregistry.gov.uk/deed/1.0.0/swagger.json<br/>
Generated at: 2019-05-07T17:42:40+03:00

## API Description

Land Registry Deed API

## Authorization

This API does not require authorization.

## Actions

### Deed

> The post Deed endpoint creates a new deed based on the JSON provided.<br/>
>  The reponse will return a URL that can retrieve the created deed. <br/>
>  > REQUIRED: Land Registry system requests Conveyancer to confirm that the Borrowers identity has been established in accordance with Section 111 of the Network Access Agreement.

### Deed

> The Deed endpoint returns details of a specific deed based on the unique deed reference.<br/>
> The response includes the Title Number, Property information, Borrower(s) information and deed information.

*Tags:* `Deed`

#### Input Parameters
* `deed_reference` - _required_ - Unique reference of the deed.

## License

**flow**ground :- Telekom iPaaS / landregistry-gov-uk-deed-connector<br/>
Copyright © 2019, [Deutsche Telekom AG](https://www.telekom.de)<br/>
contact: flowground@telekom.de

All files of this connector are licensed under the Apache 2.0 License. For details
see the file LICENSE on the toplevel directory.

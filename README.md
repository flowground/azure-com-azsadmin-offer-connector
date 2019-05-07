# ![LOGO](logo.png) SubscriptionClient **flow**ground Connector

## Description

A generated **flow**ground connector for the SubscriptionClient API (version 2015-11-01).

Generated from: https://api.apis.guru/v2/specs/azure.com/azsadmin-Offer/2015-11-01/swagger.json<br/>
Generated at: 2019-05-07T17:37:32+03:00

## API Description

The User Subscription Management Client.

## Authorization

Supported authorization schemes:
- OAuth2

For OAuth 2.0 you need to specify OAuth Client credentials as environment variables in the connector repository:
* `OAUTH_CLIENT_ID` - your OAuth client id
* `OAUTH_CLIENT_SECRET` - your OAuth client secret

## Actions

### Get the list of offers for the specified delegated provider.

*Tags:* `DelegatedProviderOffers`

#### Input Parameters
* `delegatedProviderId` - _required_ - Id of the delegated provider.
* `api-version` - _required_ - Client Api Version.

### Get the specified offer for the delegated provider.

*Tags:* `DelegatedProviderOffers`

#### Input Parameters
* `delegatedProviderId` - _required_ - Id of the delegated provider.
* `offerName` - _required_ - Name of the offer.
* `api-version` - _required_ - Client Api Version.

### Get the list of public offers for the root provider.

*Tags:* `Offers`

#### Input Parameters
* `api-version` - _required_ - Client Api Version.

## License

**flow**ground :- Telekom iPaaS / azure-com-azsadmin-offer-connector<br/>
Copyright © 2019, [Deutsche Telekom AG](https://www.telekom.de)<br/>
contact: flowground@telekom.de

All files of this connector are licensed under the Apache 2.0 License. For details
see the file LICENSE on the toplevel directory.

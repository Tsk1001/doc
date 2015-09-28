#Additional Parameters

AdRout provide an opportunity to add the additional parameters

| Name |Data name | Redirect | Postback | Description|
| -- | -- | -- | -- | -- |
|Campaign | camp | - | - |The name of the campaign. |
| CampaignId | cid | |  | The identifier of the campaign. |
| CountryId | land |  |  | The identifier of the country as defined in <a href='https://en.wikipedia.org/wiki/ISO_3166-1_alpha-2'>ISO 3166-2 alpha-2</a> |
|CountrySubId | regn |  | | The identifier of the principal subdivision as defined in <a href='https://en.wikipedia.org/wiki/ISO_3166-2'>ISO 3166-2</a> |
| DatacenterId |dcid | |  | The identifier of the datacenter. |
| DeviceType | devt |  |  | The type of the device. |
| EventOrigin |evor |  |  | The origin of the event of the transaction. |
| Events |evnts |  |  | The collection of the events within the transaction. |
| EventType| evtp |  | | The type of the event of the transaction. |
| HasConversion | hcon |  |  | The boolean flag which indicates whether there is an <see cref="AppAdvertising.EventType.Install" /> event within the transaction |
| HasEngagement | heng |  |  | The boolean flag which indicates whether there is an <see cref="AppAdvertising.EventType.Engagement" /> event within the transaction. |
| HasImpression | himp |  |  |The boolean flag which indicates whether there is an <see cref="AppAdvertising.EventType.Impression" /> event within the transaction. |
| HasInstall | hins |  |  | The boolean flag which indicates whether there is an <see cref="AppAdvertising.EventType.Install" /> event within the transaction. |
| HasRedirect | hred | | | The boolean flag which indicates whether there is a <see cref="AppAdvertising.EventType.Redirect" /> event within the transaction. |
| HasReject | hrej |  |  | The boolean flag which indicates whether there is a <see cref="AppAdvertising.EventType.Reject" /> event within the transaction. |
| Id | _id |  |  | The unique identifier of the transaction within the campaign within the service. |
| IpAddress | ip |  |  | The IPv6 address of the device which has initiated the transaction |
| Language | lang |  |  | The identifier of the language as defined in <a href='https://en.wikipedia.org/wiki/List_of_ISO_639-1_codes'>ISO 639-1</a>. |
| None | none |  |  | None |
| Payout | payo |  |  | The amount of money payed for the current transaction. |
| Platform | plat |  |  | The identifier of the platform |
|ProviderId | prov |  |  | The identifier of the internet provider. |
|Referrer| ref |  |  | The referrer |
| Source | src | |  | The name of the source within the system. |
| SourceId | sid |  | | The identifier of the source within the system. |
| Status | stts |  |  | The status of the transaction. |
| SubId1 | sid1 |  |  | The sub identifier #1. |
| SubId2 | sid2 |  |  | The sub identifier #2. |
| SubId3 | sid3 |  |  |The sub identifier #3. |
| TargetId | tgid | |  |The identifier of the matched target of the campaign. |
| Time | time | |  | The date-time when transaction was initiated. |
| TimeDay | time_dd | |  | The day component of the date-time of the transaction |
| TimeHour | time_HH |  |  | The hour component of the date-time of the transaction |
| TimeMinute | time_mm |  |  | The minute component of the date-time of the transaction.|
| TimeMonth | time_MM|  | | The month component of the date-time of the transaction. |
| TimeWeek | time_ww | |  |The week component of the date-time of the transaction. |
| TimeYear | time_yy |  |  | The year component of the date-time of the transaction. |
| TransactionId | tid |  |  |The identifier of the transaction. |
| UserAdvertisingId | uaid |  |  |The unique identifier of the user for advertisers. |

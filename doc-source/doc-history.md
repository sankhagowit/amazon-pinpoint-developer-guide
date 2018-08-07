# Document History for Amazon Pinpoint<a name="doc-history"></a>

The following table describes the documentation for this release of Amazon Pinpoint\.
+ **Latest documentation update:** May 1, 2018


| Change | Description | Date | 
| --- | --- | --- | 
| Events API | Use the Amazon Pinpoint API to [record events](integrate-events.md#integrate-events-api) and associate them with endpoints\. | August 7, 2018 | 
| Endpoint export permissions | [Configure an IAM policy](permissions-export-endpoints.md) that allows you to export Amazon Pinpoint endpoints to an Amazon S3 bucket\. | May 1, 2018 | 
| Updated topics for Amazon Pinpoint integration | [Integrate Amazon Pinpoint](integrate.md) with your Android, iOS, or JavaScript application by using AWS SDKs or libraries\. | March 23, 2018 | 
| AWS CloudTrail logging | Added information about [logging Amazon Pinpoint API calls with CloudTrail](logging-using-cloudtrail.md)\. | February 6, 2018 | 
| Updated service limits | Updated [Limits in Amazon Pinpoint](limits.md) with additional information about email limits\. | January 19, 2018 | 
| Public beta for Amazon Pinpoint extensions | Use AWS Lambda functions to [customize segments](segments-dynamic.md) or [create custom messaging channels](channels-custom.md)\. | November 28, 2017 | 
| External ID removed from IAM trust policies | The external ID key is removed from the example [trust policy](permissions-import-segment.md#permissions-import-segment-trustpolicy) and example [Java code](segments-importing.md) for importing segments\. | October 26, 2017 | 
| Push notification payload limits | The limits include [payload sizes for mobile push messages](limits.md#limits-mobile)\. | October 25, 2017 | 
| Updated service limits | Added SMS and email channel information to [Limits in Amazon Pinpoint](limits.md)\. | October 9, 2017 | 
| ADM and Baidu mobile push | Update your app code to handle push notifications from the [Baidu](mobile-sdk-android-push-baidu.md) and [ADM](mobile-sdk-android-push-adm.md) mobile push channels\. | September 27, 2017 | 
| User IDs and authentication events with Amazon Cognito user pools\. | If you use Amazon Cognito user pools to manage user sign\-in in your mobile apps, Amazon Cognito assigns user IDs to endpoints, and it reports authentication events to Amazon Pinpoint\. | September 26, 2017 | 
| User IDs | Assign user IDs to endpoints to monitor app usage from individual users\. Examples are provided for the [AWS Mobile SDKs](integrate-endpoints.md#integrate-endpoints-mobile-user-ids) and [SDK for Java](endpoints.md#endpoints-example-java)\. | August 31, 2017 | 
| Authentication events | Report authentication events to learn how frequently users authenticate with your app\. Examples are provided in [Reporting Events in Your Application](integrate-events.md)\. | August 31, 2017 | 
| Updated sample events | The [example events](analytics-streaming.md#analytics-streaming-data) include events that Amazon Pinpoint streams for email and SMS activity\. | June 08, 2017 | 
| Android session management | Manage sessions in Android apps by using a class provided by the AWS Mobile Hub sample app\. | April 20, 2017 | 
| Updated monetization event samples | The sample code is updated for reporting monetization events\.  \. | March 31, 2017 | 
| Event streams | You can configure Amazon Pinpoint to [send your app and campaign events to an Kinesis stream](analytics-streaming.md)\. | March 24, 2017 | 
| Permissions | See [Permissions](permissions.md) for information about granting access to Amazon Pinpoint for AWS users in your account and users of your mobile app\. | January 12, 2017 | 
| Amazon Pinpoint general availability | This release introduces Amazon Pinpoint\. | December 1, 2016 | 
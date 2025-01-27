Exposes methods that get settings from the server configuration file. 

For example, it checks whether the Excel add-in is installed, or whether online services can be installed on the server.


# Public Objects
## Server Setting (Codeunit 6723)

 Exposes functionality to fetch some application server settings for the server which hosts the current tenant.
 

### GetEnableSaaSExtensionInstallSetting (Method) <a name="GetEnableSaaSExtensionInstallSetting"></a> 
Checks whether online extensions can be installed on the server.

Gets the value of the server setting EnableSaasExtensionInstallConfigSetting.

#### Syntax
```
[Scope('OnPrem')]
procedure GetEnableSaaSExtensionInstallSetting(): Boolean
```
#### Return Value
*[Boolean](https://docs.microsoft.com/en-us/dynamics365/business-central/dev-itpro/developer/methods-auto/boolean/boolean-data-type)*

True, if they can be installed; otherwise, false.
### GetIsSaasExcelAddinEnabled (Method) <a name="GetIsSaasExcelAddinEnabled"></a> 
Checks whether Excel add-in is enabled on the server.

Gets the value of the server setting IsSaasExcelAddinEnabled.

#### Syntax
```
procedure GetIsSaasExcelAddinEnabled(): Boolean
```
#### Return Value
*[Boolean](https://docs.microsoft.com/en-us/dynamics365/business-central/dev-itpro/developer/methods-auto/boolean/boolean-data-type)*

True if enabled; otherwise, false.
### GetApiServicesEnabled (Method) <a name="GetApiServicesEnabled"></a> 
Checks whether the API Services are enabled.

Gets the value of the server setting ApiServicesEnabled.

#### Syntax
```
[Scope('OnPrem')]
procedure GetApiServicesEnabled(): Boolean
```
#### Return Value
*[Boolean](https://docs.microsoft.com/en-us/dynamics365/business-central/dev-itpro/developer/methods-auto/boolean/boolean-data-type)*

True if enabled; otherwise, false.
### GetApiSubscriptionsEnabled (Method) <a name="GetApiSubscriptionsEnabled"></a> 
Checks whether the API subscriptions are enabled.

Gets the value of the server setting ApiSubscriptionsEnabled.

#### Syntax
```
[Scope('OnPrem')]
procedure GetApiSubscriptionsEnabled(): Boolean
```
#### Return Value
*[Boolean](https://docs.microsoft.com/en-us/dynamics365/business-central/dev-itpro/developer/methods-auto/boolean/boolean-data-type)*

True if enabled; otherwise, false.
### GetApiSubscriptionSendingNotificationTimeout (Method) <a name="GetApiSubscriptionSendingNotificationTimeout"></a> 
Gets the timeout for the notifications sent by API subscriptions.

Gets the value of the server setting ApiSubscriptionSendingNotificationTimeout.

#### Syntax
```
[Scope('OnPrem')]
procedure GetApiSubscriptionSendingNotificationTimeout(): Integer
```
#### Return Value
*[Integer](https://docs.microsoft.com/en-us/dynamics365/business-central/dev-itpro/developer/methods-auto/integer/integer-data-type)*

The timeout value in milliseconds.
### GetApiSubscriptionMaxNumberOfNotifications (Method) <a name="GetApiSubscriptionMaxNumberOfNotifications"></a> 
Gets the maximum number of notifications that API subscriptions can send.

Gets the value of the server setting ApiSubscriptionMaxNumberOfNotifications.

#### Syntax
```
[Scope('OnPrem')]
procedure GetApiSubscriptionMaxNumberOfNotifications(): Integer
```
#### Return Value
*[Integer](https://docs.microsoft.com/en-us/dynamics365/business-central/dev-itpro/developer/methods-auto/integer/integer-data-type)*

The maximum number of notifications that can be sent.
### GetApiSubscriptionDelayTime (Method) <a name="GetApiSubscriptionDelayTime"></a> 
Gets the delay when starting to process API subscriptions.

Gets the value of the server setting ApiSubscriptionDelayTime.

#### Syntax
```
[Scope('OnPrem')]
procedure GetApiSubscriptionDelayTime(): Integer
```
#### Return Value
*[Integer](https://docs.microsoft.com/en-us/dynamics365/business-central/dev-itpro/developer/methods-auto/integer/integer-data-type)*

The time value in milliseconds.

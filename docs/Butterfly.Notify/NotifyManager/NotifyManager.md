# NotifyManager constructor

```csharp
public NotifyManager(IDatabase database, INotifyMessageSender emailNotifyMessageSender = null, 
    INotifyMessageSender phoneTextNotifyMessageSender = null, string notifyMessageTableName = "notify_message", 
    string notifyVerifyTableName = "notify_verify", int verifyCodeExpiresSeconds = 3600, 
    string verifyEmailFile = null, string verifyPhoneTextFile = null, byte verifyNotifyMessagePriority = 10, string verifyCodeFormat = "###-###")
```

## See Also

* interface [INotifyMessageSender](../INotifyMessageSender.md)
* class [NotifyManager](../NotifyManager.md)
* namespace [Butterfly.Notify](../../Butterfly.Notify.md)

<!-- DO NOT EDIT: generated by xmldocmd for Butterfly.Notify.dll -->
---
title: FrozenPricesThawingNotification
description: API reference for FrozenPricesThawingNotification in Umbraco Commerce
---
## FrozenPricesThawingNotification

```csharp
public class FrozenPricesThawingNotification : NotificationEventBase
```

**Inheritance**

* class [NotificationEventBase](../../umbraco-commerce-common/umbraco-commerce-common-events/notificationeventbase.md)

**Namespace**
* [Umbraco.Commerce.Core.Events.Notification](README.md)

### Constructors

#### FrozenPricesThawingNotification

```csharp
public FrozenPricesThawingNotification(IReadOnlyCollection<FrozenPrice> prices)
```


### Properties

#### Prices

```csharp
public IReadOnlyCollection<FrozenPrice> Prices { get; }
```


<!-- DO NOT EDIT: generated by xmldocmd for Umbraco.Commerce.Core.dll -->

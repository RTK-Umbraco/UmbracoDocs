---
title: OrderStatusNotificationEventBase<TEntity>
description: API reference for OrderStatusNotificationEventBase<TEntity> in Umbraco Commerce
---
## OrderStatusNotificationEventBase&lt;TEntity&gt;

```csharp
public abstract class OrderStatusNotificationEventBase<TEntity> : NotificationEventBase
    where TEntity : OrderStatusReadOnly
```

**Inheritance**

* class [NotificationEventBase](../../umbraco-commerce-common/umbraco-commerce-common-events/notificationeventbase.md)

**Namespace**
* [Umbraco.Commerce.Core.Events.Notification](README.md)

### Constructors

#### OrderStatusNotificationEventBase&lt;TEntity&gt;

```csharp
public OrderStatusNotificationEventBase(TEntity orderStatus)
```


### Properties

#### OrderStatus

```csharp
public TEntity OrderStatus { get; }
```


<!-- DO NOT EDIT: generated by xmldocmd for Umbraco.Commerce.Core.dll -->

---
title: OrderLineChangingNotification
description: API reference for OrderLineChangingNotification in Umbraco Commerce
---
## OrderLineChangingNotification

```csharp
public class OrderLineChangingNotification : OrderLineChangeNotification<Order>
```

**Inheritance**

* class [OrderLineChangeNotification&lt;TEntity&gt;](orderlinechangenotification-1.md)

**Namespace**
* [Umbraco.Commerce.Core.Events.Notification](README.md)

### Constructors

#### OrderLineChangingNotification

```csharp
public OrderLineChangingNotification(Order order, OrderLineReadOnly orderLine, 
    ChangingValue<Guid?> taxClassId, ChangingValue<decimal> quantity, 
    DictionaryDiff<string, PropertyValue> properties)
```


<!-- DO NOT EDIT: generated by xmldocmd for Umbraco.Commerce.Core.dll -->

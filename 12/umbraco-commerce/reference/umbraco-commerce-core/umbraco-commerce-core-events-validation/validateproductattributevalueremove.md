---
title: ValidateProductAttributeValueRemove
description: API reference for ValidateProductAttributeValueRemove in Umbraco Commerce
---
## ValidateProductAttributeValueRemove

```csharp
public class ValidateProductAttributeValueRemove : ValidationEventBase
```

**Inheritance**

* class [ValidationEventBase](../../umbraco-commerce-common/umbraco-commerce-common-events/validationeventbase.md)

**Namespace**
* [Umbraco.Commerce.Core.Events.Validation](README.md)

### Constructors

#### ValidateProductAttributeValueRemove

```csharp
public ValidateProductAttributeValueRemove(ProductAttributeReadOnly productAttribute, 
    ProductAttributeValueReadOnly value, int index)
```


### Properties

#### Index

```csharp
public int Index { get; }
```


---

#### ProductAttribute

```csharp
public ProductAttributeReadOnly ProductAttribute { get; }
```


---

#### Value

```csharp
public ProductAttributeValueReadOnly Value { get; }
```


<!-- DO NOT EDIT: generated by xmldocmd for Umbraco.Commerce.Core.dll -->
